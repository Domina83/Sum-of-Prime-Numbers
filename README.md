# Sum of Two Prime Numbers

This C++ program checks if a given number can be expressed as the sum of two prime numbers.

## Language
C++

## Description
- The user inputs a positive integer.
- The program checks all possible pairs `(i, n - i)` where both are prime.
- If such a pair is found, it prints the pair(s).
- If not, it displays a message saying it can't be expressed as the sum of two primes.

## Sample Output

Enter a positive integer: 34

34 = 3 + 31

34 = 5 + 29

34 = 11 + 23

34 = 17 + 17

If no pairs found:

Enter a positive integer: 7

7 can't be expressed as sum of two prime numbers.

## How to Run
1. Save the code in a file called `sum_of_primes.cpp`
2. Compile and run using:
```bash
g++ sum_of_primes.cpp -o prime_sum
./prime_sum

What I Learned

How to check for prime numbers using loops

Using functions to organize logic

Looping through pairs to find combinations

Boolean flags for condition control
