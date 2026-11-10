To flash this firmware, you will need esptool or similar software.

Flashing Method:

Copy the command below into the Windows command prompt.

esptool --chip esp32 --port COMx --baud 460800 write_flash --flash_mode dio --flash_size 4MB 0x0 MinionRadioV2.0.3.bin

ATTENTION!!
This firmware will never stop evolving, and bugs and errors will be discovered all the time. If they occur, you can simply turn the radio off and on again.
