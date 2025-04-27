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
summary: "Generate fun band names based on your city and pet’s name!"
draft: false
---

# 🎸 Band Name Generator

<div class="project-badge hx-inline-block hx-mb-6 hx-px-4 hx-py-1.5 hx-bg-blue-500 dark:hx-bg-blue-400 hx-text-white hx-text-sm hx-font-bold hx-rounded-full hx-shadow-md">
  Beginner Project
</div>

<div class="project-thumbnail hx-mx-auto hx-my-8 hx-w-72">
  <img src="/images/band-name-generator.png" alt="Band Name Generator" class="hx-rounded-lg hx-shadow-lg hx-w-full hx-h-auto">
</div>

**Description:**  
A fun little Python project that generates creative band names using your city and pet’s name!

---

## 🎮 Live Demo

<div class="live-demo-card hx-bg-gray-100 dark:hx-bg-neutral-800 hx-rounded-xl hx-p-6 hx-shadow-lg hx-max-w-4xl hx-mx-auto hx-my-10">
  <h2 class="hx-text-xl hx-font-bold hx-text-center hx-mb-6">🎮 Try It Out!</h2>
  <iframe src="https://trinket.io/embed/python/1b194acdf36e?outputOnly=true&runOption=run" class="hx-w-full hx-h-[600px] hx-rounded-lg"></iframe>
  <p class="hx-text-center hx-text-sm hx-text-gray-600 dark:hx-text-gray-400 hx-mt-4">Note: This demo runs inside an embedded Python environment.</p>
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

