### BUBBLE SORT

[Bubble Sort](https://en.wikipedia.org/wiki/Bubble_sort) is the easiest and simple sorting algorithm that you have ever known. Bubble sort repeatedly compares adjacent elements through the list and swaps them if any element is in wrong order.

### EXAMPLE

<p align="center">
	<img src="https://upload.wikimedia.org/wikipedia/commons/c/c8/Bubble-sort-example-300px.gif">
</p>

<p align="center">
Here each pair of adjacent elements is compared and the elements are swapped if they are not in order through the array.
</p>

### COMPLEXITY

| **Bubble Sort Performance** | **Comparisons & Swaps**            |
| --------------------------- | :--------------------------------: |
| Worst-Case Performance      | ![O(n^2)](https://render.githubusercontent.com/render/math?math=O(n%5E2)) comparisons, ![O(n^2)](https://render.githubusercontent.com/render/math?math=O(n%5E2)) swaps |
| Best-Case Performance       | ![O(n)](https://render.githubusercontent.com/render/math?math=O(n)) comparisons, ![O(1)](https://render.githubusercontent.com/render/math?math=O(1)) swaps |
| Average-Case Performance    | ![O(n^2)](https://render.githubusercontent.com/render/math?math=O(n%5E2)) comparisons, ![O(n^2)](https://render.githubusercontent.com/render/math?math=O(n%5E2)) swaps |
| Worst-Case Space Complexity | ![O(n)](https://render.githubusercontent.com/render/math?math=O(n)) total, ![O(1)](https://render.githubusercontent.com/render/math?math=O(1)) auxiliary |

### Test

1. To compile(Here *run* is the name of executable file of *Bubble Sort*)

```
h1manshu@asus:~/Sorting-Algorithm/Bubble_Sort
$ gcc -o run BubbleSort.c 
```

2. To run

```
h1manshu@asus:~/Sorting-Algorithm/Bubble_Sort
$ ./run 
```

3. Output of Bubble Sort

```
	---BUBBLE SORT---
Enter the size of array(max 20): 10

Enter the elements in the array: 5
6
3
9
10
1
2
8
0
7

Elements in the array : 5 6 3 9 10 1 2 8 0 7 
Elements in ascending order:
0 1 2 3 5 6 7 8 9 10
```

### CODE IMPLEMENTATION

[BubbleSort.c](https://github.com/Himanshu40/Sorting-Algorithm/blob/master/Bubble_Sort/BubbleSort.c)