# h1-rf-test-slot-flasher
Tool used to flash slot EEPROM using PiPico for module RF tests

## Usage

```plaintext
Usage: write.py [OPTIONS] SERIAL_PORT

Options:
  -t, --test [UNMODULATED|MODULATED|SWEEP]
                                  RF test type  [required]
  -c, --channel [0|40|80]         RF test channel, for modulated nad
                                  unmodulated tests  [required]
  --help                          Show this message and exit.
```

## Example

```shell
./write.py /dev/serial/by-id/usb-Raspberry_Pi_Pico_E660443043452626-if00 -t MODULATED -c 40
```