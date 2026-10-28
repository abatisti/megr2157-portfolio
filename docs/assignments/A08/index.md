# A8 – Gears

## Introduction

&nbsp;&nbsp;&nbsp;&nbsp;  The objective of this assignment is to design a gearbox that can be assembled and disassembled. The design focuses on selecting and dimensioning the spur gears, shafts, and journal bearings to ensure proper operation, adequate strength, and sufficient clearance between components. Engineering equations from Machinery’s Handbook will be used to determine the required dimensions, evaluate bearing pressure and sliding velocity, and select appropriate materials and fits.


**Description:**  


Design a gearbox which can be assembled and disassembled. The spur gears have a gear ratio of 24:9 and are listed in the resource section. The output gear torque and speed are to be 1.25 in-lbf and 1100 rpm relative. The input (pinion,power-transmission) and output (gear, short shaft) shaft diameters are .125 and .25 inches respectively and each have a length of 1 inch. Use the appropriate equations in the Machinery’s Handbook for empirical units. The critical features of the gearbox include the shafts, and the journal bearings.


**Assumptions:**
  
  - Assume appropriate strength of shafts, use Machinery’s Handbook.
  - The gear train is ideal.
  - The moment of the radial force from the gear train is small enough to be ignored.


**Note:**
  
  - The shafts are press fit through the hubs of the gears.
  - Make sure there is enough clearance between the gears and the gearbox.
  - Use a running sliding fit for the size of the hole for the shafts.



## 1) Design for the shafts

&nbsp;&nbsp;&nbsp;&nbsp;  In this section it will be evaluated whether the specified shaft diameters satisfy the design requirements under the expected operating conditions. The shafts will be analyzed using the appropriate engineering equations from Machinery’s Handbook to verify their strength and suitability for transmitting the required torque and rotational speed.


<img width="1198" height="1313" alt="1409" src="https://github.com/user-attachments/assets/0e1819c2-5afb-4f6d-881d-a00f2be82897" />


&nbsp;&nbsp;&nbsp;&nbsp;  Following the calculations, the specified shaft geometry was approved, as it satisfies the required design criteria for the intended operating conditions.


## 2) Design for the journal bearings: 


&nbsp;&nbsp;&nbsp;&nbsp;  The objective of this section is to select a suitable journal bearing material by analyzing its pressure, sliding velocity, and pressure-velocity (PV) rating.

<img width="1002" height="1425" alt="1410" src="https://github.com/user-attachments/assets/71b65be8-2beb-4a2f-924d-e3bff464ccae" />
<img width="1207" height="1170" alt="1411" src="https://github.com/user-attachments/assets/0cc06a6c-1b66-4595-a70d-77cee7ac154b" />


&nbsp;&nbsp;&nbsp;&nbsp;  Therefore, porous brass was selected as the journal bearing material for this design.  

&nbsp;&nbsp;&nbsp;&nbsp;  Additionally, an error was identified in this section: the bearing length was initially selected arbitrarily rather than determined from the specifications of the exact McMaster-Carr component chosen. The correct approach would have been to select the bearing model first and use its specified length in the subsequent calculations for its material.


## 3) Gearbox sketch:

&nbsp;&nbsp;&nbsp;&nbsp;  This is a rough sketch of the designed gearbox, plus a couple of calculations used for its design.  


<img width="1043" height="1661" alt="1413" src="https://github.com/user-attachments/assets/70369d65-fbfe-4bbd-b005-a090bf27ab8e" />



## 4) CAD model:

&nbsp;&nbsp;&nbsp;&nbsp;  First I started building both of my shafts, using the hole of the gear as dimeter and 1 inch as lengh.  

&nbsp;&nbsp;&nbsp;&nbsp; At this stage, another error was made, as the appropriate clearance between the shaft and the journal bearing was not included. This oversight was only identified later in the design process, when the tolerances were being specified in the technical drawings.


