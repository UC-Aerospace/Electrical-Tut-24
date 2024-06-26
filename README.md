# 2024 Avionics tutorial example boards!!
Here's where you'll find basic examples of a flight computer board using the RP2040 microcontroller. 

We have two different example sizes.  
  
(50mm x 50mm) This shows it's possible to design a 2-layer 50mm x 50mm board to fit the minimum rocket tube diameter of 50mm. Made by Grayson. This is the one we have ordered and will be avalible to pass around.  
  
~~(66mm x 66mm) This 2-layer example board is slightly bigger but small enough to fit in an L2 rocket. Made by Kaden.~~  
Unfortunatly this board has some issues at the moment, we might look into fixing it. Left for now as it shows a different general approach.

> [!NOTE]
> While making a 2-layer 50mm x 50mm board is possible, routing something this small can be quite a puzzle especially to do nicely. If you do target 50x50 we would reccomend a 4-layer board. Otherwise, we'd suggest something either 66x66mm or 88x88mm.

> [!CAUTION]
> We are not experts and are still all learning a lot ourselves. As such some of these designs may be suboptimal, don't take them as best practice. If you see an issue with any of the boards, or even just think you do, feel free to create an issue so we can all learn.

## Templates

These are barebones files to use as a starting point, and very simply include a board outline with holes that will match with our sleds, the RP2040 footprint and the Sense module footprint. Avalible in 50x50, 66x66 and 88x88 to modify as you wish.

## Resources / Datasheets
**_Please look_** at the datasheets for any major components you plan to use, e.g. (Voltage regulator, RP2040, Flash chip, Screen, LEDs, USB-C connector, etc..) They provide the information necessary to integrate them with your project and if any extra components are needed to work correctly.

The Raspberry Pi Foundation has provided a massive amount of technical information for the RP2040 microcontroller we use, so I'd suggest reviewing their datasheets to help build your boards! They definitely helped me :) 

[RP2040 Datasheet](https://datasheets.raspberrypi.com/rp2040/rp2040-datasheet.pdf)  
[RP2040 Hardware design examples](https://datasheets.raspberrypi.com/rp2040/hardware-design-with-rp2040.pdf)  
[Raspberry Pi Pico datasheet](https://datasheets.raspberrypi.com/pico/pico-datasheet.pdf)
  
Also take a look at the sensor package used which we have got assembled for you:
[MicroSense](https://github.com/UC-Aerospace/Sense)

If you have any questions about the example board, then come talk to me!  
Happy making! (The first year Grayson) :3

<img width="935" alt="image" src="https://github.com/UC-Aerospace/Electrical-Tut-24/assets/137386245/378ba17e-57df-4a23-9018-d43e8866c3ac">
  
^ Graysons demo flight computer, we will have a few to pass around.
