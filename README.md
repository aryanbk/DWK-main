# DSA-with-Kunal
[![GitHub forks](https://img.shields.io/github/forks/asdsyd/DSA-with-Kunal.svg)](https://GitHub.com/asdsyd/DSA-with-Kunal/network/)
[![GitHub stars](https://img.shields.io/github/stars/asdsyd/DSA-with-Kunal.svg)](https://GitHub.com/asdsyd/DSA-with-Kunal/stargazers/)
[![GitHub watchers](https://img.shields.io/github/watchers/asdsyd/DSA-with-Kunal.svg)](https://GitHub.com/asdsyd/DSA-with-Kunal/watchers/)
[![GitHub contributors](https://img.shields.io/github/contributors/asdsyd/DSA-with-Kunal.svg)](https://GitHub.com/asdsyd/DSA-with-Kunal/graphs/contributors/)

Learn Fundamentals of Datastructres and Algorithms in Java with Kunal.

## What is Java?
<img src="https://cdn.jsdelivr.net/npm/programming-languages-logos/src/java/java.png" height="70" align="left">

[Java](https://www.java.com/) is a popular programming language first released by Sun Microsystems in 1995. It is a general-purpose programming language intended to let programmers write once, run anywhere (WORA), meaning that compiled Java code can run on all platforms that support Java without the need to recompile. It is owned by Oracle.

# Let's get started 

We have 8 primitive data types in Java:
1. `byte`
2. `short`
3. `int`
4. `long`
5. `float`
6. `double`
7. `boolean`
8. `char`

Non-primitive data types include
1. `String`
2. `Arrays`
3. `Classes`

## Arrays
Now let's look at Arrays!

Array in java is a group of like-typed variables referred to by a common name.

### Creating and Initializing an Array :
1. Using **new** operator
```java
datatype[] nameOfArray = new datatype[sizeOfArray];
```

<p align="center">OR</p>

```java
datatype nameOfArray[] = new datatype[ sizeOfArray];
```

**Example:**
```java
int[] myArray = new int[10];
```

2. Shortcut syntax
```java
datatype[] nameOfArray = {elt1, elt2, ... };
```

<p align="center">OR</p>

```java
datatype nameOfArray[] = {elt1, elt2, ... };
```

**Example:**
```java
int[] myArray = {10,20,30,40};
```
💡 Note: *Here the length of the array is determined by the number of values provided between braces and separated by commas.*

### Accessing an Array
1. Using **for** loop
```java
for (int i=0; i < nameOfArray.length; i++)
    System.out.println(nameOfArray[i]);
```
2. Using **for-each** loop
```java
for (datatype variable : Array)
    System.out.println(nameOfArray[i]);
```
**Example:**
```java
for(int i : arr)
    System.out.println(arr[i]);
```

3. Using **Arrays.toString()** method
```java
System.out.println(Arrays.toString(nameOfArray));
```

<br>

---
<br>


# Complete Java + DSA Bootcamp Syllabus

## NOTE
- All topics will contain problems from LeetCode Easy to Hard, explained in an easy-to-understand manner.
- Complete custom implementation of all Data Structures and Algorithms.
  
## Lectures
- [ ] [Complete Git & GitHub Course](https://youtu.be/apGV9Kg7ics)
- [ ] [Introduction to Programming](https://youtu.be/wn49bJOYAZM)
    - [ ] [Types of languages](https://youtu.be/wn49bJOYAZM?t=171)
    - [ ] [Memory management](https://youtu.be/wn49bJOYAZM?t=1488)
- [ ] [Flow of the program](https://youtu.be/lhELGQAV4gg)
    - [ ] [Flowcharts](https://youtu.be/lhELGQAV4gg)
    - [ ] [Pseudocode](https://youtu.be/lhELGQAV4gg?t=715)
- [ ] [Introduction to Java](https://youtu.be/4EP8YzcN0hQ)
    - [ ] [Introduction](https://youtu.be/4EP8YzcN0hQ)
    - [ ] [How it works](https://youtu.be/4EP8YzcN0hQ?t=93)
    - [ ] [Setup Installation](https://youtu.be/4EP8YzcN0hQ?t=1486)
    - [ ] [Input and Output in Java](https://youtu.be/TAtrPoaJ7gc)
    - [ ] [Conditionals & Loops in Java](https://youtu.be/ldYLYRNaucM?t=88)
        - [ ] [if-else](https://youtu.be/ldYLYRNaucM?t=88)
        - [ ] [loops](https://youtu.be/ldYLYRNaucM?t=440)
        - [ ] [Switch statements](https://youtu.be/mA23x39DjbI)
    - [ ] [Data-types](https://youtu.be/TAtrPoaJ7gc?t=2800)
    - [ ] [Coding best practices](https://youtu.be/waGfV-IoOt8)
- [ ] [Functions](https://youtu.be/vvanI8NRlSI)
    - [ ] [Introduction](https://youtu.be/vvanI8NRlSI)
    - [ ] [Scoping in Java](https://youtu.be/vvanI8NRlSI?t=2801)
    - [ ] [Shadowing](https://youtu.be/vvanI8NRlSI?t=3584)
    - [ ] [Variable Length Arguments](https://youtu.be/vvanI8NRlSI?t=4013)
    - [ ] [Overloading](https://youtu.be/vvanI8NRlSI?t=4327)
- [ ] [Arrays](https://youtu.be/n60Dn0UsbEk)
    - [ ] [Introduction](https://youtu.be/n60Dn0UsbEk)
    - [ ] [Memory management](https://youtu.be/n60Dn0UsbEk?t=632)
    - [ ] [Input and Output](https://youtu.be/n60Dn0UsbEk?t=1675)
    - [ ] [ArrayList Introduction](https://youtu.be/n60Dn0UsbEk?t=4868)
    - [ ] Searching
        - [ ] [Linear Search](https://youtu.be/_HRA37X8N_Q)
        - [ ] [Binary Search](https://youtu.be/f6UU7V3szVw)
        - [ ] [Modified Binary Search](https://youtu.be/f6UU7V3szVw?t=2508)
        - [ ] [Binary Search on 2D Arrays](https://www.youtube.com/watch?v=enI_KyGLYPo)
    - [ ] Sorting
        - [ ] [Insertion Sort](https://youtu.be/By_5-RRqVeE)
        - [ ] [Selection Sort](https://youtu.be/Nd4SCCIHFWk)
        - [ ] [Bubble Sort](https://youtu.be/F5MZyqRp_IM)
        - [ ] [Cyclic Sort](https://youtu.be/JfinxytTYFQ)
- [ ] [Pattern questions](https://youtu.be/lsOOs5J8ycw)
- [ ] [Strings](https://www.youtube.com/watch?v=zL1DPZ0Ovlo)
    - [ ] [Introduction](https://www.youtube.com/watch?v=zL1DPZ0Ovlo)
    - [ ] [How Strings work](https://youtu.be/zL1DPZ0Ovlo?t=216)
    - [ ] [Comparison of methods](https://youtu.be/zL1DPZ0Ovlo?t=977)
    - [ ] [Operations in Strings](https://youtu.be/zL1DPZ0Ovlo?t=1681)
    - [ ] [StringBuilder in java](https://youtu.be/zL1DPZ0Ovlo?t=4199)
- [ ] [Maths for DSA](https://youtu.be/fzip9Aml6og)
    - [ ] [Introduction](https://youtu.be/fzip9Aml6og?t=20)
    - [ ] [Complete Bitwise Operators](https://youtu.be/fzip9Aml6og?t=95)
    - [ ] [Range of numbers](https://youtu.be/fzip9Aml6og?t=4169)
    - [ ] [Prime numbers](https://youtu.be/lmSpZ0bjCyQ?t=57)
    - [ ] [Sieve of Eratosthenes](https://youtu.be/lmSpZ0bjCyQ?t=850)
    - [ ] [Newton's Square Root Method](https://youtu.be/lmSpZ0bjCyQ?t=1989)
    - [ ] [Factors](https://youtu.be/lmSpZ0bjCyQ?t=3004)
    - [ ] [Modulo properties](https://youtu.be/lmSpZ0bjCyQ?t=3980)
    - [ ] [Number Theory](https://youtu.be/lmSpZ0bjCyQ?t=4405)
    - [ ] [HCF / LCM](https://youtu.be/lmSpZ0bjCyQ?t=5110)
    - [ ] [Euclidean algorithm](https://youtu.be/lmSpZ0bjCyQ?t=5520)
- [ ] [Recursion](https://www.youtube.com/playlist?list=PL9gnSGHSqcnp39cTyB1dTZ2pJ04Xmdrod)
    - [ ] [Introduction](https://youtu.be/M2uO2nMT0Bk)
    - [ ] [Flow of recursive programs - stacks](https://youtu.be/M2uO2nMT0Bk?t=2124)
    - [ ] [Why recursion?](https://youtu.be/M2uO2nMT0Bk?t=2708)
    - [ ] [Tree building of function calls](https://youtu.be/M2uO2nMT0Bk?t=3033)
    - [ ] [Tail recursion](https://youtu.be/M2uO2nMT0Bk?t=4308)
    - [ ] [Sorting](https://www.youtube.com/playlist?list=PL9gnSGHSqcnq-9CXLt9DsInytRMLoyZQ_)
        - [ ] [Merge Sort](https://youtu.be/iKGAgWdgoRk)
        - [ ] [Quick Sort](https://www.youtube.com/watch?v=Z8svOqamag8&list=PL9gnSGHSqcnr_DxHsP7AW9ftq0AtAyYqJ&index=27)
    - [ ] [Backtracking](https://youtu.be/zg5v2rlV1tM)
        - [ ] [N-Queens](https://youtu.be/nC1rbW2YSz0)
        - [ ] [N-Knights](https://youtu.be/nC1rbW2YSz0?t=2342)
        - [ ] [Sudoku Solver](https://youtu.be/nC1rbW2YSz0?t=3190)
        - [ ] [Maze problems](https://www.youtube.com/watch?v=zg5v2rlV1tM)
    - [ ] [Recursion String Problems](https://youtu.be/gdifkIwCJyg)
    - [ ] [Recursion Google, Amazon Questions](https://youtu.be/9ByWqPzfXDU)
    - [ ] [Recursion Array Problems](https://youtu.be/sTdiMLom00U)
    - [ ] [Recursion Pattern Problems](https://youtu.be/ymgnIIclCF0)
    - [ ] [Subset Questions](https://youtu.be/9ByWqPzfXDU)
- [ ] [Space and Time Complexity Analysis](https://youtu.be/mV3wrLBbuuE)
    - [ ] [Introduction](https://youtu.be/mV3wrLBbuuE)
    - [ ] [Comparisons of various cases](https://youtu.be/mV3wrLBbuuE?t=1039)
    - [ ] [Solving Linear Recurrence Relations](https://youtu.be/mV3wrLBbuuE?t=6252)
    - [ ] [Solving Divide and Conquer Recurrence Relations](https://youtu.be/mV3wrLBbuuE?t=4609)
    - [ ] [Big-O, Big-Omega, Big-Theta Notations](https://youtu.be/mV3wrLBbuuE?t=2271)
    - [ ] [Little Notations](https://youtu.be/mV3wrLBbuuE?t=2960)
    - [ ] [Get equation of any relation easily -best and easiest approach](https://youtu.be/mV3wrLBbuuE?t=8189)
    - [ ] [Complexity discussion of all the problems we do](https://youtu.be/mV3wrLBbuuE?t=3866)
    - [ ] [Space Complexity](https://youtu.be/mV3wrLBbuuE?t=3330)
    - [ ] [NP-Completeness Introduction](https://youtu.be/mV3wrLBbuuE?t=8695)
- [ ] [Object Oriented Programming](https://www.youtube.com/playlist?list=PL9gnSGHSqcno1G3XjUbwzXHL8_EttOuKk)
    - [ ] [Introduction](https://www.youtube.com/watch?v=BSVKUk58K6U)
    - [ ] [Classes & its instances](https://youtu.be/BSVKUk58K6U?t=467)
    - [ ] [this keyword in Java](https://youtu.be/BSVKUk58K6U?t=3380)
    - [ ] [Properties](https://www.youtube.com/watch?v=46T2wD3IuhM)
        - [ ] [Inheritance](https://youtu.be/46T2wD3IuhM?t=146)
        - [ ] [Abstraction](https://youtu.be/46T2wD3IuhM?t=7102)
        - [ ] [Polymorphism](https://youtu.be/46T2wD3IuhM?t=4226)
        - [ ] [Encapsulation](https://youtu.be/46T2wD3IuhM?t=7022)
    - [ ] [Overloading & Overriding](https://youtu.be/46T2wD3IuhM?t=4834)
    - [ ] [Static & Non-Static](https://youtu.be/_Ya6CN13t8k?t=1137)
    - [ ] [Packages](https://youtu.be/_Ya6CN13t8k?t=182)
    - [ ] [Access Control](https://youtu.be/W145DXs8fFg)
    - [ ] [Interfaces](https://youtu.be/rgHZa7-Dibg?t=1510)
    - [ ] [Abstract Classes](https://youtu.be/rgHZa7-Dibg?t=68)
    - [ ] [Annotations](https://youtu.be/rgHZa7-Dibg?t=3438)
    - [ ] [Singleton Class](https://youtu.be/_Ya6CN13t8k?t=4240) 
    - [ ] [final, finalize, finally](https://youtu.be/46T2wD3IuhM?t=6317)
    - [ ] [Object Cloning](https://youtu.be/OY2lPr8h93U?t=4352)
    - [ ] [Object Class](https://youtu.be/W145DXs8fFg?t=1943)
    - [ ] [Generics](https://www.youtube.com/watch?v=OY2lPr8h93U)
    - [ ] [Exception Handling](https://youtu.be/OY2lPr8h93U?t=3405)
    - [ ] [Collections Framework](https://youtu.be/9ogGan-R1pc?t=49)
    - [ ] [Vector Class](https://youtu.be/9ogGan-R1pc?t=668)
    - [ ] [Lambda Expression](https://youtu.be/OY2lPr8h93U?t=2894) 
    - [ ] [Enums](https://youtu.be/9ogGan-R1pc?t=909)
- [ ] Linked List
    - [ ] [Introduction](https://youtu.be/58YbpRDc4yw)
    - [ ] [Singly + Doubly + Circular LinkedList](https://youtu.be/58YbpRDc4yw)
    - [ ] [Fast and slow pointer](https://youtu.be/70tx7KcMROc)
    - [ ] [Cycle Detection](https://youtu.be/70tx7KcMROc)
    - [ ] [Reversal of LinkedList](https://youtu.be/70tx7KcMROc)
    - [ ] [Linked List + Recursion](https://youtu.be/70tx7KcMROc)
- [ ] Stacks & Queues
    - [ ] Introduction
    - [ ] Interview problems
    - [ ] Push efficient
    - [ ] Pop efficient
    - [ ] Queue using Stack and Vice versa
    - [ ] Circular Queue
- [ ] Trees
    - [ ] Introduction
    - [ ] Binary Trees
    - [ ] Binary Search Trees
    - [ ] DFS
    - [ ] BFS
    - [ ] AVL Trees
    - [ ] Segment Tree
- [ ] Heaps
    - [ ] Introduction
    - [ ] Theory
    - [ ] Priority Queue
    - [ ] Heapsort
    - [ ] Two Heaps Method
    - [ ] k- way merge
    - [ ] Top k elements
    - [ ] Interval problems
- [ ] HashMap
    - [ ] Introduction
    - [ ] Theory - how it works
    - [ ] Comparisons of various forms
    - [ ] Limitations and how to solve
    - [ ] Map using LinkedList
    - [ ] Map using Hash
    - [ ] Count Sort
    - [ ] Radix Sort
    - [ ] Chaining
    - [ ] Probing
    - [ ] Huffman- Encoder
    - [ ] Top K elements problems
- [ ] Subarray Questions: Sliding window, Two Pointer, Kadane's Algorithm
- [ ] Graphs
    - [ ] Introduction
    - [ ] BFS
    - [ ] DFS
    - [ ] Working with graph components
    - [ ] Minimum Spanning Trees
    - [ ] Kruskal Algorithm
    - [ ] Prims Algorithm
    - [ ] Dijkstra’s shortest path algorithm
    - [ ] Topological Sort
    - [ ] Bellman ford
    - [ ] A* pathfinding Algorithm
- [ ] Dynamic Programming
    - [ ] Introduction
    - [ ] Recursion + Recursion DP + Iteration + Iteration Space Optimized
    - [ ] Complexity Analysis
    - [ ] 0/1 Knapsack
    - [ ] Subset Questions
    - [ ] Unbounded Knapsack
    - [ ] Subsequence questions
    - [ ] String DP
- [ ] Greedy Algorithms
- [ ] Tries

### Advanced concepts apart from interviews 
- [ ] Fast IO
- [ ] File handling
- [ ] Bitwise + DP
- [ ] Extended Euclidean algorithm
- [ ] Modulo Multiplicative Inverse
- [ ] Linear Diophantine Equations
- [ ] Matrix Exponentiation
- [ ] Mathematical Expectation
- [ ] Catalan Numbers
- [ ] Fermat’s Theorem
- [ ] Wilson's Theorem
- [ ] Euler's Theorem
- [ ] Lucas Theorem
- [ ] Chinese Remainder Theorem
- [ ] Euler Totient
- [ ] NP - Completeness
- [ ] Multithreading
- [ ] Fenwick Tree / Binary Indexed Tree
- [ ] Square Root Decomposition
