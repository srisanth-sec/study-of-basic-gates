**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**

<img width="836" height="298" alt="Screenshot 2025-11-23 145739" src="https://github.com/user-attachments/assets/267d2554-ea08-4583-816b-8d60ab159a47" />

 Developed by: SRI SANTH
 RegisterNumber: 25003365
 
**Logic symbol & Truthtable**

<img width="572" height="812" alt="Screenshot 2025-11-23 150151" src="https://github.com/user-attachments/assets/e0ecb372-a85f-4a29-8ce1-91a5b01972b6" />
<img width="751" height="765" alt="Screenshot 2025-11-23 150228" src="https://github.com/user-attachments/assets/e32f4675-8c8b-45de-b877-c395c9510f2b" />
<img width="696" height="247" alt="Screenshot 2025-11-23 150235" src="https://github.com/user-attachments/assets/bab349fe-7460-4cd9-933d-e2918d70111d" />

**RTL realization Output:** 
<img width="1040" height="549" alt="Screenshot 2025-11-23 134635" src="https://github.com/user-attachments/assets/59fa32d0-5648-4505-9863-ccd1b125cb9a" />

**RTL**
<img width="1034" height="543" alt="Screenshot 2025-11-23 134709" src="https://github.com/user-attachments/assets/68872c5f-1e3f-44e3-bd0c-9da7556f9830" />

**Result:**

Thus the different digital IC’s are studied and the truth table for different logic gates  are verified.

