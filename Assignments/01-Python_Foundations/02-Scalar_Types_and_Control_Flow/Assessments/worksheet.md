# 📝 Worksheet: 03 - Scalar Types and Control Flow

Use this worksheet to reinforce your understanding of variables, comparisons, and decision logic.

---

## 🧠 Section 1: Scalar Types

1. What is the output of the following code?

```python
x = 10
print(type(x))
```

`Answer:` <class 'int'>_______________________

2. What scalar type would best represent:
   - A person's name: _str______
   - Their age: _int______
   - Whether they passed a test: _bool______

---

### ✏️ Task: Type Practice

```python
age = 24
height = 5.7
c = "Manoj"
d = True

print(a, type(a))
print(b, type(b))
print(c, type(c))
print(d, type(d))

```

---

## 🔁 Section 2: Comparison Operators

3. What does the `!=` operator mean?

`Answer:` _not equal to______________________

4. What will the following code print?

```python
a = 5
b = 3
print(a < b or b < 10)
```

`Answer:` _True______________________

---

## 🔀 Section 3: Control Flow

5. Write a conditional that prints "Pass" if a grade is >= 70, and "Fail" otherwise.

```python

if grade >= 70:
    print("Pass")
else:
    print("Fail")

```

6. What does `elif` allow you to do?

`Answer:` it allows us to check multiple conditions after an if statement_______________________

---

### ✏️ Task: Your Turn

Write a program that asks for the weather and prints:
- "Bring sunscreen" if it's sunny
- "Take an umbrella" if it's raining
- "Check the forecast" otherwise

```python
weather = input("Enter weather: ")
if weather == "sunny":
    print("Bring sunscreen")
elif weather == "raining":
    print("Take an umbrella")
else:
    print("Check the forecast")
```