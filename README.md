# Random-Joke-Generator
A fun and interactive web app that fetches and displays random jokes using the JokeAPI with a smooth fade animation effect.
# 😂 Random Joke Generator

A simple and fun web app that displays a random joke every time you click the button. Built using **HTML**, **CSS**, and **JavaScript**, and powered by the [JokeAPI](https://v2.jokeapi.dev/).

---

## 🎯 Features

- Fetches random jokes from the JokeAPI.
- Smooth fade animation for each new joke.
- Clean and responsive UI.
- Single click to generate new jokes instantly.

---

## 🛠️ Technologies Used

- **HTML5** – Structure of the webpage.
- **CSS3** – Styling and layout.
- **JavaScript (Fetch API)** – Fetching jokes dynamically from the API.
- **JokeAPI** – External API providing a wide range of jokes.

---

## ⚙️ How It Works

1. The user clicks the **"Get Random Joke"** button.  
2. JavaScript makes a `fetch()` request to the JokeAPI.  
3. The returned joke is displayed dynamically on the page.  
4. A fade animation is applied to make the transition smooth.

---

## 🚀 Getting Started

### 1. Clone this repository
```bash
git clone https://github.com/your-username/random-joke-generator.git

2. Open the project folder
cd random-joke-generator

3. Open index.html in your browser

Simply double-click index.html or drag it into your browser window.

📁 Project Structure
random-joke-generator/
│
├── index.html        # Main HTML file
├── style1.css        # Stylesheet for design and layout
└── script1.js        # JavaScript file for fetching and displaying jokes

🧩 API Reference

Endpoint:

https://v2.jokeapi.dev/joke/Any?blacklistFlags=nsfw,religious,political,racist,sexist,explicit&type=single


Returns:

{
  "error": false,
  "category": "Programming",
  "type": "single",
  "joke": "Why do programmers prefer dark mode? Because light attracts bugs!",
  "id": 101,
  "safe": true,
  "lang": "en"
}
