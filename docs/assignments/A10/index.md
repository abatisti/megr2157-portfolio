# A10 – Lead Screw Design


## Introduction (Ana Carolina)


&nbsp;&nbsp;&nbsp;&nbsp;  Design and build a mechanically driven tensile tester capable of applying up to 2 kN axial tensile load with a controllable crosshead speed from 1 to 50 mm/min. Each team is responsible for the mechanical components outlined below. The system will provide consistent, well-aligned loading for polymers and light metals, suitable for instructional use and basic materials evaluation.


**Key Constraints**  
- No electronics, no software: purely mechanical.
- Load capacity: 2 kN (with appropriate safety factor in structure and drivetrain).
- Speed range: 1–50 mm/min (achieved via screw lead selection).
- Form factor: bench-top footprint favored; manageable overall height; 18 inch leadscrew minimum.
- Safety Factor: 4




## Lead screw design (Ana Carolina)

### Minimum diameter: 

&nbsp;&nbsp;&nbsp;&nbsp;  The minimum minor diameter was determined by analyzing the allowable tensile stress in the lead screw while incorporating the required factor of safety.  
&nbsp;&nbsp;&nbsp;&nbsp; The selected material was carbon steel. Since the design does not require the higher strength of alloy steel, carbon steel was considered sufficient to meet the design requirements while offering a lower material cost.


<img width="1168" height="1468" alt="1462" src="https://github.com/user-attachments/assets/ade05e6d-16c0-42c6-9216-86df5004e385" />


### Rotational speed:

&nbsp;&nbsp;&nbsp;&nbsp;  To calculate the rotational speed required to achieve the specified linear speed, a lead screw had to be selected to determine its travel per revolution (lead). Therefore, the screw that best matched the diameter calculations was the smallest available option. Upon further inspection, its minor diameter was found to be 0.4 inches, significantly exceeding the calculated minimum requirement.

**Screw chosen:** 

<img width="1422" height="472" alt="image" src="https://github.com/user-attachments/assets/3f428395-68ac-466a-b2fd-0e26ff82bf8b" />

**Rotational Speed Calculations:**  The rotational speed was calculated in both revolutions per minute (RPM) and radians per second (rad/s) to express the required screw rotation in two different units.

<img width="1381" height="1886" alt="1463" src="https://github.com/user-attachments/assets/b5846b6d-5f24-4f82-8a79-115e72ea0453" />


### Maximum torque:  

&nbsp;&nbsp;&nbsp;&nbsp; The maximum torque will be calculated using the equation provided in Machinery's Handbook, page 2647:

<img width="1716" height="627" alt="c832fc3a-23e7-4b8b-838d-642d1b0e5554" src="https://github.com/user-attachments/assets/a353a2d7-ef11-4a8f-8263-d220c511c6bf" />

**Torque calculations**


<img width="1183" height="702" alt="1464" src="https://github.com/user-attachments/assets/638e2ae7-c11d-437d-965a-fd6cf51d776f" />


### Screw Chosen:

&nbsp;&nbsp;&nbsp;&nbsp; After completing all calculations, the lead screw selected in the rotational speed section was retained as the final design choice. The selected component is the 2 ft long, 1/2"-10 ACME carbon steel lead screw (McMaster-Carr part number 98935A911).

<img width="1422" height="472" alt="image" src="https://github.com/user-attachments/assets/3f428395-68ac-466a-b2fd-0e26ff82bf8b" />


## 2) Nut and Flange Design (Ana Carolina)

By applying the following selection criteria to the available nuts and flanges:  

- Material: Bronze
- Thread Size: 1/2"-10
- Thread direction: Right-hand
- Class: 2G

The remaining suitable option was the 932 Bearing Bronze Flange Nut (McMaster-Carr part number 95120A111):

<img width="1107" height="397" alt="image" src="https://github.com/user-attachments/assets/b201278c-4c81-4aeb-88ac-256417c7b033" />


 &nbsp;&nbsp;&nbsp;&nbsp; With the flange nut already selected, the next step is to evaluate the nut threads' bending stress and verify that it does not exceed the allowable stress of the material after accounting for the required factor of safety.


<img width="1170" height="1462" alt="1465" src="https://github.com/user-attachments/assets/92980696-e9be-41da-849e-3ae4e37b8117" />


&nbsp;&nbsp;&nbsp;&nbsp; The allowable stress was found to exceed the calculated bending stress in the nut threads. Therefore, the selected flange nut satisfies this design criterion and is approved based on thread bending stress.


## Designing the Crosshead (Logan Dreifuss)

I discussed with my teammates regarding what beam analysis model to use: "both ends overhanging supports", "supported at both ends", or "fixed at both ends". We decided on "fixed at both ends" model, because that prevents the crosshead from twisting at its ends.

<img width="1892" height="2220" alt="1" src="https://github.com/user-attachments/assets/21999318-b518-4b89-be39-ccc878808d8a" />


The diameter of the flange that the team decided on was 1.25 inches, so I used that for the minimum base dimension (converting to mm, which results in a base length of 31.75 mm). With a combination of research and the knowing the height of the lead screws we were using, we decided that the length of the crosshead (between the centerlines of the lead screws) would be 1 foot (which, converted to metric, is 304.8 millimeters).


The team decided that the material for the crosshead would be ASTM A36 steel, which has an elastic modulus of 2x10^11 N/m^2, and a yield strength equal to 2.5x10^8 N/m^2. As such, the stress/strain analysis resulted in a height of 1.054x10^-3 mm, and the deflection analysis resulted in a height of 28.145 mm, which is the height we decided to use for the crosshead.


<img width="2362" height="1272" alt="2" src="https://github.com/user-attachments/assets/7397ddf6-3e1e-48a6-873c-02a07add59f5" />


### Drawings:

<img width="3065" height="1342" alt="3" src="https://github.com/user-attachments/assets/8a7ffa11-44e9-4c2c-9a96-6be0e48eae0c" />

<img width="3007" height="1345" alt="4" src="https://github.com/user-attachments/assets/7a2a7b66-03cd-470d-9bbd-661bb218bd19" />


## Tabulating Costs (Logan Dreifuss)

| Item Number | Quantity | Name | Cost/Item | Cost | Purchase Link |
| --- | --- | --- | --- | --- | --- |
| #1 | 2 | Lead Screw | $6.95 | $13.90 | [Lead Screw Purchase Link](https://www.mcmaster.com/98935A911/) |
| #2 | 2 | Flange Nut | $125.72 | $251.44 | [Flange Nut Purchase Link](https://www.mcmaster.com/95120A111/) |
| --- | --- | --- | Total Cost: | $265.34 | --- |

