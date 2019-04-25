# Function-return-exercise
A tutorial coding exercise from CodeAcademy
The following exercise will simply practice returning a value given a defined function. These examples are set around physics. Practice remaking this code from scratch!
Given the following variables that should first be defined in the global environment:

train_mass = 22680
train_acceleration = 10
train_distance = 100

bomb_mass = 1

You will now do a series of steps. First, define a function that converts farenheit to celsius (takes a F temp as an argument). It shoult return a temp in celsius. Conversion = (F - 32) * 5/9
Now call your function to a saved variable (like f_100_in_C) that takes 100 as an input. Print this function to the console.
Define a new function that converts C to F, and returns the temp in Farenheit. Conversion = C * (9/5) + 32
Call function to a new variable with 0 Celsius as input, and print this new variable to the console.
Define a function get_force, with mass and acceleration as parameters and returns a new variable force (F = m * a)
Call this function to a new variable for train force, that takes train_mass and train_acceleration as input.
Print the string "The GE train supplies X Newtons of force." to the console, replacing X with the value of line 17's saved variable.
Define a function get_energy that takes mass and c. C being a constant should default to 3 * 10 ** 8. This funtion should multiply mass * c squared, and return a variable with energy value.
Call this function on a new variable that takes (bomb_mass) as input and save this variable.
Print "A 1 kg bomb supplies X Joules." with X replaced with the value of line 20's variable.
Define a function that calculates work, with mass, acceleration and distance as arguments. This function should calculate force first using get_force and multiply it by distance. Have this function return a variable with work value (m * a * d)
Call this funtion to a variable that calculate's the train's work, using train_mass, train_acceleration and train_distance as input.
Print "The GE train does X Joules of work over Y meters." with X and Y replaced by the value of the train's work as X and train_distance as Y.
The output of this exercise should be:

37.77777777777778
32.0
The GE train supplies 226800 Newtons of force.
A 1kg bomb supplies 90000000000000000 Joules.
The GE train does 22680000 Joules of work over 100 meters.

The code is also supplied as a separate file on this repo in case it needs to be consulted.
