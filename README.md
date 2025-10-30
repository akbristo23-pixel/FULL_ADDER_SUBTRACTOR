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

**Truthtable**
full subtracture
![IMG-20251030-WA0016 1](https://github.com/user-attachments/assets/3a01734d-a0f8-4d37-a5f6-a1e81d6dea95)
full adder
<img width="528" height="480" alt="Screenshot 2025-10-30 122348" src="https://github.com/user-attachments/assets/a3e9745d-45b4-487b-b253-ed51c26ba015" />


**Procedure**
run the program in Quartus software.

Compile and run the program.

Generate the RTL schematic and save the logic diagram.

Create nodes for inputs and outputs to generate the timing diagram.

For different input combinations generate the timing diagram


**Program:**
Program to design a full adder and full subtractor circuit and verify its truth table in quartus using Verilog programming. 
Developed by: bristo AK
RegisterNumber: 25011512


**RTL Schematic**
![IMG-20251030-WA0012 1](https://github.com/user-attachments/assets/b28116d0-fec0-4a15-8993-7e97e3bfd63e)
![IMG-20251030-WA0013 1](https://github.com/user-attachments/assets/6454e35d-701e-44e9-9e0d-e455a5fe0019)

**Output Timing Waveform**
![IMG-20251030-WA0014 1](https://github.com/user-attachments/assets/93616201-dd45-40b7-9ead-8c6c3e4a2941)
![IMG-20251030-WA0015 1](https://github.com/user-attachments/assets/fa17efa6-4846-427e-a8a9-64cfbce85eb3)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



