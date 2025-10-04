# Wallpaperstudio
I'd rather deliver wallpapers by my this website
!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Wallpaper Website</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      text-align: center;
      background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
      color: white;
    }

    header {
      padding: 20px;
      background: rgba(0, 0, 0, 0.6);
      font-size: 28px;
      font-weight: bold;
    }

    .wallpapers {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 15px;
      padding: 20px;
    }

    .wallpapers img {
      width: 100%;
      height: auto;
      border-radius: 12px;
      box-shadow: 0px 4px 15px rgba(0,0,0,0.5);
      transition: transform 0.3s ease;
    }

    .wallpapers img:hover {
      transform: scale(1.05);
    }

    footer {
      margin-top: 20px;
      padding: 10px;
      background: rgba(0,0,0,0.7);
      font-size: 14px;
    }
  </style>
</head>
<body>

  <header>🌸 Anime & BMW Wallpapers 🚘</header>

  <section class="wallpapers">
    <!-- Add Anime Wallpaper -->
    <img src="https://wallpapercave.com/wp/wp9416089.jpg" alt="Anime Wallpaper">

    <!-- Add BMW Wallpaper -->
    <img src="https://wallpapercave.com/wp/wp7456397.jpg" alt="BMW Car">

    <!-- Another Anime Wallpaper -->
    <img src="https://wallpapercave.com/wp/wp12190022.jpg" alt="Anime Girl">

    <!-- Another BMW Wallpaper -->
    <img src="https://wallpapercave.com/wp/wp7726161.jpg" alt="BMW Supercar">
  </section>

  <footer>© 2025 My Wallpaper Site</footer>

</body>
</html>
