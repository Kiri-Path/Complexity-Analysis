# Time complexity


## O(1) - Constant Time

#### Description: 
The operation takes a fixed amount of time regardless of the size of the input.

#### Examples: 
Accessing an array element by index, basic arithmetic operations, and simple assignments.

#### Implications -Good: 
This is the best possible time complexity, as the operation is extremely efficient and scales perfectly with input size.

#### Practical Understanding: 
No matter how large the dataset, the time required for the operation remains constant.


## O(log n) - Logarithmic Time

#### Description: 
The time complexity grows logarithmically with the input size. Common in algorithms that halve the input size at each step.

#### Examples: 
Binary search, balanced tree operations (e.g., AVL trees, Red-Black trees), and certain divide-and-conquer algorithms.

#### Implications - Good: 
Very efficient, especially for large datasets. Each additional element adds a smaller amount of extra time.

#### Practical Understanding: 
Doubling the input size increases the operation count by a constant, small amount.


## O(n) - Linear Time

#### Description: 
The time complexity grows linearly with the input size. Each element of the input is processed once.

#### Examples: 
Iterating through an array, finding the maximum element in a list, basic list operations.

#### Implications -Good: 
Reasonably efficient. The performance scales linearly with the size of the input.

### Practical Understanding: 
If the input size doubles, the time required doubles as well.


## O(n log n) - Linearithmic Time

#### Description: 
The time complexity grows proportionally to n times the logarithm of n. Common in efficient sorting algorithms.

#### Examples: 
Merge sort, heapsort, and certain divide-and-conquer algorithms.

#### Implications - Good: 
Efficient for most practical purposes, especially for large datasets.

### Practical Understanding: 
Slightly more than linear but much better than quadratic for large datasets.


## O(n^2) - Quadratic Time

#### Description: 
The time complexity grows proportionally to the square of the input size. Typically seen in algorithms with nested loops.

#### Examples: 
Bubble sort, selection sort, insertion sort, and checking for duplicates in an array with a nested loop.

#### Implications -Bad: 
Becomes inefficient for larger datasets as the time required grows quickly.

### Practical Understanding: 
If the input size doubles, the time required increases by a factor of four.


## O(n^3) - Cubic Time

#### Description: 
The time complexity grows proportionally to the cube of the input size. Common in algorithms with three nested loops.

#### Examples: 
Certain dynamic programming algorithms, matrix multiplication (naive method).

#### Implications -Bad: 
Very inefficient for larger datasets. Not practical for large inputs.

#### Practical Understanding: 
If the input size doubles, the time required increases by a factor of eight.


## O(2^n) - Exponential Time

#### Description: 
The time complexity doubles with each addition to the input size. Common in recursive algorithms that solve subproblems independently.

#### Examples: Recursive calculation of Fibonacci numbers, the power set generation, solving the traveling salesman problem using brute-force.

#### Implications - Very Bad: 
Becomes impractical very quickly as input size grows. Not suitable for large datasets.

### Practical Understanding: 
If the input size increases by one, the time required doubles.


## O(n!) - Factorial Time

#### Description: 
The time complexity grows factorially with the input size. Common in algorithms that generate all permutations.

#### Examples: 
Brute-force solutions to the traveling salesman problem, generating all permutations of a set.

#### Implications - Extremely Bad: 
Completely impractical for all but the smallest inputs.

#### Practical Understanding: 
If the input size increases by one, the time required multiplies by the current size of the input.


# Space Complexity

## O(1) - Constant Space

#### Description: 
Memory usage is constant, regardless of input size.

#### Implications - Good: 
Best possible space complexity, extremely efficient.

#### Practical Understanding: 
Memory usage remains constant regardless of dataset size.

## O(log n) - Logarithmic Space

#### Description: 
Memory usage grows logarithmically with input size.

#### Implications - Good: 
Efficient memory usage, particularly for algorithms that halve the problem size.

#### Practical Understanding: 
Memory usage increases very slowly as input size grows.


## O(n) - Linear Space

#### Description: 
Memory usage grows linearly with input size.

#### Implications - Moderate: 
Generally efficient but becomes significant with very large datasets.

#### Practical Understanding: 
Doubling the input size doubles the memory usage.


## O(n log n) - Linearithmic Space

#### Description: 
Memory usage grows proportionally to n times the logarithm of n.

#### Implications - Moderate: 
Efficient for many practical applications, though higher than linear space.

#### Practical Understanding: 
Slightly more than linear but still manageable for large datasets.


## O(n^2) - Quadratic Space

#### Description: 
Memory usage grows quadratically with input size.

#### Implications - Bad: 
Memory usage becomes impractical for large input sizes.

#### Practical Understanding: 
Doubling the input size quadruples the memory usage.


## O(2^n) - Exponential Space

#### Description: 
Memory usage doubles with each addition to the input size.

#### Implications - Very Bad: 
Becomes impractical very quickly as input size increases.

#### Practical Understanding: 
Increasing input size by one doubles the memory usage.


## O(n!) - Factorial Space

#### Description: Memory usage grows factorially with input size.

#### Implications - Extremely Bad: 
Memory usage grows extraordinarily fast, becoming impractical for most inputs.

#### Practical Understanding: 
Increasing input size by one multiplies memory usage by the new size.
