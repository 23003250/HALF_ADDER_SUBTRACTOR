# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
```
Developed by: MIDHUN S
RegisterNumber: 212223240087
```
**CODE:**

**HALF ADDER:**

![exp 3 half adder program ](https://github.com/23003250/HALF_ADDER_SUBTRACTOR/assets/139331462/67ae384f-bb0d-4ced-a160-418f5ff13024)
**HALF SUBTRACTOR:**

![exp 3 half subtractor program ](https://github.com/23003250/HALF_ADDER_SUBTRACTOR/assets/139331462/abecc47f-e78f-4396-bc8d-b075e1a134e9)

**RTL Schematic:**

**HALF ADDER:**

![exp 3 rtl output hadd ](https://github.com/23003250/HALF_ADDER_SUBTRACTOR/assets/139331462/fa51e73f-3e19-47d3-a18e-a3878fe3f680)
**HALF SUBTRACTOR:**

![exp 3 rtl output hsub ](https://github.com/23003250/HALF_ADDER_SUBTRACTOR/assets/139331462/e87677fe-a662-49bc-881c-8954e4742a82)

**Output/TIMING Waveform:**

**HALF ADDER:**

![exp 3 waveform add](https://github.com/23003250/HALF_ADDER_SUBTRACTOR/assets/139331462/f88fecb2-e4cb-4721-a902-aa070d69b760)
**HALF SUBTRACTOR:**

![exp 3 waveform sub](https://github.com/23003250/HALF_ADDER_SUBTRACTOR/assets/139331462/bb78044c-fd53-45b1-a988-a2bca3e31191)

**Result:**
Thus, a half adder and half subtractor circuit is designed to verify its truth table in Quartus using Verilog programming.
