# 🔢 Scientific Calculator (Tkinter + CustomTkinter)
A modern, responsive, and theme-switchable scientific calculator built with Python’s `customtkinter` library. Supports basic arithmetic and scientific operations with a clean GUI and light/dark mode toggle.

## 🔗 Clone the Repository

```bash
git clone https://github.com/your-username/scientific-calculator-app.git
cd scientific-calculator-app
```

## ✨ Features
* ✅ Basic arithmetic operations (`+`, `-`, `*`, `/`)
* 🧮 Scientific functions (`√`, `log`, `exp`, `^`)
* 🌙 Light/Dark theme toggle
* 🔄 Delete (`DEL`) and Clear (`C`) functionality
* 📱 Responsive UI layout using `grid` system
* 🎯 Keyboard-free usage with clickable buttons

## 📸 Screenshot
![image alt](https://github.com/GITWithAkshay/PRODIGY_AD_01/blob/3e5e5b17f62ad0d40047ae1d8d59f430c16952f3/Screenshot%20(182).png)
![image alt](https://github.com/GITWithAkshay/PRODIGY_AD_01/blob/79ce2bdbffa61317863086e6d084da2659437a9b/Screenshot%20(180).png)

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

---

## 🙏 Acknowledgements

This project leverages the power of several open-source technologies and communities. Heartfelt thanks to:

* [**Tom Schimansky**](https://github.com/TomSchimansky) for the brilliant [**CustomTkinter**](https://github.com/TomSchimansky/CustomTkinter) library which gives Tkinter a beautiful, modern UI.
* [**Python Software Foundation**](https://www.python.org/psf/) for building and maintaining Python – the backbone of this application.
* Stack Overflow, GitHub, and open-source contributors for continual guidance, fixes, and inspiration.
* [**Math Module Documentation**](https://docs.python.org/3/library/math.html) for mathematical function references used in the calculator engine.

> This project is created for educational and productivity purposes. You're welcome to use, modify, and distribute it under the terms of the MIT license.


## 📄 License
Feel free to use, modify, and distribute.
