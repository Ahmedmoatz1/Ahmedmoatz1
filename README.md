<body>
  <style>
    body {
      background: #000;
      color: #fff;
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
    }

    h1, h2, h3 {
      margin: 0;
    }

    /* ===== Banner ===== */
    .banner img {
      width: 100%;
      height: 300px;
      object-fit: cover;
      border-radius: 0;
    }

    /* ===== Header ===== */
    .header {
      background: linear-gradient(135deg, #000000 0%, #1a1a1a 100%);
      padding: 40px 20px;
      text-align: center;
    }

    .header h1 {
      font-size: 3rem;
      margin-bottom: 10px;
      background: linear-gradient(45deg, #8B5CF6, #A78BFA);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      font-weight: bold;
    }

    .header h3 {
      font-size: 1.5rem;
      color: #A78BFA;
      margin-bottom: 20px;
      font-weight: 300;
    }

    /* ===== About Me ===== */
    .about {
      background: #0F0F0F;
      padding: 30px;
      border-radius: 15px;
      border-left: 5px solid #8B5CF6;
      margin: 20px;
    }

    .about span {
      color: #A78BFA;
      font-weight: 500;
    }

    /* ===== Contact Section ===== */
    .contact {
      background: #000;
      padding: 30px;
      border-radius: 15px;
      margin: 20px;
    }

    .contact-links {
      text-align: center;
      margin-bottom: 25px;
    }

    .contact-links a {
      display: inline-block;
      margin: 5px;
      padding: 12px 20px;
      background: linear-gradient(45deg, #8B5CF6, #7C3AED);
      color: white;
      text-decoration: none;
      border-radius: 25px;
      font-weight: 600;
      transition: all 0.3s ease;
    }

    .contact-links a:hover {
      transform: scale(1.05);
      background: linear-gradient(45deg, #7C3AED, #8B5CF6);
    }

    .contact-info {
      background: #1a1a1a;
      padding: 25px;
      border-radius: 10px;
      border: 1px solid #8B5CF6;
      font-size: 0.95rem;
    }

    .contact-info span {
      color: #A78BFA;
    }

    /* ===== Tech Stack ===== */
    .tech {
      background: #0F0F0F;
      padding: 40px;
      border-radius: 15px;
      margin: 20px;
      text-align: center;
    }

    .tech-stack {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 15px;
      margin-top: 20px;
    }

    .tech-item {
      background: #000;
      padding: 15px;
      border-radius: 10px;
      border: 2px solid #8B5CF6;
      min-width: 70px;
      text-align: center;
      transition: 0.3s;
    }

    .tech-item span {
      color: #8B5CF6;
      font-weight: bold;
    }

    .tech-item:hover {
      background: #8B5CF6;
      color: #fff;
      transform: scale(1.05);
    }

    /* ===== Footer ===== */
    .footer {
      background: linear-gradient(45deg, #000000 0%, #8B5CF6 100%);
      padding: 50px 20px;
      text-align: center;
      margin-top: 40px;
      position: relative;
      overflow: hidden;
    }

    .footer h3 {
      color: #fff;
      font-size: 1.5rem;
      margin-bottom: 20px;
      z-index: 2;
      position: relative;
    }

    .footer p {
      color: #E0E0E0;
      font-size: 1rem;
      position: relative;
      z-index: 2;
    }

    .footer small {
      display: block;
      color: #A78BFA;
      font-size: 0.9rem;
      margin-top: 15px;
      position: relative;
      z-index: 2;
    }
  </style>

  <!-- Banner -->
  <div class="banner" align="center">
    <img src="image.png" alt="Ahmed Moatz Banner" />
  </div>

  <!-- Header -->
  <div class="header">
    <h1>👋 Hi, I'm Ahmed Moatz</h1>
    <h3>🎓 Front-End Developer | Tech Enthusiast</h3>
    <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&pause=1200&color=8B5CF6&center=true&vCenter=true&width=435&lines=Problem+Solver+%F0%9F%A7%A0;Building+Modern+Web+UIs+%F0%9F%92%BB" alt="Typing SVG" />
  </div>

  <!-- About Me -->
  <div class="about">
    <ul>
      <li>🧑‍🎓 <span>Recent graduate</span> from <b>Faculty of Computers and Artificial Intelligence – Benha University</b></li>
      <li>💻 <span>Skilled</span> in <b>React.js</b>, <b>Tailwind CSS</b>, <b>HTML</b>, <b>CSS</b>, <b>JavaScript</b></li>
      <li>🌱 <span>Passionate</span> about learning <b>Next.js</b> and advanced front-end patterns</li>
      <li>⚡ <span>Strong</span> problem-solving and UI/UX design skills</li>
    </ul>
  </div>

  <!-- Contact -->
  <div class="contact">
    <div class="contact-links">
      <a href="https://www.linkedin.com/in/ahmed-moatz-a81b4a352">LinkedIn</a>
      <a href="https://github.com/ahmedmoatz">GitHub</a>
      <a href="mailto:moatz0742@gmail.com">Email</a>
      <a href="tel:+201013818318">Phone</a>
    </div>

    <div class="contact-info">
      <p>📱 <b>LinkedIn:</b> <a href="https://www.linkedin.com/in/ahmed-moatz-a81b4a352">linkedin.com/in/ahmed-moatz-a81b4a352</a></p>
      <p>💻 <b>GitHub:</b> <a href="https://github.com/ahmedmoatz">github.com/ahmedmoatz</a></p>
      <p>📧 <b>Email:</b> <span>moatz0742@gmail.com</span></p>
      <p>📞 <b>Phone:</b> <span>+20 1013818318</span></p>
      <p>📍 <b>Address:</b> <span>Estanha - El-Bagour Center - Menoufia Governorate</span></p>
      <p>🎂 <b>Birthday:</b> <span>May 15</span></p>
    </div>
  </div>

  <!-- Tech Stack -->
  <div class="tech">
    <h2>🔧 Tech Stack & Tools</h2>
    <div class="tech-stack">
      <div class="tech-item"><span>HTML5</span></div>
      <div class="tech-item"><span>CSS3</span></div>
      <div class="tech-item"><span>JavaScript</span></div>
      <div class="tech-item"><span>React</span></div>
      <div class="tech-item"><span>Tailwind</span></div>
      <div class="tech-item"><span>Git</span></div>
      <div class="tech-item"><span>GitHub</span></div>
      <div class="tech-item"><span>VS Code</span></div>
    </div>
  </div>

  <!-- Footer -->
  <div class="footer">
    <h3>Let's Build Something Amazing Together! 🚀</h3>
    <p>Thank you for visiting my profile! Feel free to reach out for collaborations or just to say hello! 👋</p>
    <small>© 2024 Ahmed Moatz - Crafted with 💜 and Black</small>
  </div>
</body>
