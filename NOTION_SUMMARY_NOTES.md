# #DAY 19 — FOR LOOPS IN PYTHON

---

## 1. Introduction to Loops

Sometimes we need to repeat a task multiple times in a program.

Instead of writing the same code again and again, we use **loops**.

A **loop** allows a block of code to run repeatedly until a condition or sequence ends.

Real-world example:

- Printing numbers from 1 to 10
- Displaying items in a list
- Processing each character of a word

---

## 2. Types of Loops:

1. For Loops
2. While Loops

---

## 3. What is a `for` Loop?

A **for loop** is used to iterate over a sequence like:

- strings
- lists
- tuples
- ranges

### Basic syntax:

```python
for variable in sequence:
	code
```

---

## 4. Looping Through a String

```python
word="Python"

for letter in word:
	print(letter)
```

Output:

```python
P
y
t
h
o
n
```

The loop prints **each character** one by one.

---

## 6. Loop with List

```python
fruits= ["apple","banana","mango"]

for fruit in fruits:
	print(fruit)
```

Output:

```python
apple
banana
mango
```

---

## 7. Using `range()` in For Loop

`range()` generates a sequence of numbers.

```python
for i in range(1,6):
	print(i)
```

Output:

```
1
2
3
4
5
```

Here:

- start = 1
- end = 6 (not included)

---

## 8. Simple Example

```python
for i in range(5):
	print(i)
```

Output:

```
0
1
2
3
4
```

The loop runs **5 times**.

---

## 9. Quick Quiz:-

```python
for i in range(1,10,2):
	print(i)
```

Output:

```
1
3
5
7
9
```

Here the loop increases by **2 each time**.

---

## 8. Important Points

- `for` loop repeats code for each item in a sequence.
- `range()` is commonly used with loops.
- Loop stops automatically when sequence ends.
- Indentation is important in loops.

---

# 📝 SUMMARY — FOR LOOPS

- Used for repetition
- Works with sequences
- Often used with `range()`
- Runs until sequence finishes

---

## One-Line Concept

> A `for` loop is used to iterate through a sequence and execute a block of code multiple times.
>
