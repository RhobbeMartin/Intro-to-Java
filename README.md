Java file: All of our code

.md:Text,Defiition,Ext;
## Intro to Java

A Java program can be characterized as an **object** represented in a **class**.
Currently our program has a *main* object. Inside the object has a *main* class.

## Output
In Java to output an item to the console we use 'System.out.print("")' and 
'System.out.println("")'
'System.out.println()' prints the statement and moves to the next line, while
'System.out.print()' print out sentences
## Comments
A comment is used as a user annotation wit the purpose of being human redable. 

**Line comments** follow double backslashes.`//`

**Block Comments** are contained within `/* Comments*/` It turns all the code to a comment. It works as long as it is in between the block comment.

## Identifiers

In Java use the term **Identifier** to describe a variable, parameter,constant,user-defined method or user-defined class.

-cannot begin with digit
-can only contain letters,digits,or underscore
-Case-sensitive `age != Age`



*Note: *
- Class name start with capital letters
- reserved words are entierly lowercase and may not be used as identifiers.(Reserved words will show up blue)

## Types
**Primitive** or **Built-in** types in java are
- `int` an integer (int age=13;)
- `Boolean` True or False (Boolean shirtColor = false;)
- `Double` floating point number ( double number = 2.37;)
- `char` (char letter = 'c';)

*Note: * Integers have a fixed amount of memory, so there is a limit to how many digits you can store (2^31 -1)

## Variables
Variables are a type of identifier that stores a value of a specific type

we can create variables using **declaration**
- `int age;`
- `double x, y`
- `Boolean found;`
- `char letter;`

We can also int initialize a variable in its **declaration**

- `int count = 1;`
- `x = 3.14;`
- `char c = '8';`

## Notes

Decalairation a variable menas to exist 

Ex-`int number`

Initializing

Ex-`int number = 10;`

Not Ex-`int number = ten;`

Not Ex-`int number = 10.1;`double

## End Notes

## Chars
[ASCII CHART]
(https://docs.google.com/document/d/1oubLTqAHmdkadtjbR8xxREG7auvuUqiQ/edit)

Each character is assosiated with an ASCII value.


## Type cast

One type can be a cast to another compatible type if appropriate

- `char letter = 'c';`
```


int total, n;
double average;
average = (double)total/n //total cast to double to ensure real division is used
```
*Note: * Casting a floating-point number to an integer simpily truncates  the number (rounds down)



