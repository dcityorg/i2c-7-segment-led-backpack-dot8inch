#### I²C LCD Backpack Board for character LCD modules

<div style="text-align: center;">
<div style="display: inline-block; margin-right: 5px;">
<img  src="http://wht.io/wp-content/uploads/projects/i2c-7-segment-led-dot8inch/i2c-7-segment-led-dot8inch-seeeduino.jpg" alt="i2c LED display" width="300" height="300" />
</div>
</div>

<div style="text-align: center;">
<div style="display: inline-block; margin-right: 5px;">
<img  src="http://wht.io/wp-content/uploads/projects/i2c-7-segment-led-dot8inch/i2c-7-segment-led-dot8inch-front.jpg" alt="i2c LED display" width="300" height="300" />
</div>
</div>

<div style="text-align: center;">
<div style="display: inline-block; margin-right: 5px;">
<img  src="http://wht.io/wp-content/uploads/projects/i2c-7-segment-led-dot8inch/i2c-7-segment-led-dot8inch-back.jpg" alt="i2c LED display" width="300" height="300" />
</div>
</div>

LEDs are inexpensive and provide a great way to display information from microcontrollers. This project provides the details for making a 4 digit 7 segment LED module using LEDs that have a height of 0.8 inches (see my other projects for other sizes). To make the module easy to use with Arduino, Particle and Raspberry Pi boards, [software libraries](http://wht.io/portfolio/i2c-7-segment-led-library) are available for these microcontrollers.

This design uses the AMS AS1115 LED controller chip ([datasheet](http://ams.com/eng/content/download/18430/343782/15670)). Only two pins are used to communicate between the microcontroller and the LED module (using the I²C interface). The board has I²C pullup resistors (enabled with solder jumpers) and jumpers to select the I²C address. The module will operate with either 3.3 volts or 5 volts and a pot is used to easily adjust the brightness of the LED (and your software can also control the brightness).

To make it easy to use this LED display, I wrote a [software library](http://wht.io/portfolio/i2c-7-segment-led-library) for the Arduino, Particle and Raspberry Pi boards. The library consists of 12 functions, such as clear(), moveCursor(), and write() (for displaying ASCII characters). 
Bare PC boards are available from OSH Park.

Our website has [details](http://wht.io/portfolio/i2c-7-segment-led-dot8inch/) including parts lists, assembly instructions, jumper configuration, and software library usage.

This hardware project is open source. See LICENSE.md for license information.
