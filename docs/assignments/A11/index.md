# A11 – Motor Selection Design

## Motor Selection (Ana Carolina)

&nbsp;&nbsp;&nbsp;&nbsp; To select an appropriate motor for the design, it was necessary to identify a model capable of delivering sufficient output torque throughout the required rotational speed range. These parameters were previously calculated in the lead screw section of the preceding assignment, as follows: 

- Torque = 14.31 lbf*in = 229 in*ozf
- Rot. speed range = 0.3937 - 19.68 RPM

**Obs:** An error was identified in the initial rotational speed calculation. The specified linear speed was mistakenly interpreted as mm/s rather than the correct unit, mm/min. This unit conversion error was corrected, and the revised rotational speed value is being used in the subsequent motor selection process.

### Motor selected:

&nbsp;&nbsp;&nbsp;&nbsp;  The selected motor is the NEMA 23 stepper motor (McMaster-Carr part number 6627T631). It provides an output torque ranging from 240 to 260 ozf·in across the required rotational speed range when operated at 7.07 A with parallel wiring or 3.54 A with series wiring. 
&nbsp;&nbsp;&nbsp;&nbsp;  Additionally, its stepper motor design allows for precise and repeatable control of the crosshead velocity, which is essential for maintaining the specified testing conditions. Its compact dimensions also make it suitable for integration into the tensile tester's benchtop configuration. Among the NEMA 23 options evaluated, this model was the least expensive alternative that satisfied the required torque specifications.
&nbsp;&nbsp;&nbsp;&nbsp; DC motorswere to fast and didnt deliver as much torque as needed, and gearmotors proved hard to understand when choosing a model on master car, therefore thats why I landed on stepper motors, besides the name "NEMA" sounded familiar since we were introduced to it during classes.

**Motor link:** https://www.mcmaster.com/6627T631/ 

<img width="464" height="601" alt="Motor picture" src="https://github.com/user-attachments/assets/1821522f-babb-4236-bec5-d0b0a33db8a5" />

<img width="1050" height="811" alt="Motor dimentions" src="https://github.com/user-attachments/assets/2825f8be-3567-4bf8-90e4-f4ed6ae40670" />



<img width="377.5" height="286" alt="Torque speed charch 3A" src="https://github.com/user-attachments/assets/d4ec2557-814f-4814-8017-274885c9c11c" />
<img width="377.5" height="286" alt="Troque speed charch 7A" src="https://github.com/user-attachments/assets/76320a6e-c0ec-4df0-b8a9-68bf3bc6b9f8" />




need the charchas and important info.

## Analyze


## Decide
_Reference your concept selection (Pugh matrix) here. How does this design follow from that decision?_

## Communicate
