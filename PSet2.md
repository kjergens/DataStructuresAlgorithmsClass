The Dalton School, Computer Science, Data Structures and Algorithms

# Problem Set 2

This problem set covers review of sorting. 

## Prep
In `src` folder create a new Java class called `ProblemSet2`. 

In `test` folder create a new Java class called `ProblemSet2Test` and import the necessary JUnit libraries. 

## Implement two  sorting algorithms 
Do the following in Sort.java. 

### Part 1
Choose one sort from the following to implement. (Note: For this assignment you can assume you are sorting an array of integers.)

* bubble sort
* radix sort
* shell sort

### Part 2
Look up the sorting algorithm that the Java library Arrays.sort() uses and implement your own version. (Implement the traditional algorithm, not the dual-pivot version developed by Yaroslavskiy, Bentley, and Bloch.)


## Part3: Implement test cases
Do the following in SortTest.java.

For each of the sorting algorithms you implemented in `ProblemSet2`, write several test cases in `ProblemSet2Test` to calculate how long each algorithm takes to sort the following lists:
```
a list of 1000 identical numbers
a list of 1000 numbers that increase, peak, then decrease, e.g. 1 2 3 ... 498 499 500 500 499 498 ... 3 2 1
a list of 1000 numbers in increasing order
a list of 1000 numbers in decreasing order
a list of 990 numbers in increasing order, followed by 10 numbers in decreasing order
a list of 10,000 identical numbers 
a list of 10,000 numbers that increase, peak, then decrease
a list of 10,000 numbers in increasing order
a list of 10,000 numbers in decreasing order
a list of 9,900 numbers in increasing order, followed by 100 numbers in decreasing order
```

Run each test 10 times and make a table with your average as well as the standard deviation for each algorithm/list type, e.g. get the average of 10 runs of shell sort using a list of 1000 identical numbers, then get a separate average of 10 runs of shell sort using a list of 100 that peak, etc. 

## Written Analysis 
Using the table you created, answer the following questions:

1. Which sort worked best on data in constant or increasing order (ie already sorted data)? Did the same sort do well on the case of mostly sorted data?
2. In general, did the ordering of the incoming data affect the performance of the sorting algorithms? Using the data from your table, support your answer.
3. Which sort did best on the shorter (ie n=1000) data sets? Did the same one do better on the longer (ie n=5000) data sets?
4. In general, did the sorts from Part 1 or Part 2 do better? Give a hypothesis as to why the difference in performance exists.

## Submission Packet
Double-check that you submitted the entire packet:
1. ProblemSet2.java
2. ProblemSet2Test.java
3. A table of running times. (Save as a .pdf and attach. Do not share a Google Doc).
4. Print your analysis answers. (Save as a .pdf and attach. Do not share a Google Doc).
