EXPERIMENT-4 **FULL ADDER SUBTRACTOR**

NAME:SUSHMITHA S

REF NO.:24008099

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**EQUIPMENTS REQUIRED:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**TRUTH TABLE:**
i)FULL ADDER

![Screenshot 2024-12-26 102126](https://github.com/user-attachments/assets/155a719c-e378-45e0-a9be-a2da4619187f)

ii)FULL SUBTRACTOR

![Screenshot 2024-12-26 102139](https://github.com/user-attachments/assets/388a6da6-b911-48db-be17-45eabca500a7)


**PROCEDURE:**

1. Type the program in Quartus software.

2. Compile and run the program.

3. Generate the RTL schematic and save the logic diagram.

4. Create nodes for inputs and outputs to generate the timing diagram.

5. For different input combinations generate the timing diagram.



**PROGRAM:**

i)FULL ADDER

![FULLADDER](https://github.com/user-attachments/assets/842fe255-0d5d-4f2e-a8b4-d3f2a9e056f7)


ii)FULL SUBTRACTOR

![Screenshot 2024-12-26 104101](https://github.com/user-attachments/assets/6c66b889-915b-4fae-802f-46e57a8bca13)


**RTL Schematic:**

FULL ADDER

![Screenshot 2024-12-26 102206](https://github.com/user-attachments/assets/b6b0bdd9-9cc6-4249-874a-33f91d6e5ed5)

FULL SUBTRACTOR

![Screenshot 2024-12-26 102226](https://github.com/user-attachments/assets/e24fbaf6-53e4-4ab0-aabb-834601fbf3e4)


**OUTPUT TIMING WAVEFORM:**

FULL ADDER

![Screenshot 2024-12-26 102239](https://github.com/user-attachments/assets/de08e88f-a6b4-4f62-93a5-a8cd06849255)

FULL SUBTRACTOR

![Screenshot 2024-12-26 102252](https://github.com/user-attachments/assets/303bb5a1-c180-445a-a584-83fad74c8598)



**RESULT:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



