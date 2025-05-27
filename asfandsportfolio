<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Asfand Ullah - Portfolio</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <style>
    /* Global Styles */
    body {
      font-family: 'Open Sans', sans-serif;
      background-color: #f0f0f0;
      color: #333;
      margin: 0;
      padding: 0;
    }

    /* Header Styles */
    header {
      background-color: #321ae8;
      color: white;
      padding: 2rem;
      text-align: center;
      position: relative;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1); /* Added for depth */
    }

    .header-content {
      max-width: 800px;
      margin: 0 auto;
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }

    header p {
      font-size: 1.2rem;
      margin: 0.25rem 0;
    }

    .hamburger {
      display: none;
      font-size: 2rem;
      cursor: pointer;
      position: absolute;
      top: 1rem;
      right: 1rem;
    }

    /* Navigation Styles */
    nav {
      background-color: #333;
    }

    nav ul {
      display: flex;
      justify-content: center;
      list-style: none;
      padding: 1rem;
      margin: 0;
    }

    nav ul li {
      margin: 0 1rem;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-size: 1.1rem;
    }

    /* Main Content Styles */
    main {
      max-width: 1000px;
      margin: 2rem auto;
      padding: 0 1rem;
    }

    .section {
      background-color: white;
      padding: 2rem;
      margin: 1rem 0;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      border-radius: 8px;
      opacity: 0;
      transform: translateY(20px); /* Initial offset */
    }

    .section.animate {
      animation: waveIn 0.8s cubic-bezier(0.68, -0.55, 0.27, 1.55) forwards; /* Wave animation */
    }

    @keyframes waveIn {
      to { opacity: 1; transform: translateY(0); } /* Animates to final position */
    }

    h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
      color: #1a73e8;
    }

    h2 i {
      margin-right: 0.5rem;
    }

    /* Skills Grid */
    .skills-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
    }

    .skills-grid div {
      padding: 1rem;
      border: 1px solid #ddd;
      border-radius: 4px;
    }

    .skills-grid div:hover {
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: box-shadow 0.3s;
    }

    /* Project Cards */
    .project-card {
      padding: 1rem;
      border: 1px solid #ddd;
      border-radius: 4px;
      margin-bottom: 1rem;
    }

    .project-card:hover {
      transform: scale(1.02);
      transition: transform 0.3s;
    }

    /* Lists */
    ul {
      list-style: disc inside;
      padding-left: 1rem;
    }

    /* Footer */
    footer {
      background-color: #1a73e8;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }

    /* Links */
    a {
      color: #111212;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    /* Responsive Styles */
    @media (max-width: 768px) {
      .hamburger {
        display: block;
      }

      nav ul {
        display: none;
        flex-direction: column;
        position: absolute;
        top: 60px;
        left: 0;
        width: 100%;
        background-color: #333;
      }

      nav ul.show {
        display: flex;
      }

      nav ul li {
        margin: 1rem 0;
        text-align: center;
      }

      header h1 {
        font-size: 2rem;
      }

      header p {
        font-size: 1rem;
      }

      h2 {
        font-size: 1.5rem;
      }

      .section {
        padding: 1rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="header-content">
      <h1>Asfand Ullah</h1>
      <p>Computer Science Student | Mobile App Developer</p>
      <p><a href="mailto:asfandullah2000@gmail.com">asfandullah2000@gmail.com</a> | +92 311 4274251 | I-8/4, Islamabad</p>
    </div>
    <div class="hamburger" onclick="toggleMenu()">☰</div>
  </header>

  <nav>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#education">Education</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#certifications">Certifications</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <main>
    <section id="about" class="section">
      <h2><i class="fas fa-user"></i> About Me</h2>
      <p>Highly motivated Computer Science student with a strong foundation in programming languages (Java, Kotlin, Python) and hands-on experience in Android app development, UI/UX design, and API integration using tools like Android Studio and Firebase. Passionate about contributing to innovative projects and eager to further develop technical and analytical skills in software, hardware, and data management.</p>
    </section>

    <section id="education" class="section">
      <h2><i class="fas fa-graduation-cap"></i> Education</h2>
      <div>
        <h3>Shaheed Zulfiqar Ali Bhutto Institute of Science and Technology, Islamabad</h3>
        <p>Bachelor of Computer Science, Expected 2025</p>
        <ul>
          <li>Programming Languages (Java, Kotlin, Python)</li>
          <li>Mobile App Development</li>
          <li>Database Management Systems</li>
          <li>Data Structures and Algorithms</li>
          <li>Software Engineering</li>
        </ul>
      </div>
    </section>

    <section id="skills" class="section">
      <h2><i class="fas fa-code"></i> Technical Skills</h2>
      <div class="skills-grid">
        <div>
          <h3>Programming Languages</h3>
          <p>Python, Java, Kotlin</p>
        </div>
        <div>
          <h3>Web Development</h3>
          <p>HTML, CSS, JavaScript</p>
        </div>
        <div>
          <h3>Database Management</h3>
          <p>SQL Server, MS Excel, Access, Oracle</p>
        </div>
        <div>
          <h3>Software and Tools</h3>
          <p>SQL, Android Studio, Firebase, MS FrontPage, Teams, Excel, Word, Zoom</p>
        </div>
      </div>
    </section>

    <section id="certifications" class="section">
      <h2><i class="fas fa-certificate"></i> Certifications</h2>
      <ul>
        <li>HarvardX CS50x: Introduction to Computer Science, edX</li>
        <li>HarvardX CS109x: Introduction to Data Science with Python, edX</li>
        <li>Financial Markets, Yale University, Coursera</li>
        <li>Cisco Certified in Cybersecurity, Cisco Networking Academy, May 2025</li>
        <li>Team Organizer, Google Developer Group on Campus (GDGoC), SZABIST</li>
      </ul>
    </section>

    <section id="projects" class="section">
      <h2><i class="fas fa-project-diagram"></i> Projects</h2>
      <div class="project-card">
        <h3>Desktop Notifier</h3>
        <p>A Python-based application for sending desktop notifications.</p>
      </div>
      <div class="project-card">
        <h3>Offline Dictionary</h3>
        <p>A dictionary application using SQLite for offline word lookup.</p>
      </div>
      <div class="project-card">
        <h3>Notes Taking App</h3>
        <p>An Android application for creating and managing notes, developed with Android Studio.</p>
      </div>
    </section>

    <section id="contact" class="section">
      <h2><i class="fas fa-envelope"></i> Contact</h2>
      <p>Feel free to reach out to me via email at <a href="mailto:asfandullah2000@gmail.com">asfandullah2000@gmail.com</a> or by phone at +92 311 4274251.</p>
    </section>
  </main>

  <footer>
    <p>© 2025 Asfand Ullah. All rights reserved.</p>
  </footer>

  <script>
    function toggleMenu() {
      const nav = document.querySelector('nav ul');
      nav.classList.toggle('show');
    }

    // Close menu when a link is clicked
    document.querySelectorAll('nav a').forEach(link => {
      link.addEventListener('click', () => {
        document.querySelector('nav ul').classList.remove('show');
      });
    });

    // Add wave animation to sections
    document.addEventListener('DOMContentLoaded', () => {
      const sections = document.querySelectorAll('.section');
      const options = {
        threshold: 0.1 // Trigger when 10% of the section is visible
      };

      const observer = new IntersectionObserver((entries, observer) => {
        entries.forEach(entry => {
          if (entry.isIntersecting) {
            entry.target.classList.add('animate');
            observer.unobserve(entry.target); // Stop observing after animation triggers
          }
        });
      }, options);

      sections.forEach(section => {
        observer.observe(section);
      });
    });
  </script>
</body>
</html>
