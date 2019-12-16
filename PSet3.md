The Dalton School, Computer Science, Data Structures and Algorithms

# Problem Set 3
This problem set covers dynamic arrays.

## Prep
Do the following in your DataStructuresAlgorithms project.

In src folder create a new Java class called ArrayList.

In test folder create a new Java class called ArrayListTest and import the necessary JUnit libraries.

## Part 1: Implement ArrayList
In ArrayList, design an object that behaves like an ArrayList. You can make it an array of ints. (Advanced: make it generic enough hold any Object - String, Integer, Double, etc.)

1. Add attributes. Make all your attributes **private**. There should be:
  * an array
  * the last active index
  * the chunk size

2. Add a constructor.

3. Add these public behaviors:
- **append** - adds a new element to the ArrayList. (Hint: if the array is full make a new array that adds another "chunk" of space.)
- **get** - returns the element at the given index.
- **getCapacity** - returns how many spaces are available in the array attribute.
- **insert** - inserts an element at the given index. (Same note as for append.)
- **remove** - removes the element at the given index.
- **set** - sets the element at the given index to the given value.
- **size** - returns an int that is the size of the ArrayList

## Part 2: Implement test cases
Do the following in ArrayListTest.java.

For each of the behaviors you implemented in ArrayList, write several test cases in ArrayListTest. Include at least the following:
- append
- get
- getCapacity
- insertBeginning
- insertMiddle
- insertEnd
- removeBeginning
- removeMiddle
- removeEnd
- set
- size

## Submission Packet
Double-check that you submitted the entire packet:

1. ArrayList.java
2. ArrayListTest.java
