# Convert from seconds

People find it easier to read time in seconds, minutes, and hours rather than just seconds.

The first line of code provided takes an input as seconds.

Write a program that outputs the input time in seconds, minutes, and hours.

Ex: If the input is:

`4000`
the output is:
```
Seconds: 40
Minutes: 6
Hours: 1
```
# Square Root
Output the square root of the given number. The number will be saved under the variable name "mynum". Use the appropriate function from the math module to perform the operation.

Use the following statement to output your answer:
print(f'Square root of {value1:.2f} = {value2:.2f}'), where value1 is the input number and value2 is its square root.

Ex: If the input is:

9.0
the output is:

Square root of 9.00 = 3.00

# Pizza Party
Given the number of people attending a pizza party, output the number of people, number of pizzas needed, and the total cost for the number of pizzas. The number of people will be saved as the variable "num_people". For the calculation, assume that people eat 2 slices on average. Each pizza has 12 slices and costs $14.95.

Use the following statement to output the cost of the pizzas:
print(f'Cost for {numPizzas} pizza(s): ${cost:.2f}')

Hint: Use the ceil() function from the math module to round up the number of pizzas so that enough pizzas are ordered.

Ex: If the input is:

20
the output is:

People: 20
Pizza(s): 4
Cost for 4 pizza(s): $59.80

# Hypotenuse
Given two numbers that represent the lengths of a right triangle's legs (sides adjacent to the right angle), output the length of the third side (i.e. hypotenuse) with two digits after the decimal point. This formula for this is called Pythagorean's Theorem, as shown:

\begin{equation} c=\sqrt{(a^2+b^2)} \end{equation}

Where a and b are the legs of the of the right triangle and c is the hypotenuse.

The numerical lengths of the a and b will be saved to variables of the same name.

Note: To output the length of the hypotenuse with two digits after the decimal point, use:
print(f'Hypotenuse is {side3:.2f}'), where side3 is the variable representing the length of the hypotenuse.

Ex: If the input is:

3.00
4.00
the output is:

Right triangle has side lengths 3.00 and 4.00
Hypotenuse is 5.00
