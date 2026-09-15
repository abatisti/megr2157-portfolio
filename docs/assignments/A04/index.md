# A4 – Motor Mount

## "First look"

**Given**

  - Mount Sketch:
    
    <img width="123" height="99" alt="download" src="https://github.com/user-attachments/assets/8856c894-e4be-4280-9728-8204326a16f5" />


    
  - Motor sketch:
    
    <img width="1625" height="505" alt="unnamed" src="https://github.com/user-attachments/assets/8be8fe76-7bb6-423a-8cd1-7b4fd8b6859b" />



  - Motor used: Brushed 24V DC Gear Motor 3.6Kg.cm/46RPM w/ 99.5:1 Planetary Gearbox
  - Weight of the motor is neglectable
  - P = 300 N
  - Maximum deflection (for both features): 0.30 mm
  - Safety factor: 3
  -  Material:  ABS, PETG,  or PLA (ABS was chosen because the links for PETG and PLA given are not working, and while i tried to find another credible source for PLA properties, it became cofusing due to the amount of websites and their credibility.)


**Objective:**  

&nbsp;&nbsp;&nbsp;&nbsp;  Design a motor mount by first analyzing it for yield strength and then for maximum deflection.


**Initial sketch**  

&nbsp;&nbsp;&nbsp;&nbsp;  Before analyzing any specific features, an initial design was created based on the desired geometry and the dimensions of the motor.


<img width="1198" height="1180" alt="1278" src="https://github.com/user-attachments/assets/a46abb16-2ae0-45d5-aeb4-88792eb7e85d" />


<br><br>
## Feature 1:


**Assumptions**
  
  - Deflection of the feature attached to the wall is zero and the derivative with respect to x is also zero (aka treat as a cantilever beam).
  - Safety factor accounts for the holes for the motor shaft and the screws in your calculation.

**FBD**

<br><br>
**Knons and Unknows**

<img width="1193" height="1260" alt="1277" src="https://github.com/user-attachments/assets/ef0cbb87-ab4e-42c2-8bc5-33ed08775fdf" />

<br><br>
**Solve for Strength**  


<img width="1190" height="944" alt="1279" src="https://github.com/user-attachments/assets/a642ff82-66cf-45cb-ad71-0cb319a0008c" />


<br><br>
**Solve for Deflection**


<img width="1182" height="939" alt="1280" src="https://github.com/user-attachments/assets/eff44c9a-7371-4476-b433-3f3c71929d17" />

<br><br>
**Compare obtaned results**


<img width="1184" height="324" alt="1281" src="https://github.com/user-attachments/assets/c324aa19-9e40-4db2-b355-8e7f79bc13ea" />




<br><br>
## Feature 2:


**Assumptions**
  
  - Rigid wall A can support bolts.


**FBD**  

<img width="1318" height="441" alt="1282" src="https://github.com/user-attachments/assets/6cd456de-70c5-42e7-bb56-c819383ca481" />


<br><br>
**Knons and Unknows**

  
<img width="1321" height="1376" alt="1283" src="https://github.com/user-attachments/assets/a5b8601f-2269-4faf-97b1-254128aa71f4" />


<br><br>
**Solve for Strength**  

<img width="1230" height="1000" alt="1284" src="https://github.com/user-attachments/assets/9d42d4c7-b250-42a1-a8cb-c3b2695e655f" />


<br><br>
**Solve for Deflection**


<img width="1231" height="1125" alt="1285" src="https://github.com/user-attachments/assets/c043b526-383c-4986-803d-925e54b9f543" />


<br><br>
**Compare obtaned results**


<img width="1224" height="379" alt="1286" src="https://github.com/user-attachments/assets/7919919f-5f2a-4426-a00c-9bb7f23e19d6" />
