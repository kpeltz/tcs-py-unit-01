

# Unit 1 - Lesson 1: Set Up and Installation


## KEY CONCEPTS
### What is an IDE/workspace?
Before you start coding, you will need an integrated development environment (IDE). 
An IDE is software that you can create, edit, and run programs in. 
Think of it as a super fancy Word or Notepad.

### How do we create and run a program?
Let's get used to the IDE we will be using. 
The instructor should go to [CodeInterview's remote code pad](https://codepad.remoteinterview.io) 
and invite their student to join the workspace.

There are two important parts of the IDE:
- (To the left) you'll see the editor area where you can create files and write code in them. 
After you write this code, you can tell the IDE to run it.
- (To the right) there is an area called the terminal. 
You can type `python3` in the terminal, and the prompt will change. 
You now have an active Python shell. 
You can use the command `exit()` to leave the Python shell.

Try it out!
```bash
$ python3           # activate Python 3 shell
...
>>> exit()          # leave Python 3 shell
$ 
```
When you type code here, as soon as you press enter the IDE runs your code. 
This is useful for testing commands. \
Try it out!
```python
print("Hello, World!")
```
That should have displayed the word hello underneath what you typed! 
You can type `exit()` to go back to normal. 
We also use the terminal to compile and run our programs. 
We'll do that in our activities today.

### What is a print statement and how do we write one?
A print statement displays the __string__ we pass into `print(...)` in the terminal.
To print a string, or any set of letters and words, you put it in quotation marks `"..."`. 
For example, we just ran a line of code which printed `"Hello, World!"`. 
In this example, `"Hello, World!"` is a string, so we put `"..."` around it so we could print it. 


## ACTIVITY #1
### Printing A Number
You can also print out numbers simply by putting the number (without quotes) after the print command.
Try to out and print your favorite number!
### Solution
```python
print(16)
```


## ACTIVITY #2
### Print a sentence with a number
Sometimes you want to print out a string and numbers together. 
You can use the `+` operator to append (put together) numbers and strings. 
If you want to put together numbers and strings, 
the number needs to have str with parentheses around it. 
This tells the computer to convert the number to a string.
### Solution
```python
print("My favorite number is " + str(16))
```


## ACTIVITY #3
### Tell us about you
Print your name on one line, your age on the next line, 
and then your favorite color on the last line. 
Here's what your output could look like:
```bash
My name is Bob.
I am 12 years old.
My favorite color is red.
```
### Solution
```python
print("My name is Bob.")
print("I am 12 years old.")
print("My favorite color is red.")
```

## ADDITIONAL PRACTICE
### Make a Square
We can draw some fun pictures by printing things. 
Try to print a square made of `#`s. 
We can make it with 4 `#`s per side, so it will look like this:
```bash
#### 
#  # 
#  # 
#### 
```
### Solution
```python
print("####")
print("#  #")
print("#  #")
print("####")
```


## MORE ADVANCED PRACTICE
### Coding is Fun!
Print the word "FUN" made out of any character you want. Here’s an example using `&`.
```bash
&&&&&& &&   && &&   && 
&&     &&   && &&&  && 
&&&&&  &&   && && & && 
&&     &&   && &&  &&& 
&&     &&&&&&& &&   && 
```

Make yours as big or small as you want!


## RESOURCES
- Here’s an [extra tutorial on printing](https://www.tutorialspoint.com/python/python\_basic\_syntax.htm)
- Here's where you can try the [IDE](https://codeinterview.io/) some more on your own

## HOMEWORK
- Print out a statement saying what you're most excited to learn about in this course!
- Print out the number 5 and the string "days" using one line of code
- Design and print a shape made out of @ signs
