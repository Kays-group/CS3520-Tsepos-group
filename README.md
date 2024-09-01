# Group members
##### 202100168
##### 202322248
##### 202322249
##### 201400290
##### 202322250
####  202322252

## ASSIGNMENT 0- BINARY ADDER

### OBJECTIVE
The objective is to design and simulate a functional digital circuit that adds two 2-bit binary numbers and produce a 3-bit output
using basic digital logic gates, and reveal report skills using modern collaboration and publishing platforms.

### DESIGN
The attached file shows the schematic diagram and the truth table.

![image](https://github.com/user-attachments/assets/2ea1a596-30bb-4db9-bd58-a652f640c857)

![image](https://github.com/user-attachments/assets/eff809d8-1dda-4b7d-a044-0dbf1c1e05d1)





### SIMULATION AND RESULTS
The attached screenshots show all the combinations of the two 2-bit binary numbers and their results.

10 + 10 = 100
![image](https://github.com/user-attachments/assets/0a24a577-87c1-4d9a-b455-c1044709a4a6)

11 + 10 = 101
![image](https://github.com/user-attachments/assets/55dd29b5-e91f-449f-9b99-64cd528690a4)

### TESTING STRATEGY WITH TESTING CASES
We used sequence generator to add all our inputs to the half adders and also used LED to determine our outputs. When the LED lights 
red the output is 1 and when the LED does not light the output is 0.The outputs we obtained when using a sequence generator 
corresponds to those we obtained when adding numbers manually in either decimal form or binary form .
The 2-bit binary numbers that were used to test our adder are 00,01,10,11. For example,the expected 3-bit number when adding 0 and 1 is 1, which is 00 + 01 = 001 and the expected 3-bit  number when adding 2 and 3 is 5, which is 10 + 11 = 105.
With these test cases, we verified that our 2-bit binary adder gives expected outcomes.







### CHALLENGES FACED
In order for us to add a carry from the first half adder and the sum of the most significant bit from the second adder, we had to 
include another exclusive-or-gate. The 2-bit binary adder works as expected except for the combination of 01 + 01 which gives an unexpected outcome.

### CONCLUSION
This project effectively demonstrated our capabilities in designing, simulating, and documenting a digital curcuit that operates 
as a 2-bit binary adder using fundamental digital logic gates. By incorporating two half adders and a single OR gate, we 
successfully achieved the task of adding two 2-bit binary numbers and producing a 3-bit output, which includes both sum bits and 
the carry-out bit.
