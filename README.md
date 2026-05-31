# Python String Methods Practice

## Project Overview

This project contains hands-on practice of Python String Methods and basic string operations. The purpose of this project is to understand how strings are manipulated, cleaned, searched, and analyzed using built-in Python functions.

These concepts are important for Data Science because real-world data often contains text that needs cleaning and preprocessing before analysis.

---

## Topics Covered

### Basic String Operations

* User Input
* String Length using `len()`
* String Indexing

### String Methods

* `strip()`
* `split()`
* `upper()`
* `lower()`
* `count()`
* `startswith()`
* `endswith()`
* `find()`
* `replace()`

### Mini Programs

* Vowel Counter
* Word Finder
* Word Replacer

---

## Examples

### Remove Extra Spaces

```python
text = "     Hello World!     "
print(text.strip())
```

Output:

```text
Hello World!
```

---

### Count Characters

```python
name = "i love mumbai"
print(len(name))
```

Output:

```text
13
```

---

### Convert String to List

```python
name.split()
```

Output:

```python
['i', 'love', 'mumbai']
```

---

### Convert to Uppercase

```python
name.upper()
```

Output:

```text
I LOVE MUMBAI
```

---

### Count Spaces

```python
name.count(" ")
```

Output:

```text
2
```

---

### Vowel Counter

```python
count = 0

for char in name.lower():
    if char in "aeiou":
        count += 1

print(count)
```

Output:

```text
4
```

---

### Find a Word

```python
sentence = "i love data science"

word = "data"

print(sentence.find(word))
```

Output:

```text
7
```

---

### Replace a Word

```python
sentence = "I love Mumbai"

print(sentence.replace("Mumbai", "Pune"))
```

Output:

```text
I love Pune
```

---

## Learning Outcomes

Through this project, I learned:

* How strings are stored and manipulated in Python
* How to clean text using `strip()`
* How to split text into words
* How to search for words using `find()`
* How to replace words using `replace()`
* How to count vowels in a sentence
* How string methods are useful in data preprocessing

---

## Data Science Relevance

String processing is an important part of:

* Data Cleaning
* Text Analytics
* Natural Language Processing (NLP)
* Sentiment Analysis
* Data Preprocessing

These skills are commonly used before applying Machine Learning algorithms.

---

## Future Improvements

* Build a complete Text Analyzer
* Add Word Frequency Counter
* Add Sentence Statistics
* Save analysis results to a file
* Create a menu-driven version

---

## Author

Created as part of my Data Science Learning Journey.

Day 6 – Python Strings and String Methods
