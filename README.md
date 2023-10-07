# SWD_Debugger
Design files for an SWD debugger based on the <a href="https://github.com/electronut/ElectronutLabs-Bumpy">bumpy probe</a>. Compatible with Black Magic Probe and ST-Link V2 firmware. 

Hardware Changes from Bumpy 2.0 Project:
- Changed male USB-A plug to a female USB-C receptacle
- Changed pinout of the SWD/UART pins so that all SWD related pins are on top and all UART & power pins are on bottom
- Changed form factor and created an enclosure out of a cover PCB and 3d printed spacers.
- Changed resonator to an equivalent option in a different package
- Changed STM32 to a different package of the same product (for sourcing purposes at the time of designing)
<br>
<br>
<p align="center">
  <img width="90%" src="readme-visuals/debugger.png">
</p>