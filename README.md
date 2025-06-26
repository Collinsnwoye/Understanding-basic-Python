# Understanding-basic-Python

  ## Variables
I see it as a name given a value, call it the container's name. You can gave a Variable different names in this sense :

```python 
# I'm wealthy thats who I am.
Collins = "I'm wealthy thats who I am."

# School friends call me Brown
Brown = Collins

# Colleagues at work call me Collinzo 
Collinzo = Brown 

# I stopped using my name and name given to me by my school friends
del Collins
del Brown

# But colleagues nickname to me still refers to me.
print(Collinzo)
```
### In Python, there are keywords you can use to label or tag a value;
 these keywords are reserved for Python itself. Here are some of them: False, await, 
else, import, pass, None, break, in, except, raise, True, class, fina ly, is, return, 
and, continue, for, lambda, try, as, def, from, nonlocal, while, assert, del, global, 
not, with, async, elif, if, or, and yield. 
 Meaning, you can't use these words as variables as to the fact that they are words part of the pythons language's structure.
  I'll breakdown every keyword to how it used and what it means.
  ------------

  ### Fales 
  is one of the two Boolean values(George Boole a mathematician that's named after it, which is a data type that can be either true or false) which literally means "not true." Python treats it as the opposite of True, and it behaves like the number 0 in calcultaions.
  Used in conditional staements and more.
