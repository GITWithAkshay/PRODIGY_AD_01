# 🔢 Scientific Calculator (Tkinter + CustomTkinter)
A modern, responsive, and theme-switchable scientific calculator built with Python’s `customtkinter` library. Supports basic arithmetic and scientific operations with a clean GUI and light/dark mode toggle.

## ✨ Features
* ✅ Basic arithmetic operations (`+`, `-`, `*`, `/`)
* 🧮 Scientific functions (`√`, `log`, `exp`, `^`)
* 🌙 Light/Dark theme toggle
* 🔄 Delete (`DEL`) and Clear (`C`) functionality
* 📱 Responsive UI layout using `grid` system
* 🎯 Keyboard-free usage with clickable buttons

## 📸 Screenshot
![image alt](https://github.com/GITWithAkshay/PRODIGY_AD_01/blob/3e5e5b17f62ad0d40047ae1d8d59f430c16952f3/Screenshot%20(182).png)

## 🚀 Getting Started

### Prerequisites
Make sure you have **Python 3.7+** installed.
You will also need to install:
```bash
pip install customtkinter
```

### Running the App
```bash
python calculator.py
```

## 🛠️ Code Overview
* `Calculator` class inherits from `ctk.CTk` and sets up the full GUI.
* `_create_widgets` sets up the buttons, display, and theme toggle.
* `_on_button_click` handles button logic and display.
* `_evaluate` safely parses and evaluates mathematical expressions using the `math` module.

## 📦 Technologies Used
* **Python 3**
* **CustomTkinter** – modern UI toolkit based on `tkinter`
* **math** module – for scientific computations

## ⚠️ Security Note
This app uses Python’s `eval()` in a controlled environment for expression evaluation. It restricts access to built-in functions by limiting the globals and locals dictionary:

```python
eval(expr, {"math": math, "__builtins__": {}})
```

Still, it is **not safe** for untrusted input. Use with caution.

## 📄 License
MIT License – feel free to use, modify, and distribute.
