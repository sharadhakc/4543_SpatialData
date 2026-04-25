# 📝 Worksheet: 03 - Scalar Types and Control Flow

Use this worksheet to reinforce your understanding of variables, comparisons, and decision logic.

---

## 🧠 Section 1: Scalar Types

1. What is the output of the following code?

```python
x = 10
print(type(x))
```

`Answer:` _____<class 'int'>______________

2. What scalar type would best represent:
   - A person's name: __str_____
   - Their age: ___int____
   - Whether they passed a test: ___bool___

---

### ✏️ Task: Type Practice

```python
# Create a variable for each type and print its value and type
# Example: an int, float, str, and bool
num = 5
price = 9.99
name = "Alex"
is_valid = True

print(num, type(num))
print(price, type(price))
print(name, type(name))
print(is_valid, type(is_valid))
```

---

## 🔁 Section 2: Comparison Operators

3. What does the `!=` operator mean?

`Answer:` _______not equal________________

4. What will the following code print?

```python
a = 5
b = 3
print(a < b or b < 10)
```

`Answer:` _______True________________

---

## 🔀 Section 3: Control Flow

5. Write a conditional that prints "Pass" if a grade is >= 70, and "Fail" otherwise.

```python
# Your code:
if (grade >=70):
   print ("Pass")
else:
   print("Fail")
```

6. What does `elif` allow you to do?

`Answer:` check another condition if statemenr is not true.

---

### ✏️ Task: Your Turn

Write a program that asks for the weather and prints:
- "Bring sunscreen" if it's sunny
- "Take an umbrella" if it's raining
- "Check the forecast" otherwise

if weather=="sunny":
   print("Bring sunscreen")
elif weather=="raining":
   print("Take an umbrella")
else:
   print("Check the forcast")
