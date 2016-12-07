
# Processing a String One Character at a Time

## Problem
- You want to process a string one character at a time.

## Solution

- __You can build a list whose items are the string’s characters__

```python
thelist = list(thestring)
```

- __Loop directly on the string__

```python 
for c in thestring:
    do_something_with(c)
```

- __List comprehension__

```python
results = [do_something_with(c) for c in thestring]
```

- __`map` built-in function__

```python
results = map(do_something, thestring)
```
