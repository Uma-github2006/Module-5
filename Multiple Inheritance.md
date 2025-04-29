# Exp.No:23  
## Multiple Inheritance


### AIM  
To write a Python program that uses a destructor (__del__ method) to delete an instance of a class and print a message when the object is destroyed.

### ALGORITHM

1. Start the program.
2.Define a class named Student.
3.Inside the class:
4.Create a constructor __init__ to initialize name and age.
5.Create a method printDetail() to display student details.
6.Create a destructor __del__() to print a message when the object is deleted.
7.Create an instance s1 of the Student class.
8.Call printDetail() using the instance.
9.Use del s1 to delete the object explicitly and trigger the destructor.
10.End the program.

### PROGRAM

```
class Student:
	def __init__(self, name, age):
		self.name = name
		self.age = age

	def printDetail(self):
		print(f"My name is {self.name} and I am {self.age} years old.")
	def __del__(self):
	    print(f"{self.name} student is deleted.")

s1 = Student("Vishvajit Rao", 22)
s1.printDetail()
del Student

```

### OUTPUT
![image](https://github.com/user-attachments/assets/d0903e52-0f15-4de5-ab61-923937af5903)



### RESULT
Thus the Python program to delete an instance of a class and print a message when the object is destroyed is implemented and executed successfully.




