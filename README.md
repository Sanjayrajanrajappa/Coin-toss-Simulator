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
## In the above line the import keyword is used to make code in one module available in another. 
## The random module can be used in generating random numbers , printing random value for a list or string , etc…

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
## “\n” is used to create a new line. When inserted in a string all the characters after the character are added to a new line.
## random is the Module Name.
## .choice() function call or method returns a random element from the given sequence.

# Output:
![dff](https://github.com/Sanjayrajanrajappa/Coin-toss-Simulator/assets/91653459/3344fa96-b2d5-41a5-87fa-852986b8c918)

![zx](https://github.com/Sanjayrajanrajappa/Coin-toss-Simulator/assets/91653459/dadd1979-4680-43d7-9412-94ee9b6c52f1)

# Thank You









