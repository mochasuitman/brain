type:: [[algorithm]]
title:: Insertion Sort
algorithmic-family:: #[[sorting algorithm]] 
performance:: $$O(n^2)$$
difficulty:: #[[🟢 simple]]

-
- ## Notes
	- It is good for partially sorted arrays. It sorts the array without needing to create a copy of the array.
	- Similar at how humans sort a deck of cards
	-
- ## Code
	- ```C
	  void insertion_sort(int arr[], int len) {
	    int i, j;
	    for (i = 1; i < len; i ++) {
	      j = i;
	      while ((j > 0) && (arr[j] < arr[j - 1])) {
	        swap(&arr[j], &arr[j - 1]);
	        j --;
	      }
	    }
	  }
	  ```
	-
- ## Visualization
	- ![insertion_sort_animation.gif](../assets/insertion_sort_animation_1699649086325_0.gif){:height 188, :width 300}
	-
	-
- ## Performance Analysis
	-
	-
- ## Correctness Proof
	-
	-