<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Chante' Johnson – Instructional Designer & Web Developer</title>
 <style>
  html {
    scroll-behavior: smooth;
  }

  body {
    padding-top: 80px;
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
    align-items: center;
  }

  .nav-links li {
    margin-left: 2rem;
    position: relative;
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
</style>
</head>
<body>

<!-- Navigation -->
<nav class="top-nav" role="navigation" aria-label="Main navigation">
  <div class="nav-container">
    <div class="brand">Chante' Johnson</div>
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
    <h1 style="font-size: 2.5rem; color: #880E4F; margin-bottom: 1rem;">Rooted in Story. Wired for Change.</h1>
    <div style="font-size: 1.25rem; line-height: 1.8; color: #1a1a1a;">
       <p>
    I’m Chante’ Johnson, a technologist and learning experience designer driven by clarity, inclusion, and lifelong learning. Originally from Harlem, New York, my journey has taken me across the East Coast and now to Texas—each chapter shaping how I approach design, communication, and growth. I see every challenge as a learning opportunity, and I bring that mindset into everything I create.
  </p>

  <p>
    My name, given to me by my aunt, is French for “to sing”—and I’ve always believed in the power of voice, whether through storytelling, design, or digital strategy. I love reading, traveling, and gaining new skills that keep me curious and connected.
  </p>

  <p><strong>Academically, my path reflects the layered approach I bring to my work:</strong></p>
  <ul>
    <li>
      My <strong>Master of Arts in Learning, Design, and Technology</strong> integrates instructional strategy, curriculum development, and digital learning leadership. Through courses like Instructional Methods for Digital Environments, Online Teaching Design, Assessment and Evaluation, and Issues and Trends in Digital Learning, I’ve built a foundation for designing inclusive, learner-centered experiences that are both strategic and innovative.
    </li>
    <li>
      My <strong>Bachelor of Science in Computer Science</strong> combines business principles with technical fluency in front-end development, databases, networking, and systems architecture. With coursework in Advanced Programming, Business Analytics, Corporate Finance, and Strategic Planning, I’ve developed the skills to build scalable, user-centered digital solutions that support real-world impact.
    </li>
    <li>
      My <strong>Associate of Science in Computer Information Systems</strong> provided hands-on training in advanced WAN/LAN networking, server patching, scripting, and hardware configuration. I also developed an advanced understanding of Microsoft Office products—including Excel, Word, Access, and PowerPoint—which continue to support my work in documentation, data analysis, and instructional design. The program included coursework in accounting, business applications, and statistics, giving me a practical foundation in both technical systems and analytical thinking.
    </li>
  </ul>
  <p>
    To reflect my skills and values, I built this portfolio site from the ground up—writing every line of code and designing every section to showcase not just what I do, but who I am: someone committed to innovation, equity, and using technology to make a meaningful impact.
  </p>

  <h3>How can I help you?</h3>
  <p>
    Let’s create learning that resonates—clear, inclusive, and built with purpose. I believe education should meet people where they are, honor their lived experiences, and equip them with the tools to grow, adapt, and thrive. My goal is to design content that doesn’t just deliver information, but inspires confidence and sparks meaningful change. Please <a href="mailto:chantej1@yahoo.com?subject=Inquiry from Portfolio Site">contact me</a> and discover what we can build together.
  </p>
</div>
  </div>

  <!-- Profile Photo -->
  <div style="flex: 0 0 280px; text-align: center;">
    <img src="right.jpeg" alt="Chante Johnson in a yellow blazer posing in a professional setting" style="width: 100%; max-width: 280px; border-radius: 50%; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
  </div>

</div>
<footer style="text-align: center; font-size: 0.9rem; color: #666; margin-top: 3rem;">
  © 2025 Chante’ Johnson. All rights reserved.  
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

  <!-- Cybersecurity Module -->
      <div style="text-align: center;">
      <h3>Cybersecurity & HIPAA in the Workplace Module</h3>
      <p>Cybersecurity & HIPAA in the Workplace is a microlearning module I designed to help employees build everyday habits that protect sensitive data. Through interactive lessons, real-world scenarios, and quick knowledge checks, I guide learners through the essentials of HIPAA compliance, secure sharing practices, breach response, and cloud safety. The course is built in Articulate Rise with accessibility and clarity at its core—perfect for hybrid teams, healthcare professionals, and anyone who handles protected information.</p>
      <iframe src="cybersecurity.pdf" width="100%" height="200" style="border:1px solid #ccc; border-radius:8px; margin-bottom:2rem;"></iframe>
      <p><a href="cybersecurity.pdf" target="_blank" style="color: #0078D4; text-decoration: none;"> 📄 View or download the full presentation (PDF)</a></p>
      </div>
        
  <!-- Health Equity Presentation -->
       <div style="text-align: center;">
       <h3>Using Purchasing Power to Promote Health Equity</h3>
       <p> This presentation explores how procurement policies can be used as strategic tools to advance health equity. Created for public sector professionals, it offers practical approaches to aligning purchasing decisions with community well-being. I designed the deck in PowerPoint, incorporating visual storytelling, plain language, and accessibility best practices to ensure clarity and impact across diverse audiences.</p>
       <iframe src="Delegation of Procurement Authority.pdf" width="100%" height="200" style="border:1px solid #ccc; border-radius:8px; margin-bottom:2rem;"></iframe>
       <p><a href="Delegation of Procurement Authority.pdf" target="_blank" style="color: #0078D4; text-decoration: none;"> 📄 View or download the full presentation (PDF)</a></p>
       </div>

 <!-- Public Speaking -->
      <div style="text-align: center;">
      <h3 id="public-speaking-title" style="font-size: 1.5rem; margin-top: 2rem;">Ways to Improve Public Speaking</h3>
      <p>Public speaking hasn’t always come naturally to me—but over time, I’ve learned how structure, intention, and empathy can transform a message. This presentation offers the tools I wish I had starting out: ways to speak with clarity, manage nerves, and truly connect with an audience. It’s designed for professionals who want to lead with authenticity and presence.</p>
      <a href="YourThoughtsandFeelings.pdf" target="_blank" title="Download full presentation">
        <img src="Screenshot 2025-08-31 194321.png" alt="Slide preview: Public Speaking for Beginners" style="width: 90%; max-width: 400px; height: auto; border: 1px solid #ccc; border-radius: 8px; margin: 1.2rem 0;">
      </a>
      <p><a href="YourThoughtsandFeelings.pdf" target="_blank" style="color: #0078D4; text-decoration: none;"> 📄 View or download the full presentation (PDF)/a></p>
      </div>

<!-- Healthcare Training Module -->
      <div style="text-align: center;">
      <h3>Healthcare Training Module</h3>
      <p>I built this onboarding guide from scratch using HTML, CSS, and GitHub to support professionals across hospitals, nursing homes, funeral homes, coroner offices, and the Pennsylvania Department of Health’s registered offices. Tailored by role, the module delivers clear, intuitive guidance for navigating the eVitals system with confidence and compliance.</p>
      <iframe src="https://cjohns4.github.io/chante-healthcare-training/Welcome.html" width="100%" height="200" style="border:1px solid #ccc; border-radius:8px; margin-bottom:2rem;"></iframe>
      <p><a href="https://cjohns4.github.io/chante-healthcare-training/Welcome.html" target="_blank" style="color: #0078D4; text-decoration: none;">🔗 eVitals Navigator – Role-Based Healthcare Onboarding</a></p>
      </div>

<!-- Microeconomics Module -->
      <div style="text-align: center;">
      <h3>Microeconomics Module</h3>
      <p>As a sample project for Columbia College’s ECON 294: Microeconomics, I built this interactive module using HTML, CSS, Bootstrap, and GitHub Pages to help students explore market structures like monopolistic competition and oligopolies. The content is organized into clear, responsive sections with real-world context to support online learning.</p>
      <iframe src="https://cjohns4.github.io/ECON-Module-Columbia/" width="100%" height="200" style="border:1px solid #ccc; border-radius:8px; margin-top:1rem;"></iframe>
      <p><a href="https://cjohns4.github.io/ECON-Module-Columbia/" target="_blank" style="color: #0078D4; text-decoration: none;">🔗 Microeconomics for Columbia College</a></p>
      </div>

<!-- The Memory Keeper -->
      <div style="text-align: center;">
      <h3>The Memory Keeper (Excerpt)</h3>
      <h4 style="font-size: 1.4rem; font-weight: 500; margin-bottom: 1rem;"><em>Why I Write</em></h4>
      <p>As a learning experience designer, I believe stories shape how we learn, connect, and grow. This excerpt from <em>The Memory Keeper</em> reflects the emotional lens I bring to my work—centered on voice, vulnerability, and the power of remembering.</p>
      <iframe 
      src="Memory.pdf" 
      style="width: 100%; height: 500px; border: 1px solid #ccc; border-radius: 8px; margin: 2rem 0;" 
      loading="lazy">
      </iframe>
      <p><a href="Memory.pdf" target="_blank" style="font-size: 1.1rem; color: #0078D4; text-decoration: none;">✍️ View or download the full (PDF)</a></p>
     </div>

<!-- Sanctified Shadows: A Glimpse into My Fictional World -->
      <div style="text-align: center;">
      <h3>Sanctified Shadows (Excerpt)</h3>
      <h4 style="font-size: 1.4rem; font-weight: 500; margin-bottom: 1rem;"><em>A literary work-in-progress exploring legacy, silence, and spiritual tension across generations.</em></h4>
      <p><em>Sanctified Shadows</em> is a deeply personal fiction project that blends emotional realism with atmospheric storytelling. Set between the rural South and urban Northeast, it follows a family shaped by faith, silence, and ancestral memory. Through layered characters and spiritual ambiguity, the story explores what we inherit, what we suppress, and how we choose to heal. This glimpse reflects my creative process and the themes I return to—voice, identity, and transformation.</p>
      <iframe 
      src="Personal.pdf" 
      style="width: 100%; height: 500px; border: 1px solid #ccc; border-radius: 8px; margin: 2rem 0;" 
      loading="lazy">
      </iframe>
      <p><a href="Personal.pdf" target="_blank" style="font-size: 1.1rem; color: #0078D4; text-decoration: none;">✍️ View or download the full (PDF)</a></p>
      </div>

<!-- Blog -->
      <div style="text-align: center;">
      <h3>Blog</h3>
      <p>This is where I share my thoughts on digital literacy, accessibility, and what it really means to design for real-world learners. From instructional strategies to tech tips, I explore how thoughtful design can empower people—not just inform them. If you're curious about how I build inclusive, learner-centered experiences, this is the place to start.</p>
      <iframe src="https://chanteshotspot.blogspot.com/" width="100%" height="200" style="border:1px solid #ccc; border-radius:8px; margin-top:1rem;"></iframe>
      <p><a href="https://chanteshotspot.blogspot.com/" target="_blank" style="color: #0078D4; text-decoration: none;">🔗 Visit my blog</a></p>
      </div>

      <hr style="border: none; border-top: 2px solid #D35400; margin: 3rem 0;">
</section>
<footer style="text-align: center; font-size: 0.9rem; color: #666; margin-top: 3rem;">
  © 2025 Chante’ Johnson. All rights reserved.  
  Content on this site may not be reproduced, distributed, or used without written permission.
</footer>
  <hr>
  
<!-- Banner  -->
    <div class="banner"></div>
  
<!-- Resume -->
  <h2>📄 Resume</h2>
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

<footer style="text-align: center; font-size: 0.9rem; color: #666; margin-top: 3rem;">
  © 2025 Chante’ Johnson. All rights reserved.  
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

</section>
<footer style="text-align: center; font-size: 0.9rem; color: #666; margin-top: 3rem;">
  © 2025 Chante’ Johnson. All rights reserved.  
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
