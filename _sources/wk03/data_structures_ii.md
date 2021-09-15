---
jupytext:
  formats: ipynb,md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.10.3
kernelspec:
  display_name: Python 3 (ipykernel)
  language: python
  name: python3
---

# Data Structures II

## EOSC 211

**Week 3 Day 2**

**Learning Objectives:**  
1. Get more experience with Numpy arrays
2. Use built in functions to write efficient, *Pythonic* code

```{code-cell} ipython3
import numpy as np
```

## Question 1

**A) Execute the following cells and describe IN WORDS what is happening in each cell**

```{code-cell} ipython3
lats = np.arange(1,21)
lats = np.arange(10,16)
```

```{code-cell} ipython3
L2 = np.array([lats[2], lats[4]])
```

your answer here

```{code-cell} ipython3
L3 = np.array([lats[-1], lats[0]])
```

your answer here

```{code-cell} ipython3
L4 = lats[lats > 13]
```

```{code-cell} ipython3
L5 = lats[lats >= 13]
```

```{code-cell} ipython3
L6 = lats[::-1]
```

```{code-cell} ipython3
L7 = lats[-1]
L7 = lats[4]
L7 = lats[len(lats)-1]
```

## Question 2

**A) We can change the shape of our `lats` array with numpy's built in funciton `reshape()`. What does the following code do?**

```{code-cell} ipython3
newlats = lats.reshape([2,3])
```

**B) What are all the possible shapes we can reassign to `lats`? Why do some work and others not**

+++

your answer here

+++

**C) We can return `lats` to it's original shape using `flatten()`, i.e.**

```{code-cell} ipython3
lats = newlats.flatten()
lats
```

**How else could you accomplish this? Write code in the following cell that outputs the same result starting with any of the `newlats` shapes we used above**

```{code-cell} ipython3
# your code here
```

## Question 3

**Along with `+`, `-`, `*`, `/`, python also defines the *floor division operator* `//` and the *modulo operator* `%`. Floor division (`//`) outputs the *quotient* of two integers, and modulo (`%`) outputs the remainder. Example code:**

```{code-cell} ipython3
5 // 2
```

```{code-cell} ipython3
5 % 2
```

**Write a few lines of code that will create the array `B`, which contains only the even valued elements of an array `A`. You don't know the size of `A` but you do know it contains only integers.**

```{code-cell} ipython3
# your code here
```
