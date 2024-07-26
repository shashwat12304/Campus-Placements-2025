# Tredence Campus Placement
##  Round-1 DSA questions
## Question 1: Filter Binary Numbers 🚫💡

### Description
Given a set of binary numbers, filter out all numbers that contain the substring "11".

### Input Format
1. The first line contains the number of binary numbers to be evaluated.
2. The following lines contain one binary number each.

### Output Format
Print the filtered binary numbers as a single string, separated by spaces.

### Example
#### Input
```
2
1
3
```
#### Explanation
- Convert `1` and `3` to binary: `1` and `11`
- Remove numbers containing `11`

#### Output
```
1 100
```

---

## Question 2: Spiral Order Matrix Traversal 🔄📋

### Description
Given an `m x n` matrix, return all elements of the matrix in spiral order.

### Input Format
- A matrix represented as a list of lists.

### Output Format
- A list of integers representing the elements of the matrix in spiral order.

### Example
#### Input
```python
matrix = [
  [1, 2, 3],
  [4, 5, 6],
  [7, 8, 9]
]
```
#### Explanation
Traverse the matrix in a spiral order: right → down → left → up, until all elements are visited.

#### Output
```
[1, 2, 3, 6, 9, 8, 7, 4, 5]
```

---

## Question 3: Minimum Path in Grid 🌱🛤️

### Description
Given a grid where:
- `1` represents plants 🌱,
- `2` represents your starting position 🧍,
- `0` represents an empty path 🛤️,

Find the minimum path to reach the edge of the grid without stepping on any plants. It is guaranteed that there will be only one starting position (2) in the grid.

### Input Format
- A grid represented as a list of lists containing integers `0`, `1`, and `2`.

### Output Format
- The length of the minimum path to reach the edge of the grid.

### Example
#### Input
```python
grid = [
  [1, 0, 0, 1],
  [1, 0, 1, 1],
  [1, 2, 0, 0],
  [1, 1, 1, 1]
]
```
#### Explanation
Find the shortest path from `2` to the edge, avoiding `1`.

#### Output
```
3
```

---

## Question 4: Sum of Floor Division Modulo ➗🔢

### Description
Given an array of integers where `N <= 10^5`, calculate the sum of `floor(Ai / Aj) % 100003` for all pairs `(Ai, Aj)` that can be formed from the elements of the array.

### Input Format
1. A single integer `N` representing the number of elements in the array.
2. A list of `N` integers.

### Output Format
- A single integer representing the sum of `floor(Ai / Aj) % 100003` for all pairs.

### Example
#### Input
```
4
5 1 2 3
```
#### Explanation
Calculate the sum of `floor(Ai / Aj) % 100003` for all pairs:
- `floor(5/5) % 100003`, `floor(5/1) % 100003`, `floor(5/2) % 100003`, `floor(5/3) % 100003`, ...
- Continue for all pairs and sum the results.

#### Output
```
15
```