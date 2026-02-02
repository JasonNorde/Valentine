# Valentine

<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Für meine Liebste 💖</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h1>Alles Liebe zum Valentinstag, Sophie! ❤️</h1>
    
    <!-- GIF einfügen -->
    <img src="https://media.giphy.com/media/l0MYt5jPR6QX5pnqM/giphy.gif" alt="Love GIF" class="love-gif">

    <p>Ich liebe dich mehr, als Worte ausdrücken können. 🌹</p>

    <button onclick="alert('Willst du mein Valentine sein? 💌')">Klick mich 💖</button>
  </div>
</body>
</html>

body {
  margin: 0;
  padding: 0;
  font-family: 'Arial', sans-serif;
  background: linear-gradient(to bottom right, #ffb6c1, #ffc0cb);
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.container {
  text-align: center;
  background: rgba(255, 255, 255, 0.8);
  padding: 40px;
  border-radius: 20px;
  box-shadow: 0 0 20px rgba(0,0,0,0.2);
}

h1 {
  color: #d10068;
  margin-bottom: 20px;
}

.love-gif {
  width: 300px;
  border-radius: 20px;
  margin-bottom: 20px;
}

p {
  font-size: 1.2em;
  color: #b0004a;
  margin-bottom: 30px;
}

button {
  background-color: #ff4da6;
  border: none;
  padding: 15px 30px;
  font-size: 1em;
  color: white;
  border-radius: 10px;
  cursor: pointer;
  transition: 0.3s;
}

button:hover {
  background-color: #ff1a75;
  transform: scale(1.1);
}
