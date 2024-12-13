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
```
Developed by: Jagadeesh.A
RegisterNumber: 24010183
```
 F1
```
 module logic_function2(a,b,c,d,f1);
 input a,b,c,d;
 output f1;
 assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
 endmodule
```

 F2
 ```
module logic_function2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```





**RTL realization**

**Output:**

**RTL**
  OUTPUT F1
  ![Screenshot (37)](https://github.com/user-attachments/assets/dcf8a168-c1cb-4af9-9419-2fe04b8ee742)
  OUTPUT F2
  ![Screenshot (40)](https://github.com/user-attachments/assets/904996cb-48f1-41ee-b961-14423d7db07d)




**Timing Diagram**
  DIAGRAM F1:
  ![Screenshot (38)](https://github.com/user-attachments/assets/af9979d4-f844-4d37-a098-74e9d868321d)
  DIAGRAM F2:
  ![Screenshot (41)](https://github.com/user-attachments/assets/fc9a7e3e-7463-46c7-a5ec-2c6e907abc78)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

