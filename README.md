<h1>Laterna Matrix</h1>

Laterna Matrix has an integrated LED Controller. There are two variants of this board, the Attiny85 and the ESP line.
It can contain a LED matrix in following formats 8x8 or 16x16

You can power the board using the USB Type C connector or using an external 5V power supply. 

Additionally Laterna Matrix - ESP boards are mainly intended to be used with [WLED software ](https://github.com/Aircoookie/WLED "WLED's Homepage") or [ESPHome](https://esphome.io), but you can also program the board using your own code or other library.

The controller can be ordered on [Aliexpress](https://de.aliexpress.com/store/1100075030?spm=a2g0o.detail.1000007.1.2ffd267fcF2rAb)<br>

<h3>Attiny85 Features</h3>
Chip:   Attiny85 no Wifi and Bluetooth
<br>USB Type C connector for 5V power
<br>1 channel LED Matrix in 8x8 or 16x16 format
<br>5V VIN

<h3>ESP Features</h3>
Chip:   ESP8285 for Wifi
all other features for the Attiny85 version


<h3>Attnity85 Installation</h3>
Refer to following guide for attiny85 installation

https://create.arduino.cc/projecthub/arjun/programming-attiny85-with-arduino-uno-afb829

Refer to following guide for LED library for Attiny85
https://create.arduino.cc/projecthub/talofer99/arduino-and-addressable-led-b8403f

<h3>ESP Installation</h3>

All our boards are delivered with the latest WLED version. You can use the board out of the box.

You can customize the software based on your needs and flash it by **USB** or the **programming connector**.

For Flashing a precompiled Firmware we recommend [ESPHome Flasher](https://github.com/esphome/esphome-flasher/releases "ESPHome Flasher Releases")

<h5>Required steps for manual flashing</h5>

* First you need to put the Board in flash mode
* Press and hold the Flash button before connecting the board to USB or programmer connector. Rlease the flash button after you connected the board.


<h3>Attiny85 PINOUT Description</h3>

<img src="/Photos/IMG_1288_Pinout.png" width="50%">


We recommend to power the module by using a USB power supply or external powersupply. **DO NOT POWER LED Strips directly from laptop/PC port**

<br>
Please take note that this Laterna Version **only support 5V**.


<h3>Use Cases - Videos</h3> 

**Plug and play example - Simple Connection**

[![Alt text](https://img.youtube.com/vi/jTaMgcbers8/0.jpg)](https://youtu.be/jTaMgcbers8)

* plug and play example - External power supply
(**Work in Progress**)

<h3>License</h3>

Software used in this guide is open source and licensed under the **MIT License**

<h3>FAQ</h3>

* Can I use this board with my own code?
  - yes, you can write your own code and programm this board. Refer to programming steps section
 (**Work in Progress**)

<h3>Acknowledgment</h3>

We would like to thank WLED Developers for their great job, our platform relies strongly on their work
[![Alt text](https://github.com/Aircoookie/WLED/blob/master/images/wled_logo_akemi.png)](https://github.com/Aircoookie/WLED)
