## Features

The main features of the SAO are :
- An optical sensor : a VEML3328 to provide a 1x1 pixel RGB+IR camera
- An IMU (accel + gyro) : an LSM6DSO, because every good telescope needs to know its orientation (note that only one remaining gyroscope is working correctly on Hubble, so my SAO has the same number of gyroscope, nice !)
- 4 photodiodes : they represent the solar panels of Hubble. I'm using BPW34s (the IR version, to be precise). They are wired to the ADC of the microcontroller.
- An IR LED : to provide a way to send wireless data
- An microcontroller : I used a ATmega328PB

On top of that, there are :

- A standard yellow LED, because an SAO would be nothing without some blinky LEDs
- A button

## License
 Hubble SAO by pdulab is licensed under CC BY-NC-SA 4.0 

 ## Disclaimer
 This is a project for fun. I do not guarantee anything about it.
 The author is not affiliated with the official Hubble Space Telescope project or endorsed by it (or any related organization) in any way whatsoever.
