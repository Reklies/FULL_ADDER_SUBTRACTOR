# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

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
**Procedure**

Write the detailed procedure here
**Full Adder:**
1.Open Quartus II and create a new project.
2.Use schematic design entry to draw the full adder circuit. 
3.The circuit consists of XOR, AND, and OR gates. 
4.Compile the design, verify its functionality through simulation. 
5.Implement the design on the target device and program it.

**Full Subtractor:** 
1.Follow the same steps as for the full adder. 
2.Draw the full subtractor circuit using schematic design. 
3.The circuit includes XOR, AND, OR gates to perform subtraction. 
4.Compile, simulate, implement, and program the design similarly to the full adder.

**Program (1A):**
```
 Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: Reklies J
RegisterNumber: 212223230170
```

![Screenshot (352)](https://github.com/user-attachments/assets/0a0f0979-879d-4b22-b4ac-8e871478f2db)

**RTL Schematic (1A)**

![Screenshot (354)](https://github.com/user-attachments/assets/ea427acf-8936-45ed-8eaa-17e3b576dce7)

**Output Timing Waveform(1A)**

![Screenshot (353)](https://github.com/user-attachments/assets/756a0bd5-f812-45e6-8ad1-64f0ba2848f8)

**Program(1B):**

![Screenshot (355)](https://github.com/user-attachments/assets/407237ff-9556-4feb-bda3-d69faa122ccb)

**RTL Schematic(1B)**

![Screenshot (356)](https://github.com/user-attachments/assets/ec5ed049-5e8e-46ee-8feb-93bf14da3f76)

**Output Timing Waveform(1B)**

![Screenshot (357)](https://github.com/user-attachments/assets/5fb0e8c8-82d8-4bf2-9f5d-b8a8cbe06a8e)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



