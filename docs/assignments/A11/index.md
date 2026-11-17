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

## Analyze and design a Frame (Ana Carolina)

### Bracket design

&nbsp;&nbsp;&nbsp;&nbsp;  To desing the bracket the wort case scenario witll be used, in witch all toque of the motor is transfered to the frame instead of the lead screw. And as instructed in the assingment the reactions will be analyzed at the ends of the top frame instead of the bracket screw, where they would mostly be locaded in real life.


Only one bracket was found that worket with the geometry of the frame component. lets check if it stands the forces acting on it, unfortunately that would be to complicated to do, therefore it will be done on solidworks, with material being aluminium (6063-T6) and the forces and fixtures being added into the wholes themsellves.


<img width="887" height="618" alt="Screenshot 2026-11-17 121808" src="https://github.com/user-attachments/assets/e9965e2b-6b50-498c-b9f5-84f929ecebcf" />


<img width="797" height="558" alt="Screenshot 2026-11-17 121826" src="https://github.com/user-attachments/assets/a1a42dcc-6c95-40c8-91dc-754fd730f6b2" />

Therefore, according to study the bracket does work with the according 4 safety factor.

### Top frame verification

&nbsp;&nbsp;&nbsp;&nbsp; Frame from previos fbd was created and the forces applied to it were simulated, using the edge faces as fixed supports to simplify it and to further maqtch the calculations.

<img width="1348" height="342" alt="Screenshot 2026-11-17 160706" src="https://github.com/user-attachments/assets/384ac155-cf46-4882-9c6c-cfc4057f9990" />


Closer view to model setup:

<img width="792" height="452" alt="Screenshot 2026-11-17 160718" src="https://github.com/user-attachments/assets/e343ef44-c681-424c-8c5d-515980000f66" />


Study results: The study showed that the factor of safety under the stress of the material is kept at a higher value than needed, and the deflection is kept at mkinimum, therefore the top frame was successfully verified.

<img width="1166" height="501" alt="Screenshot 2026-11-17 161622" src="https://github.com/user-attachments/assets/703d6d3b-c76f-405d-a3be-82bed9277bc2" />

<img width="1103" height="507" alt="Screenshot 2026-11-17 161906" src="https://github.com/user-attachments/assets/dd603b2e-daac-4558-8a3d-f8ade346f5be" />

<img width="1126" height="462" alt="Screenshot 2026-11-17 161745" src="https://github.com/user-attachments/assets/f41bc9a4-e460-49b7-a5eb-74f8c48a3917" />

