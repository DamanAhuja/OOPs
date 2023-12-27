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
