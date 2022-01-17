# binary-tree-subrange
algorithm that takes a range of numbers as input and returns array of numbers in that range


## concept
Поиск минимума.
Теперь в цикле:
1. Поднимаемся наверх.
2.  if (current.left == prev)
3.    if (current.has-right-child)
4.      Начинаем обход правого поддерева
5.      if (found-max) 
6.        goto max-part
7.  else
8.    contiunue;

max-part:
1. if (current.has-left-child)
2.  Берем все элементы левого поддерева
3. Поднимаемя наверх
