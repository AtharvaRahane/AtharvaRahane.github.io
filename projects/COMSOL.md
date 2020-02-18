---
layout: project
type: project
image: images/CHIP.jpg
title: Battery Engineering
permalink: projects/COMSOL
# All dates must be YYYY-MM-DD format!
labels:
  - COMSOL
  - ANSYS Fluent
  - Cell Modeling and Simulation
summary: Battery Modeling and Simulation.
---

## Simulation of a Battery Cell Using Multi-Scale Multi-Dimensional Model (MSMD) in ANSYS Fluent
The discharge behavior of a lithium-ion battery ismodeled using Newman, Tiedemann, Gu and Kim (NTGK)
model. The battery is a 14.6 Ah LG Chem LiMn2O4 cathode and graphite anode battery. The results
show that surface monitor plot of discharge curve at 1 C has a decreasing trend and volume monitor plot
of maximum temperature in the domain has slightly increasing pattern over the simulation time. For the
curves of discharge and maximum temperature in the domain, lowest and the highest rate of changes
were seen for O.5 C and 5 C respectively.

  <img class="ui image" src="../images/bat1.jpg">
  
  <em>Geometry and Mesh of a Single Battery Cell</em>


  <img class="ui image" src="../images/bat2.jpg">
  
  <em>Contour Plot of Phase Potential for the Positive Electrode</em>
  
  
  <img class="ui image" src="../images/bat3.jpg">
  
  <em>Contour Plot of Phase Potential for the Negative Electrode</em>
  
  
  <img class="ui image" src="../images/bat4.jpg">
  
  <em>Contour Plot of Temperature</em>
  
  
  <img class="ui image" src="../images/bat5.jpg">
  
  <em>Vector Plot of Current Density</em>
  
  
  <img class="ui image" src="../images/bat6.jpg">
  
  <em>NTGK Model of Discharge Curves</em>
  
  
  <img class="ui image" src="../images/bat7.jpg">
  
  <em>NTGK Model of Temperature for Various Discharge Curves</em>
  
  
  
  <img class="ui image" src="../images/bat8.jpg">
  
  <em>Battery Temperature for Pulse Discharge</em>
  
  
## Electrode Utilization in a Large Format Lithium-Ion Battery Pouch Cell Using COMSOL
Most of the electric vehicle batteries are Lithium-ion batteries. The most used cell design type is the pouch
cell because of its flexibility in sizing as well as stacking. But this flexibility also has a drawback. As the size
and power of a cell is increased the voltage gradients in the highly conductive metal foil current collectors
cause a nonuniform current distribution and electrode utilization in the cell. This leads to a sub-optimal
use and aging of electrode. I have modeled the current distribution and electrode utilization of such a high
power and large lithium-ion cell in COMSOL.
The geometry is a foil to foil unit cell stacking 5 layers in the Z direction which is symmetric along the
center line.
Negative metal current collector foil: 10 µm, Cu
Negative electrode: 60 µm, graphite
Separator: 30 µm
Positive electrode: 60 µm, LMO
Positive metal current collector foil: 10 µm, Al
The electrolyte is LiPF6 in 3:7 EC:EMC
The battery is charged from 20% to 80% cell state-of-charge (SOC) with charge rates of 1C and 4C.


  
