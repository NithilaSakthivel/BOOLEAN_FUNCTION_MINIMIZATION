# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Nithila.S
RegisterNumber:24900606
*/

module 

experiment2(A,B,C,D,f1,w,x,y,z,f2);

input A,B,C,D,w,x,y,z; 

output f1,f2; 

assign f1=((~B&~D)|(~A&B&D)|(A&B&~C)); 

assign f2=((~y&z)|(x&y)|(w&y)); 

endmodule


**RTL realization**
![Screenshot 2025-01-09 102832](https://github.com/user-attachments/assets/b6b003eb-6760-4152-94af-23dbe82d9561)

**Output:**

**RTL**
![Screenshot 2025-01-09 102846](https://github.com/user-attachments/assets/ad223344-6586-4ca2-bcbd-523882a498ea)

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

