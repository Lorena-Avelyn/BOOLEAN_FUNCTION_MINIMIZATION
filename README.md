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

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: Lorena Avelyn R

RegisterNumber:212224040174

f1
```
module BFM(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

```
f2

```
module BFM1(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|(w & y)|(x & y));
endmodule

```

**RTL realization**

f1

![Screenshot 2025-04-22 213718](https://github.com/user-attachments/assets/dc6b57ed-e384-48ca-81de-ff3a622c6c53)

f2

![Screenshot 2025-04-22 215736](https://github.com/user-attachments/assets/56f49fbe-1907-449c-afde-b6dca7b6ce47)


**Timing Diagram**

f1

![Screenshot 2025-04-22 213531](https://github.com/user-attachments/assets/3b8d65d0-dae8-44c9-b652-da55a6094157)

f2

![Screenshot 2025-04-22 215657](https://github.com/user-attachments/assets/98342c76-7feb-449c-b453-8a88752858d5)

**Truth Table**

![WhatsApp Image 2025-04-22 at 21 52 56_7222a580](https://github.com/user-attachments/assets/42e5b092-130a-4a2f-bad7-0910e1452b5e)

![WhatsApp Image 2025-04-22 at 21 56 02_d85ab26b](https://github.com/user-attachments/assets/79282c7f-f3b2-43d4-a832-cdb6b9e759e4)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

