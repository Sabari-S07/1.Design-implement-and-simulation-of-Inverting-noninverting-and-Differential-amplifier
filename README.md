# 1.Design-implement-and-simulation-of-Inverting-noninverting-and-Differential-amplifier

**AIM:**
To design , implement and simulate  an inverting, non- inverting and differential amplifiers

**APPARATUS  and SOFTWARE REQUIRED:**
S.No	Name of the Apparatus	Range	Quantity
1.	Function Generator	3 MHz	1
2.	DSO	30 MHz	1
3.	Dual RPS	(0 – 30) V	1
4.	Op-Amp	µA741	1
5.	Bread Board		1
6.	Resistors	1K,10K	2
7.	Connecting wires and probes	As required	
8.  LT SPICE software

**THEORY:**
Op-amp in open-loop configuration has a very few application because of its enormous open-loop gain. Controlled gain can be can be achieved by taking a part of output signal to the input with the help of feedback. This is called as Closed- Loop Configuration. The three basic types of closed-loop amplifier configuration are:
1.	Inverting amplifier.
2.	Non-inverting amplifier.
3.	Differential amplifier.
The entire configuration can be operated with either AC or DC input.

**INVERTING AMPLIFIER:**
This is the most widely used op-amp. Here, the output voltage Vo is feedback to the inverting input terminal through the Rf – R1 network. The negative sign in gain indicates the phase shift of 180ο.
The circuit closed-loop voltage gain is Avcl= -RF / R1

**NON - INVERTING AMPLIFIER:**
If signal is applied to the non-inverting input terminal of op-amp without inverting the input signal such a circuit is called non-inverting amplifier. Here the output is feedback to the inverting input terminal. The phase shift of input signal does not occur in non-inverting terminal.
The circuit closed-loop voltage gain is ACL = 1 + ( RF / R1)

**DIFFERENTIAL AMPLIFIER**
A circuit that amplifies that amplifies the difference between two input signals is called as differential amplifier. It is useful in instrumentation amplifier. If the two input signals are the same, the output should be zero. Differential amplifier with a single op-amp has the exact gain of an inverting amplifier and it is given as
𝐴	= 	𝑉𝑜/(V2-V1) = −𝑅𝑓/R1

**DESIGN:**

**Inverting amplifier:**
    Gain is     A = -Rf/R1
        Take  A = 10
        Rf =10 R1
        Choose R1 = 1kΩ, Rf=10kΩ
        
**Non inverting amplifier:**
    Gain is    A = 1+ Rf/R1
      Take A = 2
      Rf = R1
      Choose Rf = 10kΩ, R1=10kΩ
      
**Differential amplifier**
  Gain is 𝐴=	𝑉𝑜/(𝑉1− V2)= − 𝑅𝑓/𝑅1
Take  A = 10
 Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ

**PROCEDURE:**
**Inverting and Non-inverting amplifier:**
1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1& compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
   
** Differential amplifier:**
1.	Select the value of R1, R2, R3 & Rf such that R1=R2 and R3=Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Provide constant input voltage Vin1 to Non-inverting terminal of op-amp through R1 & constant input voltage Vin2 to inverting terminal of op-amp through R2.
4.	Measure the output voltage using DSO.
5.	Calculate the theoretical Vo and compare it with practical Vo.
6.	Practical output & theoretical calculation should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
 
**PIN DIAGRAM:**

<img width="1600" height="700" alt="image" src="https://github.com/user-attachments/assets/eefb2b93-d309-4fd4-973d-54094438e85a" />

**INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**
<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/8c75f153-d8c8-4f73-bffd-20a932774994" />


  **MODEL GRAPH:**
<img width="882" height="1601" alt="image" src="https://github.com/user-attachments/assets/384fa721-2f2c-4b2e-9fa9-f1c6b29811d0" />


  **TABULATION:**
 <img width="914" height="1598" alt="image" src="https://github.com/user-attachments/assets/d0fb99f0-e2cb-4795-b05c-8f3187163a97" />


**NON INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**
<img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/c8171355-34c4-408f-8c61-b2ddb2707d96" />


  **MODEL GRAPH:**
<img width="1600" height="986" alt="image" src="https://github.com/user-attachments/assets/f8c9ee96-d0af-48a8-b0ce-09fe84fdc351" />


  **TABULATION:**
<img width="1092" height="1599" alt="image" src="https://github.com/user-attachments/assets/d4efc893-ea12-485a-856e-1aec32ad4796" />

  **DIFFERENTIAL AMPLIFIER:**
  **CIRCUIT DIAGRAM**
<img width="1378" height="1600" alt="image" src="https://github.com/user-attachments/assets/db70eb86-2b4e-46da-a7de-38b40ee1bf0a" />

  **MODEL GRAPH:**
<img width="1120" height="1600" alt="image" src="https://github.com/user-attachments/assets/ccd4174f-080b-4caa-b59c-0cd5066ae3d6" />


  **TABULATION:**
<img width="1088" height="1600" alt="image" src="https://github.com/user-attachments/assets/a46b835d-214e-42dd-af70-d4327d88b27f" />

  **CALCULATION:**
  <img width="958" height="1600" alt="image" src="https://github.com/user-attachments/assets/27ef1364-1962-4c80-9cf7-0ea2351ad8de" />

**GRAPH:**
<img width="1122" height="1599" alt="image" src="https://github.com/user-attachments/assets/08deedbd-3409-453a-9f76-356cf3c64815" />
<img width="1126" height="1598" alt="image" src="https://github.com/user-attachments/assets/eddc02c9-7537-4b28-97f2-7e7c52cb4a51" />


**LT-SPICE Tool:PROCEDURE:**
•	Double click on LT-Spice icon.
•	New schematic window open.
•	Pick and paste the required component from the library and draw the circuit diagram .
•	Complete the connection.
•	Save the file by giving file name.
•	Click on the run option ->click advanced open ->select Ac analysis->enter the amplitude time delay stop time value.
•	Click on the run option ->simulation window opens->place the probe ->output graph is obtained.
 
  **LT SPICE**
  
  **CIRCUIT and Waveform**
  <img width="1002" height="1600" alt="image" src="https://github.com/user-attachments/assets/f22dab9a-4ebe-44d3-880d-5a675b13f626" />


**RESULT:**
Thus the Inverting, Non-Inverting and Differential Amplifiers are designed and simulated performance was successfully tested using op-amp IC 741 and LT SPICE.
 






