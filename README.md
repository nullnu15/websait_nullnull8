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
      padding-top: 100px;
    }
    input, button {
      padding: 10px;
      font-size: 18px;
      border: none;
      border-radius: 10px;
      margin: 10px;
    }
    .welcome {
      margin-top: 20px;
      font-size: 24px;
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
