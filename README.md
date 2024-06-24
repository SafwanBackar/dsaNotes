# dsaNotes | Colt Steele
Section 1: Introduction
=======================
1. Intro on course

Section 2: Big O Notation
=========================
1. Time complexity and space complexity. Depends on the type of situation. Using time as a measure for code complexity isn't exactly ideal, instead we can count the number of operations that has to be executed to perform the computation. a + b has 1 operation which is addition. Addition of n numbers set up as a loop can have mulitiple no: of operations(and depends on the input n). Regardless of the situation, no: of operations can be roughly be proportional to the n, n being the argument passed to computation fn.
2. Big O, talks about the worst case scenario(upper bound) of runtime complexity of an algorithm based on the input. It depends on the algorithm and not the hardware(hardware does matter but thats not the point). As the input changes, runtime could be proportional increment O(n), or double the runtime or simply constant(O(1)). For a loop that depends on the input n, it can have runtime of O(n). If nested loop, it is O(n*n) or O(n2). O(10n) or O(5n) can be simplified to O(n). Constants(O(1 or any number)) is not really imp. Math operations, variable assinging, selecting element from array by indexing or object key-value are all constanst. In loops, time complexity is the length of the loop, times the complexity of whateever inside the loop.
3. As for space complexity, for primitive data types (numbers, undefined, null, booleans) it is constant, for strings, it is O(n) based on the string length n. For reference types like array with length n of array or n no: of keys in an object, it is O(n).
4. Logarithm: It is the power or exponent that must be raised(3) to the base(2) to yeild a given number(8). 2 raised to 3 is 8. log of a number is the number of times you can divide the number by 2 until it is less than or equal to 1. log(8) would be 3. (8/2 is 4, then 4/2 is 2, then 2/2 is 1 which is 3 times.) Time complexity of logarithm(O(log n)) is great, just like constants.

Section 3: Analyzing performance of arrays and obects (Not Imp)
=====================================================
1. In terms of BigO, if the data representation does not require order and need quick insertion and removal, objects are great choice. BigO object methods -> Obj.keys() - O(n), Obj.values() - O(n), Obj.entries() - O(n), Obj.hasOwnproperty - O(1)
2. As for arrays, they are for ordered lists. Adding/Removal of elements is constant in terms of BigO if at the end(push, pop) while for shift/unshift it would n times for bigO(O(n)) since index of all elements would be changed. searching elements is constant since all elements are indexed by their position.

Section 4: Problem Solving Approach.
====================================
1. Understand the problem, explore examples(use inputs of diff cases and print outputs), break it down, solve/simply, look back & refactor.

Section 5: Problem Solving Patterns.
====================================
1. Frequency counter problems, mulitpointer problems, sliding window pattern, divide and conquer.

Section 11: Bubble Sort.
=======================
1. In this sort, largest element is bubbled to the top by comparing element by element and swaps them from one side to other. Big O complexity is n2 but if the list is nearly sorted, it would be n and that is the best case use. But in general, a slow method.

Section 12: Selection Sort.
========================
1. Similar to bubble sort. Elements Iterates till end and swaps with the smallest value.

Section 13: Insertion Sort.
==========================
1. Starting from the 2nd element, it is inserted into the correct index where it should be and repeat until sorted. A reveresed array would be worse case for this method. Nearly sorted array would be fine.

Section 14: Comparing
=====================
1. All 3 are nearly identical but insertion and selection is slightly better in terms of time complexity compared to selection. Space complexity is same. Though they are slower, works faster in small data sets. Worst case of time complexity is n2 for all.

Section 15: Merge Sort
======================
 1. A divide-and-conquer algorithm that sorts an array by first breaking it down into smaller arrays of length 1, and then sorting the array back together the correct way so that it is sorted.
 2. Time complexity is n log n and space complexity of n

Section 16, 17: Quick Sort | Radix Sort
======================

