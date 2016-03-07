# Cache Makers 4H Club LED Ribbon

The [Cache Makers 4-H Club](http://cachemakers.org) LED Ribbon is a fun way to introduce soldering. 

It does require soldering 20 leds, an 8 pin ATtiny85 microcontroller, a button, and a battery clip. 

The end results can be worn on a string as a necklace, and is shaped much like
an award ribbon. Adding a fabric ribbon to the bottom of the circuit board
would enhance this effect. It would also be possible to add a ruffle around the
perimeter of the LED's.

The finished board is also programmable, and can be used to teach programming. 

The [Cache Makers 4-H Club](http://cachemakers.org) is in-charge of the production and distribution of this project. 

## Learn to Solder

Components to Solder

* [ATtiny85](http://www.atmel.com/devices/attiny85.aspx) Microcontroller
* a Tactile Switch style Button
* a CR2032 Battery Clip
* 20 LED's (Light Emitting Diodes) 
* a 2x3 ISCP programming header (optional)

For the users comfort, it is recommended that the leads from the components be
clipped short after they have been soldered and then the solder pad re-flowed
with a soldering iron to eliminate any sharp points. 

My personal preference is to also leave off the programming header, as the pins are sharp and pokey and interfere with comfort when worn. 
    
## Learn to Program

With the use of the [Arduino](http://arduino.cc) programming environment and support for the ATtiny85 chip from [High Low Tech](http://highlowtech.org/?p=1695) along with a AVR ICSP programmer, like the ones available from [Sparkfun](https://www.sparkfun.com/products/9825) or [Adafruit](http://www.adafruit.com/product/46), it is possible to change the programming for the device. 

The LED's are arranged in a Charlieplex configuration where each individual LED requires one pin high and one pin low to light up. By blinking the LED's on and off really fast, the illusion that they are all on or at different brightnesses can be achieved. 

# 4H Logo

This Circuit Board Design features the 4H logo. 

In order to comply with the use guidelines for the 4H logo, under US code 18
USC 707, the board must be manufactured with a green solder mask, and a white
silkscreen. 

In the logo itself, I have omitted the "18 USC 707" because it proved to be
un-readable. Instead I have placed it just outside the ring of LED's to the
bottom right.

## Attribution

This project was designed by [User Hackable](http://userhackable.com). 



