<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Chante Johnson – Instructional Designer & Web Developer</title>
  <style>
    html {
      scroll-behavior: smooth;
    }

    .banner {
      width: 100%;
      height: 300px;
      background-image: url('backgro.png');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
    }

    .top-nav {
      width: 100%;
      background-color: #1a1a1a;
      padding: 1rem 2rem;
      position: fixed;
      top: 0;
      left: 0;
      z-index: 1000;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    }

    .nav-container {
      display: flex;
      justify-content: space-between;
      align-items: center;
      max-width: 1200px;
      margin: 0 auto;
    }

    .brand {
      color: #f5f5f5;
      font-size: 1.2rem;
      font-weight: 700;
      letter-spacing: 0.5px;
    }

    .nav-links {
      display: flex;
      list-style: none;
      margin: 0;
      padding: 0;
    }

    .nav-links li {
      margin-left: 2rem;
    }

    .nav-links a {
  color: #ffffff;
  text-decoration: none;
  font-size: 1rem;
  font-weight: 600;
  transition: color 0.3s ease;
}

    .nav-links a:hover,
    .nav-links a:focus {
      color: #00aaff;
      text-decoration: underline;
      outline: none;
    }
    body {
  padding-top: 80px;
}
  </style>
</head>
<body>

    <!-- Navigation -->
<nav class="top-nav" role="navigation" aria-label="Main navigation">
  <div class="nav-container">
    <div class="brand">Chante Johnson</div>
    <ul class="nav-links">
      <li><a href="index.html">About</a></li>
      <li><a href="Projects.html">Projects</a></li>
      <li><a href="Experience.html">Resume</a></li>
      <li><a href="Contact.html">Contact</a></li>
    </ul>
  </div>
</nav>

<!-- Banner  -->
    <div class="banner"></div>

<!-- Main Content -->
  <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: flex-start; padding: 3rem 2rem; max-width: 1200px; margin: auto; gap: 2rem;">

    <!-- Bio Text -->
  <div style="flex: 1; min-width: 300px;">
    <h1 style="font-size: 2.5rem; color: #880E4F; margin-bottom: 1rem;">Born for Innovation</h1>
    <div style="font-size: 1.25rem; line-height: 1.8; color: #1a1a1a;">
      <p>I’m Chante Johnson, a technologist and learning experience designer with a Master of Arts in Learning, Design, and Technology and a Bachelor of Science in Computer Science. My career spans public service, government, healthcare, HVAC, internet, and cable industries, where I’ve applied my skills to create inclusive, user-centered digital solutions. I specialize in bridging technical systems with human-centered design and stay current with emerging technologies—especially in areas like AI—by attending workshops, following industry podcasts, and engaging with thought leaders. I built my professional portfolio site from scratch to showcase my work and reflect my commitment to innovation, equity, and using technology to empower communities and create meaningful impact.</p>
    </div>
  </div>

  <!-- Profile Photo -->
  <div style="flex: 0 0 280px; text-align: center;">
    <img src="one.png" alt="Chante Johnson posing in a professional setting" style="width: 100%; max-width: 280px; border-radius: 50%; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
  </div>

</div>

<!-- Banner  -->
   <div class="banner"></div>

<!-- Projects -->  
  <h3> Cybersecurity & HIPAA in the Workplace Module</h3>
    <p>
     Cybersecurity & HIPAA in the Workplace is a microlearning module I designed to help employees build everyday habits that protect sensitive data. Through interactive lessons, real-world scenarios, and quick knowledge checks, I guide learners through the essentials of HIPAA compliance, secure sharing practices, breach response, and cloud safety. The course is built in Articulate Rise
 with accessibility and clarity at its core—perfect for hybrid teams, healthcare professionals, and anyone who handles protected information.
    </p>
    <ul style="list-style: none; padding-left: 0; margin-bottom: 2rem;">
      <li>
        <a href="cybersecurity.pdf" target="_blank" style="color: #0078D4; text-decoration: none;">
          🗂️ HIPAA-Compliance-Module
        </a>
      </li>
    <h3>Instructional Presentations</h3>
    <p>
     This curated collection of slide decks is designed for adult learners in professional settings—whether in workshops, training sessions, or self-paced development. I focus on clarity, accessibility, and practical application across topics like leveraging procurement authority to promote health equity and strengthening public speaking skills.
    </p>
    <ul style="list-style: none; padding-left: 0; margin-bottom: 2rem;">
      <li>
        <a href="Leveraging.pptx" target="_blank" style="color: #0078D4; text-decoration: none;">
          🗂️ Using Purchasing Power to Promote Health Equity
        </a>
      </li>
     
      <li>
        <a href="YourThoughtsandFeelings.pdf" target="_blank" style="color: #0078D4; text-decoration: none;">
           🗂️ Ways to Improve Public Speaking
        </a>
      </li>
    </ul>

    <h3>Healthcare Training Module</h3>
    <p>
       I built this onboarding guide from scratch using HTML, CSS, and GitHub to support professionals across hospitals, nursing homes, funeral homes, coroner offices, and the Pennsylvania Department of Health’s registered offices. Tailored by role, the module delivers clear, intuitive guidance for navigating the eVitals system with confidence and compliance.
    </p>
      <a href="https://cjohns4.github.io/chante-healthcare-training/Welcome.html" target="_blank" style="color: #0078D4; text-decoration: none;">
        🔗 eVitals Navigator – Role-Based Healthcare Onboarding
      </a><br>

    <h3>Microeconomics Module</h3>
    <p>
      As a sample project for Columbia College’s ECON 294: Microeconomics, I built this interactive module using HTML, CSS, and GitHub to help students explore monopolistic competition, oligopolies, and market power. The content is organized into digestible sections with guided readings and real-world context, designed to support conceptual clarity in an online learning environment.
    </p>
      <a href="https://cjohns4.github.io/ECON-Module-Columbia/" target="_blank" style="color: #0078D4; text-decoration: none;">
        🔗 Microeconomics for Columbia College
      </a><br>
    <h3>Blog</h3>
    <p>
      This is where I share my thoughts on digital literacy, accessibility, and what it really means to design for real-world learners. From instructional strategies to tech tips, I explore how thoughtful design can empower people—not just inform them. If you're curious about how I build inclusive, learner-centered experiences, this is the place to start.
    </p>
 <a href="https://chanteshotspot.blogspot.com/" target="_blank" style="color: #0078D4; text-decoration: none;">
       🔗 Visit my blog
      </a><br>
  <hr>
  
<!-- Banner  -->
    <div class="banner"></div>
  
<!-- Resume -->
  <h2>📄 Experience</h2>
  <p><a href="ChanteJohnson.pdf" target="_blank" style="
  display: inline-block;
  background-color: #D35400;
  color: white;
  padding: 0.75rem 1.5rem;
  border-radius: 6px;
  text-decoration: none;
  font-weight: bold;
  margin-top: 1rem;
">
  📄 Download Resume
</a></p>

  <hr>

<!-- Banner  -->
    <div class="banner"></div>
  
<!-- Contact -->
<!-- Banner -->
<div class="banner"></div>

<!-- Contact Section -->
<section style="padding:2rem; background-color:#f9f9f9; border-radius:8px; max-width:700px; margin:auto;">

  <h1 style="color:#880E4F; border-bottom:2px solid #880E4F; padding-bottom:0.3rem; margin-bottom:1.5rem;">
    Contact 
  </h1>

  <p style="font-size:0.95rem; color:#555; margin-bottom:1rem;">
    <em>* indicates required field</em>
  </p>

  <form action="https://formspree.io/f/mvgbkdok" method="POST" style="max-width:600px;">
    <label for="name" style="display:block; margin-bottom:0.5rem;">Name <span style="color:red;">*</span></label>
    <input type="text" id="name" name="name" required style="width:100%; padding:0.5rem; margin-bottom:1rem;">

    <label for="email" style="display:block; margin-bottom:0.5rem;">Email <span style="color:red;">*</span></label>
    <input type="email" id="email" name="email" required style="width:100%; padding:0.5rem; margin-bottom:1rem;">

    <label for="message" style="display:block; margin-bottom:0.5rem;">How can I help you? <span style="color:red;">*</span></label>
    <textarea id="message" name="message" rows="5" required style="width:100%; padding:0.5rem; margin-bottom:1rem;"></textarea>

    <div class="g-recaptcha" data-sitekey="6LcS4LcrAAAAAIh0WPUH74KlurMc9rbNIM893vcK"></div>

    <button type="submit" style="background-color:#0078D4; color:#fff; padding:0.75rem 1.5rem; border:none; border-radius:4px; cursor:pointer;">
      Submit
    </button>
  </form>

  <ul style="list-style:none; padding-left:0; font-size:1.1rem; margin-top:2rem;">
    <li>
      chantej1@yahoo.com<br>
     
    <li style="margin-top:1rem;">
      <strong>LinkedIn:</strong>
      <a href="https://www.linkedin.com/in/chante-johnson-140171309/" target="_blank" style="color:#880E4F;">
        linkedin.com/in/chante-johnson-140171309
      </a>
    </li>

    <li style="margin-top:1rem;">
      <strong>Location:</strong> Austin–Killeen, TX area
    </li>
  </ul>

  <p style="margin-top:2rem; font-size:1.1rem;">
   Let’s collaborate to build learning experiences that are clear, inclusive, and purpose-driven—designed not just to inform, but to empower. I believe education should meet people where they are and give them the tools to go further with confidence and clarity.
  </p>

</section>
<script src="https://www.google.com/recaptcha/api.js" async defer></script>

</body>
</html>
