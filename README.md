<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Be My Valentine?</title>
  <style>
    body {
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
    }

    .card {
      background: white;
      padding: 40px;
      border-radius: 20px;
      text-align: center;
      box-shadow: 0 10px 25px rgba(0,0,0,0.2);
    }

    h1 {
      color: #ff4b5c;
      margin-bottom: 20px;
    }

    button {
      padding: 12px 25px;
      font-size: 16px;
      border: none;
      border-radius: 30px;
      cursor: pointer;
      margin: 10px;
      transition: 0.3s;
    }

    .yes {
      background-color: #ff4b5c;
      color: white;
    }

    .yes:hover {
      background-color: #e63946;
    }

    .no {
      background-color: #ddd;
    }

    .no:hover {
      background-color: #bbb;
    }
  </style>
</head>
<body>

  <div class="card">
    <h1>💖 Will You Be My Valentine? 💖</h1>
    <button class="yes" onclick="sayYes()">Yes 💘</button>
    <button class="no" onclick="sayNo()">No 🙈</button>
    <p id="response"></p>
  </div>

  <script>
    function sayYes() {
      document.getElementById("response").innerHTML =
        "Yay!!! 💕 I’m so happy! 🥰";
    }

    function sayNo() {
      document.getElementById("response").innerHTML =
        "Are you sure? 🥺💔";
    }
  </script>

</body>
</html>
