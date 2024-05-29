# dsaNotes | Colt Steele
Section 1: Introduction
=======================
1. Intro on course

Section 2: Big O Notation
=========================
1. Time complexity and space complexity. Depends on the type of situation. Using time as a measure for code complexity isn't exactly ideal, instead we can count the number of operations that has to be executed to perform the computation. a + b has 1 operation which is addition. Addition of n numbers set up as a loop can have mulitiple no: of operations(and depends on the input n). Regardless of the situation, no: of operations can be roughly be proportional to the n, n being the argument passed to computation fn.
2. Big O, talks about the worst case scenario(upper bound) of runtime complexity of an algorithm based on the input. It depends on the algorithm and not the hardware(hardware does matter but thats not the point). As the input changes, runtime could be proportional increment O(n), or double the runtime or simply constant(O(1)). For a loop that depends on the input n, it can have runtime of O(n). If nested loop, it is O(n*n) or O(n2). O(10n) or O(5n) can be simplified to O(n). Constants(O(n)) is not really imp. Math operations, variable assinging, selecting element from array by indexing or object key-value are all constanst. In loops, time complexity is the length of the loop, times the complexity of whateever inside the loop.
3. As for space complexity, for primitive data types (numbers, undefined, null, booleans) it is constant, for strings, it is O(n) based on the string length n. For reference types like array with length n of array or n no: of keys in an object, it is O(n).
4. Logarithm: It is the power or exponent that must be raised(3) to the base(2) to yeild a given number(8). 2 raised to 3 is 8. log of a number is the number of times you can divide the number by 2 until it is less than or equal to 1. log(8) would be 3. (8/2 is 4, then 4/2 is 2, then 2/2 is 1 which is 3 times.) Time complexity of logarithm(O(log n)) is great, just like constants.
