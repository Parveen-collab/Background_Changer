==============================
Background Changer - README.txt
==============================

📁 Project Title:
-----------------
Background Changer

📝 Description:
---------------
This is a simple HTML, CSS, and JavaScript-based mini project that allows users to dynamically change the background color of a webpage. Users can choose between four predefined color options—White, Aqua, Violet, and Black—by clicking on small circular buttons. When the background color changes, the text color of the heading and paragraph automatically adjusts to ensure readability (e.g., white text on black background).

This project is useful for beginners learning how to manipulate the DOM, use event handling, apply CSS styling dynamically, and create interactive interfaces with vanilla JavaScript.

🎯 How It Works:
----------------
- The color buttons are represented as small circular `<span>` elements styled using CSS.
- When a button is clicked, the `changeBG(color)` function is triggered.
- This function changes the background color of the page using `document.body.style.backgroundColor`.
- It also adjusts the color of text (class `"text"`) to either black or white based on the background to ensure good contrast and readability.

📚 Concepts Used:
-----------------
1. HTML Structure:
   - `<!DOCTYPE html>` for HTML5 declaration
   - Semantic tags: `<head>`, `<body>`, `<h1>`, `<p>`, `<img>`, `<div>`, `<span>`
   - Inline `onclick` handlers

2. CSS Styling:
   - Layout with `margin`, `padding`, `text-align`
   - Custom buttons using `width`, `height`, `border-radius`, and `background-color`
   - Element styling (`body`, `h1`, `p`, `img`, `.btn`)
   - ID selectors (`#white`, `#aqua`, etc.) for unique color buttons

3. JavaScript Functionality:
   - DOM Manipulation with `document.getElementsByClassName`
   - Inline event handling (`onclick`)
   - Style modification using `.style.backgroundColor` and `.style.color`
   - Conditional logic to change text color based on background

🛠️ Suggested Improvements:
---------------------------
1. Use `addEventListener()` instead of inline `onclick` for better structure and separation of concerns.
2. Add tooltips (`title`) or ARIA labels for accessibility so users can know what each button does.
3. Implement smooth transitions using CSS (`transition`) to improve UI feel when switching colors.
4. Use color brightness calculation to automatically set text color for any background color, not just black.
5. Make layout responsive for smaller screens using media queries.
6. Add more background options or allow users to pick custom colors via a color picker.
7. Improve UI by adding hover effects to buttons.

👨‍💻 Author:
------------
Parveen Kumar

📅 Date:
---------
July 2025
