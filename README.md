# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: SHASWANTH MATHAV.S
RegisterNumber:24900884
```
module exp2(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

**RTL Output**


![Exp 2 circuit](https://github.com/user-attachments/assets/f4f945c0-430f-4886-9cf5-3cb5b4bd6e4e)


**Timing Diagram**


![exp2 timing](https://github.com/user-attachments/assets/4f696f89-ebfc-402e-896a-575a96dd0856)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

