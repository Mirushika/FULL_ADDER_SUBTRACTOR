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

![Screenshot 2024-11-25 211531](https://github.com/user-attachments/assets/2d4cfab0-4d9d-47f2-b4ee-c6fc28a58d17)


![Screenshot 2024-11-25 211409](https://github.com/user-attachments/assets/e39f6d2c-34d6-4a6c-8825-2182726bb03d)



**Procedure**


1. Type the program in Quartus software.

2. Compile and run the program.

3. Generate the RTL schematic and save the logic diagram.

4. Create nodes for inputs and outputs to generate the timing diagram.

5. For different input combinations generate the timing diagram.



**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/


![Screenshot 2024-11-25 183825](https://github.com/user-attachments/assets/746fcc3e-761c-4d45-8e08-e80a9a0d5567)


![Screenshot 2024-11-25 190855](https://github.com/user-attachments/assets/2e995410-1b28-4977-b640-3ef8d0d21bd2)



**RTL Schematic**

![Screenshot 2024-11-25 183846](https://github.com/user-attachments/assets/a0fde53b-8b6c-44a3-9156-d156f0e3c9de)



![Screenshot 2024-11-25 190911](https://github.com/user-attachments/assets/da9ad096-cc62-4e06-813f-16c37a760601)


**Output Timing Waveform**


![Screenshot 2024-11-25 184818](https://github.com/user-attachments/assets/93df2c58-bc03-4c18-9362-b9f5a86cac09)



![Screenshot 2024-11-25 191313](https://github.com/user-attachments/assets/3dabe917-b487-4b19-88fc-7ee03305b963)



**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



