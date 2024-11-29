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

Developed by:Nishma sherin.k
RegisterNumber:24002101
```
```
module ex_2(a,b,c,d,w,x,y,z,f1,f2)
intput a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```
**RTL realization output**
![Screenshot (3)](https://github.com/user-attachments/assets/2208e141-8b08-4104-8775-19fe560e5ee3)


**Timing Diagram**
![Screenshot 2024-10-22 115133](https://github.com/user-attachments/assets/d404bc27-8441-4595-a57a-e8e8987e8301)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

