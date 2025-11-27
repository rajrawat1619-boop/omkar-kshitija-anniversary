<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>3rd Anniversary — Omkar ❤️ Kshitija</title>

  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #ffdde1, #ee9ca7);
      color: #4a2c2c;
      text-align: center;
      padding-bottom: 50px;
      scroll-behavior: smooth;
    }

    h1 {
      margin-top: 30px;
      font-size: 2.3rem;
      color: #4a2c2c;
    }

    .quote {
      font-size: 1.2rem;
      margin: 15px;
      padding: 10px;
      font-style: italic;
    }

    .card {
      background: rgba(255, 255, 255, 0.6);
      backdrop-filter: blur(10px);
      padding: 20px;
      margin: 20px auto;
      width: 85%;
      border-radius: 20px;
    }

    .option-btn {
      background: white;
      border: none;
      padding: 15px 20px;
      border-radius: 15px;
      margin: 10px;
      width: 80%;
      font-size: 1rem;
      color: #ee5176;
      font-weight: bold;
      cursor: pointer;
      transition: 0.3s;
    }

    .option-btn:hover {
      transform: scale(1.05);
    }

    #poemSection {
      display: none;
      padding: 20px;
      animation: fadeIn 1.5s ease-in-out;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .gallery img {
      width: 90%;
      max-width: 350px;
      margin: 10px;
      border-radius: 20px;
      box-shadow: 0px 4px 10px rgba(0,0,0,0.3);
    }

    .footer-line {
      font-size: 1.4rem;
      margin-top: 20px;
      font-weight: bold;
    }

    audio {
      margin-top: 20px;
    }
  </style>

  <script>
    function showPoem() {
      document.getElementById("poemSection").style.display = "block";
      window.location.href = "#poemSection";
    }
  </script>
</head>
<body>

  <h1>Omkar ❤️ Kshitija</h1>

  <p class="quote">"In your smile, I found my peace. In your heart, I found my forever." 💖</p>

  <!-- Choose Choose Section -->
  <div class="card">
    <h2>Choose one, My Love ❤️</h2>

    <button class="option-btn" onclick="showPoem()">Life Time (Forever ❤️)</button>
    <button class="option-btn">I will still choose the first option 😌💕</button>
  </div>

  <!-- Poem + Paragraph -->
  <div id="poemSection" class="card">
    <h2>For My Kshitija 💕</h2>

    <p>
      My love… the first time I met you in **Tolani College**,  
      something inside me changed forever.  
      I still remember your **smile**, the softness in your voice,  
      the way you cared without even trying.  
      You were gentle, pure, and the most beautiful part  
      of every day that followed.
    </p>

    <p>
      Your presence became my comfort,  
      your laughter became my favourite sound,  
      and your heart became my safest place.  
      In you, I found love… the kind people dream of.  
      And in these three years, you’ve given me  
      a million reasons to fall for you again and again.
    </p>

    <h3>💝 A Poem For You 💝</h3>

    <p style="font-style: italic;">
      The day we met, the world felt new,<br>
      My heart whispered softly, “This girl is the one for you.”<br>
      Your smile lit up places I never knew inside,<br>
      Your care wrapped my soul, like the warmest tide.<br><br>

      From Tolani’s corridors to this beautiful life,<br>
      You became my happiness, my peace, my light.<br>
      Three years later, my love has only grown,<br>
      With you, my Kshitija, I’m already home. ❤️
    </p>
  </div>

  <!-- Image Gallery -->
  <h2 style="margin-top:40px;">Our Memories 📸💞</h2>

  <div class="gallery">
    <img src="your-image1.jpg" alt="Photo 1">
    <img src="your-image2.jpg" alt="Photo 2">
    <img src="your-image3.jpg" alt="Photo 3">
    <!-- Add more images by copying the line above -->
  </div>

  <!-- Background Music -->
  <audio controls autoplay loop>
    <source src="your-song.mp3" type="audio/mpeg">
  </audio>

  <!-- Final Lines -->
  <p class="footer-line">You + Me = Best Couple Forever 💞</p>

  <h2 style="margin-top:5px; font-size:1.8rem;">I Love You ❤️</h2>

  <h2 style="margin-top:10px; font-size:2rem;">Happy 3rd Anniversary, My Love 💕</h2>

</body>
</html>
