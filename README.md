<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tina - Home</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }
    header {
      background-color: #000;
      color: #fff;
      padding: 20px 10%;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 15px;
      padding: 15px 0;
      background-color: #111;
    }
    nav a {
      text-decoration: none;
      color: #fff;
      font-size: 1.2em;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .hero {
      background: url('https://via.placeholder.com/1500x500') no-repeat center center/cover;
      height: 400px;
      text-align: center;
      color: #fff;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }
    .hero h2 {
      margin: 0;
      font-size: 2.5em;
    }
    .section {
      padding: 50px 10%;
      text-align: center;
    }
    .section h3 {
      font-size: 2em;
      margin-bottom: 20px;
    }
    footer {
      text-align: center;
      padding: 20px 10%;
      background-color: #111;
      color: #fff;
    }
    footer p {
      margin: 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>Tina</h1>
    <p>Designer | Producer | Creative</p>
  </header>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>
  <div class="hero">
    <h2>Welcome to Tina's Space</h2>
    <p>Explore her journey through Design, Drawing, and beyond</p>
  </div>
  <div id="about" class="section">
    <h3>About Ti</h3>
    <p> Explore her career and achievements!</p>
  </div>
  <div id="projects" class="section">
    <h3>Latest Projects</h3>
  </div>
  <footer>
    <p>&copy; 2024 Tina. All Rights Reserved.</p>
  </footer>
</body>
</html>
