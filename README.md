<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Jeeva S – Web Developer Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet" />
  <link rel="icon" href="favicon.ico" type="image/x-icon" />
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #f9f9f9;
      color: #333;
      line-height: 1.6;
    }

    header {
      text-align: center;
      padding: 2rem 1rem;
      background: linear-gradient(135deg, #4e54c8, #8f94fb);
      color: white;
    }

    .profile-image {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid white;
      margin-bottom: 1rem;
    }

    .role-image {
      width: 24px;
      vertical-align: middle;
      margin-right: 5px;
    }

    h1 {
      margin: 0.5rem 0;
      font-size: 2.5rem;
    }

    section {
      padding: 2rem 1.5rem;
      max-width: 900px;
      margin: auto;
    }

    .about, .skills, .projects, .contact {
      background: white;
      border-radius: 15px;
      margin-bottom: 2rem;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.05);
    }

    h2 {
      color: #4e54c8;
      margin-bottom: 1rem;
      font-size: 1.8rem;
    }

    .skills-list {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      margin-bottom: 1rem;
    }

    .skill-item {
      display: flex;
      flex-direction: column;
      align-items: center;
      width: 90px;
      text-align: center;
    }

    .skill-item img {
      width: 60px;
      height: 60px;
      border-radius: 10px;
      object-fit: cover;
      margin-bottom: 5px;
      transition: transform 0.3s ease;
    }

    .skill-item:hover img {
      transform: scale(1.1);
    }

    .skill-item a {
      text-decoration: none;
      color: #333;
      font-weight: 500;
    }

    .project-card {
      background: #f1f1f1;
      padding: 1rem;
      border-radius: 12px;
      margin-bottom: 1rem;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
    }

    .project-card h3 {
      margin-top: 0;
      color: #4e54c8;
    }

    .project-card a {
      display: inline-block;
      margin-top: 0.5rem;
      color: #4e54c8;
      font-weight: 600;
      text-decoration: underline;
    }

    .contact a {
      display: block;
      margin: 0.5rem 0;
      color: #4e54c8;
      font-weight: 500;
      text-decoration: none;
    }

    .contact a:hover {
      text-decoration: underline;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background-color: #4e54c8;
      color: white;
      font-size: 0.9rem;
    }

    @media (max-width: 600px) {
      .skills-list {
        justify-content: center;
      }

      .profile-image {
        width: 120px;
        height: 120px;
      }

      h1 {
        font-size: 2rem;
      }

      h2 {
        font-size: 1.5rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src="jeeva.jpg" alt="Jeeva S" class="profile-image" />
    <h1>Jeeva S</h1>
    <p><img src="developer.png" alt="Web Developer" class="role-image" /> Web Developer </p>
  </header>

  <section class="about">
    <h2>About Me</h2>
    <p>
      I am a passionate learner with a strong interest in web development, eager to build a career in the field of
      information technology and web development. Seeking a challenging position in IT where I can apply my skills in
      web development and grow professionally.
    </p>
  </section>

  <section class="skills">
    <h2>Skills</h2>
    <div class="skills-list">
      <span class="skill-item">
        <img src="html.jpg" alt="HTML" />
        <a href="https://developer.mozilla.org/en-US/docs/Web/HTML">HTML</a>
      </span>
      <span class="skill-item">
        <img src="css.jpg" alt="CSS" />
        <a href="https://developer.mozilla.org/en-US/docs/Web/CSS">CSS</a>
      </span>
      <span class="skill-item">
        <img src="js.jpg" alt="JavaScript" />
        <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript">JavaScript</a>
      </span>
      <span class="skill-item">
        <img src="canva.jpg" alt="Canva" />
        <a href="https://www.canva.com/">Canva</a>
      </span>
    </div>
    <p>
      I have a strong foundation in HTML, CSS, and JavaScript, with experience in creating responsive and user-friendly
      web applications. I am also proficient in using design tools like Canva for creating visually appealing designs.
    </p>
  </section>

  <section class="projects">
    <h2>Projects</h2>
    <div class="project-card">
      <h3>Resume Website</h3>
      <p>
        Created a personal resume website to showcase my academic and professional details, skills, and projects.
      </p>
      <a href="https://jeevas07.github.io/Resume/" target="_blank">View Project</a>
    </div>
    <div class="project-card">
      <h3>Blood Bank & Donor Management System</h3>
      <p>
        Developed as a college project, this system manages donor details, blood group availability, and donation
        records.
      </p>
    </div>
  </section>

  <section class="contact">
    <h2>Contact</h2>
    <a href="mailto:sj160189@gmail.com">sj160189@gmail.com</a>
    <a href="tel:+917339106440">+91 73391 06440</a>
    <a href="https://www.linkedin.com/in/jeeva-s7-531a0b352" target="_blank">LinkedIn Profile</a>
  </section>

  <footer>
    <p>© 2025 Jeeva S. All rights reserved.</p>
  </footer>
</body>
</html>
