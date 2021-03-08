# Back to basics

## Data types are the building blocks of python

A data type is like a specification of what kind of data we would like to store
in memory, these are some of the built in types in this category

1. Text type: str
2. Numeric types: int, float, complex
3. Sequence types: list, tuple, range
4. Mapping type: dict
5. Set types: set, frozenset
6. Boolean type: bool (true or false)
7. Binary types: bytes, bytearray, memoryview

## Text type

### str

str stands for string in python and used for storing text. Strings can be written
in single quotes or double quotes.

Example: ![str example](https://hackernoon.com/images/B6I7WEwrKubf11jAWFL33iiMzR13-s63531s3.png)

output:

```python
Hello, world!
```

```python
<class 'str'>
```

---

## Numeric types

### int

int is short for integer and used to store positive and negative numbers

Example:

![integer example](https://hackernoon.com/images/B6I7WEwrKubf11jAWFL33iiMzR13-qc3i312j.jpeg)

output:

```python
4
```

```python
<class 'int'>
```

---

### float

**float** is short for floating-point numbers (decimal point numbers)

Example:

![floating point example](https://hackernoon.com/images/B6I7WEwrKubf11jAWFL33iiMzR13-903s312k.png)

output:

```python
3.14
```

```python
<class 'int'>
```

---

### complex

**complex** numbers have a real and imaginary part, which are each a floating point number. Complex numbers can be written in two forms:

1. real + (imag)j
2. complex(real, imag)

Example:

![imaginary number example](https://hackernoon.com/images/B6I7WEwrKubf11jAWFL33iiMzR13-334731h8.png)

output:

```python
(5 + 10j)
```

```python
<class 'complex'>
```

---

## Sequence types

### list

a **list** data type stores a collection of data
A list can also contain different data types
A list is _ordered_ and _changeable_ and allows _duplicate members_

Example:

![list example](https://hackernoon.com/images/B6I7WEwrKubf11jAWFL33iiMzR13-a24c31qp.jpeg)

output:

```python
['Captain America', 'Iron Man', 'Thor', 'Hulk', 'Black Widow', 'Hawkeye']
```

```python
<class 'list'>
```

---

### tuple

A **tuple** data type also stores a collection of data
A tuple can also contain different data types
a tuple is _ordered_ and _unchangeable_ and _allows duplicate members_

Example:

![tuple example](https://hackernoon.com/images/B6I7WEwrKubf11jAWFL33iiMzR13-934p31ga.jpeg)

output:

```python
('Captain America', 'Iron Man', 'Thor', 'Hulk', 'Black Widow', 'Hawkeye')
```

```python
<class 'tuple'>
```

---

### range

The **range** type represents an immutable (unchangeable) sequence of numbers.
Ranges are commonly used for looping a specific number of times in for loops.

Example:

![range example](https://hackernoon.com/images/B6I7WEwrKubf11jAWFL33iiMzR13-k84z311r.jpeg)

output:

```python
range(0, 10)
```

```python
<class 'range'>
```

---

## Mapping types

### dict

**dict** stands for dictionary in python. Dictionaries are used to store data in
key: value pairs. A dictionary is a collection which is _undordered_ , _changeable_ , and does _not allow for duplicates_

Example:

![dict example](https://hackernoon.com/images/B6I7WEwrKubf11jAWFL33iiMzR13-h55931hf.jpeg)

output:

```python
{'Learning': 'Programming', 'Language': 'Python', 'Day': 4}
```

```python
<class 'dict'>
```

---

## Set types

### Set

A **set** is a data type where you can store a collection of data. A set
can also contain different data types. A set is **unordered** and **unindexed** and **allows no duplicate members**.

Example:

![set example](https://hackernoon.com/images/B6I7WEwrKubf11jAWFL33iiMzR13-lx5j31rj.jpeg)

output:

```python
{'Black Widow', 'Iron Man', 'Thor', 'Hawkeye', 'Hulk', 'Captain America'}
```

```python
<class 'set'>
```

---

### Frozenset

A frozenset data type can be created by the frozenset() function. The
frozenset() function accepts an iterable and returns an unchageable frozenset object
(which is like a set object, only unchageable)

Example:

![frozenset example](https://hackernoon.com/images/B6I7WEwrKubf11jAWFL33iiMzR13-jq5t31d8.jpeg)

output:

```python
frozenset({'cherry', 'banana', 'apple'})
```

```python
<class 'frozenset'>
```

---

## Boolean types

### bool

bool stands for boolean in python. Boolean represents two values: True or False

Example:

![boolean example](https://hackernoon.com/images/B6I7WEwrKubf11jAWFL33iiMzR13-q96631sw.jpeg)

output:

```python
True
```

```python
<class 'bool'>
```

```python
False
```

```python
<class 'bool'>
```
