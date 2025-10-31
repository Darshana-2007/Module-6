# 🐟 Method Overriding-Fish and Shark Class Inheritance in Python

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
class Fish:<br>
       def type(self):<br>
           print("fish")<br>
class Shark(Fish):<br>
    def type(self):<br>
        print("shark")<br>
f=Fish()<br>
f.type()<br>
s=Shark()<br>
s.type()
## OUTPUT
<img width="346" height="154" alt="image" src="https://github.com/user-attachments/assets/92f16c8a-8fb4-4cbd-b0d6-3801c2a8cfd2" />

## RESULT
Thus,the program excuted successfully.
