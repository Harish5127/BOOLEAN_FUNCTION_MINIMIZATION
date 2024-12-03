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
```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: Harish R
RegisterNumber: 24001191
*/
```
```
module funct1(a,b,c,d,f1);
      input a,b,c,d;
      output f1;
      assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
```

**RTL realization**

![Screenshot 2024-12-03 233659](https://github.com/user-attachments/assets/c645b34d-2b10-41f4-837c-f1016f8916eb)


**Output:**

**RTL**

![Screenshot 2024-12-03 233831](https://github.com/user-attachments/assets/491278f5-2a3f-496a-84ab-c1dee27f9c89)


**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

