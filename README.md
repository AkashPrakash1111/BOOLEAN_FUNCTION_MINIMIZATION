![image](https://github.com/user-attachments/assets/aaedb0c7-65d3-4e16-b80a-7a660670d576)# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**
![Screenshot 2024-11-16 190105](https://github.com/user-attachments/assets/a1b4f98b-9def-4673-8587-280cf08c1895)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: Akash Prakash
RegisterNumber:24008757

i)function 1

    module funct1(a,b,c,d,f1);
    input a,b,c,d;
    output f1;
    assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
    endmodule

ii) function 2

    module funct2(w,x,y,z,f2);
    input w,x,y,z;
    output f2;
    assign f2=((~y & z)|( w & y )|(x & y));
    endmodule



**truth table**

![Screenshot 2025-01-02 150337](https://github.com/user-attachments/assets/0e852b63-e1c1-470a-8452-cb8b5e20a9bc)




**RTL**

![Screenshot 2025-01-02 151219](https://github.com/user-attachments/assets/caef1203-294b-47f7-8b56-3ec39802c6e8)


**Output:**

![Screenshot 2025-01-02 151347](https://github.com/user-attachments/assets/e3ddc46b-0215-4f46-b391-b6e5c186418f)


**Timing Diagram**

![Screenshot 2025-01-02 151543](https://github.com/user-attachments/assets/caeb2e42-5655-460d-a391-073b952084b4)

**k map**

![Screenshot 2025-01-02 151645](https://github.com/user-attachments/assets/3fb17b9a-5972-4051-b9e9-997ef2208654)
![Screenshot 2025-01-02 151657](https://github.com/user-attachments/assets/12971570-f8da-41dc-a46a-375b88f7c193)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

