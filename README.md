# Beginner to Intermediate Programming in Python
***Date:** May 2019*

# Contents:

- [9th May2019](#9th-may2019)
- [10th May2019](#10th-may-2019)
- [12th May2019](#12th-may-2019)
- [14th May2019](#14th-may-2019)
- [15th May2019(Regular Expressions)](#15th-may-2019)
- [16th May2019](#16th-may-2019)
- [17th May2019(Numpy, Pandas, CSV files)](#17th-may-2019)
- [18th May2019(Matplotlib)](#18th-may-2019)
- [19th May2019](#19th-may-2019)

---

## [9th May2019](#contents)

**Problem statement-01:** Given 2 int values, return True if first parameter is negative and second parameter is positive or vice versa. Except if the third parameter is True, then return True only if first two parameters are negative.

**Test Cases**

    pos_neg(1, -1, False) → True
    pos_neg(-1, 1, False) → True
    pos_neg(-4, -5, True) → True
    pos_neg(-1, 1, True) -> False
    pos_neg(1, 6, True) -> False
    pos_neg(-1, -9, False) -> False

**Problem statement-02:** Create a Random Number Generator which takes the Range(lb, ub) and returns a Random number in the given range. lb < random number < ub

**Test Cases¶**

    RandomGenerator(1, 100) -> will be in range (1,100)

**Problem statement-03:** Given an integer N, calculate the sum of N random numbers in the range `[0, 1000000000000000)`

**Problem statement-04:** Design a procedure to perform Linear search on list of N unsorted unique numbers. It take an array and the key element to be searched and returns the index of the element of key element if found. Else returns -1

**Test Cases**

    linearSearch([1,4,8,0,3,5,6], 3) -> 4
    linearSearch([15, 12, 9, 6, 3, -3], 0) -> -1
    linearSearch([321, 543, 567, 789], 567) -> 2

**Problem statement-05:** Procedure to generate multiplication tables.

**Problem statement-06:** Procedure to return the list of factors of a given number.

**Test Cases**

    factorsList(6) -> [1, 2, 3, 6]
    factorsList(100) -> [1, 2, 4, 5, 10, 20, 25, 50, 100]
    factorsList(1) -> [1]

**Problem statement-07:** Design a procedure to determine if a given string is a Palindrome

**Test Cases**

    Palindrome("racecar") -> True
    Palindrome("python") -> False

---

## [10th May 2019](#contents)

**Problem statement-01:** Solve the following problems using Recursion and Iteration

- Power of a number
- Factorial
- GCD
- Towers of Hanoi
- Generating the nth Fibonacci number

**Problem statement-02:** Define a function to identity the number of times a substring is repeating in a given string

        substringCount('str', 'substr') -> 1
        substringCount('1234567891122334455', '3') -> 3
        substringCount('abccddccc', 'cc') -> 3
        substringCount('aaaaaaa', 'aaa' ) -> 5

**Problem statement-03:** Define a function to merge the characters of two strings alternatively. The remaining characters of the longer string are printed in the same order at the end.

        mergeString('abcd', 'abcd') -> 'aabbccdd'
        mergeString('abc', '123456') -> 'a1b2c3456'
        mergeString('0', '123456') -> '0123456'

**Problem statement-04:** Define a function to convert a binary number to the corresponding decimal number

        binaryToDecimal(1100) -> 12
        binaryToDecimal(1010) -> 10
        binaryToDecimal(111000) -> 56

**Problem statement-05:** Define a function to convert a decimal number to the corresponding binary number

        decimalToBinary(15) -> 1111
        decimalToBinary(1) -> 1

**Problem statement-06:** Define a function to check if a given year is a leap year. Returns a boolean value

        2000 -> True
        1900 -> False
        2012 -> True
        2020 -> True
        0200 -> False

**Problem statement-07:** Design a Python script to determine the difference in date for given two dates in YYYY:MM:DD format(0 <= YYYY <= 9999, 1 <= MM <= 12, 1 <= DD <= 31) following the leap year rules. Return the total number of days existing between the two dates.

        dateDifference('2019:05:10', '2019:05:01') -> 9
        dateDifference('0003:03:03', '0003:06:06') -> 95
        dateDifference('0001:03:27', '0001:06:03') -> 68

**Problem statement-07:** Define a function to find the average of all the outer elements of an N x M matrix.

        averageOuterMatrix([[1, 2, 3], [4, 5, 6], [7, 8, 9], [10, 11, 12]] -> 4.5

**Problem statement-08:** Define a function to print the sequence of spiral pattern elements for a given N x N matrix

        spiralPattern([[1,2,3], [4,5,6], [7,8,9]]) -> 1 2 3 6 9 8 7 4 5

---

### [12th May 2019](#contents)

**Problem statement-01:** You are given n words. Some words may repeat. For each word, output its number of occurrences. The output order should correspond with the input order of appearance of the word.

First line of input contains the total number of words n. Next n lines contain words that need to processed.

First line of the output should contain the total number distinct words. Second line of output must contain the frequency of words the same order of their appearance as in the input

**Sample Input :** 6

    abcd
    ijkl
    abcd
    pqrs
    abcd
    ijkl

**Sample Output :** 3

    3  2   1

**Problem statement-02:** Define a function to validate email addresses based on the following rules.

- Email should be in the format `username@domain.extension` username must start with an alphabet and can contain lowercase alphabet, digits, hyphen(-) and underscores( \_ ).
  username must not contain special characters, uppercase letters, whitespaces.
- Length of username must be in the range (6, 16)
- Domain can only contain lowercase alphabet and digits with length in range (3, 10) . No special characters are allowed
- Extension can only contain lower case alphabet and its length must be in the range (2, 4)

**Constraints:**
First line of input contains total number of email addresses n. Next n lines contain n email addresses.

Output must contain contain n lines with either 'Valid' or 'Invalid'

**Sample Input :** 6

    abc456@gmail.com
    456abc@yahoo.com
    abc_456@gitam.ed1
    abc-456@abc-d.in
    python@python.edu
    abc 456@edu.edu

**Sample Output :** Valid

    Invalid
    Invalid
    Invalid
    Valid
    Invalid

**Problem Statement-03:** Define a function that take an array of integers A, and an integer K and returns the longest possible sub-set of A i.e A' such that the sum of no two elements in A' is divisible by K.

**Constraints:**
First line in input contains the length of A and the integer K. Second line of input contains len(A) space-separated integers.

Output must contain the length of A' list

**Sample Input :** 4 3

    1 7 2 4

**Sample Output :** 3

---

## [14th May 2019](#contents)

### Hackathon - Phase 1

**Problem Statement-01:** For a given integer N, find the total number of Non - Prime Factors in the range (1, N) (both exclusive) that do not contain the digit 0

nonPrimeFactorsCount( 100 ) -> 2
nonPrimeFactorsCount( 50 ) -> 1

**Problem Statement-02:** For a given integer N. Find the least positive integer X made up of only 9's and 0's, such that, X is a multiple of N.

X is made up of one or more occurrences of 9 and zero or more occurrences of 0.

    Multiple( 5 )  -> 90
    Multiple ( 7 )  -> 9009
    Multiple( 1 )  -> 9

---

## [15th May 2019](#contents)

**Topics:**

- Python Packages and Modules
- Regular Expressions
- Iterators and Generators

---

## [16th May 2019](#contents)

**Topics:**

- File Handling / Data Processing
- Functional Programming
- External Libraries

---

## [17th May 2019](#contents)

**Topics:**

- Numpy library for N-dimensional Array operations
- Pandas library for Data Analysis
- Data Processing of CSV files

---

## [18th May 2019](#contents)

**Topics:**

- **Matplotlib** library for Data Visualization
  1. Line Plots
  2. Bar Graphs
  3. Scatter Plot
  4. Histograms
  5. Pie Charts

---

## [19th May 2019](#contents)

**Problem statement-01:** Consider the following algorithm to generate a sequence of numbers. Start with an integer n. If n is even, divide by 2. If n is odd, multiply by 3 and add 1. Repeat this process with the new value of n, terminating when n = 1. For example, the following sequence of numbers will be generated for n = 22:

    22 11 34 17 52 26 13 40 20 10 5 16 8 4 2 1

**Problem statement-02:** It is conjectured (but not yet proven) that this algorithm will terminate at n = 1 for every integer n. Still, the conjecture holds for all integers up to at least 1, 000, 000. For an input n, the cycle-length of n is the number of numbers generated up to and including the 1. In the example above, the cycle length of 22 is 16. Given any two numbers i and j, you are to determine the maximum cycle length over all numbers between i and j, including both endpoints.

---
