# zigflea

The ZigFlea board provides an easy way of using ZigBee wireless communication together with Dan Overholt’s CUI32Stem sensor interface

The board is the result of the Master’s thesis of Øyvind Hauback, which he carried out as part of the Sensing Music-related Actions project in the fourMs group. It is described more thoroughly in Øyvind’s thesis (in Norwegian), as well as in short form (and English) in our NIME 2012 paper. Here are the technical details, taken from the Seedstudio web page:

Based on the Freescale MC13201 transceiver, which supports the IEEE 802.15.4 standard used by ZigBee and ZigFlea. Serial Peripheral Interface (SPI) pins are provided as standard, with the layout matching the CUI32Stem pin locations. The transceiver runs at 2.4 GHz and has support for 16 channels and a speed of up to 250 Kbps.

ZigFlea is a subset of the ZigBee protocol, as implemented in StickOS. It equals ZigBee regarding the physical layer, but is a point-to-point protocol focused on sending in only one direction at a time (half-duplex). The benefit of this is that the protocol stack is as little as 3 KB, as compared to the 30 KB for ZigBee (which includes multiple hops and other features).

* [More information](https://www.uio.no/ritmo/english/research/labs/fourms/downloads/hardware/zigflea/index.html)
