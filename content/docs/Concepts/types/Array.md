---
title: Arrays 
type: docs
prev: docs/concepts/types
next: docs/examples/algorithms
---

Arrays are the most complex type in Rash:

```go {filename=int.rash}
array = [0, 1, 2, 3, 4, 5];
print(arr[0]); // 0-indexed
print(arr[-1]); // Negative indexing (Goes from the end)
```

### Methods

```go {filename=int.rash}
array = pop(array)
array = push(array, 7)
array = swap(array, 0, 42)
```
