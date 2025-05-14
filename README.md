# Ex:6(a) 🐍 Python OOP: Abstract Class & Method Example

## 🎯 AIM

To create an **abstract class** named `Shape` with an **abstract method** `calculate_area`, and implement this method in two subclasses: `Rectangle` and `Circle`.

---

## 🧠 ALGORITHM

1. **Import ABC module**:
   - Use `from abc import ABC, abstractmethod` to define abstract classes and methods.

2. **Create Abstract Class `Shape`**:
   - Define an abstract method `calculate_area()` with `@abstractmethod`.

3. **Create Subclass `Rectangle`**:
   - Set default values for `length` and `breadth`.
   - Override `calculate_area()` to compute the rectangle area.

4. **Create Subclass `Circle`**:
   - Set default value for `radius`.
   - Override `calculate_area()` to compute the circle area.

5. **Create Objects & Call Methods**:
   - Instantiate `Rectangle` and `Circle`.
   - Call their `calculate_area()` methods.

---

## 💻 Program
Developed By: V Mythili
Reg No: 212223040123

```
from abc import ABC
class Shape(ABC):
   def calculate_area(self):
        Pass
class Rectangle(Shape):
    length = 5
    breadth =3
def calculate_area(self):
    print("Area of a rectangle:",self.length * self.breadth) class
Circle(Shape):
   radius = 4
   def calculate_area(self):
        print("Area of a circle:",3.14 * self.radius * self.radius)
a=Rectangle()
b=Circle()
a.calculate_area()
b.calculate_area()
```
## Output

![image](https://github.com/user-attachments/assets/0c609692-09cb-4cbb-b991-1d3d3a294bfd)

## Result
Thus, the program has been successfully executed.

# Ex:6(b) 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
Developed By: V Mythili
Reg No: 212223040123


![image](https://github.com/user-attachments/assets/8f7196a4-d607-4698-8526-a5fcf34a3186)


## Output

![image](https://github.com/user-attachments/assets/5e40ab99-3941-4bf1-b2d6-5cbe39ed3012)

## Result

Thus, the program has been successfully executed.


# Ex:6(c) 🐟 Method Overriding-Fish and Shark Class Inheritance in Python

## 🧠 AIM:
To write a Python program that demonstrates class inheritance by creating a parent class `Fish` with a method `type`, and a child class `Shark` that overrides the `type` method.

## 📋 ALGORITHM:

1. Define the `Fish` class with a method named `type()` that prints `"fish"`.
2. Define the `Shark` class as a subclass of `Fish`, and override the `type()` method to print `"shark"`.
3. Create an instance of the `Fish` class named `obj_goldfish`.
4. Create an instance of the `Shark` class named `obj_hammerhead`.
5. Use a `for` loop to iterate over both objects.
6. Within the loop, call the `type()` method using the loop variable.
7. Output will demonstrate method overriding: printing `"fish"` and `"shark"` accordingly.

## 💻 PROGRAM:
Developed By: V Mythili
Reg No: 212223040123


![image](https://github.com/user-attachments/assets/c565c1a6-cca5-46d6-9ead-0a64e84c02a8)


## OUTPUT

![image](https://github.com/user-attachments/assets/a02ba297-c9ed-4947-95fb-5bc06fff95c9)

## RESULT
Thus the program has been successfully executed.


# Ex:6(d) 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## 🧠 ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.

---

## 💻 Program
Developed By: V Mythili
Reg No: 212223040123

![image](https://github.com/user-attachments/assets/cca09f97-010b-436e-bfff-9a5ba421b2f6)

## Output

![image](https://github.com/user-attachments/assets/36fa6a6c-32ae-45a6-8ef6-3b9def043dca)


## Result

Thus, the program has been successfully executed.


# Ex:6(d) 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## 🧠 ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.

---

## 💻 Program
Developed By: V Mythili
Reg No: 212223040123

![image](https://github.com/user-attachments/assets/cca09f97-010b-436e-bfff-9a5ba421b2f6)

## Output

![image](https://github.com/user-attachments/assets/36fa6a6c-32ae-45a6-8ef6-3b9def043dca)


## Result

Thus, the program has been successfully executed.
