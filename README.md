## Adafruit TLV320DAC3100 I2S DAC with Headphone and Speaker Out PCB

<a href="http://www.adafruit.com/products/6309"><img src="assets/6309.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit TLV320DAC3100 I2S DAC with Headphone and Speaker Out. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/6309

### Description

We stock a lot of chips and development boards that are able to do high quality digital I2S out, which makes for great quality audio playback. That's great when you have enough processing power to decode WAVs or MP3s in real time. However, most give you stereo line-out which cannot connect to head-phones...until now!

We really love the sounds coming out of the Adafruit TLV320DAC3100 I2S DAC with Stereo Headphone and Mono Speaker output - it's got clean, excellent-quality, stereo audio that can connect directly to your 16Ω headphones and/or a 4Ω-8Ω speaker. This makes it excellent for all-in-one audio projects without needing an external amplifier. Please note that while it does not need a MCLK signal (you can configure it to use BCLK as the PLL input) it does require I2C configuration! You will need a microcontroller with our library (Arduino, CircuitPython or Python) to set up the board for audio playback.

This breakout makes amplified I2S digital audio easy. You can power it with 3V (headphone only) or 5VDC (for speaker support) and provide BCLK (bit clock), WSEL (left/right word select), and DIN (data in). Then configure the board with I2C to determine the gain and which output you want activated. There's tons of configuration options available, but we've used it mostly for 16-bit I2S audio. There's a built-in PLL that will generate an MCLK signal from BCLK for you so it can be used by any I2S source.

Audio output from the headphone is AC-coupled. Audio from the speaker is a class-D amplifier and must be connected to a speaker only. If you need an external amplifier, use the headphone jack. 

There's a few extra breakouts on this board: MIC and BIAS are connected to the 'fourth' contact on headsets that often have a microphone. You can configure the amp to provide a 2V bias voltage which will let you detect when a headset+mic is plugged in, and also detect when the headset button is pressed. There's also AIN1/AIN2 which are alternative mix-ins for the audio outputs, not I2S encoders. There is one 'GPIO' pin which can also be used as an IRQ line.

Note that this board can be powered from 3~5VDC but all logic level is 3.3V only (it's quite rare for an I2S microcontroller/computer to have 5V logic!)

Each order comes with one Adafruit TLV320DAC3100 DAC breakout and some header you can solder on for breadboard usage.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
