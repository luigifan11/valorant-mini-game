<!DOCTYPE html>
<html>
<head>
  <title>Valorant Mini Game</title>

  <style>
    body {
      margin: 0;
      background: #0f1923;
      color: white;
      font-family: Arial, sans-serif;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
    }

    .container {
      border: 2px solid #ff4655;
      padding: 50px;
      width: 500px;
      background: #111820;
    }

    h1 {
      color: #ff4655;
      letter-spacing: 4px;
    }

    .status {
      color: #9aa0a6;
      margin: 25px 0;
      line-height: 1.8;
    }

    button {
      background: #ff4655;
      color: white;
      border: none;
      padding: 15px 35px;
      font-size: 18px;
      cursor: pointer;
    }

    button:hover {
      background: white;
      color: #ff4655;
    }
  </style>
</head>

<body>

  <div class="container">

    <p>CLASSIFIED // SPECIAL OPERATION</p>

    <h1>MISSION AVAILABLE</h1>

    <div class="status">
      PLAYER 1: FOUND<br>
      PLAYER 2: CONNECTION LOST<br><br>

      OBJECTIVE:<br>
      FIND PLAYER 2
    </div>

    <button>ACCEPT MISSION</button>

  </div>

</body>
</html>
