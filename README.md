![image](https://github.com/Sanjayrajanrajappa/Coin-toss-Simulator/assets/91653459/77993888-402f-4efa-81be-d891b04073da)
# Coin-toss-Simulator
## Description
### The Coin-toss-Simulator is a simple and fun way to simulate a coin being tossed virtually and getting the outputs *Head* and *Tail*.

## Table Of Contents:
### Used Modules,Functions,etc
### Code Explanation 
### Outputs

# Used Modules,Functions,etc:
### => Random Module
### => Variable Assignment 
### => List 
### => Multiline Strings 
### => Print 
### => Method From Random Module

# Code Explanation:
```python
import random 
```
## In the above line the import keyword is used to make code in one module available in another. The random module can be used in generating random numbers , printing random value for a list or string , etc…

```python
cointoss = [
'''**   **  ******    *****     ******
 **   **  **      **     **   **    **
 *******  ******  *********   **     **
 **   **  **      **     **   **    **
 **   **  ******  **     **   ******''',
'''*******   *****    ******  **
   **    **     **    **    **
   **    *********    **    ** 
   **    **     **    **    ******
   **    **     **  ******  ******''']
```
## In the above lines of code the variable name *cointoss* is initialized and a list with two elements *Head* and *Tail* is assigned to it.

```python
print(“\n”,random.choice(cointoss))
```
## In the above lines of code, *print()* function is used to print the output on the screen.





