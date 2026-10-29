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

**Input bearing:** https://1drv.ms/u/c/18c7b03a5d0433a3/IQAZeP35LllKT6Ep9sh3ioyEAXXha0GKGxNK-xVV6vwO-K4?e=BGPaik

**Output bearing:** https://1drv.ms/u/c/18c7b03a5d0433a3/IQBTPEVv9R6ASpGgDa1GfJ7GAS3BS5dYBApzxTBrABVlCzo?e=Keo8xR


## 3) Gearbox sketch:

&nbsp;&nbsp;&nbsp;&nbsp;  This is a rough sketch of the designed gearbox, plus a couple of calculations used for its design.  


<img width="1043" height="1661" alt="1413" src="https://github.com/user-attachments/assets/70369d65-fbfe-4bbd-b005-a090bf27ab8e" />



## 4) CAD model:


**Shafts**


&nbsp;&nbsp;&nbsp;&nbsp;  First I started building both of my shafts, using the hole of the gear as dimeter and 1 inch as length. The shafts were modeled by first extruding the basic geometry to the of 1 inch length. After assembling the shafts into the gearbox, a smaller-diameter section was added to each shaft to help secure it within the housing and minimize unwanted movement.

&nbsp;&nbsp;&nbsp;&nbsp; At this stage, another error was made, as the appropriate clearance between the shaft and the journal bearing was not included. This oversight was only identified later in the design process, when the tolerances were being specified in the technical drawings.


Input Shaft:  

<img width="966" height="311" alt="image" src="https://github.com/user-attachments/assets/ff2bf158-8c62-4f16-b319-2a42c7940ec3" />



Output shaft:  

<img width="457" height="415" alt="image" src="https://github.com/user-attachments/assets/25b6f2b8-4fdc-4f66-accf-216c3f5f3ac2" />



**Gears assembly**

&nbsp;&nbsp;&nbsp;&nbsp;  My next step was to start the assembly by correctly placing the gears in parallel with the adequade distance between them.

<img width="943" height="742" alt="Screenshot 2026-10-27 111006" src="https://github.com/user-attachments/assets/9991ff6b-6d78-4ec3-8d36-583400b4c4c7" />


**Gearbox**

&nbsp;&nbsp;&nbsp;&nbsp; Using the measurements obtained in the previous step, I created the gearbox base profile, which was used for both the top and bottom halves of the housing. The profile was created by offsetting the gear circumferences by 0.1 in to provide clearance and connecting the resulting arcs with tangent lines. Both the top and bottom halves were then given walls by bossing an inward offset of 0.05 in to the thickness calculated in the gearbox design calculations.

<img width="870" height="787" alt="Screenshot 2026-10-27 113111" src="https://github.com/user-attachments/assets/03ae592c-779b-4f77-8796-02f11d0e6d2d" />



&nbsp;&nbsp;&nbsp;&nbsp; The top half had pins added to them, and the bottom side its respective holes.

&nbsp;&nbsp;&nbsp;&nbsp; And unfortunately just like a previous step I forgot to add the correct clearance, and in the future, the correct tolerances.

**Top gearbox**

<img width="925" height="657" alt="Screenshot 2026-10-27 114231" src="https://github.com/user-attachments/assets/69e3aac5-c9cb-457c-87f4-5fa3c10c7bdf" />


**Bottom gearbox**

<img width="821" height="612" alt="Screenshot 2026-10-27 114550" src="https://github.com/user-attachments/assets/45841a6c-ca0c-466c-8cba-04fad36d46f7" />


**Complete assembly**

&nbsp;&nbsp;&nbsp;&nbsp; With the gears assembled, I first added their respective shafts, followed by the gearbox halves. The following pictures show the modified shaft and gearbox holes designed to reduce unwanted gear movement within the housing. This design was inspired by a plastic gearbox I had previously worked with.

**Exploded view**

<img width="720" height="583" alt="Screenshot 2026-10-27 114900" src="https://github.com/user-attachments/assets/58ce9580-7bca-40fc-af94-aedef76b502a" />


**Isometric view + transparent gearbox**

<img width="556" height="538" alt="Screenshot 2026-10-27 121119" src="https://github.com/user-attachments/assets/e88a76bc-d605-49b2-945f-71ac2a2bdc71" />


**Upper view**

<img width="677" height="677" alt="Screenshot 2026-10-27 121053" src="https://github.com/user-attachments/assets/327b84f5-85bd-4b30-ae0c-fe67a8fd24e6" />


**Upper view + transparent gearbox**

<img width="682" height="690" alt="Screenshot 2026-10-27 121105" src="https://github.com/user-attachments/assets/08c06dd0-2715-41d4-8a1b-42729339250a" />


## 5) Drawings


&nbsp;&nbsp;&nbsp;&nbsp;  An FN1 fit was selected as the interference fit between the shafts and the gear hubs to ensure secure attachment and prevent relative rotation during operation.

- **Input Shaft:** https://1drv.ms/u/c/18c7b03a5d0433a3/IQD47FNRBxK2Sol2JbMdiKBOAVJ7sX14egcYeW31P1gCS7k?e=umpo3a
- **Output Shaft:** https://1drv.ms/u/c/18c7b03a5d0433a3/IQAWiyrdFWAmQqQmep-I3HpxAVzdzeQusf4AdoupxMjm_JQ?e=LJvhVu

**Gearbox top:**

[Gearbox top.pdf](https://github.com/user-attachments/files/34108023/Gearbox.top.pdf)

  
- **Gearbox bottom:** https://1drv.ms/u/c/18c7b03a5d0433a3/IQAZmb_u06KrQ4GxxIw2-RuGAVRZI2vkwYaB-l_DdQAjtIg?e=XiWXMQ
- **Input gear:** https://1drv.ms/u/c/18c7b03a5d0433a3/IQBAT8fbefl4TZJ1fdFGbOroAUdLrM89BAgi4yPuyZ14S1c?e=CUORIY
- **Output gear:** https://1drv.ms/u/c/18c7b03a5d0433a3/IQAIm16Dx0K-SZo_4Sl2aVIJAYem-fa_jKhLmRjaQUEYlbE?e=835Sjg



## Final observations

&nbsp;&nbsp;&nbsp;&nbsp;  I recognize that several mistakes were made during this assignment, including forgetting to account for part clearances and specify the appropriate tolerances. These issues could have been avoided by consulting Machinery’s Handbook while designing the parts. Unfortunately, I developed the habit of assigning the same nominal dimensions to mating components, which may work in a CAD assembly but would not necessarily work in a real-life application.  

&nbsp;&nbsp;&nbsp;&nbsp;  Another aspect I would approach differently given more time is incorporating the journal bearings into the gearbox assembly. I initially decided not to include them because the bearings I found were considerably thicker than I had envisioned for my design, and I was unsure how to address this issue. After reviewing reference assignments from TAs and students from previous semesters, I noticed that they had also omitted the bearings, so I followed the same approach.

&nbsp;&nbsp;&nbsp;&nbsp; Overall, this assignment took approximately 7 hours to complete, with the most time-consuming part being the initial calculations, as I needed time to understand the equations required for the design.





## CAD links:

**Input Shaft:**

<img width="1634" height="935" alt="Input Shaft" src="https://github.com/user-attachments/assets/d0f134b2-040e-4ffb-a5f3-712d0cdd7c5c" />

  
- **Output Shaft:** https://1drv.ms/u/c/18c7b03a5d0433a3/IQAWiyrdFWAmQqQmep-I3HpxAVzdzeQusf4AdoupxMjm_JQ?e=LJvhVu
- **Gearbox top:** https://1drv.ms/u/c/18c7b03a5d0433a3/IQAQX5OCSltXR6uau0axqstGAS1r4G8q6ck9tbUWQn7q7gc?e=ASMZYS
- **Gearbox bottom:** https://1drv.ms/u/c/18c7b03a5d0433a3/IQAZmb_u06KrQ4GxxIw2-RuGAVRZI2vkwYaB-l_DdQAjtIg?e=XiWXMQ
- **Input gear:** https://1drv.ms/u/c/18c7b03a5d0433a3/IQBAT8fbefl4TZJ1fdFGbOroAUdLrM89BAgi4yPuyZ14S1c?e=CUORIY
- **Output gear:** https://1drv.ms/u/c/18c7b03a5d0433a3/IQAIm16Dx0K-SZo_4Sl2aVIJAYem-fa_jKhLmRjaQUEYlbE?e=835Sjg
- **Assembly:** https://1drv.ms/u/c/18c7b03a5d0433a3/IQC9J5kOXBLBRrcjN4dAiVtmARXJx4RzRc_jFC-1Tl-Y7HY?e=Pr30o7






