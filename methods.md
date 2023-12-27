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