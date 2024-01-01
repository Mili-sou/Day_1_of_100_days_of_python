#Remeber: Python file is always saved using a .py extension.

PRINT FUNCTION:
Firstly working with python we need to know how to print a line .
Well, print() function helps us to print something.
NOTE:The sentence or word which we want to print/display  should be enclosed within " " inside the print function.

Example:
print("Hello World")

![Screenshot (2)](https://github.com/Mili-sou/Day_1_of_100_days_of_python/assets/155342372/3c8e4b14-6cc9-4d57-9dac-fdb05106d19a)

This above line of code will print Hello World in the terminal .
Here " " shows the beginning and ending of the string of characters.

what is a string?
For instance string is a collection of alphabets,words and characters.
Now what if one wants to write the "Hello" and "World" in two different lines.Yes its possible in python with "\n"->which refers to new line character.
Example:
print("Hello\nWorld")

Output:
![Screenshot (3)](https://github.com/Mili-sou/Day_1_of_100_days_of_python/assets/155342372/bec00772-70eb-4783-a20b-211b76f7bf0e)

NOTE:Start writing the code from first line without any gap otherwise running the code will yield you an "Indentation error".

INPUT FUNCTION:
SUppose you want to create a program which takes input from the user!Yes that's interesting and we can do that easily with a help of input function.
Example:
input("Whats your name?")
#the above line of code will first print "Whats your name?" in the terminal and then you will see a blinking cursor which indicates the user to enter the desired input .

Output:
![Screenshot (4)](https://github.com/Mili-sou/Day_1_of_100_days_of_python/assets/155342372/f7c3defa-ba13-4fa0-94d4-56649fb4bcc4)

Here Rohini is the user input.
Now, lets combine the print and input function.But before doing that lets learn about the concatenation.COncatenation is a concept used with string.Basically concatenation means combining two strings together.
"+" is used to concate to strings.
Example:
print("Hello"+"World")

output:
![Screenshot (5)](https://github.com/Mili-sou/Day_1_of_100_days_of_python/assets/155342372/736f94b3-a977-42a6-8427-46312d208e86)

But what if we want to print a space between the two concatenated strings??Lets look at 3 ways by which it is possible:
1.print("Hello "+"World")
2.print("Hello"+" World")
3.print("Hello"+" "+"World")
First two ways include leaving a space with either after the "Hello" or either before the "World".And the third way is to separate the two strings by printing a space.
NOw we can hop to our idea of working with both the print and input function.
Example:
print("Hello"+input("What is your name?"))

output:
![Screenshot (6)](https://github.com/Mili-sou/Day_1_of_100_days_of_python/assets/155342372/a9fb0cac-41d0-4b71-b7bc-c62503d514b9)

Here first the input() function gets executed because if we see the logic that we need to print "Hello --The user input--". So first printed line is "What is your nane?"and then program asks for the user input .
After taking the user input we get:
print("Hello Rohini")
and then the line gets printed i.e. Hello Rohini

Thats all required to start with your 1st python program!
