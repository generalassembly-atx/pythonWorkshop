
# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Python Programming 101

### LEARNING OBJECTIVES
*After this lesson, you will be able to:*

- Discuss the history of Python and its use across different industries.
- Define how Python compares to other programming languages.
- Describe the benefits of a Python workflow when working with data.
- Demonstrate basic Python programming fundamentals to solve real world problems.
- Create a custom learning plan to help you continue to build fundamental python skills after this workshop.

### STUDENT PRE-WORK
*Before this lesson, you should already be able to:*

- Bring a laptop with [Anaconda](https://www.continuum.io/downloads) using [Python 2.7](https://www.python.org/download/releases/2.7/) installed. Note: Make sure to choose the *Python 2.7* version for your operating system. 
- If you are using a PC, also install [git-bash terminal](https://git-for-windows.github.io).
- *Optional*: Install a text editor like [Sublime Text 3](http://www.sublimetext.com) or [Atom](https://atom.io) on your computer. If you are using Anaconda, **Spyder** is included in the distribution.

---

<a name="opening"></a>
## Opening (10 mins)

#### Instructor Bio

Welcome to Python Programming 101! Here's a bit about me:

#### Introduce Yourselves

Before we dive in, let's chat a bit about you!

#### Our Expectations

- You're ready to take charge of your learning experience.
- You've installed Anaconda & Python 2.7.
- You're interested in learning about Python!

#### Our Objectives

What we’ll cover:

* Why Python & What can Python do for me?
* Writing Python Code
* Common Python Libraries
* Programming Fundamentals (pseudocode and Python)
* How you can use Python to work with data (and solve real world problems!)

Why this topic matters:

* Programming is a highly sought-after skill 
* Python has been gaining popularity


Why this topic rocks:

* Python opens up a door to a variety of opportunities, from data science to research and web development!

***

<a name="intro1"></a>
## Introduction: Why Python? What Can Python Do For Me? (15 mins)

**What is Python?**

- Python was created by Guido Van Rossum in 1991
- Emphasizes **productivity** and **readability**
	* The language is easy to pick up and learn
	* This gentle learning curve brings makes it easier for many to contribute to production level code
	* Readable code means that almost anyone can pick up a piece of code and understand what it is doing
- Interpreted, object-oriented, high-level programming language with dynamic semantics
	* **Interpreted**: Code implementations execute instructions without having to *compile* them into machine-language instruction.
	* **Object-oriented** (OO): Instead of concentrating on isolated "actions", object-orientation enables us to focus on "objects" that contain data (attributes). Objects have specific procedures, known as methods (code) that can access and modify the attributes of the object.
		* OO makes it easier to write and reuse code in other programs
	* **High-level programming**: Related to the code readability mentioned earlier
		* Python syntax is similar to English, which makes it easy to use and automate!
	* **Dynamic semantics**: Once data has been specified, the machine must be instructed to perform operations on the data. Dynamic semantics provides flexibility at run-time.

**So why Python?**

* Python is extremely fun to develop in!
* Everything can be done with Python!
* If something can't be done, you can easily create an extension for it :)
* Everything can not only be done, but it can be done **fast**. For example, a program that takes you weeks in C++ might only take you a day to write in Python.
* Great for individual prototyping and commercial settings.
* Because it is a modern, elegant, highest level language.
* Because it is highly expressive, i.e., you will earn higher productivity.
* Because it comes with "batteries included", i.e. libraries for whatever you want.
* Because it is well documented and has a well-established and growing community.

<a name="demo1"></a>
## Demo: Let's Write Some Python Code (25 mins)

Solve finding the maximum of a list !

**Where is Python used?**

* Industry & Academia
* Middleware Tools and Plugins
* Research
* Web Development & Web Applications
* Game Development
* Windows Applications
* You name it!

### Here are some specific examples:

* Industry
	- [Drug discovery](https://www.python.org/about/success/astra/)
	- [Financial services](https://www.python.org/about/success/resolver/)
	- [Films and special effects](https://www.python.org/about/success/ilm/)
* Academia
	- [Gravitational waves](https://software.intel.com/en-us/blogs/2016/02/14/python-brings-us-the-ligo-gravity-wave-sound)
	- [Scientific visualisation](https://www.python.org/about/success/mayavi/)
	- [Biomolecule simulation](https://www.python.org/about/success/mmtk/)

## The Benefits of Python


What other languages have you heard of? 

Python is often compared to other interpreted languages, such as Java, JavaScript, or Perl.

What is an *interpreted language*? This simply means a language that executes right away, which means you can run your code immediately after writing it!


#### EXAMPLE

Let's see what Python looks like, starting with "Hello World!" This is an old computer science joke, as "hello world!" is a phrase commonly used when writing your first line of code :)


So in essence, we will be writing some Python code in order to print the message "Hello World!" on our screen. 

- **Python**

```python
print("hello world")
```

Well that was easy! What did we just do here?

> Note: Discuss basic print statements

Now, how does this compare with some other common programming languages? This will help demonstrate how much more *efficient* and *fun* it is to write code with Python.

#### Writing "Hello world!" in **C++**

```c++
#include<iostream>
using namespace std;

int main()
{
	cout << "Hello World!";
	return 0;
}

```

The Python version of this program is very simple: one line of code that will `print` the string `'Hello World!`.  It is easy to read and easy to understand.

The C++ version does exactly the same thing, but it requires us to write a LOT more information. For example, we would need to define a `main` function, we would have to be more careful with our punctuation, and `cout` is not very understandable in lay terms.

The same exact statement in Java is similarly confusing:

> Note: *Java* is different from *Javascript*

#### Writing "Hello world!" in **Java**

```java
public class HelloWorld
{
    public static void main (String[] args)
    {
        System.out.println("Hello, world!");
    }
}
```

> Note for advanced programmers: Notice that in the Java version, we define the code inside the context of class.

In Object Oriented Programming, a *class* is a template definition of the methods and variables in a particular kind of object. In other words, an object is a specific instance of a class; it contains actual values instead of variables.

#### Python: shell vs scripts

In the example shown above, we are assuming that we are using an interactive shell, i.e. we are writing code that is executed immediately by the Python interpreter, which means we are able to "interact" with the results of the commands we pass. We can do this via :

- **python shell**: A python shell has a similar look and feel to a regular terminal shell. You can launch a python shell with:

```
> python
```

- **ipython shell**: The look and feel is more interesting than a regular terminal, providing syntax coloring and shortcuts that help us interact with our code. You can launch an ipython shell with:

```
> ipython
```

- **Jupyter Notebook**: A Jupyter Notebook is one of the most popular interfaces for using python to work with data. A Jupyter notebook is a web interface that uses formatting and allows us to run our code in "dataframes", or :

```
> jupyter notebook
```

Alternatively, there may be instances where we do not need to interact with our Python code. Instead, we may want to execute a program (in batch mode for instance) and simply get our results.

In those cases, we would need to create a Python script. We can use any *plain text editor* of our choice and save the code in a `.py` file.

#### What is a "plain text editor"?

Plain text, as you might have guessed, is rather plain! It supports standard ASCII characters, including numbers, symbols, and spaces, but does not support any type of text formatting. Therefore you cannot apply bold, italic, or underlined styles, and you cannot use different fonts or font sizes in a plain text document.

Common plain text editors include Atom, NotePad (Win), TextEdit (Mac), Nano (Linux, Mac), NotePad++ (Win) or TextWrangler (Mac).

An alternative to using plain text editors is the use of an integrated development environment (IDE), which  provides comprehensive facilities to computer programmers for software development. A good IDE consists of a source code editor, build automation tools, and a debugger as well as intelligent code completion.

Some standard Python IDEs:

- [PyCharm](https://www.jetbrains.com/pycharm/)
- Eclipse with [PyDev](http://www.pydev.org)
- [Atom](https://atom.io)
- Anaconda distributions (Mac, Win, Linux) come with an IDE called `Spyder`.


> Check: What are some ways we can interact with python? Why would we use these?

#### Putting it all together

Ok. Let's write a barebones script for our "Hello World!" program. Let's save this to a file called `hi.py`. 

How would we do this?

> Answer
```python
print("Hello world!")
```

Now, to run our script by passing it as a Python command in our terminal, we would *also* need to write:

```python
> python hi.py
```

Voila! You've just run your first python script!!

> ** Note** Only go over the following subsection if the majority of your class has a programming background! If your class is mostly beginners, ask them to practice writing their own basic `print` statements. 

### Explanation for Programmers

In Python, all of the code at indentation level 0 gets executed. Functions and classes that are defined but are not on at the 0-th level indentation are not executed.

Unlike other languages, there's no `main()` function that gets run automatically - the `main()` function is implicitly all the code at the top level.

In this case, the top-level code is an if block.  `__name__` is a built-in variable which evaluates to the name of the current module. We can test whether our script is being run directly or being imported by something else by testing

```python
if __name__ == "__main__":
    ...
```

A more sophisticated version of the "Hello World!" script is therefore:

```python
def main():
	print("hello world")

if __name__ == '__main__':
    main()
```

<a name="guided-practice1"></a>
## Guided Practice: Installing and Configuring Common Python Libraries (20 mins)

> Instructor Note: We recommend that you demonstrate how to run the following commands and concepts using a **Jupyter notebook**.

1. Open Jupyter: in a terminal type: `jupyter notebook`
2. Navigate to an appropriate folder where your work will be saved.
3. On the top-right-hand-side click in the button called "New" and select "Python 2"
4. Voilà, you are ready to type the commands we will cover below.

**Packages**

Packages are libraries of code written to solve particular set of problems. In Python, there are many packages that help you work more efficiently with data. These include: pandas, Scikit-learn, and NumPy

* `pandas`
	* Ever used Excel? How do you fancy working with data structured in a similar way, but without the irritation of formatting, long formulae, and better graphics? In that case, use *pandas*.
* `SciPy/NumPy`
	* Does your application require the use of advanced mathematical functions or numerical operations with arrays, vectors or matrices? Try *SciPy* (scientific python) and *NumPy* (numerical python).
* `Scikit-Learn`
	* Are you interested in using python in a data science workflow to exploit the use of machine learning in your applications? Look no further than *Scikit-learn*!
* `matplotlib`
	* Are you tired of the bland-looking charts produced with Excel? Are you bored of looking for the right menu to move a label in your plot? Take a look at some of the visuals offered by *matplotlib*.	
* `statsmodels`
	* Is your boss asking about significance testing and confidence intervals? Are you interested in descriptive statistics, statistical tests, plotting functions, and result statistics? Well *statsmodels* offers you all that and more!
* `Beautiful Soup`
	* All the data you require is available freely on the web but there is no download button. What if you need to scrape the website? Well then you're in luck! You can extract data from any HTML webpage using *Beautiful soup*.

### Installs

You can install a package with `conda` or `pip`. For example:

`pip install <package-name>`

This is similar to how we installed `plotly` earlier!

> Check: What is a package in python? What are they used for? How are they installed?

### Importing a module
```python
import math
x = math.cos(2 * math.pi)
print(x)

from math import *

log(10)

log(10,2)
```

### Types, Variables, assignment

```python
# variable assignments
x = 1.0
my_variable = 12.2
type(x)

y = 1
type(y)

b1 = True
type(b1)

s = "String"
type(s)
```
```python
import types
print(dir(types))

1+2, 1-2, 1*2, 1/2

1.0+2.0, 1.0-2.0, 1.0*2.0, 1.0/2.0

# Comment

# Comparison: >, <, <=, <=, ==
2 > 1

# Testing for equality
2 == 2
```

**Lists**

```python
l = [1,2,3,4]
print(type(l))
print(l)
print(l)
print(l[1:3])
print(l[::2])

# Python starts counting from 0
print(l[0])
```

**Tuples**

```python
point = (10, 20)
print(point, type(point))

x, y = point
print("x =", x)
print("y =", y)
```

**Dictionaries**

```python
params = {"parameter1" : 1.0, "parameter2" : 2.0,
"parameter3" : 3.0,}
print(type(params))
print(params)
```

***

<a name="ind-practice1"></a>
## Independent Practice: Applying Python Pseudo-code to Sample Data (20 mins)

Pseudocode is a language (very close to English!) that allows us to represent a program concisely. The only thing you need is a statement to show where you are starting and where you are ending a program.

Calculate and print the average of three numbers: 5, 10, and 15.

```
Start
	num1 = 5
	num2 = 10
	num3 = 15
	sum = num1 + num2 + num3
	average = sum/3.0
	print average
End
```

### Proposed problems:

<details>
<summary>
1. Create a complete programme that will calculate the area circle with radius r.
</summary>
```
Start
	pi = 3.14159265359
	radius = r
	area = pi * r * r
	print area
End
```
</details>

<details>
<summary>
2. Calculate and print the square of a number. If the number is larger than 10 also calculate the cube.
</summary>
```
Start
	number = n
	square = n^2
	print square 
	
	if n > 10 then
		cube = n^3
		print cube
	else
		do nothing
	end if

End
```
</details>

<details>
<summary>
3. List the letters in the sentence "Python is awesome"
</summary>
```
Start
	MyString = "Python is awesome"
	
	for each letter in MyString
		print letter
	end for
End
```
</details>

***

**BREAK** (5-10 min)

***

<a name="intro2"></a>
## Introduction: Python Programming Fundamentals (15 mins)

We recommend using a Jupyter notebook for this guided practice. This is a standard interface used across platforms (Mac or Win) and is commonly used when programming in Python and working with data.

To open a new Jupyter notebook:
1. Open up your terminal and type:
`jupyter notebook`
2. Navigate to an appropriate folder where your work will be saved.
3. On the top-right-hand-side click in the button called "New" and select "Python 2"
4. Voilà, you are ready to type the commands we will cover below.

## Programming fundamentals

Understanding core programming concepts and why they are used is just as important as knowing how to write code. 

Before we start, let's review some basic programming concepts:

- **Syntax**: the syntax of a programming language is the set of rules that define the combinations of symbols that result in structured programs for that language.

- **Variables**: A variable is a storage location and an associated symbolic name that contains a value (in other words, a known or unknown quantity or piece of information). Variables can be of different `types`.
	- Strings
	- Integers
	- etc

- **Data Structures**: Data structurse are a particular way of storing and organizing data in a computer so that it can be used efficiently. Some examples include:
	- Lists
	- Tuples
	- Arrays
	- Matrices
	- Dataframes

- **Control Structures**: A control structure is a block of programming that analyses variables and chooses a direction in which to go based on given parameters. The term flow control details the direction the program takes (which way program control “flows”). Hence it is the basic decision-making process in computing; flow control determines how a computer will respond when given certain conditions and parameters. Some typical structures include
	- `If` statement
	- `For` loop
	- Functions 

The interrelationship of these elements make it possible for us to write programs that implement algorithms and solve problems!


### Control Flow

* The term `control flow` details the direction the program takes (which way control “flows” through the program). In other words, it determines how a computer will respond when given certain conditions and parameters.

#### **If**

An `if` statement is a conditional structure that, if proved true, performs a function or displays information. 

Think of this as a decision that moves the flow of your program depending on the answer to a TRUE-FALSE question. 

```
IF a person is older than 18
THEN they can vote
ELSE they cannot vote
```

We can express the pseudo-code above in Python as follows:

```python
if age_person > 18:
	return "They can vote"
else:
	return "They cannot vote"	
```

Let's see another example:

```python
A = 10
B = 100
if A>B:
	print("A is larger than B")
elif A==B:
	print("A is equal to B")
else:
	print("A is smaller than B")
```

**Activity: Can you explain what the code above is doing?**

#### **For loop**

A loop statement in programming performs a predefined set of instructions or tasks until a predetermined condition is met. Think of this as a repetitive action that has to be performed until a specific condition occurs. 

``` 
FOR each user of a service in a list
   PRINT greet them
```

In the pseudo-code above, the condition we are asked is to greet each user in a list. We stop the repetition when we reach the end of the list. 

We can express this loop in Python as follows:

```python
users = ["Jeff", "Jay", "Theresa"]

for user in users:
    print("Hello %s" % user)
```

**Tip**: When creating a `for` loop, make sure the condition will always be met in order to prevent an endless loop, which can crash your environment.

Let's see another example. Can you explain what the program is doing?

```python
for x in [1,2,3]:
    print(x)

for key, value in params.items():
    print(key + " = " + str(value))
```

##### List comprehension

List comprehensions are an elegant way to define and create lists in Python. A list comprehension uses a `for` loop inside the definition of the list itself.

Let's take a look at one, and see if you can figure out what is happening here:

```python
l1 = [x**2 for x in range(0,5)]
```

#### **Functions**

A function is a group of instructions, also known as a `named procedure`, used by programming languages to return a single result or a set of results. 

Functions are a convenient way to divide our code into useful blocks, providing us with order as well as making the code more readable and reusable.

Here is how you define a function in python:

```python
def function_name(input1, input2...): 
    1st block of instructions 
    2nd block of instructions
    ...
```

Let us define a function that returns the square of the input value:

```python
def square(x):
	"""
	Return the square of x.
	"""
	return x ** 2
```

We can call this function as follows:

```python
var1 = 7

var2 = square(var1)

print(var2)
```

***

<a name="demo2"></a>
## Demo: Writing Programs in Python (15 mins)

Python is an *interpreted* language, which means you can run a program as soon as you make changes to the file. This makes iterating, revising, and troubleshooting programs much quicker than many other languages.

> Note: Explain that the mathematical constant `Pi` is included in the `math` module.

<details>
<summary>
1. Create a complete programme that will calculate the area circle with radius r.
</summary>

```python
# We are importing the value of pi from 
# that module - Easy to read, right?
from math import pi

def circ_area(r):
	return pi * r**2

r = 3
area = circ_area(r)
print(area)
```
</details>

***

<a name="guided-practice2"></a>
## Guided Practice: Dive into Data with Python (20 mins)

Let's create a new Jupyter notebook for this practice. We'll work in pairs.

1. Save the file called [Python101_Part2_GuidedPractice.ipynb](./code/Python101_Part2_GuidedPractice.ipynb) in a known location in your local file system.
2. Start Jupyter by running `jupyter notebook` and navigate to the location where you last saved the file.
3. Open the file.
4. Voilà, you can now start the Guided Practice!


***

<a name="ind-practice2"></a>
## Independent Practice: More Python Practice (20 mins)

### DISCUSION

Given your interests and knowledge, which are you more interested in learning about:

- practical applications of python, or
- python fundamentals?

> ### OPTION 1:

You can use the [Iris Dataset notebook included in the materials](./code/Python101_Part2_IndPractice.ipynb) to follow up the introduction to pandas in the previous section. Note that the notebook makes reference to the [Iris Dataset included here](./code/data/iris.csv).
>
> This activity demonstrates some of the practical applications of python on real data. 

> ### OPTION 2
Alternatively, you can tackle programming tasks that review many of the python fundamentals covered earlier. Here are some suggestestions:

<details>
<summary>1. A recipe you are reading states how many grams you need for the ingredient. Unfortunately, your store only sells items in ounces. Create a program to convert grams to ounces.

`ounces = 28.3495231 * grams`
</summary>
```python
def gr2oz(x):
	return 28.3495231 * x

grams = 10
ounces = gr2oz(grams)
print(ounces)
```
</details>

<details>
<summary>
2. Read in a Fahrenheit temperature. Calculate and display the equivalent centigrade temperature. The following formula is used for the conversion:

`C = (5 / 9) * (F – 32)`
</summary>
```python
def F2C(F):
    return (5.0/9.0) * (F - 32)

f=86
c= F2C(f)

print("{0} Fahrenheit is {1} centigrade".format(f,c))
```
</details>

<details>
<summary>
3. Calculate the amount obtained by investing the principal P for N years at the rate of R. The following formula is used for the conversion:

`A = P * (1 + R) ^ N`
</summary>
```python
def compound_interest(P, R, N):
    return P * (1 + R)**N

P = 1000
R = 0.1
N = 2

Interest = compound_interest(P, R, N)

print(Interest)
```
</details>

### FOLLOW UP ACTIVITY

***

<a name="conclusion"></a>
## Conclusion: Review + Recap Topics (10 mins)

### Class discussion

- What have you accomplished today? 

### Review Topics Covered

In the workshop you have covered the following topics:

* Discuss the history of Python and its use across different industries.
* Compare Python with programming languages.
* The benefits of a Python workflow
* Python programming fundamentals.
* Use Python code to solve real world data problems.

***

<a name="takeaway"></a>
## Takeways: Learning Plan + Q&A (15 mins)

#### What Should You Do Next?

We suggest checking out different resources, such as books, podcasts, GA courses, and more. Here are some tips:

* For beginner programmers:
	* Go through [Learn Python the hard way](http://learnpythonthehardway.org)
	* Read up on and familiarise yourself with the language by going through the tutorials [A Beginner's Python Tutorial](https://en.wikibooks.org/wiki/A_Beginner%27s_Python_Tutorial)

* For programmers new to python:
	*  Read the information in [Moving to Python From Other Languages](https://wiki.python.org/moin/MovingToPythonFromOtherLanguages)
	* [Python for java developers](https://antrix.net/static/pages/python-for-java/online/)
	* [Python for MATLAB users](http://bastibe.de/2013-01-20-a-python-primer-for-matlab-users.html)

* For more seasoned programmers:
	* Challenge yourself by tackling the [Python Challenge](http://www.pythonchallenge.com) 

* If you are interested to apply Python in Data Science:
	* Look at the Data Science workshops and courses in [General Assembly](https://generalassemb.ly/education/data-science?&gclid=CjwKEAjwk6K8BRDM3aCSkdCtzSQSJAA3Vf38leCWKuRFD33jAqNkjHhIqVTVv6i6PiiBtxse7DW1SRoCFE3w_wcB)

#### Q & A


***

## ADDITIONAL RESOURCES

- [Python success stories](https://www.python.org/about/success/)
- [Learn Python the hard way](http://learnpythonthehardway.org)
- [Beginners' Guide to Python](https://wiki.python.org/moin/BeginnersGuide)
- [10 Minutes to Pandas](http://pandas.pydata.org/pandas-docs/stable/10min.html)
- [Comparing Python to Other Languages](https://www.python.org/doc/essays/comparisons/)
