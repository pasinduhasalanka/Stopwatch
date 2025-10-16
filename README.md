# ⏱️ React Stopwatch App

A clean and simple **React Stopwatch Application** that allows users to start, stop, reset, and record lap times. Built using **React Hooks** and styled with modern CSS for a minimal look.

---

## 🚀 Features

- ▶️ **Start / Stop** functionality  
- 🔄 **Reset** the stopwatch to zero  
- 🧾 **Lap recording** feature to track multiple time intervals  
- ⏱️ Displays **minutes, seconds, and milliseconds**  
- ⚛️ Built using **React Hooks** (`useState`, `useEffect`)  
- 💾 Lightweight and efficient with automatic state updates  
- 🎨 Responsive, clean, and modern UI  

---

## 🧩 Project Structure

```
📂 react-stopwatch-app
 ┣ 📜 App.css
 ┣ 📜 Stopwatch.jsx
 ┣ 📜 App.jsx
 ┣ 📜 main.jsx
 ┣ 📜 index.css
 ┗ 📜 package.json
```

---

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/pasinduhasalanka/Stopwatch.git
   cd react-stopwatch-app
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the app:**
   ```bash
   npm run dev
   ```

4. **Open in browser:**
   ```
   http://localhost:5173/
   ```

---

## 💡 How It Works

- The stopwatch keeps track of **elapsed time** using a `useState` variable.  
- A `useEffect` hook runs an interval (`setInterval`) to update the time when the stopwatch is running.  
- When paused, the interval is cleared to stop counting.  
- The **lap feature** records current time snapshots into an array for display.  
- The **reset button** clears both the elapsed time and lap history.  

---

## 🧠 Technologies Used

- **React 18+**
- **Vite**
- **JavaScript (ES6+)**
- **CSS3**

---



## 👨‍💻 Author

Pasindu Hasalanka  
📧 your.pasinduhasalanka21@gmail.com  
🌐 [GitHub](https://github.com/pasinduhasalanka)

---

