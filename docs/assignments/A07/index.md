# A7 – FEA on Bracket


## Objective


## Initial design

C  The initial design of the bracket is the one created on assingment 6.

<img width="435" height="738" alt="Screenshot 2026-09-29 113950" src="https://github.com/user-attachments/assets/55057750-82d4-4a51-90dd-eebf2003d54a" />

## First Outer Loop:

&nbsp;&nbsp;&nbsp;&nbsp;  For the first outer loop the correct constrains and loading were added to the previos geometry.

<img width="437" height="727" alt="image" src="https://github.com/user-attachments/assets/785121fb-b048-4c2b-83a7-4202b5d4bc4a" />


**Fisrt inner loop**

First mesh was done at the set value on solidworks

<img width="435" height="732" alt="image" src="https://github.com/user-attachments/assets/2645ed4c-398c-4e60-a868-d36cbfeb4b8f" />

**Results**

Stress: The stress is also above the yield stress, and it further shows that my mistake is concentrated on part B or the bracket

<img width="577" height="627" alt="image" src="https://github.com/user-attachments/assets/d5dce188-c16d-4017-a5bf-5b1d28b51e09" />


Deflection: also beyond allowed value

<img width="575" height="731" alt="image" src="https://github.com/user-attachments/assets/3946b244-77fc-4616-8d05-9e84566b9864" />


Safety factor: The SF is actually under the desired value, this shows that a calculation or setup mistake was made or is caused by the assumptions used to do such calculations

<img width="595" height="726" alt="image" src="https://github.com/user-attachments/assets/53981683-9e35-485e-98d8-f77926f468c4" />


Mass: <img width="132" height="27" alt="image" src="https://github.com/user-attachments/assets/0cdc3517-7cba-4d79-8c4f-95912ec85be5" />



**Second inner loop - (finner mesh)**

<img width="432" height="727" alt="image" src="https://github.com/user-attachments/assets/3c018895-e2ee-45a5-9671-b1533fc0ab3f" />

Stress

<img width="625" height="632" alt="image" src="https://github.com/user-attachments/assets/7de4d4a6-7859-4321-b93c-862934f00e4c" />


Deflection

<img width="555" height="738" alt="image" src="https://github.com/user-attachments/assets/e99eb2f5-011a-4985-b4b5-66c55853860f" />


Factor of safety

<img width="572" height="732" alt="image" src="https://github.com/user-attachments/assets/d88d2617-cafc-4ff1-a636-3d5c0a6e2368" />


**Error estimation between loop 1 and 2**

Formula: (Value1 - Value2) / ( Value1 + Value1) /2 ) ) * 100 %

Stress: 6.80%
Deflection: 0.707%
FOS: 0.001%

Error percentage < 7%: Model validated!

## Second outer loop

Now it was time to adjust the overall geometry of the bracket. for this first alteration the main goal was to make bracket withing all requirements for its strength, stiffness and factor of safety. Following alterations were done:  


- Overall thickness of bracket decreased from t= 4 to t = 2 inches.
- Vertical lenght of part B decreased from 4 inches to 2 inches
- Width of part D increased from 0.022 inches to 0.1 inches
- Fillets were added

  <img width="417" height="702" alt="image" src="https://github.com/user-attachments/assets/c5542d74-2dc7-4656-a2b2-deb40bd58455" />



## Fisrt inner loop

Stress: The maximum stress now falls under the yield stress and the factor of safety.

<img width="605" height="707" alt="image" src="https://github.com/user-attachments/assets/da84bf1c-5008-4f86-b79c-5c5216e5707d" />



Deflection: Deflection is also now under the maximum

<img width="577" height="717" alt="image" src="https://github.com/user-attachments/assets/c9390886-504c-4291-b0d4-198f5e298d2d" />


Factor of safety: The design now also follows the factor of safety requirements

<img width="575" height="695" alt="image" src="https://github.com/user-attachments/assets/c2dcc216-a31a-4d16-b1d2-9552cf7a62ce" />


Weight: Besides all requirements being met the weight was reduced from the first design

<img width="282" height="162" alt="image" src="https://github.com/user-attachments/assets/bca06337-408a-4d5f-a773-ed1b7dd0227c" />



##  Second inner loop


Stress:

<img width="586" height="712" alt="image" src="https://github.com/user-attachments/assets/02844d92-ee3b-41c8-b155-869a1fa58463" />


Deflection:

<img width="548" height="727" alt="image" src="https://github.com/user-attachments/assets/a0862170-6bc3-464b-b1e7-53a9b0ff5939" />


Factor of Safety:

<img width="548" height="718" alt="image" src="https://github.com/user-attachments/assets/8ea966f1-c6bc-46d1-87b2-48eae0f1d76c" />


## Error estimation between loop 1 and 2:

Same calculation as previosly made

Stress: 2.52%

Deflection: 0.45 %

factor of safety: 2.55%

Error percentage < 7%: Model validated!


## Third outer loop

For this geometry alteration, the main goal was weight reduction and final finer alterations

Changes made:

- Overall radius of part A reduced from original design to 1.6 inches
- Part A was hollowed out throughout and a chamfer was added
- Areas of part E were removed in triangular cross sections shapes.
- fillets radius altered to fit alterations decrease stress concentration


<img width="457" height="682" alt="image" src="https://github.com/user-attachments/assets/ba83d892-db62-4748-9664-1b0cbeb66f03" />

## 3.1) Inner Loop


Stress: There are 3 main areas with a stress concentration, all below the maximum alowed stress.

<img width="636" height="722" alt="image" src="https://github.com/user-attachments/assets/d31a2d87-f29e-47f6-b541-7da37ef16e5f" />


Deflection: The deflection is still below the meximum

<img width="588" height="710" alt="image" src="https://github.com/user-attachments/assets/b6d25a6d-3df7-4fde-acf0-ce22f795b3fe" />


Factor of safety: The safety factor is very close to the allowed, but still above it.

<img width="585" height="720" alt="image" src="https://github.com/user-attachments/assets/79fef2a9-2556-4b5d-a1cd-b46bf97debde" />


Weight: With all alterations the weight was now decreased to 0.33 pounds

<img width="231" height="90" alt="image" src="https://github.com/user-attachments/assets/6431384f-7459-40d0-9640-c0d992c52e5d" />


## 3.2) Inner Loop

Stress:

<img width="617" height="700" alt="image" src="https://github.com/user-attachments/assets/08deb390-4f31-46a9-b7e0-2c1cb1e14ed1" />


Deflection:

<img width="592" height="707" alt="image" src="https://github.com/user-attachments/assets/0ad6fa64-ae03-46fc-9a7c-56d057bb44af" />


Factor of Safety:

<img width="587" height="711" alt="image" src="https://github.com/user-attachments/assets/f2f45e63-03f0-442c-b986-b411faf242e5" />


**Error estimation between loop 3.1 and 3.2**

Formula: (Value1 - Value2) / ( Value1 + Value1) /2 ) ) * 100 %

Stress: 0.26%
Deflection: 5.97%
FOS: 0.27%

Error percentage < 7%: Model validated!

## Results:


**Initial design:** 

<img width="435" height="738" alt="Screenshot 2026-09-29 113950" src="https://github.com/user-attachments/assets/55057750-82d4-4a51-90dd-eebf2003d54a" />

Stress: 173.3 ksi
Deflection: 0.6531 inches
Factor of safety: 0.2092
Weight: 1.0185 pounds


**Final design:**

<img width="457" height="682" alt="image" src="https://github.com/user-attachments/assets/ba83d892-db62-4748-9664-1b0cbeb66f03" />

Stress: 9.056 ksi
Deflection: 0.002484 inches
Factor of Safety: 4.004
Weight: 0.3251 pounds


**Final consideration:**

&nbsp;&nbsp;&nbsp;&nbsp;  Based on results it proves that with enough critical thinking it is possible to make a design fall under all requirements (stress, deflection, and factor of safety), while also decreasing its overall weigth.  
&nbsp;&nbsp;&nbsp;&nbsp;  Additionaly, from the results of the first outer loop it is very perceptible how assumptions during calculation can affect the design part and its simulation results.

&nbsp;&nbsp;&nbsp;&nbsp;  This assingment took me around 5 hours to fully complete so far.

## Link

&nbsp;&nbsp;&nbsp;&nbsp;  First the link fit had to be altered to match the new diameter of the bracket.

New Diameter: D = 1.6 inches

