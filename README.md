# The cheap_boi mechanical keyboard
### The cheap_boi is going to be a new custom mechanical keyboard with a low pricetag
## TL;DR
- WIP, PCB v0.2 has been tested and confirmed working 
- cheap, ortholinear keyboard with  OLED-Display and RGB underglow
- Gerbers added, print on own risk
- [BOM](http://htmlpreview.github.io/?https://github.com/MangoIV/cheap_boi/bom/ibom.html)
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
- acrylic case has been made and is confirmed working 
- easier crystal footprint since v0.2
### planned
- alps/mx hybrid switch cutouts on the top plate
- add some nice silkscreen art on PCB and top plate 
### in the future
- change the design to arm, won't come that quickly though 
### current status concerning prototype
- PCBs and parts have arrived and been tested
- the second Prototype has been built and is fully working 
### problems of the current design
- the fit of the acrylic top plate wit the oled is very tight. this results in the need of filing of some materials off the corner of the oleds, this isn't much work tho and doesn't change the functionality of the oled
