---
title: Functions 
type: docs
prev: docs/concepts/loops
next: docs/concepts/std
---

Bash supports functions, define your own like so:

```rust {filename=functions.rash}
fn add(x, y) {
  print(f"Adding ${x} and ${y}");
  return {x + y};
}

// Call them like so
z = add(5, 6)
```
