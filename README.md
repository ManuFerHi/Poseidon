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
The FPGA board must be in passive serial mode, change the jumper to PS.
https://github.com/mist-devel/mist-board/wiki/DocIni

You can buy Poseidon board [here](https://manuferhi.com/p/poseidon-motherboard)



Known compatible boards - [QMTech CycloneIV EP4CGX150 - ](https://es.aliexpress.com/item/1005004065727282.html?spm=a2g0o.store_pc_groupList.8148356.3.254577a24VMAg9&pdp_npi=4%40dis%21EUR%21%E2%82%AC%2092%2C65%21%E2%82%AC%2092%2C65%21%21%2198.81%2198.81%21%40211b88ee17030282752154763ef215%2112000027923175398%21sh%21ES%21130548741%21)
