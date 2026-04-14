# 🧮 Basic Calculator (Java Swing)

## 📌 Description

This is a simple **GUI-based calculator application** built using Java Swing in NetBeans. It performs basic arithmetic operations with an interactive interface designed using drag-and-drop (JFrame Form).

---

## 🚀 Features

* ➕ Addition
* ➖ Subtraction
* ✖️ Multiplication
* ➗ Division
* 📊 Percentage calculation
* 🔢 Decimal input support
* 🧹 Clear/Reset button
* 🖱️ Button-based user input

---

## 🛠️ Tech Stack

* Language: Java
* GUI Framework: Java Swing
* IDE: NetBeans

---

## 📂 Project Structure

```bash
BasicCalculator/
│── src/
│   ├── CalculatorUI.java
│   ├── CalculatorUI.form
│
│── nbproject/        # NetBeans configuration files
│── build/            # Compiled classes
│── manifest.mf
│── build.xml
│── README.md
```

---

## ▶️ How to Run

### 🔧 Option 1: Using NetBeans (Recommended)

1. Open NetBeans
2. Click **File → Open Project**
3. Select the `BasicCalculator` folder
4. Click **Run ▶️**

---

### 💻 Option 2: Using Terminal

```bash
javac src/CalculatorUI.java
java CalculatorUI
```

*(Make sure you're inside the project directory and Java is installed)*

---

## 💡 How It Works

* User inputs numbers via buttons
* The selected operator is stored
* When `=` is pressed:

  * The calculation is performed using stored values
  * Result is displayed in the text field

---

## 🧠 Code Highlights

* Uses **JFrame** for GUI window
* Event-driven programming (button click handlers)
* Stores:

  * `num1` → first number
  * `num2` → second number
  * `operator` → selected operation

---



## 👤 Author

**Emauel M. Makgura**

---

## ⭐ Future Improvements

* History of calculations
* Dark/light theme toggle
* Convert into a desktop app installer

---

## 📜 License

This project is for educational purposes.
