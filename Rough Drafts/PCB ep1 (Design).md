[]
EEVblog #1176 - 2 Layer vs 4 Layer PCB EMC TESTED!
https://www.youtube.com/watch?v=crs_QLuUTyQ
(YouTube Video) Summary
Having a 4 layer board with an inner ground and power plane is better than having a 2 layer board because the emc can be less by 10 - 15 dBuV in the near field. This is due to having shorter pathes creating less noise.

Two-Layer PCB Design Tips: Achieving the Optimal Layout
https://www.youtube.com/watch?v=XkFncBaFlB8
(YouTube Video) Summary
<!-- <> Almost verbatim -->
Common Types of 2 Layer Boards
* Simple Interface/ Connector Boards
* Digital Boards, not high speed
  * May be high speed in a differential pair format
  * <ins>At most</ins> have USB, 100Base-T Ethernet, SPI
  * <ins>Usually</ins> low-speed with I2C, some fast GPIOs
* Analog Boards
  * Low frequency, audio frequencies
* Low Power Boards
* RF Boards (usually sub-GHz)
<!-- </> Almost Verbatim -->
<!-- <> Verbatim -->
Types of 2 Layer Boards (Cont.)
* Lower frequency -> Routed ground (e.g., audio)
* Slower digital -> Relies on ground pour, orthogonal routing
* RF -> Single layer, ground on L2
* All of these -> routed power, large pours for power, etc.
<!-- </> Verbatim -->
Good Design Practices for 2 Layer PCBs:
1. Ground Pour for digital signals
2. Have pours on both sides of the PCB for balancing to avoid warping
3. Slow digital boards tend to use orthogonal traces: top layer(left to right), bottom layer(top to bottom)
4. When your design becomes so dense with traces it does not seem worth to fill with ground pours, it is worth upgrading to 4 layer PCB
5. https://youtu.be/XkFncBaFlB8?si=ie_8g20uoP0i5o8G&t=737

Questions:
What is cross talk?

2-Layer PCB Design Tips - Phil's Lab #137
https://www.youtube.com/watch?v=M6_an34wQJk
(YouTube Video) Summary
