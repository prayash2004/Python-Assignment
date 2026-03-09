# Python-Assignment
# 1. Student class with method show() to display name, age and roll number
class Student:
    def __init__(self, name, age, roll):
        self.name = name
        self.age = age
        self.roll = roll
     def show(self):
        print("Name:", self.name)
        print("Age:", self.age)
        print("Roll No:", self.roll)
s1 = Student("Prayash", 20, 45)
s1.show()

# 2.Create a class Person with variable name, create object and print the name
class Person:
    def __init__(self, name):
        self.name = name
p1 = Person("Prayash")
print("Name:", p1.name)
