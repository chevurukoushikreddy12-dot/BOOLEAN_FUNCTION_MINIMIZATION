# BOOLEAN_FUNCTION_MINIMIZATION

*AIM:*

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

*Equipment Required:*

Hardware – PCs, Cyclone II , USB flasher

*Software – Quartus prime*

*Theory*

*Logic Diagram*

*Procedure*

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


*Program:*
```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: chevuru koushik 

RegisterNumber: 25014537
*/
```
```
module Exp2(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(a&b&~c)|(~a&b&d));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```


*RTL realization*

*Output:*

*RTL*
<img width="1424" height="923" alt="Screenshot 2025-09-26 114327" src="https://github.com/user-attachments/assets/a66900a1-1784-4aa8-9f19-33d3be3aa575" />

*Timing Diagram*
<img width="1466" height="429" alt="Screenshot 2025-10-06 175018" src="https://github.com/user-attachments/assets/070bf0c9-516a-4724-936c-8dc1e22ac06c" />


*Result:*

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.
