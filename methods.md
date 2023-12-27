# _ _ init _ _
_ _ init _ _ method is like default constructor in C++ and Java.

The task of constructors is to initialize(assign values) to the data members of the class when an object of the class is created.

Example - 
``` bash
# A Sample class with init method
class Person:
 
    # init method or constructor
    def __init__(self, name):
        self.name = name
 
    # Sample Method
    def say_hi(self):
        print('Hello, my name is', self.name)
 
 
p = Person('Nikhil')
p.say_hi()
```
# _ _ str _ _
The python _ _ str _ _ method returns the object representation in a string format. This method is supposed to return a human-readable format which is used to display some information about the object.

Example - 
``` bash
class Employee: 
    def __init__(self, name, age, id): 
        self.name = name 
        self.age = age
        self.id = id 
    
    def __str__(self):
        return f'Employee name is {self.name}, employee\'s age is {self.age} and id is {self.id}'

employeeObject = Employee('employeeName', 20, 1101)

print(str(employeeObject))
```
# _ _ repr _ _
The _ _ repr _ _ method in python also returns a string representation of an object which can be used for debugging purposes and development and it must be unambiguous.

Example - 
``` bash
class Employee: 
    def __init__(self, name, age, id): 
        self.name = name 
        self.age = age
        self.id = id 

    def __repr__(self):
        return f'Employee(name = {self.name}, age = {self.age}, id = {self.id})'


employeeObject = Employee('employeeName', 20, 1101)

print(repr(employeeObject))
```
# _ _ del _ _
_ _ del _ _ is a destructor method which is called as soon as all references of the object are deleted i.e when an object is garbage collected.

Example - 
``` bash
class Example:  
    # Initializing 
    def __init__(self): 
        print("Example Instance.")  
    # Calling destructor 
    def __del__(self):  
        print("Destructor called, Example deleted.")  

obj = Example()  

del obj  
```
# _ _ main _ _
In Python, there is no concept of the main() function, as it is an interpreter based language.

Python includes the special variable called _ _ name _ _ that contains the scope of the code being executed as a string. _ _ main _ _ is the name of the top-level scope in which top-level code executes.

Example - 
``` bash
>>>__name__
'__main__'
```