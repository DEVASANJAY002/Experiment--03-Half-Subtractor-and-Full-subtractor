# Experiment--04-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure



Write the detailed procedure here 


## Program:

Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: DEVASANJAY N
RegisterNumber:  23013004

## Code : 
HALF SUBTRACTOR : ![Exp4 hs code](https://github.com/DEVASANJAY002/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152069249/a3e5fe4c-6dfb-4bc9-8f05-17104ede607d)

FULL SUBTRACTOR : ![Exp4 fs code](https://github.com/DEVASANJAY002/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152069249/ebddc0b7-027d-4928-9de6-4639c39d866b)

## Truthtable : 
HALF SUBTRACTOR : ![Exp4 truthtable hs](https://github.com/DEVASANJAY002/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152069249/5475de94-ba41-4585-b14e-3d5966540757)

FULL SUBTRACTOR : ![Exp4 truthtable fs](https://github.com/DEVASANJAY002/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152069249/e67ae023-5b64-4de2-8cba-2ca51f8408da)


##  RTL realization
HALF SUBTRACTOR : ![Exp4 hs RTL diagram](https://github.com/DEVASANJAY002/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152069249/dc1d370a-a7b9-4031-8afc-57d6f9694624)

FULL SUBTRACTOR : ![Exp4 fs RTL diagram](https://github.com/DEVASANJAY002/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152069249/73a5daa0-6ca8-4af4-93d3-e01a7b148487)


## Timing diagram 
HALF SUBTRACTOR : ![hs wave](https://github.com/DEVASANJAY002/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152069249/ce8db61e-7207-4847-af98-ff905dd103ce)
FULL SUBTRACTOR : ![fs wave](https://github.com/DEVASANJAY002/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152069249/d645fcef-7e07-414c-9ecd-4d3b1266f0fb)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
