# A9 – Pulleys

## Introduction


&nbsp;&nbsp;&nbsp;&nbsp; Design a pulley system to transfer power between two parallel axes separated by a center distance of 4–6 inches. The system must meet the following requirements:

- Pulley Diameter: Both pulleys shall have a diameter of 3 inches.
- Rotational Speed: Select an operating speed between 1000–2000 rpm.
- Belt Tension (Static): Select a belt tension between 4–6 lbf under stationary conditions.
- Material: Pulleys may be made from aluminum, ABS, or steel, and may include a groove and shaft diameter of your choosing (within reasonable manufacturing limits).
- Safety Factor: The design must satisfy a minimum safety factor of 3.
- Assume the belt is made from polyurethane rubber, with a yield strength of 3.25 MPa (471 psi) at 20% strain, based on: Wanga, Chena, Wua, Zhangb, Suna, “Strain-induced Structural and Dynamic Changes in Segmented Polyurethane Elastomers.”


<img width="295" height="100" alt="download" src="https://github.com/user-attachments/assets/442a48ee-c490-4eba-9556-4929a68ba12e" />



## 1) Belt Design


&nbsp;&nbsp;&nbsp;&nbsp; To select a suitable belt, the tension forces on its tight and slack sides were first calculated. These forces were then used to determine the minimum belt diameter based on the allowable tensional normal stress.

&nbsp;&nbsp;&nbsp;&nbsp; A specific static friction coefficient for the aluminum pulley and rubber belt combination could not be determined because the available research articles were either inaccessible to the public or required paid access.

<img width="876" height="1229" alt="1440" src="https://github.com/user-attachments/assets/1fb91dd7-1bf8-46cf-a1b0-44a44b36c87d" />

<img width="1169" height="1404" alt="1441" src="https://github.com/user-attachments/assets/9bc2804e-c21f-453d-ae0d-573a70a39f96" />


&nbsp;&nbsp;&nbsp;&nbsp;  Therefore, as shown in the image, the selected belt was the polyurethane rubber belt (3044K707), with a diameter of 5/16 in and a total length of 24 1/4 in.


## 2) Shaft design


&nbsp;&nbsp;&nbsp;&nbsp; To design the pulley shaft, the torque and shear stress equations were combined to derive an expression for the shaft diameter using only known variables.


<img width="1139" height="1562" alt="1442" src="https://github.com/user-attachments/assets/63bfee85-f5e0-46c4-a19b-e918d7392393" />


&nbsp;&nbsp;&nbsp;&nbsp;  After rounding up to the nearest 1/16 in, the calculated shaft diameter was 3/16 in. However, this diameter was not available through McMaster-Carr, where the smallest available diameter was 1/4 in. Therefore, an alternative solution would be required to accommodate the available shaft dimensions.


## 3) Journal bearing design



&nbsp;&nbsp;&nbsp;&nbsp;  The journal bearing material was selected by calculating the maximum operating speed, bearing pressure, and PV value, then comparing these results with the allowable material limits listed in Table 4, page 2440, of the Machinery's Handbook.


<img width="1120" height="784" alt="1443" src="https://github.com/user-attachments/assets/7efa3425-3b98-41de-8772-9c9afb064964" />


&nbsp;&nbsp;&nbsp;&nbsp; The selected material was porous bronze, as it satisfies all calculated operating constraints. Additionally, it is a commonly used bearing material that offers several commercially available options.


## 4) Frame design


<img width="1035" height="408" alt="1444" src="https://github.com/user-attachments/assets/6edda738-301d-451c-ac9e-b31a22ae0e0e" />


## 5) Final notes

**Lesson learned:** I learned how belt tension, friction, and pulley geometry influence system design. Most importantly, I also learned to consider commercially available components early in the design process, since calculated dimensions may not match available sizes.

**Time taken:** A total of 5 hours was required to complete the assignment.
