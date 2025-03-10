# PrimeGeneratorChecker_202401100400193

#Prime Number Generator and Checker

>>Description
This Python program allows users to:
1. Generate all prime numbers up to a given limit.
2. Check if a specific number is prime.

>>Features
1. Efficient prime-checking using the square root method.
2. Generates prime numbers up to a user-specified limit.
3. Simple and interactive command-line interface.

>>Usage
  1. Run the script using Python:
	  python prime_generator_checker.py

  2. Choose an option:
    * Enter 1 to generate prime numbers up to a limit.
    * Enter 2 to check if a specific number is prime.
  
  3. Follow the prompts to input a number or limit.

#Example
>>Generating Prime Numbers:
	Do you want to (1) generate prime numbers or (2) check if a number is prime? 
	Enter 1 or 2: 1
	Enter the limit: 20
	Prime numbers: [2, 3, 5, 7, 11, 13, 17, 19]

>>Checking if a Number is Prime:
	Do you want to (1) generate prime numbers or (2) check if a number is prime? 
	Enter 1 or 2: 2
	Enter a number: 17
	17 is a prime number.

#Requirements
Python 3.7/3.8/3.9/3.10/3.11 or 3.12.

#How It Works
	The is_prime(n) function checks if n is prime by testing divisibility from 2 to sqrt(n).
	The generate_primes(limit) function iterates through numbers from 2 to limit, checking for primes and storing 	them in a list.
	The main script prompts the user for input and calls the appropriate function.

#Author
	Developed by SuJaL KuMaR

#License
>>This project is open-source and free to use.
