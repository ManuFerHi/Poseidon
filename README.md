# Poseidon
Poseidon board for FPGA

![alt text](https://i.postimg.cc/3J4Hh5Cq/IMG20231017222956.jpg)

Poseidon is a base board MIST firmware compatible, support for connecting QMTech or compatible FPGA boards.
The Poseidon daughter board enables all of these options to the QMTech board.
- Upload core from SD.
- MIST firmware supported.
- 4 USB Ports.
- 2 DB9 joystick ports (Atari standard).
- I2S chip sound.
- VGA DAC 6 bits.
- Overvoltage and overcurrent protection.
- 80 pin expansion port.

Poseidon is delivered with the firmware installed, to update the firmware follow the instructions from the official MIST git (The official MIST firmware files are compatible with Poseidon).
https://github.com/mist-devel/mist-board/wiki/HowToInstallTheFirmware

Instructions.
Place the core.rbf file in the root of the SD, start Poseidon, Poseidon automatically uploads core to the FPGA (needs QMtech board with passive serial).
Optionally you can configure a mist.ini file, to configure mist.ini follow the instructions from the official MIST git.
https://github.com/mist-devel/mist-board/wiki/DocIni
