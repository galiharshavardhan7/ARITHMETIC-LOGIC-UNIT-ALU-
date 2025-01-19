# ARITHMETIC-LOGIC-UNIT-ALU-

**Company** :CODETECH IT SOLUTIONS
**Name**    :Gali HarshaVardhan Reddy
**InternId**:  CT06MKS
**Domain**  :VLSI
**BatchDuration: Jan 15-th to -FEB 15th  4 weeks
**Mentor Name**:Neela Santhosh
 **Description**

**DESIGN A BASIC ALU SUPPORTING OPERATIONS LIKE ADDITION, SUBTRACTION, AND, OR, AND NOT**
**Designing a Basic Arithmetic Logic Unit (ALU)**
An Arithmetic Logic Unit (ALU) is a digital circuit that performs arithmetic and logical operations. In this design, we will implement a basic ALU that supports addition, subtraction, AND, OR, and NOT operations.
**ALU Architecture**
The ALU will have the following components:
Two 4-bit input registers (A and B)
One 4-bit output register (Result)
One 3-bit operation selection register (OP)
Arithmetic and logical operation circuits
OP[2] 	OP[1]	 OP[0] 	Operation
0	      0	      0	  Addition
0	      0	      1	  Subtraction
0	      1       0	  AND
0      	1	      1   OR
1      	0       0   NOT A
1      	0	      1	  NOT B
**Arithmetic Operations**
*Addition*
The addition operation will be performed using a 4-bit ripple carry adder.
*Subtraction*
The subtraction operation will be performed by inverting the bits of B (two's complement) and then adding A and B using the ripple carry adder.
*Logical Operations*
AND
The AND operation will be performed using a 4-bit bitwise AND gate.
OR
The OR operation will be performed using a 4-bit bitwise OR gate.
NOT
The NOT operation will be performed using a 4-bit bitwise inverter
*ALU Circuit Diagram*
The ALU circuit diagram will consist of the following components:
4-bit input registers A and B
3-bit operation selection register OP
Ripple carry adder
Bitwise AND gate
Bitwise OR gate
Bitwise inverter
4-bit output register Result
**Truth Table**
The truth table for the ALU will have the following inputs and outputs:
A[3]	A[2]	A[1]	A[0]	B[3]	B[2]	B[1]	B[0]	OP[2]	OP[1]	OP[0]	Result[3]	Result[2]	Result[1]	Result[0]
*Example Use Cases*
Addition: Set OP to 000 (addition), A to 1010 (10), and B to 1100 (12). The result will be 10110 (22).
Subtraction: Set OP to 001 (subtraction), A to 1100 (12), and B to 1010 (10). The result will be 0010 (2).
AND: Set OP to 010 (AND), A to 1010 (10), and B to 1100 (12). The result will be 1000 (8).
OR: Set OP to 011 (OR), A to 1010 (10), and B to 1100 (12). The result will be 1110 (14).
NOT A: Set OP to 100 (NOT A), A to 1010 (10), and B to XXXX (don't care). The result will be 0101 (5).
This basic ALU design can be extended to support more operations and larger input sizes.ion.

##OUTPUT

https://github.com/galiharshavardhan7/ARITHMETIC-LOGIC-UNIT-ALU-/issues/2#issuecomment-2600904135
https://github.com/galiharshavardhan7/ARITHMETIC-LOGIC-UNIT-ALU-/issues/2#issue-2797677397


