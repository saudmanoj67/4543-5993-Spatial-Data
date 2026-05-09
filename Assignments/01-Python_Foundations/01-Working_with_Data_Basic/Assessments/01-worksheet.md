# 📝 Worksheet: 02 - Working with Data

Use this worksheet to review and reinforce your understanding of Python data containers.

---

## 🧠 Section 1: Lists

1. What method adds an item to the end of a list?  
   `Answer:` append()____________________________

2. How can you remove an item from a list by value?  
   `Answer:` remove()____________________________

3. What’s the result of this code?

```python
nums = [2, 4, 6]
nums.append(8)
print(nums)
```

   `Answer:` [2,4,6,8]___________________________

---

### ✏️ Task: List Practice

```python
# Create a list of your top 3 favorite foods.
# Add another food to the list.
# Remove one item and print the list.
```
    foods = ["pizza", "momo", "burger"]
    foods.append("pasta")
    foods.remove("burger")
    print(foods)

    output: ["pizza", "momo", "pasta"]

---

## 🔒 Section 2: Tuples

4. What is a key difference between a list and a tuple?  
   `Answer:` Lists are mutable but tuples are immutable____________________________

5. Can you change the contents of a tuple once it is created? Why or why not?  
   `Answer:` Since tuples are immutable so they cannot be changed after creation.____________________________

---

### ✏️ Task: Tuple Practice

```python
# Create a tuple with your favorite 3 numbers.
# Unpack it into three variables and print each.
```
    nums = (10, 20, 30)
    a, b, c = nums
    print(a)
    print(b)
    print(c)

    output: 
            10
            20
            30

---

## 🔑 Section 3: Dictionaries

6. What does the `.get()` method do differently from accessing a key directly?  
   `Answer:` if the key doesn't exit, instead of causing an error it returns as none.____________________________

7. How do you loop through both keys and values in a dictionary?  
   `Answer:` by using loop with .items()____________________________

---

### ✏️ Task: Dictionary Practice

```python
# Create a dictionary with keys: 'name', 'age', and 'hobby'.
# Print each key and value in the format "key: value".
```
    person= {
        "name": "Manoj",
        "age": 21,
        "hobby": "pool"
    }
    for key, value in person.items():
        print(f"{key}: {value}")

    output: 
        name: Manoj
        age: 21
        hobby: pool

---

## 🧾 Submit Checklist

- [X] I practiced creating and modifying lists.
- [X] I understand how tuples are different from lists.
- [X] I accessed and looped through dictionary items.
