# React Stopwatch Application

A clean, responsive, and accurate Stopwatch application built with **React** and **Vite**. This project demonstrates efficient state management, side-effect handling with `useEffect`, and direct value persistence across renders using React hooks like `useRef`.

---

## 🚀 Features

- **Start / Stop / Reset Controls**: Smoothly control timer execution without unexpected lag or state drift.
- **High-Precision Formatting**: Displays time accurately formatted as `HH:MM:SS:MS` (Hours, Minutes, Seconds, Milliseconds).
- **Optimized Rendering**: Leverages `useRef` to hold interval references and timestamps without triggering unnecessary re-renders.

---

## 🛠️ Tech Stack

- **Framework/Library**: React
- **Build Tool**: Vite
- **Styling**: CSS3
- **Language**: JavaScript (ES6+)

---

## 📁 Project Structure

```text
stopwatch/
├── src/
│   ├── assets/
│   ├── App.jsx
│   ├── index.css
│   ├── main.jsx
│   └── StopWatch.jsx
├── index.html
├── package.json
└── vite.config.js
```

---

⚙️ Setup and Installation

Follow these steps to get the application up and running locally:

1. Clone the repository

```
git clone [https://github.com/eyob-tk/Stop-Watch.git](https://github.com/eyob-tk/Stop-Watch.git) 
cd stopwatch
```

2. Install dependencies

```
npm install
```

3. Start the development server

```
npm run dev
```

4. View in browser

Open the local server link printed in your terminal (typically `http://localhost:5173`).

---

## 📄 License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).