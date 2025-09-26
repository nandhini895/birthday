<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Happy Birthday jayshree🎂</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: "Comic Sans MS", cursive, sans-serif;
      text-align: center;
      background: linear-gradient(to right, #ff9a9e, #fad0c4);
      overflow: hidden;
    }
    h1 {
      font-size: 3rem;
      margin-top: 40px;
      color: #fff;
      text-shadow: 2px 2px #ff69b4;
    }
    p {
      font-size: 1.5rem;
      color: #fff;
      margin: 15px;
    }
    .cake {
      font-size: 100px;
      margin: 20px 0;
    }

    /* Slideshow */
    .slideshow-container {
      max-width: 600px;
      position: relative;
      margin: 20px auto;
    }
    .mySlides {
      display: none;
      animation: fade 1.5s;
    }
    img {
      border-radius: 20px;
      width: 100%;
      height: auto;
      box-shadow: 0 4px 20px rgba(0,0,0,0.3);
    }
    @keyframes fade {
      from {opacity: .4} 
      to {opacity: 1}
    }

    /* Balloons */
    .balloon {
      position: absolute;
      bottom: -150px;
      font-size: 50px;
      animation: float 6s infinite;
    }
    @keyframes float {
      0% { transform: translateY(0); opacity: 1; }
      100% { transform: translateY(-120vh); opacity: 0; }
    }
    audio {
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <h1>🎉 Happy Birthday, jayshree! 🎉</h1>
  <div class="cake">🎂</div>
  <p>Dear Sister, wishing you endless joy, love, and laughter on your special day 💖💐</p>

  <!-- Slideshow -->
  <div class="slideshow-container">
    <div class="mySlides"><img src="photo1.jpg" alt="Sister Photo 1"></div>
    <div class="mySlides"><img src="photo2.jpg" alt="Sister Photo 2"></div>
    <div class="mySlides"><img src="photo3.jpg" alt="Sister Photo 3"></div>
    <div class="mySlides"><img src="photo4.jpg" alt="Sister Photo 3"></div>
    <div class="mySlides"><img src="photo5.jpg" alt="Sister Photo 3"></div>
    <div class="mySlides"><img src="photo6.jpg" alt="Sister Photo 3"></div>
  </div>
