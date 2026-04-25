# 📝 Worksheet: 04 - Loops and Iteration

Practice and reflect on how loops work in Python.

---

## 🔁 Section 1: For Loops

1. What does `range(5)` produce?

`Answer:` __number from 0 to 4________________

2. Write a `for` loop that prints numbers 1 to 10, but skips 5.

```python
for i in range(1, 11):
    if i == 5:
        continue
    print(i)
```

---

## 🔁 Section 2: While Loops

3. What’s the difference between a `for` loop and a `while` loop?

`Answer:` ____for loop runs for a set number for time while loop runs as long as the condition is True_

4. What happens if a `while` loop's condition never becomes `False`?

`Answer:` _________we get a infinite loop__________________________________

---

### ✏️ Task: Countdown with While

```python
# Use a while loop to count down from 5 to 1.
n=5
while n>0:
    print(n)
    n=n-1
```

---

## 📁 Section 3: File Reading and `with`

5. What does the `with` statement do when opening a file?

`Answer:` ___it automatically opens and closes the file safely.________________________________________

6. How do you loop over each line in a file?

`Answer:` _____________for line in file:______________________________

---

### ✏️ Task: File Filter

Write code that prints only the lines in a file that contain the word `"error"`.

```python
if "error" in line.lower():
```

