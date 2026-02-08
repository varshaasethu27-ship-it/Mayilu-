<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>For Mayilu 💖</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      background: linear-gradient(135deg, #ff758c, #ff7eb3);
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: 'Segoe UI', sans-serif;
    }
    .card {
      background: white;
      padding: 45px;
      border-radius: 25px;
      text-align: center;
      box-shadow: 0 25px 50px rgba(0,0,0,0.25);
      animation: fadeIn 1.6s ease;
    }
    h1 {
      color: #e91e63;
      margin-bottom: 10px;
      font-size: 30px;
    }
    p {
      color: #555;
      font-size: 18px;
      margin-bottom: 25px;
    }
    button {
      padding: 14px 32px;
      border: none;
      border-radius: 35px;
      font-size: 17px;
      cursor: pointer;
      margin-top: 15px;
      background: #e91e63;
      color: white;
      transition: transform 0.25s;
    }
    button:hover {
      transform: scale(1.15);
    }
    .love {
      margin-top: 25px;
      font-size: 22px;
      display: none;
      color: #e91e63;
      animation: fadeIn 1s ease;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: scale(0.9); }
      to { opacity: 1; transform: scale(1); }
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>Mayilu 💕</h1>
    <p>You make my ordinary days feel magical ✨</p>
    <h1>Will you be my Valentine? 🌹</h1>

    <button onclick="showLove()">YES 💖</button>

    <div class="love" id="loveMsg">
      Yay!!! 💋💞  
      Happy Valentine’s Day, my love ❤️
    </div>
  </div>

  <script>
    function showLove() {
      document.getElementById("loveMsg").style.display = "block";
    }
  </script>
</body>
</html>
