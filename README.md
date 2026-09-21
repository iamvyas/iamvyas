<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vyas</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    
    body {
      font-family: 'Courier New', Courier, monospace;
      background: #fafafa;
      color: #111;
      line-height: 1.6;
      max-width: 720px;
      margin: 0 auto;
      padding: 3rem 1.5rem;
    }
    
    h1 {
      font-size: 1.8rem;
      font-weight: 400;
      letter-spacing: -0.02em;
      margin-bottom: 0.25rem;
    }
    
    .subtitle {
      color: #555;
      font-size: 0.95rem;
      margin-bottom: 1.5rem;
    }
    
    .links {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
      margin-bottom: 2.5rem;
      font-size: 0.9rem;
    }
    
    .links a {
      color: #111;
      text-decoration: none;
      border-bottom: 1px solid #ccc;
      padding-bottom: 1px;
    }
    
    .links a:hover {
      border-bottom-color: #111;
    }
    
    hr {
      border: none;
      border-top: 1px solid #e0e0e0;
      margin: 2.5rem 0;
    }
    
    h2 {
      font-size: 1.1rem;
      font-weight: 400;
      letter-spacing: 0.05em;
      text-transform: uppercase;
      color: #333;
      margin-bottom: 1.25rem;
    }
    
    h3 {
      font-size: 1rem;
      font-weight: 400;
      margin-bottom: 0.35rem;
    }
    
    .tech {
      color: #666;
      font-size: 0.85rem;
      margin-bottom: 0.6rem;
    }
    
    p {
      margin-bottom: 1rem;
      color: #333;
    }
    
    .job {
      margin-bottom: 1.75rem;
    }
    
    .job-meta {
      color: #666;
      font-size: 0.9rem;
      margin-bottom: 0.5rem;
    }
    
    ul {
      padding-left: 1.25rem;
      margin-top: 0.4rem;
    }
    
    li {
      margin-bottom: 0.3rem;
      color: #333;
    }
    
    .skills-grid {
      display: grid;
      gap: 1.25rem;
    }
    
    .skill-group h4 {
      font-size: 0.85rem;
      font-weight: 400;
      color: #555;
      margin-bottom: 0.4rem;
      text-transform: uppercase;
      letter-spacing: 0.04em;
    }
    
    .skill-list {
      color: #333;
      font-size: 0.95rem;
    }
    
    .contact {
      margin-top: 0.5rem;
    }
    
    .contact p {
      margin-bottom: 0.3rem;
    }
    
    .contact a {
      color: #111;
      text-decoration: none;
      border-bottom: 1px solid #ccc;
    }
    
    .contact a:hover {
      border-bottom-color: #111;
    }
    
    footer {
      margin-top: 3rem;
      font-size: 0.85rem;
      color: #777;
    }
  </style>
</head>
<body>

  <h1>Hello There, I'm Vyas</h1>
  <p class="subtitle">Fullstack Developer | SWE | Pushing the bounds</p>
  
  <div class="links">
    <a href="mailto:sbvyas07@gmail.com">email</a>
    <a href="https://www.linkedin.com/in/iamvyas">linkedin</a>
    <a href="https://github.com/iamvyas">github</a>
    <a href="https://iamvyas.github.io/me/">portfolio</a>
  </div>

  <hr>

  <h2>Projects</h2>

  <div class="job">
    <h3>File Sharing Application</h3>
    <p class="tech">MongoDB · Express.js · React.js · Node.js · Multer</p>
    <p>A real-time file sharing and messaging platform with virtual rooms. Users can join rooms to exchange text and upload files securely. Ideal for collaboration, study groups, and remote teamwork.</p>
  </div>

  <div class="job">
    <h3>Smart Order Processing System</h3>
    <p class="tech">MongoDB · Spring Boot · Kafka · RabbitMQ · Docker</p>
    <p>Developed a Spring Boot–based order management microservice with MongoDB integration and RESTful APIs. Implemented DTO separation, service-repository pattern, and Dockerized MongoDB backend. Enabled full CRUD for orders and ensured scalable architecture with modular code structure, laying the foundation for Kafka-driven event communication across microservices.</p>
  </div>

  <hr>

  <h2>Experience</h2>

  <div class="job">
    <h3>Infosys — Digital Specialist Engineer</h3>
    <p class="job-meta">Oct 2022 – Jan 2025</p>
    <ul>
      <li>Migrated Spring apps from WebSphere to Liberty</li>
      <li>Rewrote UI from Spring Tiles to JAF-Tiles</li>
      <li>Refactored and modernized backend codebase</li>
      <li>Added test cases for reliability</li>
    </ul>
  </div>

  <div class="job">
    <h3>MVDS Industries — Fullstack Developer Intern</h3>
    <p class="job-meta">May 2021</p>
    <ul>
      <li>Built a Django-based web system for syncing industrial data with Excel sheets</li>
    </ul>
  </div>

  <hr>

  <h2>Education</h2>

  <div class="job">
    <h3>Sri Venkateswara College of Engineering, Anna University</h3>
    <p class="job-meta">Bachelor of Engineering in Computer Science — CGPA: 8.43/10</p>
    <p>Chennai, India | Aug 2018 – May 2022</p>
  </div>

  <hr>

  <h2>Skills</h2>

  <div class="skills-grid">
    <div class="skill-group">
      <h4>Languages</h4>
      <p class="skill-list">Java · JavaScript · Python</p>
    </div>
    
    <div class="skill-group">
      <h4>Databases</h4>
      <p class="skill-list">MySQL · SQLite · MongoDB</p>
    </div>
    
    <div class="skill-group">
      <h4>Backend</h4>
      <p class="skill-list">Node.js · Express · Spring Boot · NGINX · Kafka · RabbitMQ</p>
    </div>
    
    <div class="skill-group">
      <h4>Frontend</h4>
      <p class="skill-list">React · TailwindCSS · Bootstrap · HTML · CSS</p>
    </div>
    
    <div class="skill-group">
      <h4>Tools & DevOps</h4>
      <p class="skill-list">AWS · Docker · Bash</p>
    </div>
  </div>

  <hr>

  <h2>Research</h2>

  <div class="job">
    <h3>Handwritten Tamil Character Recognition Using Deep Neural Networks</h3>
    <ul>
      <li>Funded by TNSCST (Tamil Nadu State Council for Science and Technology)</li>
      <li>Published in International Journal of Computer Science Trends and Technology (IJCST), August 2022</li>
    </ul>
  </div>

  <hr>

  <h2>Contact</h2>

  <div class="contact">
    <p>sbvyas07@gmail.com</p>
    <p><a href="https://iamvyas.github.io/me/">iamvyas.github.io/me</a></p>
    <p>+91 9940699617</p>
  </div>

  <footer>
    If you like my work, feel free to star the repo and connect.
  </footer>

</body>
</html>
