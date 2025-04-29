# Exp.No:25  
## Hierarchical Inheritance


### AIM  
To write a Python program to get the employee and doctor details and display them using hierarchical inheritance. Create a parent (base) class named `Details` and two child (derived) classes named `Employee` and `Doctor`.

### ALGORITHM

1. **Begin the program.**
2. **Create a class Details** with an `__init__` method to initialize three attributes: `id`, `name`, and `gender`.
3. **Define a method display_details()** to print the values of `id`, `name`, and `gender`.
4. **Create a class Employee** that inherits from the `Details` class. 
   - Add two additional attributes: `company` and `department`.
   - Override the `display_details()` method to print the employee-specific attributes (`company` and `department`) along with the inherited details.
5. **Create a class Doctor** that also inherits from the `Details` class. 
   - Add two additional attributes: `hospital` and `department`.
   - Override the `display_details()` method to print the doctor-specific attributes (`hospital` and `department`) along with the inherited details.
6. **Accept input** for employee and doctor details.
7. **Create objects of Employee and Doctor** using the input.
8. **Call the `display_details()` method** for both objects to print the details.
9. **Terminate the program.**


### PROGRAM
```
class details:
    def get_details(self):
        self.id=int(input())
        self.name=input()
        self.gender=input()
        self.hospital=input()
        self.dep=input()
        self.pa_id=int(input())
        self.pa_name=input()
        self.pa_gen=input()
        self.pa_hos=input()
        self.pa_dep=input()
class Doctor(details):
    def get_details1(self):
        print("Doctor Object")
        print("Id: ",self.id)
        print("Name: ",self.name)
        print("Gender: ",self.gender)
        print("Hospital: ",self.hospital)
        print("Department: ",self.dep)
class Patient(Doctor):
    def display(self):
        print("\nPatient Object")
        print("Id: ",self.pa_id)
        print("Name: ",self.pa_name)
        print("Gender: ",self.pa_gen)
        print("Hospital: ",self.pa_hos)
        print("Department: ",self.pa_dep)
obj=Patient()
obj.get_details()
obj.get_details1()
obj.display()
        
```

### OUTPUT  

![image](https://github.com/user-attachments/assets/89872650-d5be-4d68-a1fc-6c3871641504)
 


### RESULT
Thus the Python program to get the employee and doctor details and display them using hierarchical inheritance is implemented and executed successfully.
