<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Lakshana | Portfolio</title>

  <style>
    /* ====== RESET & BASE ====== */
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: "Poppins", sans-serif;
      background: #f9fafc;
      color: #222;
      line-height: 1.6;
      scroll-behavior: smooth;
    }
    a { text-decoration: none; color: inherit; }

    /* ====== HEADER ====== */
    header {
      position: sticky;
      top: 0;
      background: white;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
      z-index: 1000;
    }
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      max-width: 1100px;
      margin: auto;
      padding: 1rem;
    }
    .logo {
      font-size: 1.3rem;
      font-weight: 700;
      color: #3b82f6;
    }
    .nav-links {
      display: flex;
      gap: 1.5rem;
    }
    .nav-links a:hover {
      color: #3b82f6;
    }

    /* ====== HERO ====== */
    .hero {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: space-between;
      max-width: 1100px;
      margin: 3rem auto;
      padding: 2rem;
    }
    .hero-text {
      flex: 1 1 400px;
    }
    .hero-text h1 {
      font-size: 2.5rem;
      color: #111;
    }
    .hero-text p {
      margin-top: 1rem;
      color: #555;
    }
    .btn {
      display: inline-block;
      margin-top: 1.5rem;
      background: #3b82f6;
      color: #fff;
      padding: 0.8rem 1.5rem;
      border-radius: 8px;
      font-weight: 600;
      transition: background 0.3s;
    }
    .btn:hover {
      background: #2563eb;
    }
    .hero img {
      width: 300px;
      border-radius: 50%;
      box-shadow: 0 5px 20px rgba(0, 0, 0, 0.1);
    }

    /* ====== ABOUT ====== */
    section {
      max-width: 1000px;
      margin: auto;
      padding: 4rem 2rem;
    }
    h2 {
      font-size: 1.8rem;
      text-align: center;
      margin-bottom: 1.5rem;
      color: #3b82f6;
    }
    .about p {
      text-align: center;
      max-width: 700px;
      margin: auto;
      color: #444;
    }

    /* ====== PROJECTS ====== */
    .projects-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1.5rem;
      margin-top: 2rem;
    }
    .project-card {
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
      padding: 1.5rem;
      transition: transform 0.3s;
    }
    .project-card:hover {
      transform: translateY(-5px);
    }
    .project-card h3 {
      color: #111;
    }
    .project-card p {
      color: #555;
      margin: 0.8rem 0;
    }
    .project-card a {
      color: #3b82f6;
      font-weight: 600;
    }

    /* ====== CONTACT ====== */
    form {
      max-width: 600px;
      margin: 2rem auto;
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }
    input, textarea {
      padding: 0.8rem;
      border-radius: 8px;
      border: 1px solid #ccc;
      font-size: 1rem;
      width: 100%;
    }
    button {
      background: #3b82f6;
      color: white;
      padding: 0.8rem;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-size: 1rem;
      transition: background 0.3s;
    }
    button:hover {
      background: #2563eb;
    }

    /* ====== FOOTER ====== */
    footer {
      background: #111;
      color: #fff;
      text-align: center;
      padding: 1.5rem;
      margin-top: 3rem;
    }

    @media (max-width: 768px) {
      .hero { text-align: center; flex-direction: column; }
      .hero img { margin-top: 1.5rem; width: 200px; }
    }
  </style>
</head>
<body>
  <!-- ===== HEADER ===== -->
  <header>
    <nav>
      <div class="logo">Lakshana.</div>
      <div class="nav-links">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </div>
    </nav>
  </header>

  <!-- ===== HERO ===== -->
  <section id="home" class="hero">
    <div class="hero-text">
      <h1>Hi, I'm <span style="color:#3b82f6;">Lakshana</span></h1>
      <p>
        A passionate Computer Science student exploring modern web development,
        UI/UX design, and creative projects that make a difference.
      </p>
      <a href="#projects" class="btn">View My Work</a>
    </div>
    <img src="https://via.placeholder.com/300x300.png?text=Lakshana" alt="Lakshana profile photo" />
  </section>

  <!-- ===== ABOUT ===== -->
  <section id="about" class="about">
    <h2>About Me</h2>
    <p>
      I'm a final-year Computer Science & Engineering student who loves building responsive,
      user-friendly web applications. I enjoy transforming ideas into reality through clean code
      and thoughtful design.
    </p>
  </section>

  <!-- ===== PROJECTS ===== -->
  <section id="projects" class="projects">
    <h2>Projects</h2>
    <div class="projects-grid">
      <div class="project-card">
        <h3>Portfolio Website</h3>
        <p>My personal website built using HTML, CSS, and JavaScript to showcase my skills and work.</p>
        <a href="#">View Project →</a>
      </div>

      <div class="project-card">
        <h3>Smart Blind Stick</h3>
        <p>An IoT project designed to assist visually impaired individuals using ultrasonic sensors.</p>
        <a href="#">View Project →</a>
      </div>

      <div class="project-card">
        <h3>Oil Spill Detection</h3>
        <p>A system that detects oil spills in water using sensors and alerts the control system.</p>
        <a href="#">View Project →</a>
      </div>
    </div>
  </section>

  <!-- ===== CONTACT ===== -->
  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <form onsubmit="sendMessage(event)">
      <input type="text" id="name" placeholder="Your Name" required />
      <input type="email" id="email" placeholder="Your Email" required />
      <textarea id="message" rows="5" placeholder="Your Message..." required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <!-- ===== FOOTER ===== -->
  <footer>
    <p>© <span id="year"></span> Lakshana — Made with ❤️ and code.</p>
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();

    function sendMessage(event) {
      event.preventDefault();
      alert("Thank you for your message, Lakshana will reply soon!");
      event.target.reset();
    }
  </script>
</body>
</html>
