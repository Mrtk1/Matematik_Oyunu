<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Hangi Kesir Daha Büyüktür?</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      text-align: center;
      background-image: url('https://upload.wikimedia.org/wikipedia/commons/thumb/7/76/Math_Wallpaper.jpg/800px-Math_Wallpaper.jpg');
      background-size: cover;
      color: #000;
    }
    .container {
      margin-top: 60px;
    }
    .fraction-button {
      padding: 20px 40px;
      font-size: 2rem;
      margin: 30px;
      cursor: pointer;
      border: 2px solid #333;
      background-color: white;
      transition: background-color 0.3s;
    }
    .fraction-button:hover {
      background-color: #eef;
    }
    .score {
      font-size: 1.5rem;
    }
    .message {
      font-weight: bold;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Hangi Kesir Daha Büyüktür?</h1>
    <div id="buttons"></div>
    <div class="score">Puan: <span id="score">0</span></div>
    <div class="message" id="message"></div>
  </div>

  <script>
    let score = 0;

    function getRandomFraction() {
      const numerator = Math.floor(Math.random() * 9) + 1;
      const denominator = Math.floor(Math.random() * (10 - numerator)) + numerator + 1;
      return { num: numerator, den: denominator };
    }

    function displayFractions() {
      const frac1 = getRandomFraction();
      let frac2 = getRandomFraction();

      while (frac1.num / frac1.den === frac2.num / frac2.den) {
        frac2 = getRandomFraction();
      }

      const buttonsDiv = document.getElementById("buttons");
      buttonsDiv.innerHTML = "";

      const button1 = document.createElement("button");
      button1.className = "fraction-button";
      button1.textContent = `${frac1.num}/${frac1.den}`;
      button1.onclick = () => chooseFraction(frac1, frac2, true);

      const button2 = document.createElement("button");
      button2.className = "fraction-button";
      button2.textContent = `${frac2.num}/${frac2.den}`;
      button2.onclick = () => chooseFraction(frac1, frac2, false);

      buttonsDiv.appendChild(button1);
      buttonsDiv.appendChild(button2);
    }

    function chooseFraction(frac1, frac2, firstClicked) {
      const f1 = frac1.num / frac1.den;
      const f2 = frac2.num / frac2.den;
      const chosen = firstClicked ? f1 : f2;
      const other = firstClicked ? f2 : f1;

      const message = document.getElementById("message");

      if (chosen > other) {
        score++;
        message.textContent = "Doğru!";
        message.style.color = "green";
      } else {
        score = 0;
        message.textContent = "Yanlış! Skor sıfırlandı.";
        message.style.color = "red";
      }
      document.getElementById("score").textContent = score;
      setTimeout(displayFractions, 1000);
    }

    displayFractions();
  </script>
</body>
</html>
