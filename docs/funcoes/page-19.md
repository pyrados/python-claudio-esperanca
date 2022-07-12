# Lista de parâmetros variável (2)

- Se o último argumento de uma definição de função
  começa com `**`, todos os valores passados usando chaves, a partir daquele, são postos num dicionário

- Ex.:
  
  ```python
  >>> def f(a,b,**c):
          print a, b, c

  >>> f(1,2,3)
  ...
  TypeError: f() takes exactly 2 arguments (3 given)
  >>> f(1,2,x=3)
  1 2 {'x': 3}
  ```

