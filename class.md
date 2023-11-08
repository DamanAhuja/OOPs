# Class
**Defining a class**
``` bash 
class student:
```
**Constructor**: A special type of method(function) used to initialise members of the class
```bash
def __init__(self,name,roll,course):
        self.name=name
        self.roll=roll
        self.course=course
```
**Object**: The object is an entity that has a state and behavior associated with it.
```bash
Daman=student("Daman",20231409,"Comp Sci")
```
**Reference**: It is Used to refer to an object
- For eg. `Daman`=student("Daman",20231409,"Comp Sci")

**Full code**:
```bash
class student:
    def __init__(self,name,roll,course):
        self.name=name
        self.roll=roll
        self.course=course
    def record(self):
        print(self.name,"'s roll number is",self.roll,"and course is",self.course)
Daman=student("Daman",20231409,"Comp Sci")
Daman.record()
print("Student Roll No. is",Daman.roll)
```
**Output**:
```bash
Daman roll number is 20231409 and course is Comp Sci
Student Roll No. is 20231409
```
# Pillars of OOPs
- **Encapsulation**: It states that the members related with a class should not be accessible outside the class withhout permission
- **Abstraction**: It defines the accessibility level on the class members. 
  - **Private**: Within the class only.
  - **Protected**: Within the class or the child class.
  - **Public**: Can be used by the object or inherited in child class.
- **Polymophism**: It states that we can utilize an item for multiple tasks.   
