# Sympy syntax

Import sympy before starting:

```python
from sympy import *
```

## Data types and basic operations

__Defining rational values:__
```python
#Rational of type 'float'
a = 1/3
#Rational of type 'Rational'
b = Rational(1,3)
```
Evaluate `Rational` using the `.evalf()` method:
```python
print(b.evalf())
#Output: 0.333333333333333
```

__Defining logs:__
```python
a = log(8)
print(a)
#Output: log(8)
print(a.evalf())
#Output: 2.07944154167984
```
To use *e* use `exp()`, with the desired power in the parentheses

__Declaring symbolic values:__
A symbol is a placeholder for a value in an equation.
```python
x = Symbol("x")
```

## Defining Functions:
Defining mathematic functions is the same as defining python functions.
```python
def g(x):
  return x**2
print(g(2))
#Output: 4
```
