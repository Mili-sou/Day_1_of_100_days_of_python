PRINT FUNCTION:
Firstly working with python we need to know how to print a line .
Well, print() function helps us to print something.
NOTE:The sentence or word which we want to print/display  should be enclosed within " " inside the print function.

Example:
print("Hello World")

This above line of code will print Hello World in the terminal .
Here " " shows the beginning and ending of the string of characters.

what is a string?
For instance string is a collection of alphabets,words and characters.
Now what if one wants to write the "Hello" and "World" in two different lines.Yes its possible in python with "\n"->which refers to new line character.
Example:
print("Hello\nWorld")

Output:
>>Hello
>>World

NOTE:Start writing the code from first line without any gap otherwise running the code will yield you an "Indentation error".

INPUT FUNCTION:
SUppose you want to create a program which takes input from the user!Yes that's interesting and we can do that easily with a help of input function.
Example:
input("Whats your name?")
#the above line of code will first print "Whats your name?" in the terminal and then you will see a blinking cursor which indicates the user to enter the desired input .

Output:
Whats your name?Rohini

Here Rohini is the user input.
Now, lets combine the print and input function.
Example:
print("Hello"+input("What is your name?"))

output:
What is your name?Rohini

Hello Rohini

Here first the input() function gets executed because if we see the logic that we need to print "Hello --The user input--". So first printed line is "What is your nane?"and then program asks for the user input .
After taking the user input we get:
print("Hello Rohini")
and then the line gets printed..
Hello Rohini

Thats all required to start with your 1st python program!
