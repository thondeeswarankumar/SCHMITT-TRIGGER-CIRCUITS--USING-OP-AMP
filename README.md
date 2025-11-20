# SCHMITT-TRIGGER-CIRCUITS--USING-OP-AMP

## AIM:
	 To design the Schmitt trigger circuit using Op-amp IC 741.
## APPARATUS REQUIRED:  
<img width="664" height="172" alt="image" src="https://github.com/user-attachments/assets/5609257c-77ac-4e40-a405-99186a5ccdfb" />

## THEORY: 
The circuit shows an inverting comparator with positive feedback.  This circuit converts irregular shaped wave forms to a square wave or pulse.  The circuit is known as the Schmitt trigger (or) squaring circuit.  The input voltage Vin changes the state of the output Vo every time it exceeds certain voltage levels called the upper threshold voltage VUT and lower threshold voltage VLT.
When Vo= - Vsat, the voltage across R1 is referred to as lower threshold voltage, VLT.  When Vo=+Vsat, the voltage across R1 is referred to as upper threshold voltage VUT. The comparator with positive feedback is said to exhibit hysteresis, a dead band condition.

## CIRCUIT DIAGRAM:
## SCHMITT TRIGGER
<img width="596" height="422" alt="image" src="https://github.com/user-attachments/assets/3633b907-3be4-4d3c-9d5f-e9895887e06d" />

## MODEL GRAPH:
<img width="550" height="416" alt="image" src="https://github.com/user-attachments/assets/fb8c952f-c4e7-4c7d-a313-6b07db47def8" />

## TABULATION:
<img width="877" height="1280" alt="image" src="https://github.com/user-attachments/assets/258ab509-d5d7-40a1-950d-fc687e5be8d1" />

## GRAPH:
<img width="897" height="1280" alt="image" src="https://github.com/user-attachments/assets/0316e44b-1c25-4122-985a-ccf950aa5b39" />

## DESIGN:
1. Select the desire value of Vut & Vlt with same magnitude & opposite polarity.
           Let VUT = 0.3V & VLT = -0.3V.
2. For Op-amp 741C ± Vsat ≡ ±12V. And assume Vref = 0, Since the another end of R1 is grounded.
3. If Vo = +Vsat the voltage at the positive terminal will be (voltage from potential divider R1 & R2).
            VUTP = [R1/(R1+R2 )](+Vsat) 
	            VLTP   = [R1/(R1+R2 )](-Vsat) 
	              0.3=[R1/(R1+R2 )](+12)
                          0.3/12=[R1/(R1+R2 )]
	0.025(R1+R2)=R1
                             0.025R2=(1-0.025)R1
                             R2=(0.975/0.025)R1
                             R2 = 39 R1
	   Assume R1=1KΩ
	                 R2=39 KΩ

## PROCEDURE:
1.	Design the value of circuit components and select VUT & VLT as given in the design procedure.
2.	Connect the circuit as shown in the circuit diagram.
3.	Apply the input signal to the input terminal of op-amp & set VUT & VLT values.
4.	Note down the readings from the output waveform.
5.	Plot the graph & show the relationship between Input sine wave & Output

## RESULT:
<img width="1280" height="867" alt="image" src="https://github.com/user-attachments/assets/d40a2106-bc9a-43c2-b14c-40fae8e2e256" />
