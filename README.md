# The cheap_boi mechanical keyboard
### The cheap_boi is going to be a new custom mechanical keyboard with a low pricetag
## TL;DR
- WIP, PCB has been tested
- cheap, ortholinear keyboard with  OLED-Display and RGB underglow
- Gerbers added, print on own risk
## Render of front side
![render of front side](https://github.com/MangoIV/cheap_boi/blob/master/renders/pcb_front.jpg "render of front side")
![render of front side](https://github.com/MangoIV/cheap_boi/blob/master/renders/plate_front_side.jpg "render of the plate")
## Features
### implemented
- microcontroller ATmega32u4
- ortholinear layout similar to the planck
- 4 individual function keys 
- underglow LEDs using WS2812B
- OLED display using SSD1306
- FR4 Bottom- and Switchplate with windows to see microcontroller and OLED
- have a look at the folder "renders" to see renders of the PCB and plates
- a working firmware exists on my fork of the qmk_firmware on the branch cheap_boi
### planned
- add acrylic viewing window to design (needs change to PCB)
- ESD-protection for USB-Port
- acrylic Bottom- and Switchplate
- 3D-printed case
- alps/mx hybrid switch cutouts on the top plate
- add the easier footprint for the crystal
- add some nice silkscreen art on PCB and top plate 
### in the future
- change the design to arm, won't come that quickly though 
### current status concerning prototype
- PCBs and parts have arrived and been tested
- the first Prototype has been built and is fully working 
### problems of the current design
- one of the switches is not connected to the matrix
- the current footprint of the crystal is really hard to solder 
- I need to add a cutout on the top plate for the usb port, as it is under the top plate and not usable with a normal cable, also the switches don't sit flush on the PCB due to that problem. This will also make it possible to use 0.7cm standoffs instead of 1cm
