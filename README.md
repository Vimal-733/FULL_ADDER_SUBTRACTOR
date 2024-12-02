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

**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

**RTL Schematic**
![WhatsApp Image 2024-12-02 at 20 37 20_85c3c464](https://github.com/user-attachments/assets/6557a803-22c4-48c3-8e38-08ad240d7fad)
![WhatsApp Image 2024-12-02 at 20 37 20_4a4c4539](https://github.com/user-attachments/assets/fc421366-511a-4b05-b41b-c21395a68dfa)

**Output Timing Waveform**
![WhatsApp Image 2024-12-02 at 20 37 21_8c0bad2d](https://github.com/user-attachments/assets/0610e819-2a67-47c8-89f4-fdc3864fba87)
![WhatsApp Image 2024-12-02 at 20 37 21_273172a3](https://github.com/user-attachments/assets/480abfaf-ef5b-46fe-b458-5b66db6fb6a2)

**Result:**
A Full Adder-Subtractor is a digital circuit that performs both addition and subtraction for three single-bit binary inputs: 
𝐴
A, 
𝐵
B, and 
𝐶
𝑖
𝑛
C 
in
​
  (carry/borrow input). The mode selector 
𝑀
M determines whether the circuit performs addition (
𝑀
=
0
M=0) or subtraction (
𝑀
=
1
M=1).
Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



