# A2 – Truss Stress Analysis


&nbsp;&nbsp;&nbsp;&nbsp;  This assignment focuses on designing and analyzing a lightweight planar truss while applying concepts of strength, stress, and structural design. The process includes developing the truss geometry, analyzing the internal forces and critical pins, determining the required cross-sectional areas using safety factors, and estimating the overall weight. The final design will be modeled in CAD and compared with the analytical results to verify that the truss satisfies the given structural and geometric requirements.

<br><br>
**Given Template:**


&nbsp;&nbsp;&nbsp;&nbsp;  Where P between 20 - 30 kN. a = 0.4 m, b = 0.3 m. Point A is a pin and point B is a roller.  

- P was chosen to equal 20 kN: will cause the least force and stress on the truss.
  
- A-36 steel was chosen as the material because it is a communly used steel and has a yield stress similar to the material pointedin the assingment.

<br><br>
**Design sketching**

&nbsp;&nbsp;&nbsp;&nbsp;  For the truss members to experience either tension or compression, the structure should be composed of triangular elements. Based on this principle, I developed two initial sketch options, as shown below.

<img width="1227" height="412" alt="SmartSelect_20260830_163305_Samsung Notes" src="https://github.com/user-attachments/assets/147e0ddb-f3bc-4e14-b06f-d320d6affb7f" />


&nbsp;&nbsp;&nbsp;&nbsp;  In the end, Sketch B was selected for the final design because its geometry was expected to distribute the tension and compression forces more uniformly throughout the structure.

<br><br>
**Final design FBD**

&nbsp;&nbsp;&nbsp;&nbsp;  After selecting the final truss geometry, I developed the corresponding free-body diagram (FBD) to represent the forces acting on the structure.


<img width="984" height="594" alt="SmartSelect_20260830_175248_Samsung Notes" src="https://github.com/user-attachments/assets/122539fe-0953-4d93-9a85-8f1cee3e60a2" />

<br><br>
**Static Analysis**

&nbsp;&nbsp;&nbsp;&nbsp;  Each joint was analyzed to determine the internal forces in the truss members. The largest internal force was identified to be used in the subsequent structural design calculations.

<img width="1186" height="1215" alt="SmartSelect_20260830_170322_Samsung Notes" src="https://github.com/user-attachments/assets/3b0c2728-81a6-4a1f-a4bf-699551607c8f" />

<img width="1252" height="1798" alt="SmartSelect_20260901_142745_Samsung Notes" src="https://github.com/user-attachments/assets/185cc061-303b-4884-85bf-d3fe0862dda2" />

<img width="1179" height="1676" alt="SmartSelect_20260830_180347_Samsung Notes" src="https://github.com/user-attachments/assets/6cabae6d-3616-4af6-9a99-41fd40b9309c" />


<img width="1183" height="1225" alt="SmartSelect_20260830_190238_Samsung Notes" src="https://github.com/user-attachments/assets/fddef9af-7592-4f17-8f3e-66345f29df25" />

<br><br>
**Truss Cross-sectional Area and Weight Calculation**

&nbsp;&nbsp;&nbsp;&nbsp;  Using the known and calculated values of the maximum internal force (37.97 kN), the selected factor of safety (3.5), and the yield strength of A-36 steel (250 MPa), I determined the minimum required cross-sectional area for the truss members(Amin). This area was then used to estimate the approximate weight of the truss.

<img width="1304" height="1099" alt="SmartSelect_20260901_144008_Samsung Notes" src="https://github.com/user-attachments/assets/0ad1e56d-e3c0-460e-8354-899fbe50aa0f" />

<br><br>
**Pins Cross-sectional Area and Weight Calculation**


&nbsp;&nbsp;&nbsp;&nbsp;  According to the assignment instructions, the pin design should be based on the largest reaction load. Although this is different from the approach I initially expected, I followed the specified criteria. Pin A was selected for analysis because it has fewer forces acting on it, making its FBD and force distribution easier to visualize.


<img width="1321" height="231" alt="SmartSelect_20260901_151804_Samsung Notes" src="https://github.com/user-attachments/assets/4741cfb3-9b00-4940-be32-53301cc53ec5" />


&nbsp;&nbsp;&nbsp;&nbsp;  For this pin, the maximum shear force is taken as the reaction force at A, (Ra), which represents the resultant load transferred through the pin. Additionally, the yield shear strength and the density of the material were provided and converted into SI units. The minimum cross-sectional area of the truss members will be used to establish the required length of the pins.


&nbsp;&nbsp;&nbsp;&nbsp;  Finally, the required pin diameter was calculated and used as a reference for the SolidWorks design.

<img width="1196" height="1831" alt="SmartSelect_20260901_155959_Samsung Notes" src="https://github.com/user-attachments/assets/8fa23c6d-66f4-48fa-85fd-4c046223895b" /> 


<br><br>
**SolidWorks Model**


&nbsp;&nbsp;&nbsp;&nbsp;  Two main designs were created. The first included only the truss members and was used for the simulation and analysis because its simpler geometry made it easier to work with in the software. The second design included the necessary spacing to accommodate the pins.

<img width="995" height="307" alt="image" src="https://github.com/user-attachments/assets/ff56bc3e-668e-45a4-942b-f8e26e41d54f" />


<img width="992" height="307" alt="Screenshot 2026-09-01 152443" src="https://github.com/user-attachments/assets/fa0ebd0c-563e-4faf-8e4e-99a03f018036" />

<br><br>
**Model study**

<br>
<img width="1098" height="481" alt="Screenshot 2026-09-01 153257" src="https://github.com/user-attachments/assets/d0d59064-8e41-431f-b8ff-daeb56129152" />  

The minimum factor of safety throughout the truss in SolidWorks is 3.5. This result agree with the design requirement and calculations.  

<br><br>
<img width="271" height="126" alt="image" src="https://github.com/user-attachments/assets/fb60986c-01cc-4aa1-a261-e71a0a0496fb" />  

Result of the SolidWorks mass properties. The overall body weight was very similar to the calculated value, supporting the accuracy of the design calculations.  


<br><br>
<img width="385" height="487" alt="image" src="https://github.com/user-attachments/assets/fd2c1f17-0e19-49ab-ae47-1f3214cc0998" />  

The internal forces obtained from the SolidWorks simulation were consistent with the calculated internal forces for each truss member, providing further validation of the analytical results.


<br><br>
**Likelihood of Failure Modes in Truss Components**

<br> 

**Truss Members**


&nbsp;&nbsp;&nbsp;&nbsp;  After analyzing the truss, no member is expected to fail under the applied loading, as all members remain within the required factor of safety. However, if failure were to occur, the general failure mode would depend on the type of loading. Members under tension, such as AD and BD, would be expected to experience yielding, while members under compression, such as AB, BC, and CD, would be more susceptible to buckling. Throughout the truss, A-36 steel was used, which is a ductile material.


<br>

**Pins**


&nbsp;&nbsp;&nbsp;&nbsp;  The pins are a greater concern because the pin selected for the maximum shear calculation was based on a support reaction, rather than on the pins experiencing the largest applied loads. In this truss, pins C and D may be more critical because each connection directly transfers a 20 kN applied load. Therefore, these connections should be considered when evaluating the likelihood of pin failure.  

&nbsp;&nbsp;&nbsp;&nbsp;  The expected failure mode for the pins is shear yielding. The pin was designed using a yield shear strength of 170 ksi and a factor of safety of 4, resulting in a required cross-sectional area of 0.2275 cm².  

&nbsp;&nbsp;&nbsp;&nbsp;  To reduce the likelihood of shear failure, the pin diameter could be increased, which would increase its cross-sectional area and reduce the shear stress for the same applied load. Additionally, increasing the material strength of the pin could provide greater resistance to shear.

