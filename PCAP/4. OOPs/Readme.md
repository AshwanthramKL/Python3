# **Object Oriented Programming :**

### **Object Oriented vs Procedural :**

**Procedural Approach :**  
Distinguishes data (variables) and code (modules and functions).  
Functions can use the data, but the data cannot use the functions.

eg.

```python
stack = []

def push(val):
    stack.append(val)

def pop():
    val = stack[-1]
    del stack[-1]
    return val

push(3)
push(2)
push(1)
print(pop())
print(pop())
print(pop())
```
**Disadvantages :**  

* Stack variable is highly vulnerable.

* It can be modified by anyone, i.e has no protection.

* While creating a new stack, push() and pop() has to be created again.  


___


**Object Oriented Approach :**  
Data and code are enclosed together in classes.  
Objects exchange data and activate their methods.

eg.

```python
class Stack:
    def __init(self):
        self.__stack_list = []
    
    def push(self, val):
        self.__stack_list.append(val)

    def pop(self):
        val = self.__stack_list[-1]
        del self.__stack_list[-1]
        return val

stack_object = Stack()
stack_object2 = Stack()

stack_object.push(3)
stack_object.push(2)
stack_object.push(1)

stack_object2.push(10)
stack_object2.push(9)

print(stack_object2.pop())
print(stack_object.pop())
print(stack_object.pop())
print(stack_object.pop())
```
___