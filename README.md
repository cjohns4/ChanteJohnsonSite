<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Chante' Johnson – Instructional Designer & Web Developer</title>
 <style>
  html {
  scroll-behavior: smooth;
  font-size: 100%; /* Equivalent to 16px on most browsers */
}

body {
  padding-top: 80px;
  font-size: 1.125rem; /* 18px */
  font-family: 'Segoe UI', 'Helvetica Neue', Arial, sans-serif;
  line-height: 1.7;
  color: #333;
}
   h1, h2, h3, h4, h5, h6 {
  font-family: inherit;
  line-height: 1.3;
  margin-top: 1.5rem;
  margin-bottom: 0.5rem;
}

h1 { font-size: 2.5rem; }   /* ~40px */
h2 { font-size: 2rem; }     /* ~32px */
h3 { font-size: 1.75rem; }  /* ~28px */
h4 { font-size: 1.5rem; }   /* ~24px */
h5 { font-size: 1.25rem; }  /* ~20px */
h6 { font-size: 1.125rem; } /* ~18px */
p {
  font-size: 1.125rem;
  margin-bottom: 1rem;
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
    font-size: 1.5rem; /* 24px */
    font-weight: 700;
    letter-spacing: 0.5px;
  }

  .nav-links {
    display: flex;
    list-style: none;
    margin: 0;
    padding: 0;
    align-items: center;
  }

  .nav-links li {
    margin-left: 2rem;
    position: relative;
  }

  .nav-links a {
    color: #ffffff;
    text-decoration: none;
    font-size: 1.125rem; /* 18px */
    font-weight: 600;
    transition: color 0.3s ease;
  }

  .nav-links a:hover,
  .nav-links a:focus {
    color: #00aaff;
    text-decoration: underline;
    outline: none;
  }

  .menu-icon {
    list-style: none;
  }

  .menu-icon button {
    background: none;
    border: none;
    font-size: 1.5rem;
    cursor: pointer;
    color: #ffffff;
  }

  .dropdown {
    display: none;
    position: absolute;
    top: 2rem;
    right: 0;
    background-color: white;
    border: 1px solid #ccc;
    list-style: none;
    padding: 0.5rem;
    box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    z-index: 1001;
  }

  .dropdown li {
    margin: 0.5rem 0;
  }

  .dropdown li a {
    color: #333;
    text-decoration: none;
  }
  @media (max-width: 600px) {
  iframe {
    height: 300px;
  }
} 
@media (max-width: 600px) {
  .nav-links a {
    font-size: 0.85rem; /* ≈13.6px */
  }

  .dropdown li a {
    font-size: 0.85rem;
  }

  .nav-links li {
    margin-left: 1rem; /* reduce spacing between tabs */
  }
}

</style>
</head>
<body>

<!-- Navigation -->
<nav class="top-nav" role="navigation" aria-label="Main navigation">
  <div class="nav-container">
       <ul class="nav-links">
      <li><a href="index.html">About</a></li>
      <li><a href="Projects.html">Projects</a></li>
      <li><a href="Experience.html">Resume</a></li>
      <li><a href="Contact.html">Contact</a></li>
      <li class="menu-icon">
        <button onclick="toggleMenu()">☰</button>
        <ul class="dropdown" id="dropdownMenu">
          <li><a href="index.html">About</a></li>
          <li><a href="Projects.html">Projects</a></li>
                <li><a href="Experience.html">Resume</a></li>
          <li><a href="Contact.html">Contact</a></li>
         
        </ul>
      </li>
    </ul>
  </div>
</nav>

<!-- Banner  -->
    <div class="banner"></div>

<!-- Main Content -->
  <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: flex-start; padding: 3rem 2rem; max-width: 1200px; margin: auto; gap: 2rem;">

    <!-- Bio Text -->
      <div style="flex: 1; min-width: 300px;">
      <h1 style="font-size: 2.5rem; color: #880E4F; margin-bottom: 1rem;">I’m Chante’ Johnson—an IT Systems Support Specialist and Learning Experience Designer with 20+ years supporting enterprise and healthcare environments.</h1>
      <div style="font-size: 1.25rem; line-height: 1.8; color: #1a1a1a;">
        <p>I blend technical troubleshooting, systems administration, and user‑focused training to help clinics, teams, and statewide organizations adopt technology with confidence. Whether resolving complex issues, implementing EHR workflows, or building clear, accessible learning tools, my work is rooted in clarity, reliability, and human‑centered design.</p>
        <p>This site reflects that blend of technical skill and thoughtful craft—hand‑coded, intentionally designed, and built to make complex systems feel simple.</p>
       
        <h2>Let’s Create Learning That Resonates.</h2>
        <p>I develop content that’s clear, inclusive, and intentionally built. If you’re envisioning a project, seeking collaboration, or exploring new possibilities—I’d love to connect. Reach out and let’s discover what we can build together. Please <a href="mailto:chantej1@yahoo.com?subject=Inquiry from Portfolio Site">contact me</a> 
          and discover what we can build together.</p>
      </div>
    </div>

  <!-- Profile Photo -->
  <div style="flex: 0 0 280px; text-align: center;">
    <img src="807E669C-0CA1-461A-A62B-B02DECD0A6DC.png" alt="Chante Johnson in a black blazer posing in a professional setting" style="width: 100%; max-width: 280px; border-radius: 50%; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
  </div>

</div>
<footer style="text-align: center; font-size: 0.9rem; color: #666; margin-top: 3rem;">
  © 2026 Chante’ Johnson. All rights reserved.  
  Content on this site may not be reproduced, distributed, or used without written permission.
</footer>
<!-- Banner  -->
   <div class="banner"></div>

<!-- Projects Section Header -->
<section>
  <div style="max-width: 800px; margin: 0 auto; text-align: center; padding: 2rem 1rem;">
    <h1 style="margin-bottom: 0.5rem;">Project Highlights</h1>
    <p style="font-size: 1.15rem; line-height: 1.8; margin-bottom: 2rem;">
      Each project reflects my commitment to inclusive, learner-centered design—where clarity, strategy, and storytelling come together to create meaningful experiences.
    </p>
    <hr style="width: 60%; margin: 0 auto; border: none; border-top: 1px solid #ddd;">
  </div>
</section>

<!-- Cybersecurity Module -->
<section>
  <div style="max-width: 600px; margin: 0 auto; text-align: right; padding: 2rem 1rem;">
    <h3>Cybersecurity & HIPAA in the Workplace Module</h3>
    <p>Cybersecurity & HIPAA in the Workplace is a microlearning module I designed to help employees build everyday habits that protect sensitive data...</p>
    <hr style="width: 60%; margin: 0 auto; border: none; border-top: 1px solid #ddd;">
  </div>
  <div style="max-width: 800px; margin: 0 auto; text-align: left; padding: 1rem;">
    <iframe src="cybersecurity.pdf" width="100%" height="200" style="border:1px solid #ccc; border-radius:8px; margin-bottom:2rem;"></iframe>
    <p>
      <a href="cybersecurity.pdf" target="_blank" style="color: #0078D4; text-decoration: none;">
        📄 View or download the full presentation (PDF)
      </a>
    </p>
  </div>
</section>

<!-- Health Equity Presentation -->
<section>
  <div style="max-width: 600px; margin: 0 auto; text-align: right; padding: 2rem 1rem;">
    <h3>Using Purchasing Power to Promote Health Equity</h3>
    <p>This presentation explores how procurement policies can be used as strategic tools to advance health equity...</p>
  </div>
  <div style="max-width: 600px; margin: 0 auto; text-align: left; padding: 1rem;">
    <iframe src="Delegation of Procurement Authority.pdf" width="100%" height="200" style="border:1px solid #ccc; border-radius:8px; margin-bottom:2rem;"></iframe>
    <p>
      <a href="Delegation of Procurement Authority.pdf" target="_blank" style="color: #0078D4; text-decoration: none;">
        📄 View or download the full presentation (PDF)
      </a>
    </p>
  </div>
</section>

<!-- Public Speaking -->
<section>
  <div style="max-width: 600px; margin: 0 auto; text-align: right; padding: 2rem 1rem;">
    <h3 id="public-speaking-title" style="font-size: 1.5rem; margin-top: 2rem;">Ways to Improve Public Speaking</h3>
    <p>Public speaking hasn’t always come naturally to me—but over time, I’ve learned how structure, intention, and empathy can transform a message...</p>
  </div>
  <div style="max-width: 600px; margin: 0 auto; text-align: left; padding: 1rem;">
    <iframe src="YourThoughtsandFeelings.pdf" width="100%" height="200" style="border:1px solid #ccc; border-radius:8px; margin-bottom:2rem;"></iframe>
    <p>
      <a href="YourThoughtsandFeelings.pdf" target="_blank" style="color: #0078D4; text-decoration: none;">
        📄 View or download the full presentation (PDF)
      </a>
    </p>
  </div>
</section>

<!-- Healthcare Training Module -->
<section>
  <div style="max-width: 600px; margin: 0 auto; text-align: right; padding: 2rem 1rem;">
    <h3>Healthcare Training Module</h3>
    <p>I built this onboarding guide from scratch using HTML, CSS, and GitHub to support professionals across hospitals...</p>
  </div>
  <div style="max-width: 600px; margin: 0 auto; text-align: left; padding: 1rem;">
    <iframe src="https://cjohns4.github.io/chante-healthcare-training/Welcome.html" width="100%" height="200" style="border:1px solid #ccc; border-radius:8px; margin-bottom:2rem;"></iframe>
    <p>
      <a href="https://cjohns4.github.io/chante-healthcare-training/Welcome.html" target="_blank" style="color: #0078D4; text-decoration: none;">
        🔗 eVitals Navigator – Role-Based Healthcare Onboarding
      </a>
    </p>
  </div>
</section>

<!-- Microeconomics Module -->
<section>
  <div style="max-width: 600px; margin: 0 auto; text-align: right; padding: 2rem 1rem;">
    <h3>Microeconomics Module</h3>
    <p>As a sample project for Columbia College’s ECON 294: Microeconomics, I built this interactive module...</p>
  </div>
  <div style="max-width: 600px; margin: 0 auto; text-align: left; padding: 1rem;">
    <iframe src="https://cjohns4.github.io/ECON-Module-Columbia/" width="100%" height="200" style="border:1px solid #ccc; border-radius:8px; margin-bottom:2rem;"></iframe>
    <p>
      <a href="https://cjohns4.github.io/ECON-Module-Columbia/" target="_blank" style="color: #0078D4; text-decoration: none;">
        🔗 Microeconomics for Columbia College
      </a>
    </p>
  </div>
</section>

<!-- Blog -->
<section>
  <div style="max-width: 600px; margin: 0 auto; text-align: right; padding: 2rem 1rem;">
    <h3>Blog</h3>
    <p>This is where I share my thoughts on digital literacy, accessibility, and what it really means to design for real-world learners...</p>
  </div>
  <div style="max-width: 600px; margin: 0 auto; text-align: left; padding: 1rem;">
    <iframe src="https://chanteshotspot.blogspot.com/" width="100%" height="200" style="border:1px solid #ccc; border-radius:8px; margin-bottom:2rem;"></iframe>
    <p>
      <a href="https://chanteshotspot.blogspot.com/" target="_blank" style="color: #0078D4; text-decoration: none;">
        🔗 Visit my blog
      </a>
    </p>
  </div>
  <hr style="border: none; border-top: 2px solid #D35400; margin: 3rem 0;">
</section>
<footer style="max-width: 600px; margin: 3rem auto; text-align: right; font-size: 0.9rem; color: #666;">
  © 2026 Chante’ Johnson. All rights reserved.  
  Content on this site may not be reproduced, distributed, or used without written permission.
</footer>
  <hr>
  
<!-- Banner  -->
    <div class="banner"></div>
  
<!-- Experience Section -->
  <div style="max-width: 1000px; margin: 0 auto; text-align: left; padding: 2rem 1rem;">
    <h1>📄 Resume</h1>
    </div>
 <div style="max-width: 1000px; margin: 0 auto; padding: 1rem;">
  <iframe 
    src="resume CJ.pdf" 
    width="100%" 
    height="800" 
    style="border: 1px solid #ccc; border-radius: 8px;"
    title="resume CJ.pdf"
  ></iframe>
    <p>
      <a href="resume CJ.pdf" target="_blank" style="color: #0078D4; text-decoration: none;">
        📄 View or download Resume (PDF)
      </a>
    </p>
  </div>
</section>

<footer style="text-align: center; font-size: 0.9rem; color: #666; margin-top: 3rem;">
  © 2026 Chante’ Johnson. All rights reserved.  
  Content on this site may not be reproduced, distributed, or used without written permission.
</footer>
<hr>
<!-- Banner  -->
    <div class="banner"></div>
  
<!-- Contact -->
<!-- Banner -->
<div class="banner"></div>

<!-- Contact Section -->
<section style="padding:2rem; background-color:#f9f9f9; border-radius:8px; max-width:700px; margin:auto;">

  <h1 style="color:#880E4F; border-bottom:2px solid #880E4F; padding-bottom:0.3rem; margin-bottom:1.5rem;">
    📬 Contact 
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
  
      <strong>LinkedIn:</strong>
      <a href="https://www.linkedin.com/in/chante-johnson-140171309/" target="_blank" style="color:#880E4F;">
        linkedin.com/in/chante-johnson-140171309
      </a>
    </li>

    <li style="margin-top:1rem;">
      <strong>Location:</strong> Austin–Killeen, TX area
    </li>
  </ul>

</section>
<footer style="text-align: center; font-size: 0.9rem; color: #666; margin-top: 3rem;">
  © 2026 Chante’ Johnson. All rights reserved.  
  Content on this site may not be reproduced, distributed, or used without written permission.
</footer>
<script src="https://www.google.com/recaptcha/api.js" async defer></script>

<script>
  function toggleMenu() {
    const menu = document.getElementById("dropdownMenu");
    menu.style.display = menu.style.display === "block" ? "none" : "block";
  }

  window.onclick = function(event) {
    if (!event.target.matches('.menu-icon button')) {
      const dropdown = document.getElementById("dropdownMenu");
      if (dropdown && dropdown.style.display === "block") {
        dropdown.style.display = "none";
      }
    }
  };
</script>

</body>
</html>
