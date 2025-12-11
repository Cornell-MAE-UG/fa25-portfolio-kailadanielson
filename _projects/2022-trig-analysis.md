---
layout: project
title: MAE3270 - Torque Wrench Design Project
description: Class project
technologies: [Autodesk Fusion 360, MATLAB, ANSYS]
image: /assets/images/mae3270.png
---

For this project, we analyzed the structural behavior of a torque wrench using both hand calculations and finite element modeling. We created a CAD model using optimized parameters and analyzed the stress, strain, and deformation of the model under loading in ANSYS. 

![CAD Model]({{ "/assets/images/3270cad.png" | relative_url }})

Material:
We chose to use Aluminum 7075 T6 due to it being a common aluminum alloy which has a high strength-to-weight ratio. It has a Young's modulus of 10.4e6 psi, a Poisson's ratio of 0.3, a tensile strength of 83e3 psi, a fracture toughness of 24e3 psi-sqrt(in), and a fatigue strength of 25e3 psi. We found that this material was able to satifsfy our safety and output requirements. 

Loads & Boundary Conditions in FEM model:
To correctly constrain our model in ANSYS, we ensured the location of the drive could not move. We set a load of 600lbf to be applied to the end of the handle, as shown below. 

[Download our report]({{ "/assets/3260 Final Project Report.pdf" | relative_url }}) in PDF format.

Normal Strain Contours:
[Download our report]({{ "/assets/3260 Final Project Report.pdf" | relative_url }}) in PDF format.

Principal Stress Contours:
[Download our report]({{ "/assets/3260 Final Project Report.pdf" | relative_url }}) in PDF format.

Results from FEM:
Through our FEM analysis, we found the maximum normal stress (anywhere) to be 51.7 ksi, the load point deflection to be 0.39 in, and the strain at the strain gauge to be 1152.7 microstrain. We found the torque wrench sensitivity to be 1.15 mV/V. 

Strain Gauge:
For this location we selected a linear foil strain gauge, 350 Ω nominal resistance, with a gauge length of approximately 0.25 in and a grid width of about 0.10 to 0.12 in. This strain gauge was located an inch away from the center of the drive. 


[Download part 1 of our assignment]({{ "/assets/MaterialsFinalHW.pdf" | relative_url }}) in PDF format.

