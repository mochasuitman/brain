type:: [[algorithm]]
title:: Binary Search
algorithmic-family:: #[[searching algorithm]] 
performance:: $$O(log(n))$$
difficulty:: #[[🟢 simple]]

-
- ## Notes
	- Based upon the [[Teorema Di Bolzano (teorema degli zeri)]]
	-
- ## Code
	- ```C
	  int binary_search(int arr[], int len, int target) {
	    int left = 0;
	    int right = len - 1;
	    int mid;
	    
	    while (left < right) {
	      mid = (left + right) / 2;
	      
	      if (arr[mid] == target) return mid;
	      else if (arr[mid] < target) left = mid + 1;
	      else right = mid - 1;
	    }
	  }
	  ```
	-
- ## Visualization
	-
	-
- ## Performance Analysis
	-
	-
- ## Correctness Proof
	-
	-