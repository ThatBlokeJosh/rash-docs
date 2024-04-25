---
title: Algorithms 
type: docs
---

### Binary search

```go {filename=bs.rash}
// Simple binary search implementation with a wrapper so that the user doesn't need to specify the left and right

fn search_wrapper(array, l, r, target) {
    if l > r; {
	    print(f"Target ${target} not found")
	    return {-1};
    }

    middle = r - l; 
    middle = middle / 2;
    middle = middle + l;

    if target == array[middle]; {
	    return {middle};	
    } else if target < array[middle]; {
	    return {search_wrapper(array, l, middle - 1, target)}
    } else {
	    return {search_wrapper(array, middle + 1, r, target)};
    }
}

fn search(array, target) {
    r = len(array) - 1;
    return {search_wrapper(array, 0, r, target)};
}
```
Also accessible through the std:
```go {filename=algo.rash}
import {algorithms};
arr = [1, 2, 3, 4, 5]

index = search(arr, 2)
print(f"Target 2 found at index: ${index}")
```
