# DumbDeck
A Stream Deck parody, for much cheaper. Requires Java and a Windows computer.

# Quick Start
1. Install Java.
2. Build a DumbDeck device using scheme in DumbDeck.png(you can use touch buttons also).
3. Install drivers from "drv" folder(launch dpinst-x86.exe , click install anyway on all drivers).
5. Install Arduino IDE and open arduino-sketch.ino.
6. Plug in the dumbdeck device.
7. Select "Arduino Uno" and select serial port.
8. Press CTRL+U or click upload.
9. When upload is done, unplug the device.
10. Open "options.txt". 
11. Replace "serial":"COM16" to "serial":"yourport" where yourport is the port that you used for upload.
12. Save the file.
13. Open "dumbdeck.exe".
14. You're done. You can change button actions in options.php, like "1":"your batch command".

