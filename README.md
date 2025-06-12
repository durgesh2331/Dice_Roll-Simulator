🎲 Dice Roll Simulator
A simple and interactive web-based Dice Roll Simulator using HTML, CSS, and JavaScript. Every time you click the Roll Dice button, a random dice face is shown and a history of previous rolls is displayed below.

🧩 Features
🎲 Random dice face generation using Font Awesome icons

🖱️ Interactive "Roll Dice" button

📜 History log for all previous rolls

🖌️ Stylish and responsive user interface

📁 Project Structure
bash
Copy
Edit
.
├── index.html        # Main HTML file
├── style.css         # Styling for the Dice Simulator
└── script.js         # Logic for rolling dice and updating UI
🚀 How to Run
Clone or download the repository.

Make sure you are connected to the internet (Font Awesome is used via CDN).

Open index.html in any modern browser.

🔧 Dependencies
Font Awesome 6.5.0 (via CDN)

📸 UI Preview
lua
Copy
Edit
+-----------------------------+
|        Dice Roll Simulator |
|         🎲 (dice icon)     |
|         [Roll Dice]        |
|   -----------------------  |
|   Roll: 3   🎲             |
|   Roll: 6   🎲             |
|   Roll: 1   🎲             |
+-----------------------------+
📜 Code Overview
HTML (index.html)
A container that includes the title, dice display icon, roll button, and a roll history section (.card).

CSS (style.css)
Styles for layout, button appearance, icon sizing, and scrollable roll history.

JavaScript (script.js)
Listens for the button click.

Generates a random number from 1 to 6.

Updates the dice icon and appends a new entry in the roll history.

📌 To-Do / Enhancements (Optional)
Add clear history button.

Add animation or sound on roll.

Store roll history in localStorage.

Add stats: total rolls, average, frequency of each number.

🧑‍💻 Author
Made with 💙 using vanilla JS, HTML, and CSS.

