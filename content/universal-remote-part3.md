+++
title = "Universal Remote - Part III"
date = 2014-12-18

[taxonomies]
tags = ["RaspberryPi", "UniversalRemote"]
+++

The only items I didn’t purchase online were the supplies for soldering and wiring. I went with the ECG 20 Watt Miniature Corded Soldering Iron, Sn60/Pb40 Solder and 22AWG Solid Copper Wire.

With all the components and tools needed, the first step was assembling the Adafruit Prototyping Pi Plate Kit following [these instructions](https://learn.adafruit.com/adafruit-prototyping-pi-plate/solder-it). Once complete I built [the circuit for the IR receiver and transmitter](https://upverter.com/design/alexbain/f24516375cfae8b9/open-source-universal-remote/#/). With the assembly complete the Prototyping Pi Plate connects to the Raspberry Pi via the GPIO pins. In addition to referencing the circuit diagram [these high resolution pictures from alexba.in](http://alexba.in/blog/2013/06/08/open-source-universal-remote-parts-and-pictures/) were very useful.

<!-- more -->

{{ image(src="/img/SolderingSupplies.png", position="left", alt="Photograph of soldering supplies.", style="border-radius: 8px;") }}
&nbsp;
{{ image(src="/img/UniversalRemoteHardwareAssembled.png", position="left", alt="Photograph of hardware assembled.", style="border-radius: 8px;") }}

With the hardware assembled the next step is to install [Raspbian](https://www.raspberrypi.com/software/) as the OS on the SD card and the application [LIRC](http://www.lirc.org/) for controlling the hardware to test functionality.
