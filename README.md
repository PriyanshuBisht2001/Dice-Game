# 🎲 Dicee Game

A simple **two-player dice game** built using **HTML, CSS, and JavaScript**.
Each time the page refreshes, both players roll a dice randomly and the player with the **higher number wins**.

This project demonstrates **DOM manipulation, random number generation, and dynamic UI updates using JavaScript.**

---

## 🚀 Live Demo

You can play the game here:

```
(Add your GitHub Pages link here)
Example:
https://username.github.io/dicee-game/
```

---

## 📸 Preview

<img width="600" alt="Dice Game Screenshot" src="your-screenshot-link-here">

---

## 🧠 How the Game Works

1. When the page loads, JavaScript generates **two random numbers (1-6)**.
2. Each number represents a **dice roll for a player**.
3. The dice images update dynamically.
4. The game compares both numbers and displays the **winner**.

Example logic:

```javascript
if (randomNumber1 > randomNumber2) {
  document.querySelector("h1").innerHTML = "Player 1 Won";
} else if (randomNumber1 < randomNumber2) {
  document.querySelector("h1").innerHTML = "Player 2 Won";
} else {
  document.querySelector("h1").innerHTML = "Draw";
}
```

---

## 🛠️ Technologies Used

* **HTML5** – Structure of the webpage
* **CSS3** – Styling and layout
* **JavaScript (Vanilla JS)** – Game logic and DOM manipulation

---

## 📂 Project Structure

```
dicee-game
│
├── dicee.html
├── styles.css
├── index.js
└── images
    ├── dice1.png
    ├── dice2.png
    ├── dice3.png
    ├── dice4.png
    ├── dice5.png
    └── dice6.png
```

---

## 🎮 How to Run the Project

1. Clone the repository

```
git clone https://github.com/yourusername/dicee-game.git
```

2. Open the project folder

3. Run the file

```
dicee.html
```

4. Refresh the page to roll the dice 🎲

---

## 💡 Future Improvements

Some ideas to improve the project:

* 🎲 Add a **Roll Dice button**
* ✨ Add **dice roll animation**
* 🔊 Add **sound effects**
* 📊 Add **scoreboard**
* 🌐 Convert it into **multiplayer online game**

---

## 👨‍💻 Author

**Priyanshu Bisht**

* GitHub: https://github.com/yourusername

---

⭐ If you like this project, consider **starring the repository**!
