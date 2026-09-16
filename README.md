# 3.Design-implement-of-Schmitt-trigger-circuit-using-Op-amp
**Aim:**
To design and implement Schmitt-trigger-circuit-using-Op-amp

**APPARATUS REQUIRED:**
S.No	Name of the Apparatus	Range	Quantity
1.	Function Generator	3 MHz	1
2.	DSO	30 MHz	1
3.	Dual RPS	(0 – 30) V	2
4.	Op-Amp	µA741	1
5.	Bread Board		1
6.	Resistors	1K,27K,39K,33K	1
7.	Connecting wires and probes	As required	

**THEORY:**

The circuit shows an inverting comparator with positive feedback. This circuit converts irregular shaped wave forms to a square wave or pulse. The circuit is known as the Schmitt trigger (or) squaring circuit. The input voltage Vin changes the state of the output Vo every time it exceeds certain voltage levels called the upper threshold voltage VUT and lower threshold voltage VLT.
When Vo= - Vsat, the voltage across R1 is referred to as lower threshold voltage, VLT. When Vo=+Vsat, the voltage across R1 is referred to as upper threshold voltage VUT. The comparator with positive feedback is said to exhibit hysteresis, a dead band condition.
 

**DESIGN:**
1.	Select the desire value of Vut & Vlt with same magnitude & opposite polarity. Let VUT = 0.3V & VLT = -0.3V.
2.	For Op-amp 741C ± Vsat ≡ ±12V. And assume Vref = 0, Since the another end of R1 is grounded.
3.	If Vo = +Vsat the voltage at the positive terminal will be (voltage from potential divider R1 & R2).
VUTP = [R1/(R1+R2 )](+Vsat)
VLTP = [R1/(R1+R2 )](-Vsat) 0.3=[R1/(R1+R2 )](+12)
0.3/12=[R1/(R1+R2 )]
0.025(R1+R2)=R1
0.025R2=(1-0.025)R1 R2=(0.975/0.025)R1 R2 = 39 R1
Assume R1=1KΩ
R2=39 KΩ

 
**PROCEDURE:**
1.	Design the value of circuit components and select VUT & VLT as given in the design procedure.
2.	Connect the circuit as shown in the circuit diagram.
3.	Apply the input signal to the input terminal of op-amp & set VUT & VLT values.
4.	Note down the readings from the output waveform.
5.	Plot the graph & show the relationship between Input sine wave & Output


  **CIRCUIT DIAGRAM**
  <img width="392" height="232" alt="image" src="https://github.com/user-attachments/assets/f982a505-48d2-46c2-8727-d92291d15359" />



  **MODEL GRAPH:**
  <img width="452" height="247" alt="image" src="https://github.com/user-attachments/assets/2bcc78ad-a1a9-48f1-a9fb-b9d6597c04a6" />



  **TABULATION:**
  <img width="720" height="1280" alt="WhatsApp Image 2026-09-16 at 9 22 19 AM" src="https://github.com/user-attachments/assets/2fbcec3a-16d4-40da-b7c3-b04813607fe9" />

 

**Graph:**

<img width="1038" height="1280" alt="WhatsApp Image 2026-09-16 at 9 23 01 AM" src="https://github.com/user-attachments/assets/0ced0995-4ac6-4f25-8ccd-b2548e2443e2" />




**RESULT:**
Thus a Schmitt trigger is designed and tested using op-amp IC 741.
 

