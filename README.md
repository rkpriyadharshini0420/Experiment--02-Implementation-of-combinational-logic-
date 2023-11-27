# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime

## Theory
 
## Logic Diagram
## Procedure
## Program:

Program to implement the given logic function and to verify its operations in quartus using Verilog programming.

Developed by : PRIYA DHARSHINI R K 

Register Number : 23000894

Code :

/*
module DE2(a,b,c,d,f1);
input a,b,c,d;
output f1;
wire x1,x2,x3,x4,x5;
assign x1=(~a)&(~b)&(~c)&(~d);
assign x2=(a)&(~c)&(~d);
assign x3=(~b)&(c)&(~d);
assign x4=(~a)&(b)&(c)&(d);
assign x5=(b)&(~c)&(d);
assign f1=x1|x2|x3|x4|x5;
endmodule
*/

RTL realization :

![263434590-5ab2c60f-4580-4390-8c83-3c47e830b49c](https://github.com/rkpriyadharshini0420/Experiment--02-Implementation-of-combinational-logic-/assets/151533322/b3742100-d383-43be-a0f0-4fabcba7f385)

Truth Table : 

![263434612-b280551a-f504-449b-8050-3c61de9a5b15](https://github.com/rkpriyadharshini0420/Experiment--02-Implementation-of-combinational-logic-/assets/151533322/31f4889d-997d-4e6d-bfdf-0e07fd4d2dd3)

## Output:

![263435625-b4739a63-7d76-4783-9926-cea462a51185](https://github.com/rkpriyadharshini0420/Experiment--02-Implementation-of-combinational-logic-/assets/151533322/24aa49b9-ad66-48ea-bf39-bb4f9c4483dd)

## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
