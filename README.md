# graphic-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Graphic Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>My Graphic Portfolio</h1>
    <nav>
      <ul>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#about">About Me</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="projects">
    <h2>Featured Work</h2>
    <div class="gallery">
      <div class="item"><img src="images/project1.jpg" alt="Project 1" /></div>
      <div class="item"><img src="images/project2.jpg" alt="Project 2" /></div>
      <div class="item"><img src="images/project3.jpg" alt="Project 3" /></div>
    </div>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>I’m a passionate graphic designer with a love for clean, bold visuals. I specialize in branding, illustration, and digital art.</p>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 My Graphic Portfolio</p>
  </footer>
</body>
</html>
