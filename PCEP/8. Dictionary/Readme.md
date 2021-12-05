# **Dictionary :**  

Used to store data in **key-value** pairs.  
 
*Syntax:*  
```python
dict_name = {
    key1 : value1,
    key2 : value2,
    key3 : value3,
         .
         .
         .
}
```  

It does not allow duplicate elements.  

___

### **Accessing Elements :**  

*Syntax:*  
```python
dict_name = {
    key1 : value1,
    key2 : value2,
    key3 : value3,
         .
         .
         .
}

print(dict_name[key1]) #Prints value1
``` 

___

#### **keys() :**  

Returns an iterable containing the dictionary's keys.  

*Syntax:* 
```python
dict_name = {
    key1 : value1,
    key2 : value2,
    key3 : value3,
         .
         .
         .
}

print(dict_name.keys()) #Prints value1
``` 

O/P:
```  
[key1, key2, key3, ...]
```
___

#### **values() :**  

*Syntax:* 
Returns an iterable containing the dictionary's values.  

```python
dict_name = {
    key1 : value1,
    key2 : value2,
    key3 : value3,
         .
         .
         .
}

print(dict_name.values()) #Prints value1
``` 

O/P:
```  
[value1, value2, value3, ...]
```
___


#### **items() :**  

Returns an iterable containing the dictionary's elements in the form of tuples where each tuple is a key-value pair.  

*Syntax:* 
```python
dict_name = {
    key1 : value1,
    key2 : value2,
    key3 : value3,
         .
         .
         .
}

print(dict_name.items()) #Prints value1
``` 

O/P:
```  
[(key1, value1), (key2, value2), (key3, value3), ...]
```
___  

### **Modifying a Dictionary :**  

* #### Changing a specific element :

    *Syntax:*  
    ```python
        dict_name = {
            key1 : value1,
            key2 : value2,
            key3 : value3,
                .
                .
                .
        }

        dict_name[key1] = new_value1 #Changes the value
    ``` 

* #### Using update() : 

    *Syntax:*  
    ```python
        dict_name = {
            key1 : value1,
            key2 : value2,
            key3 : value3,
                .
                .
                .
        }

        dict_name.update({key1: new_value1}) #Changes the value
    ``` 

___

### **Deleting elements :**  

We do this using `del` keyword.

  *Syntax:*     
```python  
    dict_name = {
        key1 : value1,
        key2 : value2,
        key3 : value3,
            .
            .
            .
    }

    del dict_name[key1] #Deletes the element
```

___


### **Deleting last element :**  

Use the *popitem()* to delete the last element in the dictionary.


  *Syntax:*     
```python  
    dict_name = {
        key1 : value1,
        key2 : value2,
        key3 : value3,
            .
            .
            .
    }

    dict_name.popitem() #Deletes the last element
```
___


### **Clearing all elements :**  

Use the *clear()* to completely empty the dictionary.


  *Syntax:*     
```python  
    dict_name = {
        key1 : value1,
        key2 : value2,
        key3 : value3,
            .
            .
            .
    }

    dict_name.clear() #Empties the dictionary
```

___

### **Copying a Dictionary :**  

Use the *copy()* to copy a dictionary.

*Syntax:*  
```python  
    dict_name = {
        key1 : value1,
        key2 : value2,
        key3 : value3,
            .
            .
            .
    }

    new_dict = dict_name.copy() #Empties the dictionary
```

___