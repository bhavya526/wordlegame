# 📝 Wordle Clone 

A dynamic, web-based Wordle clone where players guess a hidden **5-letter verb** retrieved in real-time from an external API. Built with vanilla JavaScript, HTML5, CSS3, and styled with Animate.css for interactive UI feedback.

---

## 🚀 Live Demo

Experience the game live in your browser:
👉 **[Play Wordle Clone on Netlify](https://wordleeee-game.netlify.app/)**

---

## 🌟 Key Features

* **Dynamic Word Generation:** Fetches a fresh, random 5-letter verb for every game using the Words API.
* **Real-time Validation:** Validates submitted guesses against the Words API to ensure only valid English words are accepted.
* **Dual Input Modes:** Full support for both on-screen virtual keyboard clicks and standard physical keyboard keypresses.
* **Visual Tile Feedback:**
  * 🟩 **Green:** Letter is correct and in the right position.
  * 🟨 **Yellow:** Letter is in the word but in the wrong position.
  * ⬛ **Gray:** Letter is not in the word.
* **Interactive UI Animations:** Smooth tile-flip animations when revealing results and horizontal shaking alerts for invalid or incomplete guesses via Animate.css.
* **Game State Alerts:** Displays win/loss popups and allows instant game restarts on victory.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6+)
* **Animations:** [Animate.css](https://animate.style/)
* **External API:** [Words API](https://www.wordsapi.com/) via RapidAPI
* **Deployment:** [Netlify](https://www.netlify.com/)

---

## 💻 Local Setup

### Prerequisites

All you need is a modern web browser (Google Chrome, Firefox, Safari, Edge). No Node server or complex build tools required!

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/wordle-verb-clone.git](https://github.com/your-username/wordle-verb-clone.git)
   cd wordle-verb-clone
