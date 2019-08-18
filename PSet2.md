The Dalton School, Computer Science, Data Structures and Algorithms

# Problem Set 2

This problem set covers review of sorting. 

## Prep
In `src` folder create a new Java class called `Sort`. 

In `test` folder create a new Java class called `SortTest` and import the necessary JUnit libraries. (See Problem Set 1 for a reminder.)

## Implement two  sorting algorithms 
In class, we discussed sorting algorithms. 

Choose one sort from the following to implement:

* insertion sort
* selection sort
* bubble sort


Look up the sorting algorithm that the Java library Arrays.sort() uses. Implement your own version. (You may implement the traditional algorithm, not the dual-pivot version)


## Test Cases
For each of the sorting algorithms, calculate how long each algorithm takes to sort the following lists:
`
a list of 1000 identical numbers
a list of 1000 numbers in random order
a list of 1000 numbers in increasing order
a list of 1000 numbers in decreasing order
a list of 990 numbers in increasing order, followed by 10 numbers in random order
a list of 5000 identical numbers
a list of 5000 numbers in random order
a list of 5000 numbers in increasing order
a list of 5000 numbers in decreasing order
a list of 4990 numbers in increasing order, followed by 10 numbers in random order
`

Run each test 10 times and make a table with your average as well as the standard deviation for each algorithm. 

## Analysis 
Using the table you created, answer the following questions:

1. Which sort worked best on data in constant or increasing order (ie already sorted data)? Did the same sort do well on the case of mostly sorted data?
2. In general, did the ordering of the incoming data affect the performance of the sorting algorithms? Using the data from your table, support your answer.
3. Which sort did best on the shorter (ie n=1000) data sets? Did the same one do better on the longer (ie n=5000) data sets?
4. In general, did the sorts from the first or second list do better? Give a hypothesis as to why the difference in performance exists.

## Submission Packey
