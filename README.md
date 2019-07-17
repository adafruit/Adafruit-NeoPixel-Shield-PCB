## Adafruit NeoPixel Shield for Arduino - 40 RGB LED Pixel Matrix PCB

<a href="http://www.adafruit.com/products/1430"><img src="assets/1430.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit NeoPixel Shield for Arduino - 40 RGB LED Pixel Matrix. Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/1430

### Description

Put on your sunglasses before putting this shield onto your 'duino - 40 eye-blistering RGB LEDs adorn the NeoPixel shield for a blast of configurable color. Arranged in a 5x8 matrix, each pixel is individually addressable. Only one pin (Digital #6) is required to control all the LEDs. You can cut a trace and use nearly any other pin if you need some customization.

To make it easy to start, the LEDs are by default powered from the 5V onboard Arduino supply. As long as you aren't lighting up all the pixels full power white that should be fine. If you want to power the shield with an external power supply, solder in the included terminal block (pro-tip: put it on the bottom of the board so it doesn't stick up) to wire in an external 4-6VDC power supply - that power supply will also power the Arduino and shield. If you want to use the terminal block to power the shield but keep the Arduino itself on DC or USB power only, cut the center of the solder jumper to the right of the terminal block. There's a polarity protection FET on the external input in case you wire the power backwards (we would never do that, it was, umm, a friend of ours, yeah that's it!)

If, say, you need MORE blinky, you can chain these together. For the second shield, connect the DIN connection to the first shield's DOUT. Also connect a ground pin together and power with 5V. There you go! You can chain as many as you'd like although after 5 or more shields you may run low on RAM if you're using an UNO.

We include both stacking headers and plain headers. Use whichever you prefer - there isn't a lot of space left over for the 'duino pin breakouts so if you want to wire up some other outputs or sensors the stacking headers are good. For a slim sturdy look, solder on the plain headers.

[Our detailed NeoPixel Uberguide has everything you need to use NeoPixels in any shape and size. Including ready-to-go library & example code for the Arduino UNO/Duemilanove/Diecimila, Flora/Micro/Leonardo, Trinket/Gemma, Arduino Due & Arduino Mega/ADK (all versions)](http://learn.adafruit.com/adafruit-neopixel-uberguide)

**Note**: The terminal blocks included with your product may be blue or black.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. See license.txt for additional details.
