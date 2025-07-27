# 🧮 JavaScript Age Calculator

A simple and beautiful web-based Age Calculator built with **HTML**, **CSS**, and **JavaScript**. The user can select their birth date, and the tool will calculate their exact age in **years**, **months**, and **days**.

---

## 📌 Features

- Live age calculation based on user’s birth date  
- Easy-to-use interface  
- Clean and modern UI with responsive design  
- Restricts users from selecting future dates

---

## 🚀 Technologies Used

- HTML5  
- CSS3  
- JavaScript (Vanilla JS)

---

## 💻 How to Run

1. Clone this repository or download the ZIP  
2. Open the `index.html` file in any modern web browser  
3. Select your birth date and click **Calculate**  
4. See your exact age displayed below the input

---

## 🔧 How it Works

- The user selects a **date** using the date input.
- JavaScript calculates the **difference** between the current date and the birth date.
- The result is displayed dynamically without refreshing the page.

---

## 🛡️ Validations

- Users cannot select a future date thanks to:
  ```js
  userInput.max = new Date().toISOString().split("T")[0];

