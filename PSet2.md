The Dalton School, Computer Science, Data Structures and Algorithms

# Problem Set 2

This problem set covers review of sorting. 

## Prep
Do the following in your `DataStructuresAlgorithms` project.

In `src` folder create a new Java class called `ProblemSet2`. 

In `test` folder create a new Java class called `ProblemSet2Test` and import the necessary JUnit libraries. 

## Part 1: Implement two sorting algorithms 
Do the following in `ProblemSet2.java`. 

### Part 1a
Choose one sort from the following to implement. (Note: For this assignment you can assume you are sorting an array of integers.)

* bubble sort
* radix sort
* shell sort

### Part 1b
Look up the sorting algorithm that the Java library Arrays.sort() uses and implement your own version. (Implement the traditional algorithm, not the dual-pivot version developed by Yaroslavskiy, Bentley, and Bloch.)


## Part 2: Implement test cases
Do the following in `ProblemSet2Test.java`.

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

Run each test 5 times, and record in a table the time for every run. Record the average as well as the standard deviation for each algorithm/list combination. For example, get the average time for shell sort to sort 1000 identical numbers, then get a separate average for shell sort to sort 1000 numbers in increasing order, etc. 

## Part 3: Written Analysis 
Using the table you created, answer the following questions:

1. Which sort worked best on data in constant or increasing order (i.e. already sorted data)? Did the same sort do well on the case of mostly unsorted data?
2. In general, did the ordering of the incoming data affect the performance of the sorting algorithms? Use the data from your table to support your answer.
3. Which sort did best on the shorter (ie n=1000) data sets? Did the same one do better on the longer (ie n=10,000) data sets?
4. In general, did the sort from Part 1a or Part 1b do better? Give a hypothesis as to why the difference in performance exists.

## Submission Packet
Double-check that you submitted the entire packet:
1. ProblemSet2.java
2. ProblemSet2Test.java
3. A table of running times. (Save as a .pdf and attach. Do not share a Google Doc).
4. Print your analysis answers. (Save as a .pdf and attach. Do not share a Google Doc).
