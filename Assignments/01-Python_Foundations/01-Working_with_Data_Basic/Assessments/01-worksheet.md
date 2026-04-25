# 📝 Worksheet: 02 - Working with Data

Use this worksheet to review and reinforce your understanding of Python data containers.

---

## 🧠 Section 1: Lists

1. What method adds an item to the end of a list?  
   `Answer:` _______append()_____________________

2. How can you remove an item from a list by value?  
   `Answer:` __________remove()__________________

3. What’s the result of this code?

```python
nums = [2, 4, 6]
nums.append(8)
print(nums)
```

   `Answer:` ____________[2, 4, 6, 8]________________

---

### ✏️ Task: List Practice

```python
# Create a list of your top 3 favorite foods.
# Add another food to the list.
# Remove one item and print the list.
```
foods= ["dumplings", "pizza", "chowmein"]
foods.append("pasta")
foods.remove("pizza")
print(foods)
---

## 🔒 Section 2: Tuples

4. What is a key difference between a list and a tuple?  
   `Answer:` Tuples are immutable meaning they cannot be changed unlike lists that are mutable.

5. Can you change the contents of a tuple once it is created? Why or why not?  
   `Answer:` Nope, tuples are immutable so their contents cannot be changed once they are created.

---

### ✏️ Task: Tuple Practice

```python
# Create a tuple with your favorite 3 numbers.
# Unpack it into three variables and print each.
```
nums=(13,27,43)
a,b,c = nums
print(a, b, c)
---

## 🔑 Section 3: Dictionaries

6. What does the `.get()` method do differently from accessing a key directly?  
   `Answer:` .get() is used to access the value for the given key, and it gives a None instead of raising an error if the key doesnt exist.

7. How do you loop through both keys and values in a dictionary?  
   `Answer:` To loop through both the keys and values in a dict we use 
      for key, value in dict.items():

---

### ✏️ Task: Dictionary Practice

```python
# Create a dictionary with keys: 'name', 'age', and 'hobby'.
# Print each key and value in the format "key: value".
```
info={
   "name":"Sharadha",
   "age": 23,
   "hobby": "goofing around"}
for key, value in info.items():
   print(f"{key}: {value}")
---

## 🧾 Submit Checklist

- [*] I practiced creating and modifying lists.
- [*] I understand how tuples are different from lists.
- [*] I accessed and looped through dictionary items.
