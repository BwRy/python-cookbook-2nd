
# Converting Between Characters and Numeric Codes

## Problem
- You need to turn a character into its numeric ASCII (ISO) or Unicode code.

## Solution
- __Use the built-in functions ord and chr__

## Example 1


```python
print ord('a')
print chr(97)
```

    97
    a


## Example 2

- The built-in function ord also accepts as its argument a Unicode string of length one, in which case it returns a Unicode code value, up to 65536.


```python
print ord(u'\u2020')
print repr(unichr(8224))
```

    8224
    u'\u2020'


## Example 3


```python
print map(ord, 'ciao')
```

    [99, 105, 97, 111]


## Example 4


```python
print ''.join(map(chr, range(97, 100)))
```

    abc

