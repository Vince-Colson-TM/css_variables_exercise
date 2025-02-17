# CSS Variables Exercise 🎨

## Overview  
In this exercise, you will refactor a given CSS file by replacing hardcoded values with CSS variables. This will improve maintainability, flexibility, and scalability in your styles. You will also explore **CSS calculations**, **scope**, and **overriding variables**.  

---

## Instructions  

### 1️⃣ Setup  
1. Clone this repository:  
   ```sh
   git clone https://github.com/Vince-Colson-TM/css_variables_exercise.git
   ```
2. Open `index.html` in a browser.  
3. Open `styles.css` and start refactoring by following the next steps.  

---

### 2️⃣ Refactor with CSS Variables  
- Identify **repeated values** in `styles.css` (e.g., colors, font sizes, paddings).  
- Define these values as **CSS variables** inside `:root`.  
- Replace all hardcoded values in the CSS with `var(--your-variable-name)`.  

✅ **What to do?**  
- Replace at least **colors, font sizes, and border radii** with variables.  
- Ensure all elements still look the same after refactoring.  

---

### 3️⃣ Use Calculations with Variables (`calc()`)  
- Make the **card’s width and padding adjustable** by using `calc()` with variables.  
- Ensure the card layout remains **visually balanced**.  

✅ **What to do?**  
- Define **base padding and width** variables.  
- Use `calc()` to adjust the padding and width dynamically.  

---

### 4️⃣ Make the Layout Responsive  
- Modify the card’s width and padding for **different screen sizes** using **media queries**.  
- Ensure the design remains **clear and readable** on mobile and desktop.  

✅ **What to do?**  
- Use `@media` queries to adjust the card size for smaller screens.  
- Avoid using fixed pixel values—**use variables where possible**.  

---

### 5️⃣ Override Variables for a Second Card  
- Add a **second card** (`.card-secondary`) that has different colors from the first card.  
- Instead of defining new styles, **override CSS variables**.  

✅ **What to do?**  
- Create a `.card-secondary` class.  
- Override at least **background color and text color** using CSS variables.  

---

## 🎯 Extra Challenge (Optional)  
Experiment with CSS variables even more, and see what is possible and useful.


---

## ✅ Learning Outcomes  
By completing this exercise, you will:  
✔ Understand **how to declare and use CSS variables**.  
✔ Learn **how to modify values dynamically** with `calc()`.  
✔ Improve maintainability with **global and scoped variables**.  
✔ Implement **responsive designs using variables**.  
✔ Override variables to **create multiple themes/styles**.  
