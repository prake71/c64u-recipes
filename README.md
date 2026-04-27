# Recipes for the Commodore 64 Ultimate
This is to document my journey with my C64 Ultimate which I got Christmas 2025.

## Where to find additional documentation beside the handbook from Commodore?
As the C64 Ultimate board was already availabe before it came out under Commodore's label it existed already extensive [documentation](https://1541u-documentation.readthedocs.io/en/master/index.html).

## Knowing the different roles of the power button
The C64-Ultimate has one button on the right side of its case.

This button is called the *MultiButton*, because it handles several functions.

* *Power on:* When the machine is off, press the button briefly to switch it on
* *Power off*: Press the button for 4 seconds to switch off the machine.
* *Reset*: Press the button for about 1 second to reset the machine.
* *Menu*: Press the button briefly to enter the File Selection (Ultimate) menu.	
* *Freeze*: Hold the button and briefly tap on the RESTORE key to get into the freeze function of the selected utility cartridge.
* *Config Reset*: With the machine switched off, press the RESTORE key and keep it pressed. Then turn the U64 on by briefly pressing the button.
  
## How to enhance the disk drive speed
You can install Jiffy-DOS ROMs. Jiffy-DOS consists out of a ROM for the disk drive and for the C64U itself. The original kernel of the drive and the U64 have to be replaced by the Jiffy-DOS ROMs.

Jiffy-DOS ROMs can be purchased by the license holder at https://store.go4retro.com
The standard edition was enough for me. 

You will get a zip-file which contains *JiffyDOS_1541-II_6.00.bin* and *JiffyDOS_C64_6.01.bin*.

These files have to be copied into the Flash folder of your C64Ultimate.

Under 'Memory and ROMs" in the Ultimate Menu you can assign these ROMs to the C64 Kernal and to the 1541's firmware.

That's it!

## How to remote control my C64U?
There is a commandline interface for PC which uses the C64 Ultimate's REST API. For this the your Ultimate has to be integrated into your network and its network servcices need to be enabled. 
This is also very handy when it comes to cross-development. 
You can find everything  about *c64u - Commodore C64 Ultimate CLI* at [github.com/cybersorcerer/c64u](https://github.com/cybersorcerer/c64u).

## Proper Scanlines on CheckMate Monitor
When using the C64 Ultimate with a Checkmate IPS Retro Monitor via HDMI, the scanlines can sometimes look uneven or overly artificial. This is usually not a flaw of the scanline feature itself, but a result of how the monitor scales the incoming HDMI signal.

The solution is to use the monitor’s Point‑to‑Point (PtP) display mode.

On the Checkmate monitor, select Point‑to‑Point (PtP) as the scaling mode. This disables internal upscaling and ensures that the HDMI signal is displayed pixel‑accurately.

On the C64 Ultimate, set the HDMI output resolution to 1280×1024.

With this combination, the image fills the screen nicely while each pixel is mapped 1:1. As a result, the scanlines are evenly distributed and the overall image looks calm and natural, without the uneven or “synthetic” appearance seen with other scaling modes.

For me, this setup provides the best balance between screen usage, sharpness, and authentic scanline appearance when using HDMI.
	




	




	



  
