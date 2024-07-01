# ALU
The design of an 8-bit Arithmetic Logic Unit (ALU) using Verilog HDL. An ALU is a fundamental building block of many types of computing circuits, including the central processing unit (CPU) of computers, FPUs, and graphics processing units (GPUs). It performs arithmetic and logical operations. 
With the ALU we can perform Addition,Subtration,Multiplication,Division,Modulus,Bitwise And,Bitwise Or,Equality,Logical And,Logical Or,Logical Shift operations,Bitwise xor,inversion,Concatination.when it is default it will produce a result of Zero.With the help of  four bit select line we can choose which operator is required.The above mentioned operations are explained in a detailed manner below:

=> Addition (alu_sel = 4'b0000): Adds inputs a and b.
=> Subtraction (alu_sel = 4'b0001): Subtracts b from a.
=> Multiplication (alu_sel = 4'b0010): Multiplies a and b.
=> Division (alu_sel = 4'b0011): Divides a by b.
=> Modulus (alu_sel = 4'b0100): Computes the remainder of a divided by b.
=> Bitwise AND (alu_sel = 4'b0101): Performs a bitwise AND operation on a and b.
=> Bitwise OR (alu_sel = 4'b0110): Performs a bitwise OR operation on a and b.
=> Equality Check (alu_sel = 4'b0111): Checks if a is equal to b.
=> Logical AND (alu_sel = 4'b1000): Performs a logical AND operation on a and b.
=> Logical OR (alu_sel = 4'b1001): Performs a logical OR operation on a and b.
=> Right Shift (alu_sel = 4'b1010): Shifts a two places to the right.
=> Right Shift (alu_sel = 4'b1010): Shifts a two places to the right.
=> Right Shift (alu_sel = 4'b1010): Shifts a two places to the right.
=> Right Shift (alu_sel = 4'b1010): Shifts a two places to the right.
=> Right Shift (alu_sel = 4'b1010): Shifts a two places to the right.
=> Right Shift (alu_sel = 4'b1010): Shifts a two places to the right.
=> Right Shift (alu_sel = 4'b1010): Shifts a two places to the right.
=> Left Shift (alu_sel = 4'b1011): Shifts a two places to the left.
=> Right Shift (alu_sel = 4'b1010): Shifts a two places to the right.
=> Bitwise XOR (alu_sel = 4'b1100): Performs a bitwise XOR operation on a and b.
=> Bitwise NOT (alu_sel = 4'b1101): Performs a bitwise NOT operation on a.
=> Concatenation (alu_sel = 4'b1110): Concatenates a and b.
=> Duplication (alu_sel = 4'b1111): Duplicates a.

The c_out output is the carry out from the addition of a and b. It’s important in arithmetic operations like addition and subtraction where there can be a carry or borrow.
