The Dalton School, Computer Science, Data Structures and Algorithms

# Problem Set 3
This problem set covers dynamic arrays.

## Prep
Do the following in your DataStructuresAlgorithms project.

In src folder create a new Java class called ArrayList.

In test folder create a new Java class called ArrayListTest and import the necessary JUnit libraries.

## Part 1: Implement ArrayList
In ArrayList, design an object that behaves like an ArrayList. You can make it an array of ints. (Advanced: make it generic enough hold any Object - String, Integer, Double, etc.)

Make all your attributes *private*. There should be an array of ints, the last active index, 

1. append - adds a new element to the ArrayList.
2. get - returns the element at the given index.
3. insert - inserts an element at the given index.
4. remove - removes the element at the given index.
5. size - returns an int that is the size of the ArrayList

## Part 2: Implement test cases
Do the following in ProblemSet3Test.java.

For each of the behaviors you implemented in ArrayList, write several test cases in ArrayListTest.

## Part 3: Written Analysis
Using the table you created, answer the following questions:

1. Which sort worked best on data in constant or increasing order (i.e. already sorted data)? Did the same sort do well on the case of mostly unsorted data?
2. In general, did the ordering of the incoming data affect the performance of the sorting algorithms? Use the data from your table to support your answer.
3. Which sort did best on the shorter (ie n=1000) data sets? Did the same one do better on the longer (ie n=10,000) data sets?
In general, did the sort from Part 1a or Part 1b do better? Give a hypothesis as to why the difference in performance exists.

## Submission Packet
Double-check that you submitted the entire packet:

1. ArrayList.java
2. ArrayListTest.java
3. Written analysis. (Save as a .pdf and attach. Do not share a Google Doc).