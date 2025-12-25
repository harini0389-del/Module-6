# 🐍 Python OOP: Operator Overloading (Less Than `<`)

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

<img width="548" height="302" alt="image" src="https://github.com/user-attachments/assets/fb3f50f7-002a-4e6c-be6f-6395cb03791b" />

## Output

<img width="682" height="176" alt="image" src="https://github.com/user-attachments/assets/d394ee6e-5da7-411c-b3a7-917900f89434" />

## Result
Thus,the program is executed successfully.
