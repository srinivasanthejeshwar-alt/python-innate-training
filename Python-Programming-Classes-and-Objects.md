# 🐍 Python Programming - Classes and Objects

## 📚 Topic: Object-Oriented Programming (OOP) in Python

### Concepts Covered

- Classes and Objects
- Constructors (`__init__`)
- Instance Variables
- Methods
- List Operations
- Even/Odd Checking
- Number Manipulation
- Encapsulation

---

## 💻 Full Program (Corrected Version)

```python
# Class 1: Car Details

class Car:
    def __init__(self, model1, model2):
        self.model01 = model1
        self.model02 = model2

    def bmw(self):
        print("BMW Model:", self.model01)

    def audi(self):
        print("Audi Model:", self.model02)


cars = Car("X3", "Q4")
cars.bmw()
cars.audi()


# Class 2: Sum of Two Lists

class Num:
    def __init__(self, arr1, arr2):
        self.arr01 = arr1
        self.arr02 = arr2

    def calculate_sum(self):
        result = []

        for i in range(len(self.arr01)):
            result.append(self.arr01[i] + self.arr02[i])

        print("Sum Result:", result)


x = eval(input("Enter first list: "))
y = eval(input("Enter second list: "))

sums = Num(x, y)
sums.calculate_sum()


# Class 3: Sum of Lists and Even/Odd Check

class Num1:
    def __init__(self, arr1, arr2):
        self.arr01 = arr1
        self.arr02 = arr2

    def sum_and_check(self):
        result = []

        for i in range(len(self.arr01)):
            result.append(self.arr01[i] + self.arr02[i])

        print("Sum Result:", result)

        for n in result:
            if n % 2 == 0:
                print(f"{n} -> Even")
            else:
                print(f"{n} -> Odd")


x = eval(input("Enter first list: "))
y = eval(input("Enter second list: "))

sums1 = Num1(x, y)
sums1.sum_and_check()


# Class 4: Split Number and Check Even/Odd

class Bottle:
    def __init__(self, data):
        self.data = data

    def number(self):
        first = self.data // 100
        second = self.data % 100

        print("First Part:", first)
        print("Second Part:", second)

        for n in [first, second]:
            if n % 2 == 0:
                print(f"{n} -> Even")
            else:
                print(f"{n} -> Odd")


no = Bottle(5489)
no.number()
```

---

## 🎯 Learning Outcomes

- Creating classes and objects in Python
- Using constructors to initialize data
- Calling methods using objects
- Performing operations on lists inside classes
- Checking numbers for even and odd conditions
- Working with object-oriented programming concepts

---

## 🚀 Placement Training Progress

**Category:** Python Programming  
**Topic:** Classes and Objects (OOP Basics)
