# 🕒 Analog Clock using HTML, CSS, and JavaScript

This is a simple responsive analog clock created with HTML, CSS, and vanilla JavaScript. The clock hands rotate based on the current time using JavaScript DOM manipulation.

### 🚀 Live Demo
👉 [Click here to view](https://maneesh004-code.github.io/analog-clock)

---

## 🛠️ Features
- Real-time clock with smooth hand rotation
- Responsive design using CSS
- Fully functional without external libraries

---

## 📁 Project Structure

analog-clock/
├── index.html # Main HTML file
├── style.css # Clock styling
├── script.js # Clock logic (JS)
├── clock.png # Clock background image


---

## 📷 Preview

![Analog Clock Preview](clock.png)

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
