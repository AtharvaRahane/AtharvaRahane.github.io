---
layout: project
type: project
image: images/molly.png
title: Icepack Projects

# All dates must be YYYY-MM-DD format!
labels:
  - Simulation
  - ANSYS Icepack
  - Convection Radiation
summary: I simulated radiative and convective heat transfer using Ansys Fluent.
---

## Minimizing Thermal Resistance
In this project I Optimized a heat sink using ANSYS Icepack by minimizing the thermal resistance and reducing the amount of material with temperature constraint of 70 degree Celsius and restrained the total mass of the heat sink to 0.326 Kg
Developed a model composed of FR-4 board of 20.32 cm * 30.48 cm and 1.59 mm thick with CPU dissipating 50 W and a heat sink placed on top of it
Successfully optimized the heat sink by finding a best case with a fin count of 19 fins each of 0.5 mm thickness keeping the system at 69.244 degree Celsius and heat sink mass to 0.31659 Kg


  <img class="ui image" src="../images/Capture7.png">
  
  <em>Table of Optimization, Candidate points</em>

  
 ## Reduced Ordered Model 
Created a step response file using ANSYS Icepack and created a Reduced Ordered Model (ROM) in ANSYS Twin Builder to determine the temperature rise from 4 Field Effect Transistor (FET) placed on board which are thermally managed by forced convection
Create a ROM which can efficiently calculate temperatures at the pre-defined outputs under any transient heat dissipation scenario


  <img class="ui image" src="../images/Capture16.png">
  
  <em>Schematic of Reduced Ordered Model (ROM)</em>
  
  
  
  <img class="ui image" src="../images/Capture17.png">
  

  <em>Temperature Results</em>


 ## Parameterization Using ANSYS Icepack to Optimize Fan Location
Developed a system level model consisting of series of IC chips on a PCB which is cooled by a fan via forced convection having a bonded fin extruded heat sink attached to the IC chip
Carried a study to determine the optimum location of the fan using the parametrization study feature in ANSYS Icepack 
Specified a dynamically updating fan curve and used separate mesh assemblies to reduce the mesh count and generated a summary report for multiple solutions


  <img class="ui image" src="../images/Capture18.png">
  
  <em>Trial 1</em>
  
  
  
  <img class="ui image" src="../images/Capture19.png">
  

  <em>Trial 2</em>



