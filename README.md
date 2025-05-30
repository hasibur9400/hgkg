<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Naim ❤️ Mohona</title>
  <style>
    body {
      background: #fff0f5;
      font-family: 'Comic Sans MS', cursive, sans-serif;
      text-align: center;
      padding: 30px;
      color: #333;
    }
    h1 {
      font-size: 3em;
      color: #ff1493;
    }
    h2 {
      color: #800080;
      margin-bottom: 10px;
    }
    .box {
      background-color: #ffe4e1;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 2px 2px 10px #d8bfd8;
      margin: 30px auto;
      max-width: 800px;
    }
    .funny {
      font-style: italic;
      margin-top: 20px;
      color: #555;
    }
    .footer {
      margin-top: 50px;
      font-size: 1.2em;
      color: #ff69b4;
    }
    .video-box {
      margin: 30px auto;
    }
    .gif-box {
      margin-top: 30px;
    }
    .gif-box img {
      width: 100%;
      max-width: 600px;
      margin: 10px auto;
      border-radius: 15px;
      box-shadow: 0 0 10px #999;
    }
    .login-box {
      display: none;
      position: fixed;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background-color: rgba(0, 0, 0, 0.8);
      justify-content: center;
      align-items: center;
      z-index: 999;
    }
    .login-box.active {
      display: flex;
    }
    .login-form {
      background: white;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 0 20px #aaa;
      text-align: center;
    }
    .login-form input {
      padding: 10px;
      font-size: 1em;
      margin: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    .login-form button {
      padding: 10px 20px;
      font-size: 1em;
      background-color: #ff69b4;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .extra {
      margin-top: 40px;
      font-size: 1.1em;
      background: #fff8dc;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px #dcdcdc;
    }
  </style>
</head>
<body>
  <div id="login" class="login-box active">
    <div class="login-form">
      <h2>Enter the Secret Names 😉</h2>
      <input type="text" id="nameInput" placeholder="Enter Naim or Mohona" />
      <button onclick="checkName()">Enter</button>
    </div>
  </div>

  <div id="mainContent" style="display:none">
    <h1>🎉 BREAKING NEWS! 🎉</h1>
    <h2>Naim is Officially Off the Market!</h2>
    <div class="box">
      <p><strong>Naim ❤️ Mohona</strong> – একসাথে জীবন শুরু করলো, প্রেমে ডুবে গেছে এবং এখন আর পালানোর রাস্তা নেই! 😜</p>
      <p>তাদের সুখ-দুঃখের নতুন যাত্রা শুরু হোক <strong>ভালোবাসা, রুটি-সবজি আর রিমোট কার নিয়ে ঝগড়া</strong> দিয়ে! 😆</p>
      <p class="funny">নাঈম ভাই, এখন থেকে ঘুম আর শান্তি – দুটোই রেয়ার আইটেম!<br>আর মোহোনা, আপনি তো এখন পুরা বউ-বস! 🎤💍</p>
      <div class="video-box">
        <video width="100%" controls>
          <source src="naim_mohona_wedding_funny.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
      </div>
      <div class="gif-box">
        <img src="https://media.giphy.com/media/3o6Mb43FODaQPRdw3u/giphy.gif" alt="Funny Wedding GIF">
        <img src="https://media.giphy.com/media/3o7TKP9D5bJhlKwPgs/giphy.gif" alt="Celebration GIF">
        <img src="https://media.giphy.com/media/xUPGcgtKxm3KHe5s5K/giphy.gif" alt="Party GIF">
        <img src="https://media.giphy.com/media/fwbzI2kV3z2u0/giphy.gif" alt="Dance Funny GIF">
        <img src="https://media.giphy.com/media/jpbnoe3UIa8TU8LM13/giphy.gif" alt="Crazy Love GIF">
        <img src="https://media.giphy.com/media/3oz8xLd9DJq2l2VFtu/giphy.gif" alt="Marriage Dance">
      </div>
      <div class="extra">
        <p>🌈 <strong>Extra Wishes:</strong></p>
        <p>তোমাদের জীবনে থাকুক হাজার রঙ, হাজার গল্প, আর হাজারটা হাসির মুহূর্ত!</p>
        <p>নাঈম, ডাল গরম রাখতে ভুলো না! 😜<br>মোহোনা, এখন থেকে তুমি তার WiFi + Wife দুই-ই! 😍</p>
        <p>এই নতুন অধ্যায়ের প্রতিটা পৃষ্ঠা হোক প্রেম, পাগলামো আর পার্টিতে ভরপুর! 🎊</p>
      </div>
      <p class="footer">শুভকামনায় — তোমার চিরবন্ধু, <strong>Hasib</strong> 💖</p>
    </div>
  </div>

  <script>
    function checkName() {
      const input = document.getElementById("nameInput").value.toLowerCase();
      if (input.includes("naim") || input.includes("mohona")) {
        document.getElementById("login").style.display = "none";
        document.getElementById("mainContent").style.display = "block";
      } else {
        alert("Wrong name! Try again using Naim or Mohona");
      }
    }
  </script>
</body>
</html>
