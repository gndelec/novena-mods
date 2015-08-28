# Novena Micro Fan Assembly

![A Novena board with the micro fan assembly fitted](/images/fitted.jpg)

An ultra-slim micro fan complete with fixings for securing over the Novena's Freescale SoC.

Designed for when running computationally-intensive workloads which would otherwise cause the processor to get too hot and the CPU governor to kick in and throttle the clock speed. Typical applications including software-defined radio (SDR) and large parallel software builds.

Power is taken from the front-panel PCB that is fitted to All-in-One Desktop and Laptop configurations, and can be controlled via GPIO (default state is on). The power consumption is ~0.3W.

A ready made assembly can be bought from [Ground Electronics](http://groundelectronics.com/products/novena-micro-fan-assembly).

## Repository contents

* Adobe Illustrator (source)
* SVG
* PDF
* DXF

To be cut from 3mm acrylic. Etched areas to allow for counter-sinking of screw heads (aim for depth of approx 1mm).

## Bill of materials

In addition to the acrylic part the NMFA-01 is made up from:

| Qty | Item                                |
| --- | ----------------------------------- |
|  1  | SEPA MF15B-05 fan                   |
|  1  | 2 way 2.5mm pitch JST socket        |
|  1  | 30cm 2-core wire                    |
|  2  | M2.5x10mm F-F hex metal standoff    |
|  2  | M2.5x6mm countersunk steel screw    |
|  2  | M2.5 fibre washer                   |

## Assembly

- Remove the two hex screws that are either side of the Freescale SoC (read heatsink).

![Freescale SoC](/images/assembly_1.jpg)

- Fit the hex standoffs in place of the screws, but be careful not to over-tighten.

![Standoffs fitted](/images/assembly_2.jpg)

- Place the fibre washers on top of the stand-offs, locate the fan assembly on top and secure in place with the M2.5 countersunk srews.

![Fan fitted in place](/images/fitted.jpg)

- Plug the power connector into the 5V output on the front panel PCB.

![Connector inserted](/images/assembly_4.jpg)

**WARNING: Please note that due to the minimal clearance this must only be used with the screen/lid open and use with it closed could result in hardware failure!**

## Changelog

| Version | Date     | Summary
|---------|----------|--------------------

