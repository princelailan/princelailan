<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Joseph Onyango | Creative Developer</title>
  
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet" />
  
  <!-- FontAwesome for Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" />
  
  <style>
    /* Basic Reset & Fonts */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Montserrat', sans-serif;
      color: #fff;
      text-align: center;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      overflow-x: hidden;
      background-image: url('https://your-image-url.com'); /* Replace with your image */
      background-size: cover;
      background-position: center;
      background-attachment: fixed;
    }
    
    /* Overlay for readability */
    body::after {
      content: "";
      position: fixed;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background: rgba(0, 0, 0, 0.6);
      z-index: -1;
    }

    /* Header Styling */
    header {
      margin-bottom: 20px;
    }
    header h1 {
      font-size: 3em;
      font-weight: 700;
      letter-spacing: 2px;
      text-shadow: 4px 4px 8px rgba(0,0,0,0.5);
      color: #ff6f61;
      text-transform: uppercase;
    }
    
    /* Glassmorphism Card */
    .card {
      background: rgba(255, 255, 255, 0.2);
      backdrop-filter: blur(15px);
      padding: 35px 30px;
      width: 90%;
      max-width: 800px;
      border-radius: 20px;
      box-shadow: 0 6px 30px rgba(0, 0, 0, 0.3);
      margin-bottom: 25px;
      transition: transform 0.3s ease-in-out;
    }
    .card:hover {
      transform: translateY(-10px);
    }

    /* Section Headers */
    h2 {
      font-size: 2em;
      margin-bottom: 15px;
      color: #ffcc00;
      text-transform: uppercase;
      letter-spacing: 2px;
    }

    /* Paragraphs */
    p {
      font-size: 1.1em;
      line-height: 1.8;
      margin-bottom: 18px;
      text-shadow: 1px 1px 5px rgba(0,0,0,0.4);
    }

    /* Skills Section */
    .skills ul {
      list-style: none;
      padding: 0;
      text-align: left;
      margin: 0 auto;
      max-width: 650px;
    }
    .skills li {
      font-size: 1.3em;
      margin: 15px 0;
      display: flex;
      align-items: center;
      transition: transform 0.3s, color 0.3s ease;
    }
    .skills li:hover {
      transform: translateX(15px);
      color: #ffcc00;
    }
    .skills i {
      margin-right: 20px;
      color: #ff6f61;
      font-size: 1.8em;
      transition: transform 0.3s ease;
    }
    .skills li:hover i {
      transform: rotate(360deg);
    }
    
    /* Contact Section */
    .contact ul {
      list-style: none;
      padding: 0;
      display: flex;
      justify-content: center;
      gap: 25px;
      margin-top: 20px;
    }
    .contact a {
      color: #ffcc00;
      text-decoration: none;
      font-size: 2.5em;
      transition: transform 0.3s ease, color 0.3s ease;
    }
    .contact a:hover {
      transform: scale(1.3);
      color: #fff;
    }

    /* Footer */
    footer {
      font-size: 1.2em;
      margin-top: 20px;
      text-shadow: 1px 1px 3px rgba(0,0,0,0.3);
      color: #ffcc00;
    }
  </style>
</head>
<body>
  
  <header>
    <h1>Joseph Onyango | Creative Developer</h1>
  </header>
  
  <div class="card">
    <section class="about">
      <h2>About Me</h2>
      <p>Hi, I'm Joseph Onyango—a passionate Creative Developer blending artistic vision with technical expertise. Since 2024, I've been crafting visually striking, seamless digital experiences.</p>
      <p>I specialize in merging art and technology to build captivating web and mobile applications that push creative boundaries.</p>
    </section>
    
    <section class="skills">
      <h2>Skills & Expertise</h2>
      <ul>
        <li><i class="fas fa-code"></i> Front-end: CSS & JavaScript for dynamic UIs.</li>
        <li><i class="fas fa-database"></i> Back-end: Python & SQL for robust applications.</li>
        <li><i class="fas fa-mobile-alt"></i> Mobile: Kotlin for smooth app development.</li>
        <li><i class="fas fa-paint-brush"></i> Creative Design: Fusing art with code.</li>
        <li><i class="fas fa-lightbulb"></i> Problem-Solving: Innovative and analytical approach.</li>
      </ul>
    </section>
    
    <section class="contact">
      <h2>Connect With Me</h2>
      <ul>
        <li><a href="mailto:jesuspromisesmedia@gmail.com?subject=Let's%20Collaborate!" target="_blank"><i class="fas fa-envelope"></i></a></li>
        <li><a href="https://www.tiktok.com/@princelailan" target="_blank"><i class="fab fa-tiktok"></i></a></li>
        <li><a href="https://www.instagram.com/prince_lailan" target="_blank"><i class="fab fa-instagram"></i></a></li>
        <li><a href="https://twitter.com/princelailan" target="_blank"><i class="fab fa-twitter"></i></a></li>
        <li><a href="https://github.com/princelailan" target="_blank"><i class="fab fa-github"></i></a></li>
        <li><a href="https://www.linkedin.com/in/joseph-onyango-b98307348?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=a" target="_blank"><i class="fab fa-linkedin"></i></a></li>
        <li><a href="https://wa.me/message/MFLNQT63QNSKC1" target="_blank"><i class="fab fa-whatsapp"></i></a></li>
        <li><a href="https://www.facebook.com/profile.php?id=100070432659655" target="_blank"><i class="fab fa-facebook"></i></a></li>
        <li><a href="https://x.com/JosephOnyash" target="_blank"><i class="fab fa-x"></i></a></li>
      </ul>
    </section>
  </div>
  
  <footer>
    Let's create something extraordinary together!
  </footer>
  
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Joseph Onyango | Creative Developer</title>
  
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet" />
  
  <!-- FontAwesome for Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" />
  
  <style>
    /* Basic Reset & Fonts */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Montserrat', sans-serif;
      color: #fff;
      text-align: center;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      overflow-x: hidden;
      background-image: url('https://your-image-url.com'); /* Replace with your image */
      background-size: cover;
      background-position: center;
      background-attachment: fixed;
    }
    
    /* Overlay for readability */
    body::after {
      content: "";
      position: fixed;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background: rgba(0, 0, 0, 0.6);
      z-index: -1;
    }

    /* Header Styling */
    header {
      margin-bottom: 20px;
    }
    header h1 {
      font-size: 3em;
      font-weight: 700;
      letter-spacing: 2px;
      text-shadow: 4px 4px 8px rgba(0,0,0,0.5);
      color: #ff6f61;
      text-transform: uppercase;
    }
    
    /* Glassmorphism Card */
    .card {
      background: rgba(255, 255, 255, 0.2);
      backdrop-filter: blur(15px);
      padding: 35px 30px;
      width: 90%;
      max-width: 800px;
      border-radius: 20px;
      box-shadow: 0 6px 30px rgba(0, 0, 0, 0.3);
      margin-bottom: 25px;
      transition: transform 0.3s ease-in-out;
    }
    .card:hover {
      transform: translateY(-10px);
    }

    /* Section Headers */
    h2 {
      font-size: 2em;
      margin-bottom: 15px;
      color: #ffcc00;
      text-transform: uppercase;
      letter-spacing: 2px;
    }

    /* Paragraphs */
    p {
      font-size: 1.1em;
      line-height: 1.8;
      margin-bottom: 18px;
      text-shadow: 1px 1px 5px rgba(0,0,0,0.4);
    }

    /* Skills Section */
    .skills ul {
      list-style: none;
      padding: 0;
      text-align: left;
      margin: 0 auto;
      max-width: 650px;
    }
    .skills li {
      font-size: 1.3em;
      margin: 15px 0;
      display: flex;
      align-items: center;
      transition: transform 0.3s, color 0.3s ease;
    }
    .skills li:hover {
      transform: translateX(15px);
      color: #ffcc00;
    }
    .skills i {
      margin-right: 20px;
      color: #ff6f61;
      font-size: 1.8em;
      transition: transform 0.3s ease;
    }
    .skills li:hover i {
      transform: rotate(360deg);
    }
    
    /* Contact Section */
    .contact ul {
      list-style: none;
      padding: 0;
      display: flex;
      justify-content: center;
      gap: 25px;
      margin-top: 20px;
    }
    .contact a {
      color: #ffcc00;
      text-decoration: none;
      font-size: 2.5em;
      transition: transform 0.3s ease, color 0.3s ease;
    }
    .contact a:hover {
      transform: scale(1.3);
      color: #fff;
    }

    /* Footer */
    footer {
      font-size: 1.2em;
      margin-top: 20px;
      text-shadow: 1px 1px 3px rgba(0,0,0,0.3);
      color: #ffcc00;
    }
  </style>
</head>
<body>
  
  <header>
    <h1>Joseph Onyango | Creative Developer</h1>
  </header>
  
  <div class="card">
    <section class="about">
      <h2>About Me</h2>
      <p>Hi, I'm Joseph Onyango—a passionate Creative Developer blending artistic vision with technical expertise. Since 2024, I've been crafting visually striking, seamless digital experiences.</p>
      <p>I specialize in merging art and technology to build captivating web and mobile applications that push creative boundaries.</p>
    </section>
    
    <section class="skills">
      <h2>Skills & Expertise</h2>
      <ul>
        <li><i class="fas fa-code"></i> Front-end: CSS & JavaScript for dynamic UIs.</li>
        <li><i class="fas fa-database"></i> Back-end: Python & SQL for robust applications.</li>
        <li><i class="fas fa-mobile-alt"></i> Mobile: Kotlin for smooth app development.</li>
        <li><i class="fas fa-paint-brush"></i> Creative Design: Fusing art with code.</li>
        <li><i class="fas fa-lightbulb"></i> Problem-Solving: Innovative and analytical approach.</li>
      </ul>
    </section>
    
    <section class="contact">
      <h2>Connect With Me</h2>
      <ul>
        <li><a href="mailto:jesuspromisesmedia@gmail.com?subject=Let's%20Collaborate!" target="_blank"><i class="fas fa-envelope"></i></a></li>
        <li><a href="https://www.tiktok.com/@princelailan" target="_blank"><i class="fab fa-tiktok"></i></a></li>
        <li><a href="https://www.instagram.com/prince_lailan" target="_blank"><i class="fab fa-instagram"></i></a></li>
        <li><a href="https://twitter.com/princelailan" target="_blank"><i class="fab fa-twitter"></i></a></li>
        <li><a href="https://github.com/princelailan" target="_blank"><i class="fab fa-github"></i></a></li>
        <li><a href="https://www.linkedin.com/in/joseph-onyango-b98307348?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=a" target="_blank"><i class="fab fa-linkedin"></i></a></li>
        <li><a href="https://wa.me/message/MFLNQT63QNSKC1" target="_blank"><i class="fab fa-whatsapp"></i></a></li>
        <li><a href="https://www.facebook.com/profile.php?id=100070432659655" target="_blank"><i class="fab fa-facebook"></i></a></li>
        <li><a href="https://x.com/JosephOnyash" target="_blank"><i class="fab fa-x"></i></a></li>
      </ul>
    </section>
  </div>
  
  <footer>
    Let's create something extraordinary together!
  </footer>
  
</body>
</html>
