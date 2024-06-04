type:: [[algorithm]]
title:: Selection Sort
algorithmic-family:: #[[sorting algorithm]]
performance:: $$O(n^2)$$
difficulty:: #[[🟢 simple]]

-
- ## Notes
	- Sorting an unsorted array of elements
	-
- ## Code
	- ```C
	  void selection_sort(int arr[], int len) {
	    int i, j;
	    int min;
	  
	    for (i = 0; i < len; i ++) {
	      min = i;
	      for (j = i + 1; j < len; j ++) {
	        if (arr[j] < arr[min]) min = j;  // (<) for ascending order, (>) for descending order
	        swap(&arr[i], &arr[min]);
	      }
	    }
	  }
	  ```
	-
- ## Visualization
	- ![selection_sort_animation.gif](../assets/selection_sort_animation_1699611785088_0.gif){:height 325, :width 555}
	-
- ## Performance Analysis
	- The outer loop goes around $$n$$ times. The inner loop goes around $$ n - i - 1$$ times
	- The number of times that the $$if$$ is executed is defined by $$S(n)$$:
	- (The number $$1$$ is simply a placeholder that represents the execution of the $$if$$ statement. It can be every constant value)
	- $$S(n) = \sum_{i=0}^{n - 1}\sum_{j=i+1}^{n - 1}1 = \sum_{i=0}^{n - 1}n - i - 1 \\ S(n) = (n - 1) + (n - 2) + (n - 3) + ... + 2 + 1$$
	- We can assume that $$S(n) \le n(n - 1)$$ so:
	- $$n(n - 1) = n^2 - n \\ S(n) \le n^2 - n \Rightarrow S(n) = O(n^2)$$
-
- ## Correctness Proof
	-
	-