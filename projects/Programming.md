---
layout: project
type: project
image: images/molly.png
title: Fluid Mechanics Programming

# All dates must be YYYY-MM-DD format!
labels:
  - Mathematica
  - Python
  - Machine Learning
summary: Research and Academic Projects.
---
## Flow Classification Using Machine Learning
Classified the following flow as NRe driven flow "ascending flow", NFr driven flow "draining flow" and a mixture "mixed flow" using machine learning.
Developed a fuzzy c mean clustering code using python to classify the flow type.

<img class="ui image" src="../images/Capture43.png">
<em>Above Given is The Input Data</em>

Following results were obtained using the developed algorithm

<img class="ui image" src="../images/Capture44.png">
<em>Result</em>

Class "0" represents mixed flow, class "1" represent ascending flow and class "2" as draining flow.

## Asymptotic (Perturbation) solution of an oscillator
A comparision is made between the exact solution and an asymptotic solution generated using Mathematica to solve the linear oscillator weak damping equation.
<img class="ui image" src="../images/Capture52.PNG">

**Following are the obtained solutions for various assumptions of the asymptotic coefficient b**


<img class="ui image" src="../images/Capture53.jpg">
<em>x=5, b=0.4</em>

<img class="ui image" src="../images/Capture54.jpg">
<em>x=30, b=0.4</em>

<img class="ui image" src="../images/Capture55.jpg">
<em>x=30, b=0.04</em>

## Blassius Boundary Layer Equation for the Prandtl Boundary Layer Theory


<img class="ui image" src="../images/Capture56.PNG">


**Following are the obtained solutions**

<img class="ui image" src="../images/Capture57.jpg">
<em> Comparison of Numerical and Approximate solution for a boundary layer of thickness(x) = 10. The boundary layer ranges from x = 0 (near surface) to x = 10 (Free stream)</em>


<img class="ui image" src="../images/Capture58.jpg">
<em> Comparison of Numerical and Approximate velocity profile for a boundary layer of thickness(x) = 10. The boundary layer ranges from x = 0 (near surface) to x = 10 (Free stream)</em>

## Transitions in the KURAMOTO-SIVASHINKSY equation

**The KURAMOTO-SIVASHINKSY equation is given by**

<img class="ui image" src="../images/Capture61.PNG">

Following is the plot for the data set

<img class="ui image" src="../images/Capture62.jpg">
<em>Data set plot where Y axis represents the spatial location of data set and X axis represent the nth data set</em>

The following data set clearly shows the role of advective and diffusive terms. It can be seen that after each time step the variation of the spatial location increases in magnitude. The reason behind this is the 2nd and the 4th order equation.

<img class="ui image" src="../images/Capture63.jpg">
<em>1D plot of the data</em>

**Flow Classification**
The fuzzy-C-mean clustering approach is used for classifying the data. This approach allows the data to be within one or more clusters. It assigns a membership value to each data point. The summation of the membership value is 1 and its magnitude for a particular group determines the closeness of that point to the respective cluster.

<img class="ui image" src="../images/Capture64.jpg">
<em>Clustered data showing different classes of data set with their respective centers</em>

