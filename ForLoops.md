---
layout: page
title: For Loops
permalink: /ForLoops/
---

###Loop a definite number of times

Loop over the items in a collection:

	for i in my_list:
		# Do something with each
		# item in the list (i)

    for i in range(0,5):
        i += 1
        print i

# Practice Assessment

Below is a practice assesment for for loops that we made during class last year.

## Reading:

What do you think the following piece of code does? (don’t run it)
        
        my_list = [9, 4, 6, 5, 2, 3, 4]
        for x in my_list:
            print x

What do you think the following piece of code does? (don’t run it)

    for i in "Hello world!":
      print i

What do you think the following piece of code does? (don’t run it)

    my_list = [1, 2, 3, 4, 5]

    for i in my_list:
        for j in my_list:
            for k in my_list:
                      print i, j, k
            

## Debugging

1.  The following program is attempting to identify which numbers in my_list are greater than or equal to 5.

    a. The following code has 3 errors. What are they?

    my_list = [1, 7, 10, 3, 27]

    for “x” in (my_list)
    if x >= 5:
            print “yes”
        else:
    print “no”

b. Rewrite the code in the previous question so that it runs correctly.

2. The following program is attempting to print the square of each value in my_list.

    a. What are the 2 bugs in the following piece of code?

    ```
    my_list = [2, 4, 5, 6, 28, 57]

    for i in my_list[i]:
        print i^2

    Error 1
    Error 2
    ```

b. Rewrite the code in the previous question so that it runs correctly.

YOUR CODE HERE

Writing

Write a few lines of code that do the following:

    Make a program that takes every number in a list, triples it, and prints the list.

YOUR CODE HERE

Create a program using a for loop that asks the user for an input, then checks to see if the user’s input is in the range 0 to 23. This can be done by iterating until the input is found, or until the entire list has been searched without finding the input. Finally, have the code  print whether or not the input has been found, its index, and then end the loop.

YOUR CODE HERE

Extensions

Write a program that does the following:

For each item in a predefined list, print all the numbers that number is divisible by. 

Example: If the list = [2, 4]: the printout should be:

2 is divisible by 1
2 is divisible by 2
4 is divisible by 1
4 is divisible by 2
4 is divisible by 4

YOUR CODE HERE
 
Write a program that solves the following problem:

Use nested for loops to print out all of the possible pairs of numbers in the lists below.

list_x = [0, 1, 2, 3, 4]
list_y = [5, 6, 7, 8, 9]

Output should be:
0 5
0 6
0 7
…

YOUR CODE HERE

