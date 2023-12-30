# ATEM-mini-inside-photos
What's inside ATEM Mini Pro ISO. Photos of the main board.

Under the heatsink is the main component: a system on chip (SOC) that contains three ARM processors and an FPGA! Atem Mini Pro ISO runs on Xilinx Zynq UltraScale+ EV.

![](photos/IMG_20231229_195931.jpg)

HDMI input 1 goes into TMDS171.
Other HDMI inputs go into ADV7610.

There's an exposed and labeled UART and it sends some info during the boot.

There's also an HDMI footprint, but no HDMI connector soldered. I did detect some clock signal on it. It would be interesting to solder an HDMI connector and see what's there.



