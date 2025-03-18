# Hello
# 🎵 Musical Instruments

## 📌 Description
This project showcases a simple webpage for musical instruments using **HTML, CSS, and JavaScript**. It features a clean and responsive design, allowing users to interact with buttons to play different instrument sounds.

---

## 🎨 Demo Preview (HTML, CSS & JavaScript)
Below is a basic snippet from the project:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Musical Instruments</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            text-align: center;
            padding: 20px;
        }
        h1 {
            color: #3498db;
        }
        .btn {
            background-color: #2ecc71;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            font-size: 18px;
            margin: 5px;
        }
        .btn:hover {
            background-color: #27ae60;
        }
    </style>
</head>
<body>
    <h1>Musical Instruments 🎶</h1>
    <button class="btn" onclick="playSound('piano')">Piano</button>
    <button class="btn" onclick="playSound('guitar')">Guitar</button>
    <script>
        function playSound(instrument) {
            let audio = new Audio(`${instrument}.mp3`);
            audio.play();
        }
    </script>
</body>
</html>
```

📌 **Output Preview**: This code creates an interactive webpage where users can click buttons to play different instrument sounds.

---

## 🔹 Features
- 🖼️ **Beautiful UI** with HTML & CSS.
- 🎵 **Interactive buttons** to play instrument sounds.
- 🚀 **Responsive and easy to use.**
- 🛠️ **Customizable** styles and sound effects.

---

## 📂 Project Structure
```
📁 musical-instruments
│-- 📄 index.html
│-- 📄 style.css
│-- 📄 script.js
│-- 📂 assets
│   │-- 🎵 piano.mp3
│   │-- 🎵 guitar.mp3
```

---

## 📌 How to Use
1. **Clone the repository:**
   ```ba
