# HACKATHON-PROJECT<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Aso Uduma's Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      background-color: #f4f4f4;
      color: #333;
    }

    header, section {
      padding: 20px;
    }

    header {
      background: #222;
      color: #fff;
      text-align: center;
    }

    nav a {
      margin: 0 10px;
      color: #fff;
      text-decoration: none;
    }

    section {
      background: #fff;
      margin: 20px;
      border-radius: 8px;
    }

    h2 {
      border-bottom: 2px solid #eee;
      padding-bottom: 10px;
    }

    ul {
      list-style: none;
      padding-left: 0;
    }

    ul li {
      margin-bottom: 8px;
    }

    .projects a {
      display: block;
      margin: 10px 0;
      color: #0077cc;
    }

    .contact-form input, .contact-form textarea {
      display: block;
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 4px;
    }

    .contact-form button {
      padding: 10px 20px;
      background-color: #0077cc;
      color: #fff;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #222;
      color: #fff;
    }
  </style>
</head>
<body>
  <header>
    <h1>Aso Uduma's Portfolio</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#languages">Languages</a>
      <a href="#education">Education</a>
      <a href="#interests">Interests</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I'm Aso Uduma, a passionate developer who thrives on turning ideas into elegant web solutions. I'm driven by a love for clean code and a thirst for learning—whether it's mastering the intricacies of JavaScript or diving into new frameworks like React.</p>
  </section>

  <section id="languages">
    <h2>Programming Languages</h2>
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
      <li>Python</li>
      <li>Java</li>
    </ul>
  </section>

  <section id="education">
    <h2>Educational Background</h2>
    <p>BSc in Economics – National Open University</p>
    <p>Diploma in Software Engineering - Power Learn Project</p>
    <p><a href="your-cv-link.pdf" download>Download My CV</a></p>
  </section>

  <section id="interests">
    <h2>Tech Interests</h2>
    <p>I’m excited by innovations in AI, data science, and mobile development. I’m also passionate about building intuitive user experiences and solving real-world problems through software.</p>
  </section>

  <section id="projects" class="projects">
    <h2>Projects</h2>
    <p><a href="https://github.com/yourusername/project1">Project One – Portfolio Website</a> A fully responsive HTML/CSS personal site showcasing projects and skills.</p>
    <p><a href="https://github.com/yourusername/project2">Project Two – Task Manager</a> A sleek, JavaScript-powered web app to manage daily tasks efficiently.</p>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <form class="contact-form">
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your Email" required />
      <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Aso Uduma's Portfolio. All rights reserved.</p>
  </footer>
</body>
</html>
