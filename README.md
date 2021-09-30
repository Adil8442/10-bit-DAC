# 10-Bit-Potentiometric-DAC

This project presents the design of a 10 Bit Potentiometric Digital to Analog Converter using end-to-end Open-source EDA tools. The aim is to design a 10-bit potentiometric Digital to Analog Converter(DAC) with 3.3V analog voltage, 1.8V digital voltage  using the sky130nm technology node.

# Opensource Tools used

1. eSim: eSim is a Free and Open source EDA tool for circuit design, simulation, analysis and PCB design developed by FOSSEE, IIT Bombay. It is an integrated tool built using free/libre and open source softwares such as KiCad, Ngspice and GHDL. It serves as an alternative to commercially available/ licensed software like OrCAD, Xpedition and HSPICE. For more info refer: https://esim.fossee.in/home

2. Ngspice: Ngspice is the open source spice simulator for electric and electronic circuits. Ngspice offers a wealth of device models for active, passive, analog, and digital elements. Model parameters are provided by the semiconductor device manufacturers or from semiconductor foundries. The user simply adds his/her circuits as a netlist, and the output is one or more graphs of currents, voltages and other electrical quantities or is saved in a data file. For more info refer: http://ngspice.sourceforge.net/

3. Skywater Pdk: The SkyWater Open Source PDK is a collaboration between Google and SkyWater Technology Foundry to provide a fully open source Process Design Kit and related resources, which can be used to create manufacturable designs at SkyWater’s facility. As of May 2020, this repository is targeting the SKY130 process node. For more info refer: https://github.com/google/skywater-pdk, https://skywater-pdk.rtfd.io

# Pre Layout Simulations
   
  # switch 
  
 The screenshots of the switch circuit schematic is shown below:
   
 ![](Schematics/switch_A.png)

The result of transient analysis of the switch is shown below:

 ![](Schematics/switch_A_op.png)
