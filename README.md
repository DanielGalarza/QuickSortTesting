# QuickSortTesting
CS 4050, MSU Denver, Algorithms Course, Dr. Gordon, Program #1 Timing Quicksort.

Problem Description

Quicksort is fast BUT there are many variations. Your job is to determine which variations make Quicksort run the fastest.

For example:

Median of 3: Does using median-of-3 to determine the pivot make Quicksort run faster or slower on average?
Stopping before the bitter end: Does running Quicksort only on large regions and then using Insertion Sort run faster than using Quicksort by itself? If so, what is the optimal definition for a large region (try starting with a size of 11)?
Partitioning: The book shows partitioning algorithms (on pages 159 and 178 in my book, look for partitioning, of array, in the index). Which one gives the best results? How much better?
The Assignment

Write a program in Swift, C++ or Java to answer the above questions. To find the running time of your program, you can use mach_absolute_time() in Swift, the C++ clock() function which returns the time in microseconds or the Java System.nanoTime() method which returns the current time in nanoseconds. Sample use of these functions can be found in: Timer.swift, timer.c and Timer.java. Make sure your program sorts long enough to detect differences if they exist.

Write a paper describing what you did and the conclusions you reached. The paper should be written as if many others are going to read it. Describe the experiments, what variations you tried, and the results you obtained.
