<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Anchal, Will You Be My Valentine?</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #ff758c, #ff7eb3);
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #fff;
      text-align: center;
    }

    .card {
      background: rgba(255, 255, 255, 0.15);
      backdrop-filter: blur(10px);
      border-radius: 20px;
      padding: 30px 24px 36px;
      max-width: 420px;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.25);
    }

    .photo {
      width: 180px;
      height: 180px;
      object-fit: cover;
      border-radius: 50%;
      border: 4px solid rgba(255,255,255,0.7);
      margin: 0 auto 16px;
      box-shadow: 0 6px 18px rgba(0,0,0,0.25);
    }

    h1 {
      font-size: 2.1rem;
      margin-bottom: 8px;
    }

    p {
      font-size: 1.05rem;
      line-height: 1.6;
      margin-bottom: 22px;
    }

    .buttons {
      display: flex;
      justify-content: center;
      gap: 18px;
      flex-wrap: wrap;
    }

    button {
      padding: 12px 24px;
      font-size: 1rem;
      border: none;
      border-radius: 30px;
      cursor: pointer;
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }

    #yesBtn {
      background-color: #ff4d6d;
      color: #fff;
    }

    #noBtn {
      background-color: #fff;
      color: #ff4d6d;
      position: relative;
    }

    button:hover {
      transform: scale(1.08);
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
    }

    .heart {
      font-size: 2rem;
      animation: pulse 1.5s infinite;
      margin-bottom: 10px;
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.3); }
      100% { transform: scale(1); }
    }

    .music-note {
      font-size: 0.9rem;
      opacity: 0.9;
      margin-top: 12px;
    }
  </style>
</head>
<body>
  <div class="card">
    <img class="photo" src="data:image/jpeg;base64,
