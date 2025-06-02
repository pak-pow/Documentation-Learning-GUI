# Learning Kivy

This folder contains all my notes, examples, and progress files as I learn **Kivy**, a Python framework for building cross‐platform GUI applications. My goal is to develop small, practical apps that can later be adapted for real‐world projects.

---

## 📂 Contents

```
learning_kivy/
├── README.md
└── learning_kivy_day1.pdf
```

- **learning_kivy_day1.pdf**  
  Day 1 notes: installation steps, basic widget demos, and first “Hello, Kivy!” app.  
  (Open with any PDF reader.)

---

## 🎯 Goals

1. **Understand Kivy fundamentals**  
   - Widgets, layouts, properties, and events.
2. **Build simple demo apps**  
   - Learn how to structure a Kivy project with `.py` files and `.kv` files.
3. **Document every step**  
   - Keep a running log (PDFs, code snippets, screenshots) so I can refer back later.
4. **Apply to real projects**  
   - Once comfortable, adapt Kivy code into small utilities for my other Python projects.

---

## ⚙️ Prerequisites

Before diving in, make sure you have:

1. **Python 3.7+** installed.  
2. **Kivy** installed (recommend using a virtual environment). To install Kivy:

   ```
   python3 -m venv kivy_env
   source kivy_env/bin/activate    # (macOS/Linux)
   # or
   kivy_env\Scripts\activate.bat   # (Windows)

   pip install --upgrade pip setuptools
   pip install kivy
   ```

3. **A PDF reader** (to view the day-by-day notes).

---

## 📖 Day 1: learning_kivy_day1.pdf

**Topics covered:**

- Installing Kivy in a virtual environment  
- Writing a minimal `main.py` that launches a Kivy window  
- Using basic Widgets (Label, Button, BoxLayout)  
- Introduction to `.kv` language for separating UI from Python logic

**How to view:**

- Open `learning_kivy_day1.pdf` in your favorite PDF viewer.  
- Follow the step-by-step annotated screenshots and code blocks.

---

## 📖 **Day 2: learning_kivy_day#2.pdf**  

**Topics covered:**

- Deeper understanding of the `.kv` language and its role in separating UI from logic  
- Creating a clean form layout using nested `GridLayout`s  
- Connecting UI elements (`Button`, `TextInput`) from the `.kv` file to Python functions  
- Exploring widget properties like `id`, `text`, and `multiline`

**Highlights:**

- Successfully created a simple input form with fields for Name, Age, and Email  
- Linked the **Submit** button to a Python method using `on_press`  
- Realized how straightforward and fun it is to connect design to functionality in Kivy

**How to view:**

- Open `learning_kivy_day#2.pdf` in your favorite PDF reader  
- See layout structure, code examples, and notes on `.kv` file behavior and UI wiring


---

## 🔗 Useful Resources

- **Official Kivy Documentation**:  
  https://kivy.org/doc/stable/

- **Kivy Tutorial Python(YouTube)**:  
  https://youtube.com/playlist?list=PLzMcBGfZo4-kSJVMyYeOQ8CXJ3z1k7gHn&si=FgD06NPezieoPK1U

- **Kivy GitHub Examples**:  
  https://github.com/kivy/kivy/tree/master/examples

---

## 🤔 Feedback / Questions

If you have pointers on better structuring a Kivy project or suggestions for must-learn Kivy topics, let me know by opening an issue or dropping a comment. I’m always looking to improve my approach!

Keep tracking, keep building, and happy coding!  
– Vee
