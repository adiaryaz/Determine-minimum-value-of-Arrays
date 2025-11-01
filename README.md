# Determine minimum value of Arrays

A program to compare two 1-dimensional arrays (lists) of integers, find the minimum value within each, and then determine the overall minimum value between them.

## 📝 Description

This program takes two separate lists of numbers as input. It must first validate that both lists contain *only* integers. If they do, it finds the minimum value from the first list and the minimum value from the second list. Finally, it compares these two minimums and outputs the one that is smaller.

-----

## 🎯 Problem Statement

### Input:

  * Input 1: A list of numbers (`arr1`).
  * Input 2: A second list of numbers (`arr2`).

### Output:

  * The single lowest integer value found across both lists.
  * "Cannot determine, as there is a list." if *either* list contains a non-integer element.

### Rules:

1.  The program must read two separate lists.
2.  **Validation:** The program must check *both* lists. If *either* list contains any element that is not an integer (e.g., a string), it must output the error message "Cannot determine, as there is a list."
3.  **Function Implementation:** A function must be used to find the minimum value of a single list.
4.  **Comparison:** The program must find the minimum of the first list (`min1`), find the minimum of the second list (`min2`), and then compare `min1` and `min2` to find the absolute minimum.

-----

## 💡 Examples

### Example 1 (Sample 1)

**Input:**

```
[10, 2, 4, 10]
[2, 4, 10, 30, 2]
```

**Output:**

```
2
```

**Explanation:** The min of the first list is 2. The min of the second list is 2. The overall min is 2.

### Example 2 (Sample 2)

**Input:**

```
[1, 8, 2, 10, 18, 10, 15, 16]
[8, 10, 12, 20]
```

**Output:**

```
1
```

**Explanation:** The min of the first list is 1. The min of the second list is 8. The overall min is 1.

### Example 3 (Sample 3)

**Input:**

```
[0, 1, 2, 3, 5, 10]
[2, 11]
```

**Output:**

```
0
```

**Explanation:** The min of the first list is 0. The min of the second list is 2. The overall min is 0.

### Example 4 (Sample 6)

**Input:**

```
[10, "a", 19]
[19, 29, 19]
```

**Output:**

```
Cannot determine, as there is a list.
```

**Explanation:** The first list contains a non-integer (a string "a").

### Example 5 (Sample 7)

**Input:**

```
[10, 20, 30]
["a", 10, 30]
```

**Output:**

```
Cannot determine, as there is a list.
```

**Explanation:** The second list contains a non-integer (a string "a").

-----

## 🚀 How to Use

1.  **Clone this repository**

    ```bash
    git clone https://github.com/adiaryaz/array-min-compare.git
    cd array-min-compare
    ```

2.  **Run the program** (assuming the file is `main.py`):

    ```bash
    python main.py
    ```

    Enter the two arrays in list format (e.g., `[1, 4, 5]`) on separate lines when prompted to see the result.
