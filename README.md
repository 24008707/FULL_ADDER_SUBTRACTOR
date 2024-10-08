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

**FULL ADDER**

![TRUTH ADDER 6](https://github.com/user-attachments/assets/76540b26-13ef-4138-95a0-8352f58e96da)


**FULL SUBTRACTOR**


![TRUTH SUB 6](https://github.com/user-attachments/assets/ed0d87a2-dc2f-41ca-a0ee-8a3202ff5839)


**Procedure**

 **Full Adder**: 1.Open Quartus II and create a new project. 2.Use schematic design entry to draw the full adder circuit. 3.The circuit consists of XOR, AND, and OR gates. 4.Compile the design, verify its functionality through simulation. 5.Implement the design on the target device and program it.

**Full Subtractor**: 1.Follow the same steps as for the full adder. 2.Draw the full subtractor circuit using schematic design. 3.The circuit includes XOR, AND, OR gates to perform subtraction. 4.Compile, simulate, implement, and program the design similarly to the full adder.



**Program:**
 Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by:  **VISAL R**

RegisterNumber:   **24008707**

**RTL Schematic**
    
**FULL ADDER**

**PROGRAM**

   ![ADDER PROGRAM 6TH](https://github.com/user-attachments/assets/223df599-c10b-4987-a232-62e1adb43bb1)
   
**RTL DIADRAM**

![RTL ADDER 6](https://github.com/user-attachments/assets/59df828c-8aec-493e-89c1-3d1509b2c546)

**OUTPUT WAVE FORM**

![OUTPUT ADDER 6](https://github.com/user-attachments/assets/e8957301-657e-4564-b48e-8a724508bde2)

**FULL SUBTRACTOR**

**PROGRAM**


![SUB PROGRAM 6](https://github.com/user-attachments/assets/0daacb33-7779-4994-b00e-5eaced0e2f79)

**RTL DIAGRAM**


![RTL SUB 6](https://github.com/user-attachments/assets/f931c569-96b2-445f-8933-490e3cdfa6bd)


**OUTPUT WAVE FORM**


![OUTPUT SUB 6](https://github.com/user-attachments/assets/009b2cd0-7120-4612-8f01-da7b5a50daa1)




**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



