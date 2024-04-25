---
title: Loops 
type: docs
prev: docs/concepts/conditions
next: docs/concepts/functions
---

Similarly to Go, Rash has two loop types

### Standard iterator style
```go {filename=loops.rash}
arr = [0, 1, 5, 6]
for i = 0; i < len(arr); ++i; {
  print(arr[i]);
}  
```


### While loop style 
```go {filename=loops.rash}
for true; {
  print("Bash stinks")
}
```
