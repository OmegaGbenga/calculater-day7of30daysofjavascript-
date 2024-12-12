# 30 Days of JavaScript - Day 6: Calculator Using JavaScript

This project is a simple calculator application built using HTML, CSS, and JavaScript as part of the **30 Days of JavaScript** challenge. The calculator allows basic arithmetic operations such as addition, subtraction, multiplication, and division.

---

## 🛠 Features
- **Addition** (`+`)
- **Subtraction** (`-`)
- **Multiplication** (`*`)
- **Division** (`/`)
- Clear input (`AC`)
- Delete last character (`DE`)
- Supports decimals (`.`)
- Evaluate result (`=`)

---

## 📂 Files
1. **index.html**: Contains the structure of the calculator.
2. **style.css**: Responsible for styling the calculator.
3. **script.js**: Includes JavaScript logic for dynamic functionality.

---

## 📜 JavaScript Properties Used
### 1. `onclick`
   - **Usage**: Triggering actions when buttons are clicked.
   - Example:
     ```html
     <input type="button" value="1" onclick="display.value += '1'">
     ```
   - Functionality: Appends the clicked button's value to the display.

### 2. `eval()`
   - **Usage**: Evaluates the mathematical expression from the input.
   - Example:
     ```html
     <input type="button" value="=" onclick="display.value=eval(display.value)">
     ```
   - Functionality: Calculates the result of the input expression.

### 3. `slice()`
   - **Usage**: Removes the last character from the display for the "DE" button.
   - Example:
     ```html
     <input type="button" value="DE" onclick="display.value = display.value.toString().slice(0, -1)">
     ```
   - Functionality: Deletes the last input character.

### 4. Dynamic Input Handling
   - Appending numbers and operators dynamically to the `display`:
     ```html
     onclick="display.value += '7'"
     ```

---

## 🚀 Getting Started
1. Clone this repository.
   ```bash
   git clone <repository-url>
