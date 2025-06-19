 🔢 Web Calculator App

This is a simple, elegant calculator built using **HTML**, **CSS**, and **JavaScript**. It performs basic arithmetic operations—addition, subtraction, multiplication, and division—with a modern and responsive design.

---
🚀 Features

- Basic arithmetic: `+`, `-`, `*`, `/`
- Supports decimal inputs
- Clear all (`C`) and delete last entry (`DEL`)
- Responsive layout using **CSS Grid**
- Stylish hover and active effects

---

 🧠 How It Works

 HTML (`index.html`)
- Lays out the calculator interface using a combination of `<input>` and `<button>` elements.
- Buttons are linked to JavaScript functions using `onclick` attributes.

🎨 CSS (`styles.css`)
- Applies a modern dark theme.
- Uses **Flexbox** to center the calculator on screen.
- Organizes buttons in a **4-column grid**.
- Adds hover and press animations for better UX.

🧮 JavaScript (`script.js`)
Contains all calculator logic:

 `appendToDisplay(value)`
- Adds a number/operator to the display.

 `clearDisplay()`
- Clears the entire display.

 `deleteLast()`
- Deletes the last entered character.

 `calculateResult()`
- Evaluates the expression using `eval()` (with `try/catch` for error handling).

---

