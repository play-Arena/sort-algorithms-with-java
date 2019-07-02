# sort-algorithms-with-java

A code collection of popular sort algorithms coded using java

## Description:

This repository contains the java source codes that were written during my practice of implementing various sort algorithms
from scratch using Java.
This repo might be helpful for anyone who needs a quick refresher on popular sorting algorithms and their implementation during their
preparation for a technical interview or an examination.

## Steps To Compile & Run:

1. From the project's root directory, compile the Utility.java file.

          javac helperUtils/Utility.java

2. Then compile the required sort algorithm java code from the root of the project.

    For example to compile the bubble sort code:
    
          javac sortAlgorithms/BubbleSort.java

3. Run the compiled code using the `java` command.

   For example, to run the bubble sort code compiled from the above step:
   
          java sortAlgorithms/BubbleSort

## Contents:

### 1. Bubble Sort:

#### optimization done to the original algorithm:

The code maintains the last unsorted index which is updated on every outer loop iteration and the inner loop loops through till
the last unsorted index of the array, instead of iterating through the entire array during each loop of the bubbling process.

#### Worst case time complexity:

O(n^2)

#### Sort Type:

Stable Sort

--------------------------------------------------------------------------------------------

### 2. Selection Sort:

#### optimization done to the original algorithm:

Similar logical optimization as done in bubble sort code.

#### Worst case time complexity:

O(n^2)

#### Sort Type:

Unstable Sort

--------------------------------------------------------------------------------------------

### 3. Insertion Sort:

#### Worst case time complexity:

O(n^2)

#### Sort Type:

Stable Sort

--------------------------------------------------------------------------------------------
