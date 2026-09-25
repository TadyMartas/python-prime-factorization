# Python Prime Factorization

A simple Python program that finds the two prime factors of a number using trial division.

## Features

* Finds prime factors using trial division
* Limits the search to √n
* Measures execution time
* Displays the current number being tested
* Automatically calculates the second factor

## Requirements

* Python 3.x

## Usage

Run the program:

```bash
python prime_factorization.py
```

Enter a number when prompted:

```text
Insert number n: 1000000028000000147
```

Example output:

```text
Finding factor until √n = 1,000,000,014
----------------------------------------

✓ Factor found!
p = 1,000,000,007
q = 1,000,000,021

Time: 18.54 seconds
```

## How it works

The program checks possible factors from `2` up to `√n`.

If a factor is found, the second factor is calculated by dividing `n` by the first factor.

For example:

```text
n = p × q
```

At least one factor must satisfy:

```text
p ≤ √n
```

This allows the program to stop searching after reaching the square root of `n`.

## Limitations

The program uses simple trial division, so execution time increases significantly as the input number gets larger.

This project is intended for educational purposes and demonstrates the basic principles of integer factorization.

## Changelog

### v1.0

* Added prime factorization using trial division
* Added √n search limit
* Added execution time measurement
* Added current candidate display
* Added automatic calculation of the second factor
