# py2hs
A complementary resource that helps python programmers to learn Haskell as a new language

Python 
>>> def multiply(x, y):
...     return x * y
...
>>> multiply(2, 3)
6

Haskell
λ> multiply x y = x * y
λ> multiply 2 3
6

Flow control
Python
def bigger(x, y):
    if x > y:
        return x
    else:
        return y
        
Haskell
bigger x y = if x > y
             then x
             else y
             
             
