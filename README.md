# Simple-Openithm
    My version of Openithm as a hobby project

This is my version of Openithm as a hobby project to learn more about MCU and programming. I based largely on the Veroxzik's Openithm using Arduino Atmega32U4 and MPR121.

However, because of my lack of programming skill to compile their code (I got trouble with compiling the mpr121 as there is no library), I do the programming my own. It is not refined, but useable. Future plan is to reduce the latency and more accurate IR sensing.

**replace the Keyboard folder with the arduino Keyboard library or rename it**
this Keyboard library support more key-rollovers (the standard only support 6) up to 22



To do:
-Direct port manipulation and using registers to reduce delay
-Use HID library directly instead of using through Arduino built-in Keyboard library, which I need to modify to use more than 6 simultaneous keys. This will lower the latency while not letting anybody (if there is) who use my code have to modify the Keyboard library themselves.
-Able to change the MPR121 settings without editing the sketch
