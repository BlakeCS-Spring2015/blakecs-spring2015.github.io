---
layout: page
title: "Conditionals"
date: 2015-01-18 21:43:06
author: carolyn
tags: python
---

# Conditionals Tutorial


There are a couple of different types of conditionals: if, elif, and else. Once a statement is true, the next line of code will be run. An elif and else statement is only run once the first if statement is false. It is important to use “and” and “or” properly. When using “and” both of the statements must be true for the whole statement to be true. But for “or” statements only one of the statements must be true for the statement to be true. This can eliminate redundancy in your code. 




syntax:
--if--
 AN IF STATMENT begins the conditional. the syntax for beginning an if statement is as follows
 if condition==true/false:
--elif--
 elif is a combination of the two words else if. so essentiallly it allows you to add additional conditions to your program which are dependednt on the first one having a certain outcome so if we have this program:
 if conditon==true:
 	print "yes"
 elif condition=/=false or condition =/=true:
 	print "what?"
 else:
 	print "no"
 the program will run the if, or else statements if it is either true or false, but if it is neither, which is convered by our elif statement (also it is not physically possible but just bear with me) it will skip the if function and go straight to the elif function to print "what?".
--else--
 else is essentially the end to your conditional. if none of the conditions match or are true, the program runs the else function.




Some important information which connects to conditoinals are the comparisons/conditions. This group of syntax covers the operators that can be used to compare one of three data types (string, int, and float) to an input of the same data type. The output is then a bool (True or False).

3 == 3   #True  (are these two values equal to each other?)
3 == 4   #False (are these two values equal to each other?)
3 != 4   #True  (are these two values not equal to each other?)
3 > 3.0  #True  (is the first value greater than the second value?)
3 >= 3.0 #True  (is the first value greater than or equal to the second value?)

Typically this type of syntax is used with conditionals in order to compare the users input to a stored value. This is shown in the following example:

x = raw_input("What day of the week is it? (M, T, W, R, or F) ") 
if x == "M" or x == "F":
  print "You have CS class but no assembly!"
elif x == "T" or x == "R": 
	print "You have CS class and assembly today!"   
elif x == "W": 
	print "You don't have CS class or assembly today!"
else: 
    print "Silly that's not an option"




Olivia:




