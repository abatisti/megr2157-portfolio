# A6 – Bracket Drawing (Drawings Part 1)

## Objective

&nbsp;&nbsp;&nbsp;&nbsp;  To use the calculated dimensions from Assignment 5 to create the bracket and its engineering drawing in SolidWorks.

## Dimensions and design

&nbsp;&nbsp;&nbsp;&nbsp;  The first step is to analyze each calculated dimension from Assignment 5 and identify the limiting dimension based on either stress or stiffness. This will be done by comparing the dimensions calculated for both requirements and selecting the larger of the two, since it governs the final design.

&nbsp;&nbsp;&nbsp;&nbsp;  All calculations and dimensions used for this analysis can be found in “A05.”


&nbsp;&nbsp;&nbsp;&nbsp;  Therefore:

**A:**  
- Lenght = 4 in
- r = 1.158 in(from stiffness)


**B:** 
- h = 4 inches
- w = 2r (from part A)
- t = 0.2303 in (from stress)


**C:** 
- h = 0.5143 in (from stress)
- w = 2.4964 in
- t = 4 in


**D:** 
- h = 1.499 in
- w = 0.022 (from stress)
- t = 4 in


**E:** 
- h = 0.5143 in (from stress)
- w = 0.99902 in
- t = 4 in

<br><br>
<img width="970" height="478" alt="image" src="https://github.com/user-attachments/assets/d42786d5-aacf-4332-9539-87d54208d53e" />  
All parametric dimensions entered into SolidWorks’ Global Equations.

<br>
<img width="435" height="738" alt="image" src="https://github.com/user-attachments/assets/6542ab02-beab-49b3-b411-78c3fe860936" />    

Final solidwoks design.

&nbsp;&nbsp;&nbsp;&nbsp;  **Link:** https://1drv.ms/u/c/18c7b03a5d0433a3/IQB1lsb-INhvS47k43YEh3EnAeaWyrtCTcTt6Z9pjuLIldA?e=kmMryV


## Drawing

&nbsp;&nbsp;&nbsp;&nbsp; The drawing was created directly from the part above. First, a larger dimetric view was added without dimensions to make the part more visible and easier to understand for manufacturing. The front, top, and side views were then added. The dimensions were initially generated automatically by SolidWorks and then edited to satisfy all drawing requirements.


<img width="1634" height="849" alt="Bracket design final" src="https://github.com/user-attachments/assets/63d0ca70-0ee0-42fb-a706-25d8414ae623" />  
Final bracket drawing.

&nbsp;&nbsp;&nbsp;&nbsp;  **Link:** https://1drv.ms/u/c/18c7b03a5d0433a3/IQC8VDxm6bfEQ4lSpO1y-WQoAcC_ceAxPcM8UptfRWIiKdo?e=aJwH4y


## Reflection

&nbsp;&nbsp;&nbsp;&nbsp;  I spent approximately 5 hours completing this assignment. I learned that considering all relevant design requirements is essential when creating a part, since satisfying only one requirement can cause the design to fail under another condition. This assignment reinforced concepts from previous Sophomore Design assignments, particularly the importance of considering strength, stiffness, dimensions, tolerances, and manufacturability together rather than evaluating each factor independently.  


&nbsp;&nbsp;&nbsp;&nbsp;  For Part D, the width was determined using the strength requirement: wd = F × SF / (td × σᵧ)  
&nbsp;&nbsp;&nbsp;&nbsp;  This equation was entered directly into SolidWorks as a global equation, with the variables linked to the corresponding model dimensions and material properties. Therefore, the width was controlled by the equation rather than by manually entering a calculated value.  
&nbsp;&nbsp;&nbsp;&nbsp;If one of the parameters in the equation were changed, such as the applied force, safety factor, thickness, or yield strength, SolidWorks would automatically recalculate the required width. Since the width is parametrically linked to the model, the bracket geometry would update automatically to reflect the new dimension. Any dependent features would also update as long as their relationships were properly defined.


&nbsp;&nbsp;&nbsp;&nbsp;  A tighter tolerance was applied to the width of Part D because this dimension is directly related to the strength requirement of the bracket. A larger variation in this relatively small dimension could move the design closer to its failure condition. A tighter tolerance was also applied to the radius of Part A, since this feature needs to accommodate the required fitting and therefore has a functional role.  
&nbsp;&nbsp;&nbsp;&nbsp;  In contrast, the overall thickness of the bracket was assigned a looser tolerance because it is a larger dimension and small variations within the specified tolerance have less effect on the overall design requirements.  
&nbsp;&nbsp;&nbsp;&nbsp;  Applying the tightest tolerance to every dimension would unnecessarily increase manufacturing cost and difficulty. Non-critical dimensions do not require the same level of precision, so unnecessarily tight tolerances would require more precise manufacturing processes without providing a corresponding functional benefit.



## Link design

**Parametric dimentions:**

<img width="946" height="315" alt="image" src="https://github.com/user-attachments/assets/a7a06d44-26a0-4df6-8472-a37d801dfa0c" />  
Some dimensions depend on the geometry of other parts of the bracket. Since I did not know how to reference those dimensions directly from another feature, I entered them manually.



&nbsp;&nbsp;&nbsp;&nbsp; **First issue found:** When the dimensions were entered into SolidWorks, it revealed that the two fit holes overlapped, which would cause a design issue. This was corrected by increasing the overall height of the part. Because the height had to be changed, the calculations had to be reevaluated to determine whether the stress-based thickness would still be the minimum required thickness. After reevaluation, the stress-based thickness remained the limiting dimension, so no further changes to the part were necessary.



<img width="533" height="615" alt="Screenshot 2026-09-29 183253" src="https://github.com/user-attachments/assets/6990266f-b2c9-4f6c-b346-9d3ea3635caa" />  
Design with overlapping fit holes.  


**New Parametric dimentions:**

<img width="972" height="267" alt="image" src="https://github.com/user-attachments/assets/1b420760-5c85-4863-b857-c7646e2dc4dd" />  
It is possible to see the change in height and the calculations of both analized thicknesses.


<img width="400" height="622" alt="image" src="https://github.com/user-attachments/assets/371a8faf-788e-4ece-85bb-2803100c180e" />


**Finished Part**

<img width="347" height="698" alt="image" src="https://github.com/user-attachments/assets/35d63237-af3e-415d-a7c0-5f84d72aa64a" />


**Part Drawing**

