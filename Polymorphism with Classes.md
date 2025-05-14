# Ex:6(e) 🐍 Python OOP: Polymorphism with Classes

## 🎯 AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.

---

## 🧠 ALGORITHM

1. **Create Class `Beans`**:
   - Define `type()` method that prints `"Vegetable"`.
   - Define `color()` method that prints `"Green"`.

2. **Create Class `Mango`**:
   - Define `type()` method that prints `"Fruit"`.
   - Define `color()` method that prints `"Yellow"`.

3. **Define Generic Function `func(obj)`**:
   - Call `obj.type()` and `obj.color()` — this works with both `Beans` and `Mango` objects, showcasing **polymorphism**.

4. **Create Objects**:
   - Instantiate `Beans` and `Mango`.
   - Pass them to `func()` and execute the program.

---

## 💻 Program
Developed By: V Mythili
Reg No: 212223040123

```
class Beans ():
    def type(self):
        print("Vegetable")
    def color(self):
        print("Green")
class Mango ():
    def type(self):
        print("Fruit")
    def color(self):
         print("Yellow")
    def func(obj):
        obj.type()
        obj.color()
obj_beans = Beans()
obj_mango = Mango()
func(obj_beans)
func(obj_mango)

```

## Output

![image](https://github.com/user-attachments/assets/d7421fa0-9a5b-4409-b13a-1c12f4e053fb)

## Result

Thus, the program has been successfully executed.
