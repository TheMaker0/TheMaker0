<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mark Glenn Serinas — GitHub Profile</title>
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
      background: #f5f5f4;
      color: #1a1a1a;
      padding: 2rem 1rem;
    }

    .profile {
      max-width: 720px;
      margin: 0 auto;
      display: flex;
      flex-direction: column;
      gap: 1.25rem;
    }

    /* Hero */
    .hero {
      display: grid;
      grid-template-columns: 1fr auto;
      gap: 1.5rem;
      align-items: center;
      background: #fff;
      border: 1px solid #e5e5e3;
      border-radius: 12px;
      padding: 1.5rem;
    }

    .hero-left { display: flex; flex-direction: column; gap: 10px; }

    .avatar-row { display: flex; align-items: center; gap: 14px; }

    .avatar {
      width: 56px; height: 56px;
      border-radius: 50%;
      background: #dbeafe;
      display: flex; align-items: center; justify-content: center;
      font-size: 20px; font-weight: 500;
      color: #1d4ed8;
      flex-shrink: 0;
    }

    .name { font-size: 20px; font-weight: 600; }
    .sub  { font-size: 13px; color: #6b7280; margin-top: 2px; }

    .badge {
      display: inline-flex; align-items: center; gap: 5px;
      font-size: 12px; padding: 3px 10px;
      border-radius: 999px;
      background: #dcfce7; color: #15803d;
      width: fit-content;
    }

    .bio { font-size: 13px; color: #6b7280; line-height: 1.6; }

    .learning-tag {
      display: inline-block;
      background: #fef3c7; color: #92400e;
      font-size: 12px; padding: 4px 10px;
      border-radius: 6px; width: fit-content;
    }

    .hero-gif {
      width: 160px; height: 110px;
      object-fit: cover;
      border-radius: 8px;
    }

    /* Cards row */
    .cards-row {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 1rem;
    }

    .card {
      background: #fff;
      border: 1px solid #e5e5e3;
      border-radius: 12px;
      padding: 1.25rem;
    }

    .card.wide { grid-column: span 2; }

    .card-label {
      font-size: 11px;
      color: #9ca3af;
      text-transform: uppercase;
      letter-spacing: 0.05em;
      margin-bottom: 10px;
    }

    /* Contact */
    .contact-item {
      display: flex; align-items: center; gap: 8px;
      font-size: 13px; margin-bottom: 7px;
    }

    .contact-item a { color: #2563eb; text-decoration: none; }
    .contact-item a:hover { text-decoration: underline; }

    .icon {
      width: 20px; height: 20px;
      border-radius: 4px;
      display: inline-flex; align-items: center; justify-content: center;
      font-size: 11px; font-weight: 700;
      flex-shrink: 0;
    }
    .icon.mail { background: #fee2e2; color: #b91c1c; }
    .icon.fb   { background: #dbeafe; color: #1d4ed8; }
    .icon.ig   { background: #fef3c7; color: #b45309; }

    /* Skills */
    .skills-grid { display: flex; flex-wrap: wrap; gap: 8px; }

    .skill-pill {
      display: flex; align-items: center; gap: 5px;
      padding: 5px 10px;
      border-radius: 999px;
      background: #f9fafb;
      border: 1px solid #e5e5e3;
      font-size: 12px; color: #374151;
    }

    .skill-pill img { width: 14px; height: 14px; object-fit: contain; }

    /* Stats */
    .stats-card .section-title {
      font-size: 13px; font-weight: 500;
      margin-bottom: 12px;
    }

    .stats-card img {
      max-width: 100%;
      border-radius: 8px;
    }

    /* Responsive */
    @media (max-width: 560px) {
      .hero { grid-template-columns: 1fr; }
      .hero-gif { width: 100%; height: 160px; }
      .cards-row { grid-template-columns: 1fr; }
      .card.wide { grid-column: span 1; }
    }
  </style>
</head>
<body>
  <div class="profile">

    <!-- Hero -->
    <div class="hero">
      <div class="hero-left">
        <div class="avatar-row">
          <div class="avatar">MG</div>
          <div>
            <div class="name">Mark Glenn Serinas</div>
            <div class="sub">Frontend Developer &middot; Philippines</div>
          </div>
        </div>
        <div class="badge">&#9679; Open to opportunities</div>
        <p class="bio">
          Passionate about building clean, responsive web interfaces. Currently
          studying Computer Science and sharpening my HTML, CSS &amp; JavaScript skills.
        </p>
        <div class="learning-tag">Currently learning: Computer Science</div>
      </div>
      <img
        class="hero-gif"
        src="https://mir-s3-cdn-cf.behance.net/project_modules/hd/06f21a161921919.63cd7887d0a70.gif"
        alt="Coding animation"
        onerror="this.style.display='none'"
      />
    </div>

    <!-- Contact + Skills -->
    <div class="cards-row">

      <!-- Contact -->
      <div class="card">
        <div class="card-label">Contact &amp; socials</div>
        <div class="contact-item">
          <span class="icon mail">@</span>
          <a href="mailto:glenm906@gmail.com">glenm906@gmail.com</a>
        </div>
        <div class="contact-item">
          <span class="icon fb">f</span>
          <a href="https://fb.com/marck.facun.0120" target="_blank">Facebook</a>
        </div>
        <div class="contact-item">
          <span class="icon ig">ig</span>
          <a href="https://instagram.com/serrinaaawsss" target="_blank">Instagram</a>
        </div>
      </div>

      <!-- Skills -->
      <div class="card wide">
        <div class="card-label">Languages &amp; tools</div>
        <div class="skills-grid">
          <span class="skill-pill"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="">HTML5</span>
          <span class="skill-pill"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="">CSS3</span>
          <span class="skill-pill"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="">JavaScript</span>
          <span class="skill-pill"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="">PHP</span>
          <span class="skill-pill"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="">Python</span>
          <span class="skill-pill"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="">Java</span>
          <span class="skill-pill"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="">C</span>
          <span class="skill-pill"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="">Bootstrap</span>
          <span class="skill-pill"><img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="">Tailwind</span>
          <span class="skill-pill"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="">MySQL</span>
          <span class="skill-pill"><img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="">SQL Server</span>
          <span class="skill-pill"><img src="https://www.vectorlogo.zone/logos/sqlite/sqlite-icon.svg" alt="">SQLite</span>
          <span class="skill-pill"><img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="">Figma</span>
          <span class="skill-pill"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/photoshop/photoshop-line.svg" alt="">Photoshop</span>
        </div>
      </div>

    </div>

    <!-- GitHub Stats -->
    <div class="card stats-card">
      <div class="section-title">Top languages</div>
      <img
        src="https://github-readme-stats.vercel.app/api/top-langs?username=themaker0&show_icons=true&locale=en&layout=compact&theme=default"
        alt="Top languages"
      />
    </div>

  </div>
</body>
</html>
