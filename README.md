# NOAABandpass

A bandpass filter & bias-T powered LNA for receiving APT & LRPT satellite images in the 137MHz region.

![PCB top side](readmeimages/NOAABandpass-top.png?raw=true "PCB top side")
![PCB underside](readmeimages/NOAABandpass-bottom.png?raw=true "PCB underside")

The design uses a 3rd-order Butterworth capacitively-coupled LC resonator filter, followed by a Mini-Circuits MMIC preamp.

Supply voltage is 3V-5V to the bias T. 

![Schematic](readmeimages/schematic.png?raw=true "Schematic")
![Filter response](readmeimages/response.png?raw=true "Filter response")

