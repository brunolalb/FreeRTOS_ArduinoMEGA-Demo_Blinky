Demo Blinky on FreeRTOS project
=============
ArduinoMEGA with FreeRTOS 9.0.0
-------------------------------
 * Compiler: WinAVR
 * Programmer: AVR Dude (STK500v2)
 * IDE: Eclipse Mars.2
 
---

Tasks:

* The Queue Send Task: Writes a constant value in a queue every 200 ms.
* The Queue Receive Task: Reads the content of the queue and checks if it's right. If it is, toggles a LED.
 
---

Versions:

 * Initial version (2016-08-09): Bruno Landau Albrecht (brunolalb@gmail.com)
