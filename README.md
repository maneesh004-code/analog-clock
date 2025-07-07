# 🕒 Analog Clock Using HTML, CSS, and JavaScript

Welcome to the **Analog Clock** project — a responsive and real-time analog clock created using only **HTML**, **CSS**, and **vanilla JavaScript**. This simple yet elegant clock visually represents the current system time with animated hour, minute, and second hands over a custom clock face.

---

## 🔗 Live Demo

🌐 View it live here:  
👉 [https://maneesh004-code.github.io/analog-clock](https://maneesh004-code.github.io/analog-clock)


---

## 🧰 Technologies Used

- HTML5
- CSS3 (Flexbox, transforms)
- JavaScript (DOM manipulation, `setInterval`)
- Responsive design principles

---

## 🧠 Features

- ⏱️ Real-time clock updates every second
- 📐 Accurate hand rotations calculated using system time
- 💻 Fully responsive layout using viewport units
- 🖼️ Custom clock face image (`clock.png`)
- 🪶 Lightweight, no external libraries or frameworks

---

## 📁 Project Structure


---

## 📁 Project Structure

analog-clock/
├── index.html # Main HTML file
├── style.css # Clock styling
├── script.js # Clock logic (JS)
├── clock.png # Clock background image

---

## ✅ How It Works

- The `script.js` file uses `setInterval` to rotate the hour, minute, and second hands.
- Rotation is calculated based on the current time:
  - Hour hand: `30 * hour + minutes / 2`
  - Minute hand: `6 * minutes`
  - Second hand: `6 * seconds`

---

## 📌 Setup Instructions

1. Clone the repo:
git clone https://github.com/maneesh004-code/analog-clock.git
cd analog-clock
