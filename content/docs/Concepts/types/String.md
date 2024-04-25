---
title: Strings
type: docs
prev: docs/concepts/types
next: docs/concepts/types/integer
---

Strings are an important part of Rash, there are three types of strings:

### Standard strings
```python {filename=strings.rash}
name = "Josh";
print(name);
```


### Formated strings
```python {filename=fstrings.rash}
name = "Josh";
print(f"My name is ${name}");
```


### Command strings
```go {filename=cstrings.rash}
url = "https://pokey.remington.boo";
c"curl ${url}"; // Prints to stdout

files = c"ls"; // Doesn't print and saves it in a variable
print(files);
```
