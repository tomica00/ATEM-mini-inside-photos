# ATEM Mini inside photos
What's inside ATEM Mini Pro ISO and ATEM Mini Extreme. Photos of the main board.

# ATEM Mini Pro ISO

## The heart
Under the heatsink is the main component: a system on chip (SOC) that contains three ARM processors and an FPGA! Atem Mini Pro ISO runs on Xilinx Zynq UltraScale+ EV.

![](photos/IMG_20231229_195931.jpg)

HDMI input 1 goes into TMDS171.
Other HDMI inputs go into ADV7610.

## The main board

There's an exposed and labeled UART and it sends some info during the boot.

There's also an HDMI footprint, but no HDMI connector soldered. I did detect some clock signal on it. It would be interesting to solder an HDMI connector and see what's there.

![](photos/IMG_20231229_200541.jpg)

Bottom side:

![](photos/IMG_20231229_200512.jpg)


## How to open the case

There are 4 screws in the corners, under the rubber pads. There's another screw in the middle, under the black label. You need a T10 torx screwdriver.

![](photos/IMG_20231229_215824.jpg)

![](photos/IMG_20231229_215648.jpg)

After removing the screws, use a guitar pick and slide it along the edges to release the clips.

![](photos/IMG_20231229_212156_1.jpg)

![](photos/IMG_20231229_212225.jpg)

![](photos/IMG_20231229_212209.jpg)

Open from the thicker side first, as there are cables at the thinner side that connect the top and bottom board.

![](photos/IMG_20231229_211730.jpg)

Ignore the fan wires, I was experimenting. It's a regular XH plug with 4 wires - red is VCC, black is GND, and the blue and yellow wire are for PWM. If you remove the blue and yellow wire from the connector, the fan will run at full speed all the time. See my other repo for that mod.

If you want to remove the main board, you'll have to remove the nut on the power jack:

![](photos/IMG_20231229_215515.jpg)

I don't have a photo, but the heatsink is removed by flipping the board and squeezing the brass clips together and through the holes. Make sure to replace the thermal paste if you remove the heatsink.

# ATEM Mini Extreme

![](photos/IMG_20240119_163613.jpg)

![](photos/IMG_20240119_163641.jpg)

![](photos/IMG_20240119_163705_edit_452583718897602.jpg)

![](photos/IMG_20240119_163705_edit_452583718897602.jpg)
