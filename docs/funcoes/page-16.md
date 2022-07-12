# Exemplos de alteração de parâmetros

```python
>>> def f(x):
     x[:] = [5]

>>> a = [1]

>>> f(a)

>>> a
[5]

>>> b = a

>>> b[:] = [7]

>>> a
[7]
```

![Slide 16](images/page-16.png)

