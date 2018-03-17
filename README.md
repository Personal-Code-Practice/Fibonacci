# Fibonacci

## The Fibonacci Sequence

The Fibonacci sequence describes a sequence of numbers in which each number in the list is the sum of the previous two (with the exception of the first two numbers in the list, 0 and 1). 

The first six numbers in the Fibonacci sequence are: 0, 1, 1, 2, 3, 5.

The algorithm — or set of instructions — to produce the Fibonacci numbers is as follows:

1. Define an integer value, n. n determines the length of the list of Fibonacci numbers output by the algorithm.
2. Set the first two items in the resulting list to 0 and 1 respectively.
3. For a remaining n - 2 times (n - 2 because the first two slots in the Fibonacci sequence are taken by 0 and 1. We're assuming n > 2), compute the next item in the list by adding the previous two.
4. When the list's length is equal to n, we're done.

## Challenge

Suppose we want to create a simple interface that visually displays the Fibonacci sequence to users. The user should be able to tell us how long of a list of Fibonacci numbers to display. After they input their answer, the interface should compute and display a sequence of the correct length.

## The User Experience

* getting the number of results to compute from the user
* computing an n-length list of Fibonacci numbers
* displaying that list of numbers

