<!DOCTYPE html>
<html lang="fa">
<head>
  <meta charset="UTF-8" />
  <title>تارنمای باشکوه nullnull8</title>
  <style>
    body {
      background-color: #000;
      color: #fff;
      text-align: center;
      font-family: Tahoma;
      padding-top: 1000px;
    }
    input, button {
      padding: 100px;
      font-size: 180px;
      border: none;
      border-radius: 100px;
      margin: 100px;
    }
    .welcome {
      margin-top: 200px;
      font-size: 240px;
      color: #00e5ff;
    }
  </style>
</head>
<body>
  <h1>درود بر تو!</h1>
  <p>نامت را بنویس تا خوش‌آمدی شایسته دریافت کنی:</p>
  
  <input type="text" id="nameInput" placeholder="نامت را بنویس..." />
  <button onclick="welcome()">نمایش خوش‌آمد</button>

  <div class="welcome" id="output"></div>

  <script>
    function welcome() {
      const name = document.getElementById('nameInput').value;
      const message = درود بر تو، ${name} عزیز! شکوه از آن تو باد 🌟;
      document.getElementById('output').innerText = message;
    }
  </script>
</body>
</html>
