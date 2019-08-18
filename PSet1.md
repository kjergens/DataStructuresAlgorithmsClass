# Problem Set 1
Data Structures and Algorithms 
Computer Science
The Dalton School

This problem set covers review of linear and binary searching. See the class webpage for references for elementary searching algorithms.

## Prep
In the src folder, create a new Java class called "Search". In the test folder, create a class called "SearchTest" 
and import all the necessary JUnit library:
`
import org.junit.Before;
import org.junit.BeforeClass;
import org.junit.Ignore;
import org.junit.Test;
import static org.hamcrest.core.Is.is;
import static org.junit.Assert.*;
`

## Implement Binary Search (15 points)
In lecture, we reviewed two searching algorithms: linear search and binary search. Modify the existing code for linear sort (available from Blackboard) to also include binary search. The pseudocode for binary search is available from:

http://en.wikipedia.org/wiki/Binary_search_algorithm

You may implement either the recursive or iterative version of binary sort.

## Test Cases (20 points)
For both search algorithms, time how long each algorithm takes to find the following number from a sorted list of 500 Million numbers:

5
500
5,000
1,000,000 (1 Million)
10,000,000 (10 Million)
50,000,000 (50 Million)
100,000,000 (100 Million)
500,000,000 (500 Million)
Run each test 10 times and make a table with the running time for each run, as well as the average and the standard deviation for each algorithm. Submit your table via Blackboard.

## Analysis (15 points)
Using the table you created, answer the following questions (in complete sentences):

### Was linear search ever faster than binary search? When?
### If both searches report the time as 0 milliseconds for an instance, do they take the same amount of time? Why or why not?
### Which was the faster search overall?

## Submit
You will submit both printed and online materials. Double-check that you submitted the entire packet:
#. Print Search.java. Make the title of the page your name.
#. Print SearchTest.java. Make the title of the page your name.
#. Print your table of running times for each search.
#. Print your analysis that answers the qustions.
#. Make a .zip of your DataStructuresAndAlgorithms project and submit via the Classes system.
