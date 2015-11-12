# eeZeeSwitch User Guide

The compact eeZee Switch provides flexible options for a breadboard switch that won't fall out of your breadboard.

The breakout board contains a switch with both pins broken out, a 10k optional pull-up and a debounce capacitor (optional with Rev 0.2).

# How to Assemble

Assembly is easy. And, you can learn how to solder at the same time. Review [Sparkfun's Soldering Tutorial](https://learn.sparkfun.com/tutorials/how-to-solder---through-hole-soldering) if you need to. Here's a helpful info-graphic from the tutorial:

![soldering infographic](https://cdn.sparkfun.com/assets/c/d/a/a/9/523b1189757b7fb36e8b456b.jpg)

## You'll need
* Soldering iron, 40W
* Sponge to clean the iron (I recommend a brass sponge)
* Workbench with plenty of light
* Ventilation since breathing flux fumes is irritating
* Soldering surface (e.g., marble tile sample)
* Rosin core solder 0.022” or 0.032” diameter
* Kester #2331-ZX flux pen (optional)

## Pin headers
Apply flux to the outer pin header pads on the board.

Install the pin headers into a breadboard 5 rows apart

Place eeZeeSwitch onto the pin headers with switch silkscreen on top

Solder pin headers

## Switch
If the switch isn't pre-installed, follow these instructions.

Remove eeZeeSwitch from the breadboard.

Install the switch on the side indicated by the silk screen

It may help to bend the switch tabs to hold it in place or you can place it upside down on your workbench.

Solder the switch pins in place.

Install the pin headers on the board so the switch faces up

## Cleanup

You'll want to remove the rosin and flux

I usually just use isopropyl alcohol and an old toothbrush

You can also buy chemicals specifically for removing flux and rosin

![insert pin headers](images/assembly_isopropyl.jpg)

# How to Use

## Hookup (both) ##
![https://lh3.googleusercontent.com/-lrsTSMyLd4o/VE_I0Vi39CI/AAAAAAAAKg0/lOVdrspzIqU/w773-h580-no/eeZeeSwitch_hookup1.png](https://lh3.googleusercontent.com/-lrsTSMyLd4o/VE_I0Vi39CI/AAAAAAAAKg0/lOVdrspzIqU/w773-h580-no/eeZeeSwitch_hookup1.png)

## Active High (both), Active Low (Rev 0.2 only) ##

![https://lh3.googleusercontent.com/-PCCCCLJq-w4/VE_OSoQ5A8I/AAAAAAAAKhM/OOFUYRWHf0s/w772-h531-no/eeZeeSwitch_Active_hilo.png](https://lh3.googleusercontent.com/-PCCCCLJq-w4/VE_OSoQ5A8I/AAAAAAAAKhM/OOFUYRWHf0s/w772-h531-no/eeZeeSwitch_Active_hilo.png)

## Series Current Limit (Rev 0.2 only) ##

![https://lh5.googleusercontent.com/-ZUlTaqUCIak/VE_PThaTaAI/AAAAAAAAKho/o_ObyeX4n5o/w772-h272-no/eeZeeSwitch_current_limit.png](https://lh5.googleusercontent.com/-ZUlTaqUCIak/VE_PThaTaAI/AAAAAAAAKho/o_ObyeX4n5o/w772-h272-no/eeZeeSwitch_current_limit.png)

## Arduino Reset Circuit (Rev 0.2 only) ##

![https://lh3.googleusercontent.com/-tEm0M-Nz_64/VE_I0LGWfAI/AAAAAAAAKgw/DWyBrb80Kk4/w773-h290-no/eeZeeSwitch_Arduno.png](https://lh3.googleusercontent.com/-tEm0M-Nz_64/VE_I0LGWfAI/AAAAAAAAKgw/DWyBrb80Kk4/w773-h290-no/eeZeeSwitch_Arduno.png)
