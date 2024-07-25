## Psuedocode for linear algebra

```python


FUNCTION Solution(A,b):
    create Augmented matrix: K=[a|b]
    Reduce in Row reduced echelon form
    Rank=no of non zero rows pf RREF
    if Rank(K)!=Rank(A):
        print(system is inconsistent)
    ELSE IF:
        solve using back substitution



END FUNCTION
```

$$A=\begin {pmatrix}
    1&3&3\\
    3&4&5\\
    5&6&7\\
    \end{pmatrix}$$
