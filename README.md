
<html lang="de">
<head>
  <meta charset="UTF-8">
  <title>💖 Will you be my Valentine?</title>
  <style>
    body {
      background: #ffe6f0;
      font-family: 'Arial', sans-serif;
      text-align: center;
      padding-top: 100px;
    }
    h1 { color: #d63384; }
    button {
      font-size: 20px;
      padding: 15px 30px;
      margin: 20px;
      border-radius: 12px;
      border: none;
      cursor: pointer;
    }
    .yes { background: #ff4d6d; color: white; }
    .no { background: #ccc; }
  </style>
 
<body>

  <h1>Will you be my Valentine? 💘</h1>
  <p>Ich verspreche Schokolade, Liebe & viele dumme Witze 🍫😄</p>

  <button class="yes" onclick="alert('YAAAY 💕 Ich liebe dich!')">JA 💖</button>
  <button class="no" onclick="alert('Diese Option ist leider defekt 😜')">Nein 😅</button>
  <button class="no2" onmouseover="moveButton()">Nein 😏</button>

  <script>
  function moveButton() {
    const btn = document.querySelector('.no2');
    btn.style.position = 'absolute';
    btn.style.left = Math.random() * 80 + '%';
    btn.style.top = Math.random() * 80 + '%';
  }
  </script>

</body>
