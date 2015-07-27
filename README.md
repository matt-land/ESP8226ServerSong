This is a simple web server app for a nodemcu .9 using Arduino IDE.

 - Connect a speaker/piezo on GPIO pin 4 and an LED on GPIO pin 5. 
 - Add esp8266 to the board manager in Arduino IDE. Directions https://github.com/esp8266/Arduino 
 - Select the correct board
 - install the serial drivers (ch341ser_mac), 
 - detect, compile and upload.

Use the serial debugger to see the ip address on wifi, and load the site. The buttons will flash the led and the speaker icon will play a song.
