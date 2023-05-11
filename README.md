# Population Growth Calculator

This program calculates the number of years required for a population to reach a certain size, based on a given starting population and ending population.

## Prerequisites
* You should have the **`cs50`** library installed in your system to run this code.

## Usage
1. Compile the code using **`gcc -o population population.c -lcs50`**
2. Run the executable using **`./population`**
3. When prompted, enter the starting population.
4. When prompted, enter the ending population.
5. The program will calculate the number of years required for the population to reach the given ending population size.
6. The program will output the number of years on the console.

## Code Description
* The program takes two inputs: the starting population and the ending population.
* It then calculates the number of years required for the population to reach the ending population size, assuming that the population grows by 1/3 of its size every year, with an additional loss of 1/4 of the population due to deaths.
* Finally, the program outputs the number of years required to reach the ending population size.
