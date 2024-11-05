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
module EXP2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

Developed by: RegisterNumber:*/ 24005335


**RTL realization**
THE LOGIC GATES ARE STUDIED AND THE RTL OUTPUT IS VERIFIED

**Output:**

**RTL**
![Screenshot 2024-10-29 212221](https://github.com/user-attachments/assets/eb31c25b-452d-400c-8fb6-6cdb0e5735d6)


**Timing Diagram**
![Screenshot 2024-11-05 102843](https://github.com/user-attachments/assets/d8d49455-9842-4160-8138-25ab7deb4d28)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

