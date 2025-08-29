
## About

This is unofficial, untested, use at your risk, broken assembly instruction for building Dilemma v3 keyboard with Procyon mod.

You should check [Bastard Keyboards](https://bastardkb.com/) website for high quality, ready to use products.

## Dimensions

I'm using 3.0 mm thick acrylic plate.

In this scenario you should use 5.0 mm long M3 hex spacers.  
For top cover use 6.0 mm long M3 beveled head screws.

For 2.0 mm acrylic use 4.0 mm spacers and 5.0 mm top cover screws.  
For 1.0 mm acrylic use 3.0 mm spacers and 4.0 mm top cover screws (sanded down to 3.6 mm).

Bottom cover M3 flat head screws are always 3.0 mm.

Please note that for flat head screw you measure thread only.  
For beveled head ones you measure whole screw.

## Accessories

You need one USB-C to USB-C (or USB-A) cable for connecting keyboard with computer, tablet, phone.

![](img/acc_usb.jpg)

You need one mini-jack audio cable for connecting two keyboard parts together.  
I'm using TRRS one (4 pins). TRS (3 pins) might work too according to KiCad diagram.

![](img/acc_audio.jpg)

## Hardware Customization

Both left and right keyboard parts allows for swapping one key with rotary encoder.  
In this document encoder is on left side only.

It might be possible to place touchpad on left side.  
In that case some 3D parts should be flipped before printing.  
I've not tested this scenario so please consult KiCad diagrams and QMK firmware sources.

It is up to you regards picking keys you like the most. Same for key caps.

## Soldering

If you are lazy or do not have required skill it might be advised to order manufactured PCBs.  
In that scenario some additional soldering might be required regards to: RGB leds, audio sockets, rotary encoders, key sockets, buttons.  
Always compare with documentation and verify everything twice.

![](img/solder.jpg)

## Firmware

This document does not cover device flashing topic.  
You should go here: https://github.com/Bastardkb/qmk_userspace/releases

## Left side

### Parts

Screws

![](img/left_screws.jpg)

3D Prints  

![](img/left_prints_1.jpg)

![](img/left_prints_2.jpg)

![](img/left_prints_3.jpg)

![](img/left_prints_4.jpg)

Acrylic Plate  

![](img/left_plate.jpg)

PCB  

![](img/left_pcb_1.jpg)

![](img/left_pcb_2.jpg)

Anti-slip Pads (10.0 x 3.0 mm)

![](img/left_pads.jpg)

### Steps

Bottom flat head screws, bottom 3D print, spacers - combine.

![](img/left_asm_1.jpg)

![](img/left_asm_2.jpg)

Drop in acrylic plate. Check spacers orientation.

![](img/left_asm_3.jpg)

Drop in middle layer 3D print.

![](img/left_asm_4.jpg)

Drop in PCB. Wiggle might be required.

![](img/left_asm_5.jpg)

Drop in top layer 3D print and cover with hole for logo.  
Use beveled screws to fix everything together.

![](img/left_asm_6.jpg)

Attach pads.

![](img/left_asm_7.jpg)

Insert keys, connect USB and flash firmware if needed.  
Is is alive!

![](img/left_asm_8.jpg)

## Right side

### Parts

WIP

### Steps

WIP
