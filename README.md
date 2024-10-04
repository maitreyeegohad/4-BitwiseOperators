# Bitwise-Operators
## Aim: 
To study and implement C++ Bitwise operators

## Theory: 
Bitwise operators in C++ allow you to manipulate individual bits of integer data types. These operators are particularly useful in situations where you need to optimize performance or work closely with hardware, such as in systems programming, embedded systems, or graphics programming. Bitwise operators perform operations at the bit level, directly affecting the binary representation of data. The main Bitwise Operators in C++ are:

- **Bitwise AND (&)**
<br/>This operator compares each bit of two operands. If both corresponding bits are 1, the resulting bit is set to 1, otherwise it's 0.
<br/>eg. int a = 5;    // 5 in binary: 0101
<br/>int b = 3;    // 3 in binary: 0011
<br/>int result = a & b; // result = 0101 & 0011 = 0001 (1 in decimal)

- **Bitwise OR (|):** 
<br/>This operator compares each bit of two operands. If either of the corresponding bits is 1, the resulting bit is set to 1.
<br/>eg. int a = 5;    // 5 in binary: 0101
<br/>int b = 3;    // 3 in binary: 0011
<br/>int result = a | b; // result = 0101 | 0011 = 0111 (7 in decimal)

- **Bitwise XOR (^):**
<br/>This operator compares each bit of two operands. If the bits are different (one is 1 and the other is 0), the resulting bit is set to 1. If both bits are the same, the result is 0.
<br/>eg. int a = 5;    // 5 in binary: 0101
<br/>int b = 3;    // 3 in binary: 0011
<br/>int result = a ^ b; // result = 0101 ^ 0011 = 0110 (6 in decimal)

- **Bitwise NOT (~):** I
<br/>This is a unary operator that inverts all the bits of the operand. All 1s become 0s, and all 0s become 1s.
<br/>eg. int a = 5;    // 5 in binary: 0101
<br/>int result = ~a; // result = ~0101 = 1010 (in 2's complement, this represents -6)

- **Left Shift (<<):**
<br/>This operator shifts the bits of the first operand to the left by the number of positions specified by the second operand. Each left shift moves the bits one position to the left, effectively multiplying the number by 2.
<br/>eg. int a = 5;    // 5 in binary: 0101
<br/>int result = a << 1; // result = 1010 (10 in decimal)
<br/>// Left shift by 1 is equivalent to multiplying by 2

- **Right Shift (>>):**
<br/>This operator shifts the bits of the first operand to the right by the number of positions specified by the second operand. Each right shift moves the bits one position to the right, effectively dividing the number by 2 (with some caveats for signed integers).
<br/>eg. int a = 5;    // 5 in binary: 0101
<br/>int result = a >> 1; // result = 0010 (2 in decimal)
<br/>// Right shift by 1 is equivalent to dividing by 2
