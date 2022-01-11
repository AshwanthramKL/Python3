# **Modules :**  

* A module is a file containing Python definitons and statements, which can be imported and used when necessary.

* It helps to split our coedebase into smaller parts.  

* We can use :  
    * Own modules
    * Another developer's module
    * Python's built-in modules

* Python has several modules with built-in functions in its *Standard Library*.

___

### **Importing a module :**  

We import a module into the main file to access the code in it.

*Syntax:*
```python
import module_name
```
We can also import more than module by appending a module to the list using a `,`.

*Syntax:*
```python
import module1_name,module2_name,...
```

___

### **Using entities :**  

*Syntax:*  
```python
import module_name

module_name.entity()
```

We can also import the required entities alone from a module inorder to save space using the keyword `from`.  

**[ OR ]**

We could import all the entities from a module inorder to avoid using the dot notation.  

*Syntax:*  
```python
from module1_name import entity1,entity2
from module2_name import * #imports all the entities of a module

entity1() #belongs to module1
entity3() # belongs to module2
```

> Note:  
    It is not recommended to import multiple entities as it might cause  later in the program.
___


### **Aliasing :**  

We can import a module/entity with a name of our choice inorder to avoid naming conflict [OR] just coz we don't like it.  

*Syntax:*  
```python
import module1_name as alias1
from module2_name import entity2 as alias2, entity3 as alias3 

alias1.entity1() #belongs to module1
print(alias2()) #belongs to module2
print(alias3()) #belongs to module2
```

___