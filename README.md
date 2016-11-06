# Mars Rover

![](https://github.com/ezchx/sainsmart_uno_4wd_car_kit_code/blob/master/toy_car_pic.jpg)

Assembly Instructions: 
http://www.sainsmart.com/zen/documents/20-011-922/4WD.pdf

Wiring Video:
https://www.youtube.com/watch?v=oekNebt7Q9o

Arduino Code:
http://codemahal.com/video/building-a-4wd-autonomous-car-with-arduino/

The kit does not come with instructions and may be missing some parts. I was missing a 9 volt battery plug, female to female jumper wires, a mounting bracket for the sensor, and circuit board spacers. You will also need 6 AA batteries for the motors and a 9 volt battery for the Arduino. In addition to the tools in the instructions, you will also need a soldering iron.

The case is sturdy, but the screws are threaded into the metal and are not secure at all. When you have completed the wiring, do not worry if it does not run as per the video. You need to upload the code to activate the motors. I did not hook up the charging socket, but the external switch is handy so you don’t have to keep reaching inside the box to turn the motors on and off.

Download the Arduino software from the website, copy and save the kit car code in the Arduino GUI, plug the Arduino into a USB port on your computer, and upload the code to your car. Make sure that that Arduino software recognizes the kit car USB port. If you receive a serial port permission error, the following command line statement should fix it: sudo usermod -a -G dialout <username>. Replace <username> with your Linux username.

I had to switch forward and reverse in the code because I mounted the sensor on the “back” of the car. I also increased the sensing distance from 15 cm to 30 cm  and the right turn in the avoid function from 360 to 750 which seemed to help a bit with the crashing. 

Have fun!

