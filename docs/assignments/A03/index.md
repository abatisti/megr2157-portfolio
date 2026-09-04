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

<br><br>
<img width="1463" height="762" alt="Screenshot 2026-09-03 131226" src="https://github.com/user-attachments/assets/3584f0ec-2b77-4ecb-97af-9fb6444cb02e" />
The resulting maximum deflection was 0.008998 in, which closely matches the target deflection of 0.009 in.  

<br><br>
<img width="1497" height="718" alt="Screenshot 2026-09-03 131210" src="https://github.com/user-attachments/assets/563777c8-4919-4977-a090-aca64e3d9756" />
The maximum Von Mises stress was \(5.663\times10^2\) psi, which is significantly below the material's yield strength.

<br><br>
<img width="1491" height="762" alt="Screenshot 2026-09-03 131252" src="https://github.com/user-attachments/assets/91ca7709-2cb9-4478-bd37-c7a6857c7cff" />
The minimum factor of safety throughout the part was 14, further indicating that the design remains below the material's yield limit under the applied load.

<br><br>
**Result Reflection**


- Percentage difference:
<img width="1332" height="536" alt="SmartSelect_20260903_132629_Samsung Notes" src="https://github.com/user-attachments/assets/77a2fb67-f39e-4e65-a1f2-498f1227b455" />

&nbsp;&nbsp;&nbsp;&nbsp;  The calculated and simulated deflections are essentially the same, and the small difference can be attributed to numerical precision and the finite element approximation used in the simulation. The FEA result can be trusted more because it accounts for the modeled geometry and loading conditions directly.


<br><br>
**Modify Design Parameters**


The new design parameters are:   

- The cross-sectional dimension was increased to d=5 in, resulting in an area of A=25 in^2.
- The applied load was increased to F=60,000 lbf.


&nbsp;&nbsp;&nbsp;&nbsp; With these new values, the required bar length is expected to decrease because the increase in load is proportionally greater than the increase in cross-sectional area, resulting in a shorter length for the same target deflection.


- Results

  
&nbsp;&nbsp;&nbsp;&nbsp;  As expected, the resulting length was smaller than the previously calculated length. The deflection remained very close to the target value, while the overall stress increased and the factor of safety decreased considerably.


<img width="1213" height="548" alt="Screenshot 2026-09-04 182510" src="https://github.com/user-attachments/assets/109471d0-df58-4fbf-b782-367d2d90096c" />

<img width="1215" height="598" alt="Screenshot 2026-09-04 182455" src="https://github.com/user-attachments/assets/2210a388-e9fb-46c6-8cf6-0c19d0c88c4b" />

<img width="1157" height="573" alt="image" src="https://github.com/user-attachments/assets/519179cd-6d01-44f7-86a1-20645681b5b8" />




**Final Note**


&nbsp;&nbsp;&nbsp;&nbsp; This project took approximately 4 hours to complete, and no significant errors were encountered during the design and analysis process.



**Solidworks Link**


Model 1:  

https://1drv.ms/u/c/18c7b03a5d0433a3/IQBy-eWoYJCgSphpj3KuiF0EAWltDo41Frg7pJZ21T3tCc0?e=GmNQAH 


Model 2:  

https://1drv.ms/u/c/18c7b03a5d0433a3/IQAIFq0Kk0DNTbuf5MvlTKrsAcwp2BacciWxWtAU3ckMmUM?e=ql2FXo
