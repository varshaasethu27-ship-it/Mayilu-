<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Be My Valentine 💖</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: 'Segoe UI', sans-serif;
    }
    .card {
      background: white;
      padding: 40px;
      border-radius: 20px;
      text-align: center;
      box-shadow: 0 20px 40px rgba(0,0,0,0.2);
      animation: fadeIn 1.5s ease;
    }
    h1 {
      color: #e91e63;
      margin-bottom: 10px;
    }
    p {
      color: #555;
      font-size: 18px;
      margin-bottom: 30px;
    }
    button {
      padding: 12px 25px;
      border: none;
      border-radius: 30px;
      font-size: 16px;
      cursor: pointer;
      margin: 10px;
      transition: transform 0.2s;
    }
    .yes {
      background: #e91e63;
      color: white;
    }
    .yes:hover {
      transform: scale(1.1);
    }
    .love {
      margin-top: 20px;
      font-size: 22px;
      display: none;
      color: #e91e63;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: scale(0.9); }
      to { opacity: 1; transform: scale(1); }
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>Hey Love 💕</h1>
    <p>Every moment with you feels special…</p>
    <h1>Will you be my Valentine? 🌹</h1>

    <button class="yes" onclick="showLove()">YES 💖</button>

    <div class="love" id="loveMsg">
      Yay!!! 💕💋  
      Happy Valentine’s Day, my love 💞
    </div>
  </div>

  <script>
    function showLove() {
      document.getElementById("loveMsg").style.display = "block";
    }
  </script>
</body>
</html>
