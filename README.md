# M2_Embedded_Digital Stop Watch

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/b97f1bf7bb324c308158e5b31e4c475b)](https://app.codacy.com/gh/SunilRaj13/M2_Embedded_Digital-Stop-Watch?utm_source=github.com&utm_medium=referral&utm_content=SunilRaj13/M2_Embedded_Digital-Stop-Watch&utm_campaign=Badge_Grade_Settings)


### Steps to Build the "Digital Stop Watch" using AVR ATmega8 MCU
  *Make the circuit according to the schematic on general purpose PCB or a BreadBoard.
  *Make a project in AVR Studio and add a new file to the project. Copy/paste the "c" code. Set optimization as "o2" and CPU frequency as 16000000Hz. Save and Build the project.You will get a HEX file.
  *Burn this HEX file to an ATmega8 MCU using a tool such as eXtreme Burner AVR.
  *Set High Fuse = C9(Hex) Low Fuse = FF(Hex). How to do this depends on you programmer software.
