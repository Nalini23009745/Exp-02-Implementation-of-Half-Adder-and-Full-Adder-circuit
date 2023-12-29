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

1. Connect the supply (+5V) to the circuit
2. Switch ON the main switch
3. If the output is 1, then the led glows.
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: Nalini p
RegisterNumber: 23009745
*/
Logic symbol & Truthtable
RTL realization

### Output:
## CODE:
![image](https://github.com/Nalini23009745/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149347484/dfbbc9d6-17f5-4dce-af2a-95b356302407)

### RTL:
HALF ADDER:![image](https://github.com/Nalini23009745/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149347484/62e83465-dca7-43d0-b0fd-36366b127bfb)
FULL ADDER:![image](https://github.com/Nalini23009745/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149347484/b753fb59-adc4-47b4-8c6e-383f7cbb5dec)

### TIMING DIAGRAM
HALF ADDER:![image](https://github.com/Nalini23009745/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149347484/84d0d64e-b8ea-4a3d-a205-1d9a86a20762)

FULL ADDER:![image](https://github.com/Nalini23009745/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149347484/12e61066-3b02-4719-9dd6-a233feac2688)



### TRUTH TABLE :
HALF ADDER:
![image](https://github.com/Nalini23009745/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149347484/d2d23994-9a70-403f-9782-facc3bc9490b)

FULL ADDERl:
![image](https://github.com/Nalini23009745/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149347484/34130d44-9b14-4683-989f-2fa9e41543a8)


### Result:Thus the half adder and full adder circuit are designed and the truth table for half adder and full adder are verified.
