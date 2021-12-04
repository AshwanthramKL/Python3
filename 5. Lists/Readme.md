# **Lists :**  

A collection of items stored in a single variable.  

* Built-in data type
* Mutable - Updatable.
* Ordered.
* Allow duplicate values.

```python
Game = ['football', 'cricket', 'badminton']
            0           1           2           

           -3          -2          -1
```
___  


### Accessing elements :  

*Syntax:*  
```python
list_name[index]  
```
`Game[2]` accesses 'badminton'

> Hint:  
Lists can also be accessed using negative index.  

___  

### Iterating through a list :  

*Syntax:*  
```python
for element in list_Name:
    print(element)
```

___ 


### Changing value of list :  

*Syntax:*  
```python
list_name[index] = new_value  
```

___

### Length of list :  

*Syntax:*  
```python
len(list_name)  
```

___

### Deleting an item in a list :

*Syntx:*
```python
del list_name[index]  
```

___

### Difference between working with lists and variables :

* variables -> Stores value directly.  
* Lists -> Stores the address of the list.

When creating a new variable to store the value of the list, we are copying the same address.  

So the changes made to new list is also reflected in the old list.  

**To avoid this, we can [slice the list]().**


