# 🐍 Innate Talent Placement Training - Day 07

## 📚 Topics Covered

- Boolean Data Type
- User Input
- Integer Input
- Multiplication of Two Numbers
- Area of Rectangle
- Integer to Float Conversion
- Float to Integer Conversion
- String to Integer Conversion
- Simple Interest Calculation
- Compound Interest Calculation
- Fahrenheit to Celsius Conversion
- Kilometer to Meter Conversion
- Speed Calculation
- Area of Square

---

## 💻 Programs

### 1. Boolean Data Type

```python
a1 = True
print(type(a1))
```

### 2. Accept Name as Input

```python
name = input("Enter your name: ")
print("My name is", name)
```

### 3. Accept Age as Input

```python
age = int(input("Enter your age: "))
print(age)
```

### 4. Multiplication of Two Numbers

```python
j = int(input("Enter number 1: "))
k = int(input("Enter number 2: "))
l = j * k
print("The multiplication of the two numbers is", l)
```

### 5. Area of Rectangle

```python
length = int(input("Enter the length: "))
breadth = int(input("Enter the breadth: "))
area = length * breadth
print("Area =", area)
```

### 6. Integer to Float Conversion

```python
a2 = 20
b2 = float(a2)
print(b2)
```

### 7. Float to Integer Conversion

```python
a3 = 5.9
b3 = int(a3)
print(b3)
```

### 8. String to Integer Conversion

```python
num_str = "123"
num_int = int(num_str)
print(num_int)
print(type(num_int))
```

### 9. Simple Interest Calculator

```python
principal = float(input("Enter Principal Amount: "))
rate = float(input("Enter Rate of Interest (%): "))
time = float(input("Enter Time (years): "))
simple_interest = (principal * rate * time) / 100
print("Simple Interest =", simple_interest)
```

### 10. Compound Interest Calculator

```python
principal = float(input("Enter Principal Amount: "))
rate = float(input("Enter Rate of Interest (%): "))
time = float(input("Enter Time (years): "))
amount = principal * (1 + rate / 100) ** time
compound_interest = amount - principal
print("Compound Interest =", compound_interest)
print("Total Amount =", amount)
```

### 11. Fahrenheit to Celsius Conversion

```python
fahrenheit = float(input("Enter temperature in Fahrenheit: "))
celsius = (fahrenheit - 32) * 5 / 9
print("Temperature in Celsius =", celsius)
```

### 12. Kilometer to Meter Conversion

```python
kilometers = float(input("Enter distance in kilometers: "))
meters = kilometers * 1000
print("Distance in meters =", meters)
```

### 13. Speed Calculator

```python
distance = float(input("Enter distance (in meters): "))
time = float(input("Enter time (in seconds): "))
speed = distance / time
print("Speed =", speed, "m/s")
```

### 14. Area of Square

```python
side = float(input("Enter the side length of the square: "))
area = side * side
print("Area of the square =", area)
```

---

## 🎯 Key Concepts Learned

- Python Input and Output
- Type Conversion
- Mathematical Calculations
- Arithmetic Operators
- Variables and Data Types
- Real-world Formula Implementations

## 🚀 Placement Training Progress

**Training Program:** Innate Talent Placement Training  
**Day:** 07  
**Language:** Python 3
