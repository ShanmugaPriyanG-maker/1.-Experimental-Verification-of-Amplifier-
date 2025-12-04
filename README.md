#**EX.NO:** 1  # EXPERIMENTAL VERIFICATION OF AMPLIFIER INVERTING, NON INVERTING , DIFFERENTIAL AMPLIFIER AND INSTRUMENTATION AMPLIFIERS
**DATE:**  
---

## AIM
To design and construct an Inverting, Non-Inverting, Differential and Instrumentation amplifiers.

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K, 10K, 2.2K | 2 |
| 7 | Connecting wires and probes | As required | — |

---

## THEORY

Op-amp in open-loop configuration has limited application due to its enormous open-loop gain. Controlled gain can be achieved by taking a part of the output signal to the input through feedback.  
This is called a **Closed-Loop Configuration**.

The four basic types of closed-loop amplifier configurations are:
- Inverting amplifier  
- Non-inverting amplifier  
- Differential amplifier
- Instrumentation amplifier 

The entire configuration can operate with either AC or DC input.
		
 

---

### **Inverting Amplifier**

This is the most widely used op-amp configuration.  
The output voltage Vo  is fed back to the inverting input terminal through the  Rf - R1 network.  
The negative sign in gain indicates a **phase shift of 180°**.


Acl = -RF/R1

PIN DIAGRAM
![20251203_193644](https://github.com/user-attachments/assets/990b196b-774c-438f-ac83-2b5deb958dc2)

CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
![20251203_193945](https://github.com/user-attachments/assets/a55be93a-3b20-4f6f-8dcd-928ae2cbc37b)

MODEL GRAPH 
![20251203_193908](https://github.com/user-attachments/assets/e428d7a6-6ec3-4347-bcde-b7a010eccba1)

DESIGN:
![20251203_194023](https://github.com/user-attachments/assets/075bae95-300e-4f96-ab0e-9a55b873eb5b)

Inverting amplifier:

A = -Rf/R1
Take  A = 10
Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ

PROCEDURE:
Inverting amplifier:

1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1 & compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.


## TABULATION
![20251203_194113](https://github.com/user-attachments/assets/ec682b26-9df8-4ed1-9c32-2fdb0513ba75)

---
## OUT PUT WAVEFORM AND DISCUSSION 
![20251203_194416](https://github.com/user-attachments/assets/91ba8e43-995a-4274-ae01-87169b925588)

---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM
![circuit](https://github.com/user-attachments/assets/64abaab4-d1a6-46d9-ae46-4169c07ab0d5)

---

## MODEL GRAPH
![mg](https://github.com/user-attachments/assets/0cbf31f2-04ac-47ec-9109-283c04cf389f)

---
## DESIGN
![DES](https://github.com/user-attachments/assets/e3a34670-24f5-4de3-963c-e2f3250a2bc6)

---
PROCEDURE:
### **For  Non-Inverting Amplifier**
1. Select R1  as a constant value and choose a value for Rf .  
2. Connect the circuit as per the diagram.  
3. Apply constant amplitude input voltage.  
4. Measure the output voltage amplitude for different V1 using DSO.  
5. Compare practical and theoretical values of Vo .  
6. Verify that practical gain ≈ theoretical gain.  
7. Plot the input vs. output waveform for one practical case.

## TABULATION
![20251203_195001](https://github.com/user-attachments/assets/96a4317f-b177-43d2-a981-07e74f0db612)

---
## OUT PUT WAVEFORM AND DISCUSSION 
![20251203_195143](https://github.com/user-attachments/assets/632c9adf-c092-40a1-bfca-824f107b8f3b)

---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
![20251203_195357](https://github.com/user-attachments/assets/13940967-42db-4713-aa46-e5f286c3e2dc)

## MODEL GRAPH
![20251203_195422](https://github.com/user-attachments/assets/4baf25b3-59e8-413a-96c0-7292020a8231)

---

## DESIGN
![20251203_195658](https://github.com/user-attachments/assets/277068c1-6a52-41b3-b40f-963cb6e1aa12)

### **Differential Amplifier**

AV = Vo/{V1 - V2} = -Rf/R1


Take  A = 10 
⇒  Rf = 10R1   
Choose  R1 = 1kOhm, Rf = 10kOhm

---



## PROCEDURE (Differential Amplifier)
1. Select  R1, R2, R3, Rf  such that R1 = R2  and  R3 = Rf .  
2. Connect the circuit as per the circuit diagram.  
3. Apply constant inputs Vin1 and  Vin2 .  
4. Measure output voltage using DSO.  
5. Compare theoretical and practical  Vo .  
6. Verify practical ≈ theoretical output.  
7. Plot the input vs. output waveform.

---

## TABULATION (Differential Amplifier)
![20251203_195447](https://github.com/user-attachments/assets/04e514da-a184-4af0-9b7c-a58bf4680926)

---
## OUT PUT WAVEFORM AND DISCUSSION 
![20251203_195730](https://github.com/user-attachments/assets/16b8b2c8-a33d-4579-98a5-549ada272b7b)

---
## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER
![20251203_210400](https://github.com/user-attachments/assets/a03225ea-af8f-476d-87ad-b2cd4aa7b32b)

## MODEL GRAPH
![20251203_210807](https://github.com/user-attachments/assets/980f91eb-6bb2-419f-b68d-5fb6e708eddc)

## DESIGN
![20251203_210904](https://github.com/user-attachments/assets/6a504f7d-49a8-47a6-8f2b-00dc06af79b6)
![20251203_210851](https://github.com/user-attachments/assets/0e516e57-93fe-4d5b-a489-69055af8ae33)

PROCEDURE:

1.	Select the entire resistor with the same value. Let R be the gain varying resistor with different values of resistance for simplicity let R be a constant value.
2.	Connect the circuit as shown in the circuit diagram.
3.  + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
4.	Give the input V1 and V2 to the non-inverting terminals of first & second op-amp respectively.
5.	By varying the value of RG, measure the output voltage for common mode and differential mode operation. Since RG is selected as constant value, provide different input value of V1 and V2.
6.	Check the theoretical value with the experimental value.
7.	The output voltage is obtained in the Multimeter and the input and output voltage waveforms are plotted in a graph sheet

---

## TABULATION (Instrumentation Amplifier)
![20251203_210835](https://github.com/user-attachments/assets/ba2a6d05-de63-4069-8810-194cb8fb9e72)

---
## OUT PUT WAVEFORM AND DISCUSSION 
![20251203_210904](https://github.com/user-attachments/assets/82aa4f09-c90a-4111-b234-11a5bc037595)

---
## RESULT
![20251203_211119](https://github.com/user-attachments/assets/31b7aed5-0ddb-44ab-a23e-b74a3e853140)
![20251203_211103](https://github.com/user-attachments/assets/71709796-82ac-4b2a-8766-a8d14a6acd51)

Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
