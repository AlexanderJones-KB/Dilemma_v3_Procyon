
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

Six flat head screws, bottom 3D print, six spacers - combine.  
Align rotation of spacers.

![](img/left_asm_1.jpg)

![](img/left_asm_2.jpg)

Drop in acrylic plate.

![](img/left_asm_3.jpg)

Drop in middle layer 3D print.

![](img/left_asm_4.jpg)

Drop in PCB. Wiggle might be required.

![](img/left_asm_5.jpg)

Drop in top layer 3D print and cover with hole for logo.  
Use six beveled head screws to fix everything together.

![](img/left_asm_6.jpg)

Attach pads.

![](img/left_asm_7.jpg)

Insert keys, connect USB and flash firmware if needed.  
Is is alive!

![](img/left_asm_8.jpg)

## Right side

### Parts

Screws

![](img/right_screws.jpg)

3D Prints

![](img/right_prints_1.jpg)

![](img/right_prints_2.jpg)

![](img/right_prints_3.jpg)

Touchpad  
Two 5.0 mm M3 inserts  
Two flat head 8.0 mm M3 screws  
100.0 mm FPC 12P 0.5 mm pitch type B

![](img/right_touchpad.jpg)

Acrylic Plate

![](img/right_plate.jpg)

PCB

![](img/right_pcb_1.jpg)

![](img/right_pcb_2.jpg)

Anti-slip Pads (10.0 x 3.0 mm)

![](img/right_pads.jpg)

### Steps

Assemble touchpad.  
Put it aside.

![](img/right_asm_1.jpg)

Two flat head screws, bottom 3D print, two spacers - combine.  
Align rotation of spacers.  
Put it aside.

![](img/right_asm_2.jpg)

Four beveled head screws, top 3D print.

![](img/right_asm_3.jpg)

Drop in PCB. Fix using four spacers.  
Align rotation of spacers.

![](img/right_asm_4.jpg)

Connect touchpad.

![](img/right_asm_5.jpg)

Align and flip touchpad.

![](img/right_asm_6.jpg)

Secure touchpad using two 8.0 mm screws.

![](img/right_asm_7.jpg)

Drop in middle layer 3D print. Wiggle might be required.

![](img/right_asm_8.jpg)

Drop in acrylic plate.

![](img/right_asm_9.jpg)

Drop in bottom layer 3D print. Use four flat head screws to fix it.  
Attach pads.

![](img/right_asm_10.jpg)

Use two remaining beveled head screws on right edge.  
Insert keys, connect USB and flash firmware if needed.  
Is is alive!

![](img/right_asm_11.jpg)

## Final

It is so beautiful.

![](img/final.jpg)
