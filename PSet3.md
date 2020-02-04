Problem Set 3
​​This problem set covers dynamic arrays.
​​Prep
​​Do the following in your DataStructuresAlgorithms project.
​​In src folder create a new Java class called ArrayList.
​​In test folder create a new Java class called ArrayListTest and import the necessary JUnit libraries.

# ​​Part 1: ArrayList
1. ​​In ArrayList.java, design an object that behaves like an ArrayList. Make it an array of ints. 
2. ​​Add private attributes. There should at least be:
​​an array
​​the last active index
​​the chunk size
2. ​​Add a constructor. 
3. ​​Add these public behaviors:
​​add - adds a new element to the ArrayList. 
​​get - returns the element at the given index.
​​getCapacity - returns how many spaces are available in the array.
​​insert - inserts an element at the given index.
​​remove - removes the element at the given index.
​​set - sets the element at the given index to the given value.
​​size - returns an int that is the size of the ArrayList

# ​​Part 2: Test cases
​​Do the following in ArrayListTest.java.
​​
​​For each of the behaviors you implemented in ArrayList, write several test cases in ArrayListTest. For this Problem Set, it is up to you to design the test cases. Think about what you should include to make sure that your ArrayList works under all circumstances. 
​​
​​At the very least, include the following test methods:
​​add
​​get
​​getCapacity
​​insertBeginning
​​insertMiddle
​​insertEnd
​​removeBeginning
​​removeMiddle
​​removeEnd
​​set
​​size

# ​​Part 3: Improvements
1. ​​Make your ArrayList it generic enough hold any Object - String, Integer, Double, etc. Write at least one test case to check it works.
2. ​​Think of a useful behavior that does not come with Java’s ArrayList and implement it.

# ​​Submission Packet
​​Double-check that you submitted the entire packet:
​​ArrayList.java
​​ArrayListTest.java
​​Remember to ATTACH the .java files. Do NOT copy and paste the contents. Be careful not to submit .class files.
​​
# Problem Set 3
This problem set covers dynamic arrays.

## Prep
Do the following in your DataStructuresAlgorithms project.

In src folder create a new Java class called ArrayList.

In test folder create a new Java class called ArrayListTest and import the necessary JUnit libraries.

## Part 1: Implement ArrayList
In ArrayList, design an object that behaves like an ArrayList. You can make it an array of ints. (Advanced: make it generic enough hold any Object - String, Integer, Double, etc.)
F
1. Add attributes. Make all your attributes **private**. There should be:
   - an array
   - the last active index
   - the chunk size
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
