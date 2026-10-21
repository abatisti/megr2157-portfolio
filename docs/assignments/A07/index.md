# A7 – FEA on Bracket


<br><br>
## 1) Outer loop
<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;  For the first outer loop, the initial bracket design developed in Assignment 6 will be used.
<br>
<img width="435" height="738" alt="Screenshot 2026-09-29 113950" src="https://github.com/user-attachments/assets/55057750-82d4-4a51-90dd-eebf2003d54a" />

<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;  Then the correct constrains and loading were added to the previos geometry.
<br>
<img width="437" height="727" alt="image" src="https://github.com/user-attachments/assets/785121fb-b048-4c2b-83a7-4202b5d4bc4a" />

<br><br>
### 1.1) Inner loop

First mesh was done at the set value on solidworks

<img width="435" height="732" alt="image" src="https://github.com/user-attachments/assets/2645ed4c-398c-4e60-a868-d36cbfeb4b8f" />

<br><br>
- Stress: The obtained stress is several times greater than the material’s yield used in the calculations.
<br>
<img width="577" height="627" alt="image" src="https://github.com/user-attachments/assets/d5dce188-c16d-4017-a5bf-5b1d28b51e09" />

<br><br>
- Deflection: Also beyond allowed value previosly calculated
<br>
<img width="575" height="731" alt="image" src="https://github.com/user-attachments/assets/3946b244-77fc-4616-8d05-9e84566b9864" />

<br><br>
- Safety factor: The actual factor of safety (FoS) is below the target value, indicating a possible calculation, or a discrepancy caused by the assumptions made during the analytical calculations.
<br>
<img width="595" height="726" alt="image" src="https://github.com/user-attachments/assets/53981683-9e35-485e-98d8-f77926f468c4" />

<br><br>
Mass: <img width="132" height="27" alt="image" src="https://github.com/user-attachments/assets/0cdc3517-7cba-4d79-8c4f-95912ec85be5" />


<br><br>
### 1.2) Inner loop

Finner mesh:
<img width="432" height="727" alt="image" src="https://github.com/user-attachments/assets/3c018895-e2ee-45a5-9671-b1533fc0ab3f" />

<br><br>
- Stress
<br>
<img width="625" height="632" alt="image" src="https://github.com/user-attachments/assets/7de4d4a6-7859-4321-b93c-862934f00e4c" />

<br><br>
- Deflection
<br>
<img width="555" height="738" alt="image" src="https://github.com/user-attachments/assets/e99eb2f5-011a-4985-b4b5-66c55853860f" />

<br><br>
- Factor of safety
<br>
<img width="572" height="732" alt="image" src="https://github.com/user-attachments/assets/d88d2617-cafc-4ff1-a636-3d5c0a6e2368" />

<br><br>
**Error estimation between loop 1 and 2**

Formula: (Value1 - Value2) / ( Value1 + Value1) /2 ) ) * 100 %


Stress: 6.80%  

Deflection: 0.707%  

FOS: 0.001%


Error percentage < 7%: Model validated!

<br><br>
## 2) Outer loop

The overall bracket geometry was then modified. The primary objective of this first iteration was to meet all design requirements for strength, stiffness, and factor of safety. The following modifications were made:


- Overall thickness of bracket decreased from t= 4 to t = 2 inches.
- Vertical lenght of part B decreased from 4 inches to 2 inches
- Width of part D increased from 0.022 inches to 0.1 inches
- Fillets were added

  <img width="417" height="702" alt="image" src="https://github.com/user-attachments/assets/c5542d74-2dc7-4656-a2b2-deb40bd58455" />


<br><br>
### 2.1) Inner loop
<br><br>
- Stress: The maximum stress now falls under the yield stress and the factor of safety.
<br>
<img width="605" height="707" alt="image" src="https://github.com/user-attachments/assets/da84bf1c-5008-4f86-b79c-5c5216e5707d" />


<br><br>
- Deflection: Deflection is also now under the maximum
<br>
<img width="577" height="717" alt="image" src="https://github.com/user-attachments/assets/c9390886-504c-4291-b0d4-198f5e298d2d" />

<br><br>
- Factor of safety: The design now also follows the factor of safety requirements
<br>
<img width="575" height="695" alt="image" src="https://github.com/user-attachments/assets/c2dcc216-a31a-4d16-b1d2-9552cf7a62ce" />

<br><br>
- Weight: Besides all requirements being met the weight was reduced from the first design
<br>
<img width="282" height="162" alt="image" src="https://github.com/user-attachments/assets/bca06337-408a-4d5f-a773-ed1b7dd0227c" />


<br><br>
### 2.2) Inner loop
<br><br>
- Stress:
<br>
<img width="586" height="712" alt="image" src="https://github.com/user-attachments/assets/02844d92-ee3b-41c8-b155-869a1fa58463" />

<br><br>
- Deflection:
<br>
<img width="548" height="727" alt="image" src="https://github.com/user-attachments/assets/a0862170-6bc3-464b-b1e7-53a9b0ff5939" />

<br><br>
- Factor of Safety:
<br>
<img width="548" height="718" alt="image" src="https://github.com/user-attachments/assets/8ea966f1-c6bc-46d1-87b2-48eae0f1d76c" />

<br><br>
**Error estimation between loop 1 and 2:**

Formula: (Value1 - Value2) / ( Value1 + Value1) /2 ) ) * 100 %


Stress: 2.52%  

Deflection: 0.45 %  

Factor of safety: 2.55%  


Error percentage < 7%: Model validated!

<br><br>
## 3) Outer loop

The primary objectives of this geometry modification were to reduce the bracket's weight and make final refinements to the design.

Changes made:

- Overall radius of part A reduced from original design to 1.6 inches
- Part A was hollowed out throughout and a chamfer was added
- Areas of part E were removed in triangular cross sections shapes.
- fillets radius altered to fit alterations decrease stress concentration


<img width="457" height="682" alt="image" src="https://github.com/user-attachments/assets/ba83d892-db62-4748-9664-1b0cbeb66f03" />

<br><br>
### 3.1) Inner Loop

<br><br>
- Stress: There are 3 main areas with a stress concentration, all below the maximum alowed stress.
<br>
<img width="636" height="722" alt="image" src="https://github.com/user-attachments/assets/d31a2d87-f29e-47f6-b541-7da37ef16e5f" />

<br><br>
- Deflection: The deflection is still below the meximum
<br>
<img width="588" height="710" alt="image" src="https://github.com/user-attachments/assets/b6d25a6d-3df7-4fde-acf0-ce22f795b3fe" />

<br><br>
- Factor of safety: The safety factor is very close to the allowed, but still above it.
<br>
<img width="585" height="720" alt="image" src="https://github.com/user-attachments/assets/79fef2a9-2556-4b5d-a1cd-b46bf97debde" />

<br><br>
- Weight: With all alterations the weight was now decreased to 0.33 pounds
<br>
<img width="231" height="90" alt="image" src="https://github.com/user-attachments/assets/6431384f-7459-40d0-9640-c0d992c52e5d" />

<br><br>
### 3.2) Inner Loop

<br><br>
- Stress:
<br>
<img width="617" height="700" alt="image" src="https://github.com/user-attachments/assets/08deb390-4f31-46a9-b7e0-2c1cb1e14ed1" />
<br><br>
- Deflection:
<br>
<img width="592" height="707" alt="image" src="https://github.com/user-attachments/assets/0ad6fa64-ae03-46fc-9a7c-56d057bb44af" />

<br><br>
- Factor of Safety:
<br>
<img width="587" height="711" alt="image" src="https://github.com/user-attachments/assets/f2f45e63-03f0-442c-b986-b411faf242e5" />

<br><br>
**Error estimation between loop 3.1 and 3.2**

Formula: (Value1 - Value2) / ( Value1 + Value1) /2 ) ) * 100 %


Stress: 0.26%  

Deflection: 5.97%  

FOS: 0.27%  


Error percentage < 7%: Model validated!

<br><br>
## Results:

<br><br>
**Initial design:** 
<br>
<img width="435" height="738" alt="Screenshot 2026-09-29 113950" src="https://github.com/user-attachments/assets/55057750-82d4-4a51-90dd-eebf2003d54a" />
<br>
Stress: 173.3 ksi  

Deflection: 0.6531 inches  

Factor of safety: 0.2092  

Weight: 1.0185 pounds

<br><br>
**Final design:**

<img width="457" height="682" alt="image" src="https://github.com/user-attachments/assets/ba83d892-db62-4748-9664-1b0cbeb66f03" />
<br>

Stress: 9.056 ksi  

Deflection: 0.002484 inches  

Factor of Safety: 4.004  

Weight: 0.3251 pounds

<br><br>
**Final consideration:**

&nbsp;&nbsp;&nbsp;&nbsp;  The results demonstrate that, through critical thinking and design optimization, it is possible to meet all requirements for stress, deflection, and factor of safety while reducing the bracket's overall weight.  
&nbsp;&nbsp;&nbsp;&nbsp;  Additionally, the results from the first outer loop highlight how assumptions made during analytical calculations can significantly affect the design and its simulation results.

&nbsp;&nbsp;&nbsp;&nbsp;  This assingment took me around 5 hours to fully complete so far.

<br><br>
## Link - 1) Outer loop

&nbsp;&nbsp;&nbsp;&nbsp;  First the link fit had to be altered to match the new diameter of the bracket.

New Diameter: D = 1.6 inches  

Type of fit: running/sliding fit  

Class chosen: RC 8 - Wide commercial tolerance  

Maximum fit clearance: 0.0115 inches

<br><br>
**Initial design:**

<img width="327" height="675" alt="image" src="https://github.com/user-attachments/assets/bdc4cc61-3091-4cf5-b8dd-f17262d84f24" />

<br><br>
### 1.1) Inner loop
<br><br>
Stress: Way below maximum allowed
<br>
<img width="506" height="735" alt="image" src="https://github.com/user-attachments/assets/34c37472-17a9-406f-ab40-47b578b7b37b" />

<br><br>
Deflection: Bellow maximum
<br>
<img width="471" height="772" alt="image" src="https://github.com/user-attachments/assets/f4f4476c-aea8-4186-9f50-1acdbbc67558" />

<br><br>
Factor of Safety: Factor of safety around 22
<br>
<img width="498" height="702" alt="image" src="https://github.com/user-attachments/assets/42c873fb-3298-457d-a74f-d37115d6b3a8" />

<br><br>
Weight: 0.3538 pounds
<br>
<img width="247" height="96" alt="image" src="https://github.com/user-attachments/assets/6b4602f6-cb63-4703-a4c3-e51fafdceedf" />

<br><br>
### 1.2) Inner loop 
<br><br>
Stress:
<br>
<img width="467" height="660" alt="Screenshot 2026-10-20 184616" src="https://github.com/user-attachments/assets/023d6558-e78f-4895-b4a7-c0b563bbd34a" />

<br><br>
Deflection:
<br>
<img width="475" height="752" alt="image" src="https://github.com/user-attachments/assets/d6ddacb7-3dc4-4dd9-839b-0fc3de3ba28f" />

<br><br>
Factor of Safety:
<br>
<img width="495" height="710" alt="image" src="https://github.com/user-attachments/assets/39365c64-a602-44e0-895c-107dd2c8030b" />

<br><br>
**Error estimation between loop 3.1 and 3.2**

Formula: (Value1 - Value2) / ( Value1 + Value1) /2 ) ) * 100 %

Stress: 0.49%
Deflection: 0.19%
FOS: 0.50%

Error percentage < 7%: Model validated!

<br><br>
## 2) Outer loop

&nbsp;&nbsp;&nbsp;&nbsp;  For this first geometry alteration 2 major changes were made:

- Overall vertical letgh decreased from 6 inches to 4.5 inches
- Thickness halfed to 0.45 inches

<img width="398" height="662" alt="image" src="https://github.com/user-attachments/assets/4670c0f8-3737-4c04-af9b-389a3d7f58a2" />

<br><br>
### Inner loop 2.1 VS 2.2 and error estimation:
<br>
Stress 2.1 on top and 2.2 bottom: Both still withing maximum stress

<img width="675" height="777" alt="image" src="https://github.com/user-attachments/assets/8f8a1026-79a0-48fb-a761-517fc0a1168d" />

Stress error estimation: 0.66%

<br>
Deflection 2.1 on top and 2.2 bottom: Both still withing maximum deflection

<img width="672" height="777" alt="image" src="https://github.com/user-attachments/assets/b9adce29-8f52-47a8-bdd9-ed173c69d4af" />

Deflection error estimation: 0.66%

<br>
FOS 2.1 on top and 2.2 bottom: Both still withing maximum deflection


<img width="640" height="767" alt="Screenshot 2026-10-21 160506" src="https://github.com/user-attachments/assets/7050055f-6200-429e-bce5-98112f04e2c7" />

FOS error estimation: 0.67%

<br>
Error percentage < 7%: Model validated 

<br><br>
## 3) Outer loop

&nbsp;&nbsp;&nbsp;&nbsp;  For this first geometry alteration 2 major changes were made:

- Overall vertical letgh decreased from 4.5 inches to 4 inches
- Thickness decreased to a quarter of an inch
- Width decreased to 2 inches

<img width="396" height="692" alt="image" src="https://github.com/user-attachments/assets/ab18a5f6-7d14-4dc5-8523-6b34fa084cbe" />

<br>

### Inner loop 3.1 VS 3.2 and error estimation:
<br>

Stress 3.1 on top and 3.2 bottom: Both still withing maximum stress

<img width="595" height="786" alt="image" src="https://github.com/user-attachments/assets/77d18d34-3e25-4e08-975e-64b605c59d35" />


Stress error estimation: 0.25%

<br>
Deflection 3.1 on top and 3.2 bottom: Both still withing maximum deflection


<img width="642" height="786" alt="image" src="https://github.com/user-attachments/assets/2de23806-c650-4db5-872f-43410b309219" />


Deflection error estimation: 0.06%

<br>
FOS 3.1 on top and 3.2 bottom: Both still withing maximum deflection


<img width="625" height="756" alt="image" src="https://github.com/user-attachments/assets/781f9277-7924-44a8-8aaa-893f44bf20c2" />


FOS error estimation: 0.21%

<br>
Error percentage < 7%: Model validated 

<br><br>
## Final result
<br>
**Initial design:** 

<img width="327" height="675" alt="image" src="https://github.com/user-attachments/assets/bdc4cc61-3091-4cf5-b8dd-f17262d84f24" />


Stress: 1.642 ksi
Deflection: 0.0001006 inches
Factor of safety: 22.08
Weight: 0.3538 pounds

<br><br>
**Final design:**

<img width="396" height="692" alt="Screenshot 2026-10-21 163246" src="https://github.com/user-attachments/assets/1cdfae5f-dfaa-4247-a3c6-f9e40a1769af" />


Stress: 7.466 ksi
Deflection: 0.0003157 inches
Factor of Safety: 4.857
Weight: 0.039 pounds


**Final assingment time:** 6 hours.
<br>
**Solidwork liks:**

Bracket:

- 1 ) https://1drv.ms/u/c/18c7b03a5d0433a3/IQB1lsb-INhvS47k43YEh3EnAeeXxKNxbzb33FqQu8OGWfk?e=1w6gNd
- 2 ) https://1drv.ms/u/c/18c7b03a5d0433a3/IQAXj6z1Y-x3RpOeDa6Qwu6vAfi5lONBWcFpx3JNYQsUBVs?e=4M1d5R
- 3 ) https://1drv.ms/u/c/18c7b03a5d0433a3/IQAJmAClz1-xS5nez0S6iYlEAUe0kdga0HXiGKqUJYPW5vQ?e=R9f2t6


Link:

- 1 ) https://1drv.ms/u/c/18c7b03a5d0433a3/IQAp_OaMGrgNTZ5hpLHTt1yKAXt-T6rpHQWZR0gIdV346uY?e=UXOHrG
- 2 ) https://1drv.ms/u/c/18c7b03a5d0433a3/IQAqw-wbGT0NSoGBIKa5-FIhAbUY7TH553juOI6-bIlrS7w?e=jKtxme
- 3 ) https://1drv.ms/u/c/18c7b03a5d0433a3/IQCb_WiUSvDHT7VBENGRdhR2Adqi7hqLGzEz68vvWclhm4c?e=9C8NqO
  
