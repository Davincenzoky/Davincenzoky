<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Davincenzoky | Profile</title>
  <style>
    /* Base styles */
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 20px;
      line-height: 1.6;
      transition: background-color 0.3s, color 0.3s;
    }

    /* Dark Mode */
    body.dark {
      background-color: #0f111a;
      color: #fff;
    }

    /* Light Mode */
    body.light {
      background-color: #f5f5f5;
      color: #222;
    }

    h1, h2 {
      transition: color 0.3s;
    }

    body.dark h1, body.dark h2 { color: #00f7ff; }
    body.light h1, body.light h2 { color: #1a73e8; }

    h1 { font-size: 2.5rem; }
    h2 { margin-top: 40px; }

    p { margin: 10px 0; }

    .section { margin-bottom: 40px; }

    .icons img {
      height: 40px;
      margin-right: 12px;
      vertical-align: middle;
      transition: filter 0.3s;
    }

    body.light .icons img { filter: brightness(0.8); }

    .socials a img {
      height: 35px;
      margin-right: 10px;
    }

    .stats img { margin-top: 10px; }

    blockquote {
      font-style: italic;
      border-left: 3px solid #ffdd00;
      padding-left: 10px;
      margin-left: 0;
    }

    /* Toggle button */
    #theme-toggle {
      position: fixed;
      top: 20px;
      right: 20px;
      background: #00f7ff;
      border: none;
      padding: 10px 15px;
      cursor: pointer;
      font-weight: bold;
      border-radius: 5px;
      color: #000;
      transition: background 0.3s, color 0.3s;
    }

    body.light #theme-toggle { background: #1a73e8; color: #fff; }

    @media (max-width: 600px) {
      .icons img { height: 30px; }
      .socials a img { height: 25px; }
    }
  </style>
</head>
<body class="dark">

  <button id="theme-toggle">Switch Mode</button>

  <div class="section">
    <h1>Hey 👋 What's up?</h1>
    <p>My name is <b>Davincenzoky</b> and I'm a <b>Graphics Designer | Web System Developer | Educator</b>, from <b>Palawan, Philippines</b>.</p>
  </div>

  <div class="section">
    <h2>☕ About me</h2>
    <p>✨ Creating bugs since 20XX<br>
       📚 I'm currently learning advanced web systems & modern frontend tools<br>
       🎯 Goals: Build impactful systems and inspire future developers<br>
       🎲 Fun fact: I turn coffee into code ☕💻</p>
  </div>

  <div class="section">
    <h2>☕ Coffebits</h2>
    <blockquote>"Where creativity meets code, and ideas brew into innovation."</blockquote>
  </div>

  <div class="section">
    <h2>🛠️ I code with</h2>
    <div class="icons">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="TypeScript">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React">

      <br><br>

      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/photoshop/photoshop-plain.svg" alt="Photoshop">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/illustrator/illustrator-plain.svg" alt="Illustrator">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/aftereffects/aftereffects-plain.svg" alt="After Effects">
      <img src="https://cdn.simpleicons.org/canva/00C4CC" alt="Canva">
    </div>
  </div>

  <div class="section stats">
    <h2>📊 GitHub Stats</h2>
    <img src="https://github-readme-stats.vercel.app/api?username=Davincenzoky&show_icons=true&theme=tokyonight&hide_title=true" alt="GitHub Stats" height="150">
  </div>

  <div class="section stats">
    <h2>🔥 Streak Stats</h2>
    <img src="https://streak-stats.demolab.com?user=Davincenzoky&theme=tokyonight" alt="GitHub Streak" height="150">
  </div>

  <div class="section socials">
    <h2>🌐 Connect with me</h2>
    <a href="https://web.facebook.com/DavinciBadua20/" target="_blank">
      <img src="https://img.shields.io/badge/Facebook-1877F2?logo=facebook&logoColor=white" alt="Facebook">
    </a>
    <a href="https://www.linkedin.com/in/vbadua20/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn">
    </a>
    <a href="https://davincenzoky.github.io/myportfolio/" target="_blank">
      <img src="https://img.shields.io/badge/Portfolio-000?logo=github" alt="Portfolio">
    </a>
  </div>

  <script>
    const toggle = document.getElementById('theme-toggle');
    toggle.addEventListener('click', () => {
      document.body.classList.toggle('dark');
      document.body.classList.toggle('light');
    });
  </script>

</body>
</html>
