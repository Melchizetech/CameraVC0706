CameraVC0706
============

# camera

Camera using Arduino to detect motion and take a picture and store it on an SD card.
This Libraries is made to take photo with the camera sensor VC0706 without third party library.
It's a good brain exercise to understand how do UART via TX and RX pin via arduino.

# features
- Store photo on sd card with incremental file name "IMGXXX.jpg".
- Display state and debug on LCD.
- Take a picture if camera sensor detect change.
- Take a picture with button on arduino.
- Display processing wuth ardiono LED

# hardware

- VC0706 Radio shack or Adafruit camera sensor.
- SCard Arduino shield.
- SD Card
- LCD 16x2 
- Power supply Adriono 9V

## About the LCD 16x2 

LCD is NOT required to take a picture with VC0706.
However it's usefull to debug and cause you SHOULD NOT plug your computer to your arduino board via USB during that you run the programe and consequently cannot access the SERIAL debug via USB on your computer.

# Used Libraries

- https://code.google.com/p/sdfatlib
- http://playground.arduino.cc/Code/LCD