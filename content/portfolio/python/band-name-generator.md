---
title: "Band Name Generator"
date: 2025-04-26
categories:
  - Python
tags:
  - automation
  - fun
  - beginner
cover:
  image: "/images/band-name-generator.png"
  alt: "Band Name Generator"
draft: false
---

# 🎸 Band Name Generator

![Project Image](/images/band-name-generator.png)

**Description:**  
A fun little Python project that generates creative band names using your city and pet’s name!

---

## 🎮 Live Demo

<div class="project-demo-card">
  <h2>Try it out!</h2>
  <iframe src="https://trinket.io/embed/python/1b194acdf36e?outputOnly=true&runOption=run" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
  <p class="note">Note: This demo runs on an embedded Python environment.</p>
</div>

---

## ✨ Key Features:
- Takes user input for city and pet name
- Generates a cool band name in seconds!
- Great beginner-friendly project to practice using Python’s `input()` and string manipulation.

---

## 📚 What I Learned:
- Getting comfortable with Python’s `input()` and `print()` functions.
- Basic string concatenation.
- User interaction through the command line.

---

## 🚀 Future Improvements:
- Add more fun variations for band names.
- Integrate a random name generator for extra creativity.

---

## 🧩 Code Snippet:
```python
print("Hello and welcome to the Band Name Generator!")

city = input("What city did you grow up in?\n")
pet_name = input("What is the name of your pet?\n")

print("Your band name is " + city + " " + pet_name)

