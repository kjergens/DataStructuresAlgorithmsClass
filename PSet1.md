The Dalton School, Computer Science,Data Structures and Algorithms

# Problem Set 1

This problem set covers review of linear and binary searching. See the class webpage for references for elementary searching algorithms.

## Prep
In the src folder, create a new Java class called `Search`. In the test folder, create a class called `SearchTest` 
and import all the necessary JUnit libraries:
```
import org.junit.Before;
import org.junit.BeforeClass;
import org.junit.Ignore;
import org.junit.Test;
import static org.hamcrest.core.Is.is;
import static org.junit.Assert.*;
```

## Implement Binary Search (15 points)
In lecture, we reviewed two searching algorithms: linear search and binary search. In `Search` write a method for `linearSearch` that takes in an integer array and a value to fine and returns the index of the number or -1 if it doesn't exist using linear search. Do the same for `binarySearch`. The pseudocode for binary search is available from:

http://en.wikipedia.org/wiki/Binary_search_algorithm

You may implement either the recursive or iterative version of binary sort.

## Test Cases (20 points)
For both search algorithms, in `SearchTest` write test cases to make sure they work for a number that does exist and also for a number that does not exist in the array. When those test cases pass, write test cases to time how long each algorithm takes to find the following number from a sorted list of 500 Million numbers:

```
5
500
5,000
1,000,000 (1 Million)
10,000,000 (10 Million)
50,000,000 (50 Million)
100,000,000 (100 Million)
500,000,000 (500 Million)
```

Run each test 10 times and make a table with the running time for each run, as well as the average and the standard deviation for each algorithm. Submit your table via Blackboard.

## Analysis (15 points)
Using the table you created, answer the following questions (in complete sentences):

1. Was linear search ever faster than binary search? When?
2. If both searches report the time as 0 milliseconds for an instance, do they take the same amount of time? Why or why not?
3. Which was the faster search overall?

## Submit
You will submit both printed and online materials. Double-check that you submitted the entire packet:
1. Print Search.java. Make the title of the page your name.
2. Print SearchTest.java. Make the title of the page your name.
3. Print your table of running times for each search.
4. Print your analysis that answers the qustions.
5. Make a .zip of your DataStructuresAndAlgorithms project and submit via the Classes system.
