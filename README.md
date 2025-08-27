<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Chante Johnson – Instructional Designer & Web Developer</title>
  <style>
    body {
      background-color: #f0f4f8;
      color: #333333;
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
    }

    nav {
      background-color: #0078D4;
      padding: 1rem;
      text-align: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 1rem;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    h2 {
      color: #0078D4;
      border-bottom: 2px solid #FFD166;
      padding-bottom: 0.3rem;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    #contact {
      animation: fadeIn 1s ease-out;
    }

    .contact-card {
      background-color: white;
      padding: 1.5rem;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    .contact-card a {
      color: #0078D4;
      text-decoration: none;
    }

    .contact-card a:hover {
      text-decoration: underline;
    }
  </style>
</head>

<body>

  <!-- Navigation -->
<nav>
  <a href="#hero">Home</a>
  <a href="#projects">Projects</a>
  <a href="#contact">Contact</a>
</nav>
  <!-- Hero Banner -->
  <section id="hero" style="background-color: #0078D4; color: white; padding: 2rem; text-align: center;">
  <section style="background-color: #0078D4; color: white; padding: 2rem; text-align: center;">
    <h1 style="margin-bottom: 0.5rem;">Code, Clarity, and Connection</h1>
    <p style="font-size: 1.1rem;">Empowering learners through accessible design</p>
  </section>

  <!-- Contact Section -->
  <section id="contact" style="padding: 2rem;">
    <div class="contact-card">
      <h2>Let's Connect</h2>
      <p>I’m Chante—an Instructional Designer and Web Developer passionate about creating accessible, learner-centered training experiences. I’m open to remote, hybrid, and in-person roles, especially in the Austin–Killeen area or with organizations that value inclusive design and professional development.</p>

      <ul style="list-style: none; padding-left: 0;">
        <li><strong>Email:</strong> chantej1986@gmail.com  
          <br>
          <a href="mailto:chantej1986@gmail.com" style="display: inline-block; margin-top: 0.5rem; padding: 0.5rem 1rem; background-color: #0078D4; color: white; text-decoration: none; border-radius: 4px;">Email Me</a>
        </li>
        <li><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/chante-johnson-140171309/" target="_blank">linkedin.com/in/chante-johnson-140171309</a></li>
        <li><strong>Portfolio:</strong> <a href="https://cjohns4.github.io/ECON-Module-Columbia/" target="_blank">cjohns4.github.io/ECON-Module-Columbia</a></li>
        <li><strong>Location:</strong> Austin–Killeen, TX area</li>
      </ul>

      <p style="margin-top: 1rem;">Let’s build something learner-centered, accessible, and impactful together.</p>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects" style="padding: 2rem; background-color: #ffffff;">
    <h2>Featured Projects</h2>
    <p>Here’s a look at some of my instructional design and web development work, including interactive modules and presentation materials designed for clarity, accessibility, and learner engagement.</p>

    <div style="display: flex; flex-wrap: wrap; gap: 2rem; margin-top: 1.5rem;">
      
      <!-- ECON Module Project -->
      <div style="flex: 1; min-width: 280px; background-color: #f0f4f8; padding: 1rem; border-radius: 8px; box-shadow: 0 2px 6px rgba(0,0,0,0.1);">
        <h3 style="color: #333;">ECON Module – Columbia</h3>
        <p>An interactive module exploring monopolistic competition and market dynamics. Built with accessibility-first design and responsive layout.</p>
        <a href="https://cjohns4.github.io/ECON-Module-Columbia/" target="_blank">View Module</a>
      </div>

      <!-- PowerPoint Presentations -->
      <div style="flex: 1; min-width: 280px; background-color: #f0f4f8; padding: 1rem; border-radius: 8px; box-shadow: 0 2px 6px rgba(0,0,0,0.1);">
        <h3 style="color: #333;">Instructional Presentations</h3>
        <p>Slide decks created for adult learners, covering topics like accessibility, SharePoint training, and instructional strategy. Designed with clarity and engagement in mind.</p>
        <a href="https://your-link-to-presentations.com" target="_blank">View Presentations</a>
      </div>

    </div>
  </section>

</body>
</html>
