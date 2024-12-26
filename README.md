EXPERIMENT-4 FULL ADDER SUBTRACTOR

NAME:SUSHMITHA S

REF NO:24008099

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**EQUIPMENTS REQUIRED:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**FULL ADDER AND SUBTRACTOR**

**FULL ADDER**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

**Figure -2 FULL SUBTRACTOR**

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**TRUTHTABLE**

i)FULL ADDER

![Screenshot 2024-12-26 102126](https://github.com/user-attachments/assets/f9b9b033-6df1-40af-b2ec-16f29afbb1f2)

ii)FULL SUBTRACTOR



![Screenshot 2024-12-26 102139](https://github.com/user-attachments/assets/42fa6274-9049-4894-ad5b-1355cb80aac9)


**PROCEDURE:**

1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram.

**PROGRAM:**

FULL ADDER


![FULLADDER](https://github.com/user-attachments/assets/f485a6a0-f77a-4d20-9fca-a3a63c7d5587)


FULL SUBTRACTOR


![Screenshot 2024-12-26 102252](https://github.com/user-attachments/assets/08adc2bc-3ce9-4ede-af34-71abd9fc6077)
![Screenshot 2024-12-26 104101](https://github.com/user-attachments/assets/84bb9072-4c2b-448c-b7e7-aee1939e59ee)


**RTL SCHEMATIC:**

FULL ADDER

![Screenshot 2024-12-26 102206](https://github.com/user-attachments/assets/766f00e0-5998-48d4-9c31-60eebe274153)

FULL SUBTRACTOR


![Screenshot 2024-12-26 102226](https://github.com/user-attachments/assets/314be5d7-506a-40d9-80d6-51670d19c404)


**OUTPUT TIMING WAVEFORM:**

FULL ADDER

![Screenshot 2024-12-26 102239](https://github.com/user-attachments/assets/eef19db5-8196-4584-a32f-bfd08a6cce41)

FULL SUBTRACTOR


![Screenshot 2024-12-26 102252](https://github.com/user-attachments/assets/b5f77cc1-c154-4ffa-8778-aced78ab208f)


**RESULT:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



