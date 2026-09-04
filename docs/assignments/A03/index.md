# A3 – Parametric and FEA


This assignment focuses on designing for stiffness by analyzing a bar under an axial load using parametric modeling and finite element analysis (FEA). The objective is to investigate how force, geometry, and material properties affect axial deflection and use these relationships to develop and evaluate a suitable bar design.

**Design Choices**


&nbsp;&nbsp;&nbsp;&nbsp;  - A square cross-sectional shape was selected to simplify the geometry and analysis. The cross-sectional area is defined by A=d^2, where d is the side length. And dimension of d=1 in was selected, resulting in a cross-sectional area of A = 1 in^2. This provides a simple and consistent geometry for the analysis.  

&nbsp;&nbsp;&nbsp;&nbsp;  - An axial force of 500 lbf was selected to produce the shortest required shaft length, reducing the overall shaft length for the design.  

&nbsp;&nbsp;&nbsp;&nbsp;  - Based on the specified Young’s modulus range of (8.5-11.5) *10^6 psi, 6061 aluminum alloy was selected from the available materials in SolidWorks. The Young’s modulus of the selected material in SolidWorks is \(E=10,007,603.9\) psi.

<br><br>
**Solidworks Model**

&nbsp;&nbsp;&nbsp;&nbsp;  The design was developed in SolidWorks by assigning the selected parameters (Young’s modulus, maximum allowable deflection, applied load, and cross-sectional dimensions) to parametric equations to determine the required bar length.
<img width="793" height="262" alt="Screenshot 2026-09-03 130518" src="https://github.com/user-attachments/assets/7b572bd6-3d66-4ff1-a8bb-342d2d4b7efd" />

<br><br>
**Results**

After modeling the design and running a study using the selected applied force, the following results were obtained:

<img width="1463" height="762" alt="Screenshot 2026-09-03 131226" src="https://github.com/user-attachments/assets/3584f0ec-2b77-4ecb-97af-9fb6444cb02e" />
The resulting maximum deflection was 0.008998 in, which closely matches the target deflection of 0.009 in.  

<br>
<img width="1497" height="718" alt="Screenshot 2026-09-03 131210" src="https://github.com/user-attachments/assets/563777c8-4919-4977-a090-aca64e3d9756" />
The maximum Von Mises stress was \(5.663\times10^2\) psi, which is significantly below the material's yield strength.

<br>
<img width="1491" height="762" alt="Screenshot 2026-09-03 131252" src="https://github.com/user-attachments/assets/91ca7709-2cb9-4478-bd37-c7a6857c7cff" />
The minimum factor of safety throughout the part was 14, further indicating that the design remains below the material's yield limit under the applied load.

<br><br>
**Result Reflection**


- Percentage difference:
<img width="1332" height="536" alt="SmartSelect_20260903_132629_Samsung Notes" src="https://github.com/user-attachments/assets/77a2fb67-f39e-4e65-a1f2-498f1227b455" />

&nbsp;&nbsp;&nbsp;&nbsp;  The calculated and simulated deflections are essentially the same, and the small difference can be attributed to numerical precision and the finite element approximation used in the simulation. The FEA result can be trusted more because it accounts for the modeled geometry and loading conditions directly.

This assingment took less than 1 hours so far, no mistakes were done so far.
