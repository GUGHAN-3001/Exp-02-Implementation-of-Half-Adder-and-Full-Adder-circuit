# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

### Developed by: GUGHAN S

### RegisterNumber: 212223240043

### CODE:
### HALF ADDER:
![Exp3 ha code](https://github.com/GUGHAN-3001/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150009432/c8976b42-1e9a-460a-b534-3c9ffb4da0d1)

### FULL ADDER:
![Exp3 fa code](https://github.com/GUGHAN-3001/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150009432/84ed321b-d326-4b98-bc4f-6a593ad030b4)


### Output:
### RTL:

### HALF ADDER:
![Exp3 ha RTL diagram](https://github.com/GUGHAN-3001/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150009432/a2350b04-9649-4b47-8697-977daa52673d)

### FULL ADDER:
![Exp3 fa RTL diagram](https://github.com/GUGHAN-3001/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150009432/7b4a0cbb-5e74-4de1-b368-eb95755be01f)


### TIMING DIAGRAM:

### HALF ADDER:
![exp3 ha wave](https://github.com/GUGHAN-3001/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150009432/77ae48d3-e1cb-4442-8119-842f1a220ad3)

### FULL ADDER:
![exp 3 fa wave](https://github.com/GUGHAN-3001/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150009432/b4e93039-925f-4a05-8e0c-84b45319348e)


### TRUTH TABLE:
### HALF ADDER:
![Exp3 truthtable (ha)](https://github.com/GUGHAN-3001/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150009432/8f521dfb-da8f-45ec-8f57-10572c2b77bb)

### FULL ADDER:
![Exp3 truthtable (fa)](https://github.com/GUGHAN-3001/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150009432/bd2aab09-dd66-469e-a3f3-01096d2cc960)



### Result:
Thus, a half adder and full adder circuit is designed to verify its truth table in Quartus using Verilog
programming.
