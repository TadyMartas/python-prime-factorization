Python Prime Factorization

A simple Python program that finds the two factors of a number using trial division.

The program calculates the square root of the input number and only checks possible factors up to this limit. Once a factor is found, the second factor is calculated by division.

How it works

For a number:

n = p × q

at least one factor must satisfy:

p ≤ √n

Therefore, the program only needs to test possible factors from 2 to √n.

Example

Input:

Insert number n: 1000000028000000147

The program searches up to:

√n ≈ 1,000,000,014

and finds:

✓ Factor found!
p = 1,000,000,007
q = 1,000,000,021

Time: 18.54 seconds
Technologies
Python
math
time
Features
Accepts an integer from the user
Calculates the search limit using math.isqrt()
Searches for a factor using trial division
Calculates the second factor automatically
Measures execution time
Displays the currently tested number
Limitations

This program is intended for learning and demonstration purposes.

Trial division becomes extremely slow for large numbers. This is especially relevant to cryptography, where numbers can be hundreds or thousands of bits long.

The program is not intended for breaking real cryptographic keys.

Changelog
v1.0
Added prime factorization using trial division
Added square-root search limit
Added execution time measurement
Added current candidate display
Added automatic calculation of the second factor
License

This project is for educational purposes.
