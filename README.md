# 🏛️ fcc-Telephone Number Validator US(🌐 version)

🔗 **Live Website**: ()

> ✨ *In this project, I made some custom modifications to the original instructions to achieve a design that reflects my personal style and preferences.*

---

## 🎯 Project Objective

The goal of this project is to build a **Telephone Number Validator US** page as part of the **JavaScript Algorithms And Data Structures** curriculum on [freeCodeCamp](https://www.freecodecamp.org/).

> 💡 Inspired by:  
[Telephone Number Validator US](https://telephone-number-validator.freecodecamp.rocks/)  
⚠️ *Do not copy the demo project directly.*

---

## 📌 Project Requirements

- [x] You should have an input element with `"user-input"`
- [x] You should have an button element with `"check-btn"`
- [x] You should have an button element with `"clear-btn"`
- [x] You should have a `<div>`, `<span>` or `<p>` element with `"clear-btn"`
- [x] When you click on the `#check-btn` element without entering a value into the `#user-input` element, an alert should appear with the text `"Please provide a phone number"`
- [x] When you click on the `#clear-btn` element, the content within the `#results-div` element should be removed.
- [x] When the `#user-input` element contains a valid US number and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Valid US number:` " followed by the number.
- [x] When the `#user-input` element contains an invalid US number and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Invalid US number: "` followed by the number.

> ⚠️ **Important**: Be sure to include these lines in your HTML to link your files:  
> `<link rel="stylesheet" href="style.css">`  
> `<script src="script.js"></script>`

---

## ✅ Project Tests (User Stories)

1. Alert appears if input is empty
2. Valid US phone numbers are recognized and displayed correctly
3. Invalid US phone numbers are recognized and displayed correctly
4. Clear button removes displayed results

**✅ Valid US Number Examples**

Standard size :

- [x] 123-456-7890
- [x] (123) 456-7890
- [x] 123.456.7890
- [x] 123 456 7890
- [x] (123)456-7890

International format with US dialing code (+1 or 00-1) :

- [x] +1 123-456-7890
- [x] +1 (123) 456-7890
- [x] +1 123.456.7890
- [x] +1 123 456 7890
- [x] 00-1-123-456-7890
- [x] 00 1 123 456 7890

**❌ Invalid US Number Examples**

Other indicators than the US states (+33, +44, etc.) :

- [x] +33 1 44 78 22 33 (France)
- [x] +44 20 7946 0958 (United Kingdom)

Numbers with incorrect format :

- [x] 12345-67890
- [x] +1-123-45-67890

Numbers without area code and without the 10 mandatory digits :

- [x] 456-7890
- [x] 7890

Numbers with invalid non-numeric or special characters :

- [x] 123-ABC-7890
- [x] +1 123-456-78AB

---

## 🖼️ Project Context

This is one of the required projects to earn the **JavaScript Algorithms And Data Structures** certification from freeCodeCamp.  
Through this project, I practiced:

- Regular expression (Regex) pattern matching for phone number validation
- DOM interaction using Vanilla JavaScript
- Building a user-friendly, responsive interface
- Implementing clear UI feedback for users

---

## 📫 Contact

- GitHub: [@kroxii](https://github.com/kroxii)   
- Email: [remii.leon@gmail.com](mailto:remii.leon@gmail.com)

---

⭐ *Thanks for checking out this project! Feel free to leave a star if you found it helpful or inspiring.*
