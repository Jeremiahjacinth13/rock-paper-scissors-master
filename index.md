<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <!-- displays site properly based on user's device -->

  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">

  <title>Frontend Mentor | Rock, Paper, Scissors</title>

  <!-- Custom Css -->
  <link rel="stylesheet" href="style.css">

</head>

<body>
<div class = time></div>
  <div class="overlay"></div>
  <div class="title">
    <img src="images/logo.svg" alt="">
    <div class="score-board">
      <p class="score-tag">SCORE</p>
      <div class="score-value">0</div>
    </div>
  </div>
  <div class="game-area">
    <div class="game-options">
      <div class="image-gradient paper">
        <div class="image paper">
          <img src="images/icon-paper.svg" alt="" class=paper>
        </div>
      </div>
      <div class="image-gradient scissors">
        <div class="image scissors">
          <img src="images/icon-scissors.svg" alt="" class=scissors>
        </div>
      </div>
      <div class="image-gradient rock">
        <div class="image rock">
          <img src="images/icon-rock.svg" alt="" class=rock>
        </div>
      </div>
      <div class="triangle">
        <img src="images/bg-triangle.svg" alt="">
      </div>
    </div>
  </div>
  <div class="rules">
    <div class="rules-top">
      <h3>RULES</h3>
      <img src="images/icon-close.svg" alt="" class=icon-close>
    </div>
    <img src="images/image-rules.svg" alt="" class=rules-img>
  </div>
  </div>
  <button class=showRules>Rules</button>
  <div class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>.
    Coded by <a href="#">Lena Jeremiah</a>. 
  </div>
  <script src = 'confetti.js'></script>
  <script src="main.js"></script>
</body>
</html>
