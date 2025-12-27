# 📊​ Push Swap

![42_pushswap](https://github.com/user-attachments/assets/d207d4b5-af7a-41f8-80a9-13b5c1c907c5)

## Overview
Push Swap is a project by 42 School, whose goal is to develop a program capable of sorting a stack of integers in a minimum number of moves, using a limited set of operations.
It focuses on the design and implementation of sorting algorithms, as well as the analysis of their complexity and optimization.

## Usage
```
make bonus
# Compile the executable 'checker'

ARG="4 67 3 87 23"; ./push_swap $ARG | ./checker $ARG
# ARG: list of numbers to sort
# Returns 'OK' if sorting was successful
# Returns 'KO' if sorting failed
# Returns 'Error' if input is invalid (non-numeric character, duplicate)

make runtest ELM=100 RUN=50 MAX=700
# ELM: number of elements to sort
# RUN: number of tests to run
# MAX: maximum number of moves allowed
# The script then displays the results of the various tests (average, minimum, maximum, success rate)
```
