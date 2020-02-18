---
layout: project
type: project
image: images/bat1.jpg
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

  <img class="ui image" src="../images/bat9.png">
  
  <em>Geometry of the Battery Cell</em>


  <img class="ui image" src="../images/bat10.png">
  
  <em>Potential distribution in the positive metal foil (current collector and tab) at the beginning of
  the 4C charge.</em>
  
  
  <img class="ui image" src="../images/bat11.png">
  
  <em>Potential distribution in the negative metal foil (current collector and tab) at the beginning of
the 4C charge.</em>


  <img class="ui image" src="../images/bat12.png">
  
  <em>Current distribution in the middle of the separator at the beginning (t = 0 s) of the 4C charge.</em>


  <img class="ui image" src="../images/bat13.png">
  
  <em>Current distribution in the middle of the separator at t = 315 s of the 4C charge.</em>
  
  
  <img class="ui image" src="../images/bat14.png">
  
  <em>Current distribution in the middle of the separator at end t = 630 s of the 4C charge.</em>
  
  
  <img class="ui image" src="../images/bat15.png">
  
  <em>Current distribution in the middle of the separator at the beginning (t = 0 s) of the 1C charge.</em>
  
  
  <img class="ui image" src="../images/bat16.png">
  
  <em>Current distribution in the middle of the separator at t = 1260 s of the 1C charge.</em>
  
  
  <img class="ui image" src="../images/bat17.png">
  
  <em>Current distribution in the middle of the separator at end t = 2520 s of the 1C charge.</em>
  
  
  <img class="ui image" src="../images/bat18.png">
  
  <em>Relative electrode utilization at t = 315 s during 4C charge.</em>
  
  
  <img class="ui image" src="../images/bat19.png">
  
  <em>Relative electrode utilization at t = 630 s during 4C charge.</em>
  
  
  <img class="ui image" src="../images/bat20.png">
  
  <em>Relative electrode utilization at t = 1260 s during 1C charge.</em>
  
  
  <img class="ui image" src="../images/bat21.png">
  
  <em> Relative electrode utilization at t = 2520 s during 1C charge.</em>
  
## Aging of Lithium-Ion Battery
Complex multiple reaction occurring simultaneously at different places under various load cycle and other
variables may lead to capacity loss resulting in aging of lithium-ion batteries. Cell materials of varying
composition age differently. This combination may result in further cross-talk leading to accelerated aging.
I modeled the aging in the negative graphite electrode, where a parasitic solid-electrolyte-interface (SEI)
forming reaction results in irreversible loss of cyclable lithium. The model also includes the effect of an
increasing potential losses due to the resistance of the growing SEI film on the electrode particles, as well
as the effect of reduced electrolyte volume fraction on the electrolyte charge transport.


  <img class="ui image" src="../images/bat22.png">
  
  <em>Cell voltage during discharge for different cycle numbers</em>
  
  
  
  <img class="ui image" src="../images/bat23.png">
  
  <em>Capacity versus total accumulated cycling time.</em>
  
  
  
  <img class="ui image" src="../images/bat24.png">
  
  <em>Capacity versus cycle number.</em>
  
  
  
  <img class="ui image" src="../images/bat25.png">
  
  <em>Electrolyte volume fraction versus cycle number.</em>
  
  
  
  <img class="ui image" src="../images/bat26.png">
  
  <em>SEI film potential drop versus cycle number.</em>
  
  
  
  <img class="ui image" src="../images/bat27.png">
  
  <em>Local state-of-charge on the separator-electrode boundaries.</em>
