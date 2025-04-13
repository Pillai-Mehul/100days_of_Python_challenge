<h1>Query #1</h1>
<h2>Print a Hello World statement to the output in multiple way</h2>
<h1>Solution #1</h1>

print("Hello World")
    Or
print("Hello" + "World")
    Or
print("Hello" + " World")
    Or 
print("Hello" +  " " + "World")


<h1>Query #2</h1>
<h2>Print a Multi Line Hello World statement to the output</h2>

<h1>Solution  #2</h1>
print("Hello world!\nHello world\nHello world")

<h1>Query #3</h1>
Fix the code below 
print(Notes from Day 1") 
 print("The print statement is used to output strings") 
print("Strings are strings of characters" 
priint("String Concatenation is done with the + sign") 
print(("New lines can be created with a \ and the letter n") 
 
<h1>Solution #3</h1>

print("Notes from Day 1") 
print("The print statement is used to output strings") 
print("Strings are strings of characters") 
print("String Concatenation is done with the + sign") 
print("New lines can be created with a \ and the letter n") 
 

<h1>Query #4</h1>
<h2>Update the code to add an exclamation mark Using what you have learnt in this lesson and previous, can you figure out how take user input and slot it in between 2 strings?
 You are looking to print a sentence like this:
 Hello Name!
 e.g. Hello Mehul!</h2>

<h1>Solution #4</h1>
print("My name is" + " " + input("What is your name?") + "!")

This will take the Input from  "input("What is your name?")"
Then will print the Whole name as a concatenated string 
    E.g My name is "Smiley"(input value)!
    
<h1>Query #5</h1>
<h2>Check the length of the string inputted by the user 
Using Print Len & input function in a single line.</h2>

<h1>Solution #5</h1>
print(len(input("What is your name?")))

<h1>Query #6</h1>
<h2>Check the length of the string inputted by the user 
Using Print Len & input function as a variable.</h2>

<h1>Solution #6</h1>
Username = input("What is your name?")
Length = len(Username)
print(Length)

<h1>Query #7</h1>
<h2>We have 2 variables glass1 and glass2. glass1 contains milk and glass2 contains juice. Write 3 lines of code to switch the contents of the variables. You are not allowed to type the words "milk" or "juice". You are only allowed to use variables to solve this exercise.</h2>

<h1>Solution #7</h1>

glass1 = "milk"
glass2 = "juice"
glass1 , glass2 = glass2 , glass1

<h1>Query #8</h1>
<h2>Band name Generator Project</h2>

    1. Create a greeting for your program.
    2. Ask the user for the city that they grew up in and store it in a variable.
    3. Ask the user for the name of a pet and store it in a variable.
    4. Combine the name of their city and pet and show them their band name.

<h1>Solution #8</h1>
#Printing the Greedings 
print("Welcome to the Band Name Generator")
#Defining City & pet_name for the input value 
City = input("What's the name of the City you Grew up in?\n")
pet_name = input("What's your pet name?\n")

#Printing the final output of the Generator. 
print("Yourband name could be " + City +" "+pet_name)



