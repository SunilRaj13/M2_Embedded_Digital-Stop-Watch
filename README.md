# M2_Embedded_Digital Stop Watch

### How to Use the "Digital Stop Watch"
When initially powered up the Stop watch is in "STOP" condition. This is indicated by a blinking display. The count is 00:00 initially. Press "START" to start the watch. The blinking will now stop and the display will be fully on. It will start counting and MIN:SEC is displayed. The stop watch can be halted at any time by pressing "HALT" key. In halt state the counting freezes and the display starts blinking. You can press "START’ key again to resume counting from there. The "RESET" key is used to reset the clock to 00:00 i.e. 0 minute and 0 sec.


### Steps to Build the "Digital Stop Watch" using AVR ATmega8 MCU
  Make the circuit according to the schematic on general purpose PCB or a BreadBoard.
  Make a project in AVR Studio and add a new file to the project. Copy/paste the "c" code. Set optimization as "o2" and CPU frequency as 16000000Hz. Save and Build the project.You will get a HEX file.
  Burn this HEX file to an ATmega8 MCU using a tool such as eXtreme Burner AVR.
  Set High Fuse = C9(Hex) Low Fuse = FF(Hex). How to do this depends on you programmer software.
  
  [![Codacy Badge](https://app.codacy.com/project/badge/Grade/dc098bd500ae40efb43eb5adb6c2a5a4)](https://www.codacy.com/gh/SunilRaj13/M2_Embedded_Digital-Stop-Watch/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=SunilRaj13/M2_Embedded_Digital-Stop-Watch&amp;utm_campaign=Badge_Grade)
  
  [![Code Quality Score](https://api.codiga.io/project/30280/score/svg)](https://app.codiga.io/public/project/30280/M2_Embedded_Digital-Stop-Watch/dashboard)
  [![Code Grade](https://api.codiga.io/project/30280/status/svg)](https://app.codiga.io/public/project/30280/M2_Embedded_Digital-Stop-Watch/dashboard)

  
