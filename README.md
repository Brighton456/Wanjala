<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Brighton Wanjala | Engineer Brighton Keiser | Civil Engineering & Leadership</title>
  <meta name="description" content="Profile and blog of Brighton Wanjala, also known as Engineer Brighton Keiser, a visionary Civil Engineering student and future leader from Kenya." />
  <meta name="keywords" content="Brighton Wanjala, Engineer Brighton Keiser, Civil Engineering Kenya, Kenyan student leader, Future Kenyan President, Brighton Keiser blog" />
  <meta name="author" content="Brighton Wanjala" />

  <!-- Open Graph for social media -->
  <meta property="og:title" content="Brighton Wanjala | Engineer Brighton Keiser" />
  <meta property="og:description" content="Profile and blog of Brighton Wanjala, a visionary Civil Engineering student and aspiring leader in Kenya." />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://yourgithubusername.github.io/" />
  <meta property="og:image" content="https://i.ibb.co/5gVZ61G9/image.jpg" />

  <!-- Twitter Card -->
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Brighton Wanjala | Engineer Brighton Keiser" />
  <meta name="twitter:description" content="Profile and blog of Brighton Wanjala, a visionary Civil Engineering student and aspiring leader in Kenya." />
  <meta name="twitter:image" content="https://i.ibb.co/5gVZ61G9/image.jpg" />

  <!-- Schema.org structured data -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "Brighton Wanjala",
    "alternateName": "Engineer Brighton Keiser",
    "description": "A second-year Civil Engineering student at South Eastern Kenya University, aspiring political leader and future President of Kenya.",
    "image": "https://i.ibb.co/5gVZ61G9/image.jpg",
    "url": "https://yourgithubusername.github.io/",
    "jobTitle": "Civil Engineering Student",
    "affiliation": {
      "@type": "CollegeOrUniversity",
      "name": "South Eastern Kenya University"
    },
    "parent": {
      "@type": "Person",
      "name": "Patrick Wanjala"
    },
    "sibling": {
      "@type": "Person",
      "name": "Mercy Wanjala"
    }
  }
  </script>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@600&family=Open+Sans&display=swap" rel="stylesheet" />

  <style>
    /* Base colors and variables */
    :root {
      --primary-color: #004080;
      --background-light: #f4f7fb;
      --background-dark: #121212;
      --text-light: #333;
      --text-dark: #ddd;
      --accent-color: #1e90ff;
      --transition-speed: 0.35s;
      --shadow-light: rgba(0,0,0,0.1);
      --shadow-dark: rgba(255,255,255,0.1);
    }

    /* Reset and base */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    body {
      margin: 0;
      font-family: 'Open Sans', Arial, sans-serif;
      font-size: 1rem;
      line-height: 1.6;
      background-color: var(--background-light);
      color: var(--text-light);
      transition: background-color var(--transition-speed) ease, color var(--transition-speed) ease;
      min-height: 100vh;
      padding-top: 60px; /* For fixed nav */
      opacity: 0;
      animation: fadeIn 1s ease forwards;
    }

    /* FadeIn animation */
    @keyframes fadeIn {
      to {opacity: 1;}
    }

    /* Dark mode */
    body.dark-mode {
      background-color: var(--background-dark);
      color: var(--text-dark);
    }

    /* Container */
    main.container {
      max-width: 900px;
      margin: 2rem auto 4rem;
      padding: 0 1rem;
    }

    /* Header and Navigation */
    header {
      background-color: var(--primary-color);
      color: #fff;
      position: fixed;
      top: 0;
      width: 100%;
      height: 60px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 0 2rem;
      box-shadow: 0 3px 6px var(--shadow-light);
      z-index: 1000;
      transition: background-color var(--transition-speed) ease;
      user-select: none;
    }
    body.dark-mode header {
      background-color: #001a33;
      box-shadow: 0 3px 6px var(--shadow-dark);
    }
    .logo {
      font-family: 'Montserrat', 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      font-weight: 600;
      font-size: 1.4rem;
      letter-spacing: 1.2px;
      cursor: default;
      color: #cce4ff;
      user-select: none;
    }

    /* Nav menu */
    nav ul {
      list-style: none;
      display: flex;
      gap: 1.5rem;
      margin: 0;
      padding: 0;
    }
    nav ul li {
      margin: 0;
    }
    nav a {
      color: #cce4ff;
      text-decoration: none;
      font-weight: 600;
      font-size: 1rem;
      padding: 0.4rem 0.6rem;
      border-radius: 4px;
      transition: background-color var(--transition-speed) ease, transform var(--transition-speed) ease;
      user-select: none;
    }
    nav a:hover, nav a:focus {
      background-color: var(--accent-color);
      outline: none;
      color: white;
      transform: translateY(-3px);
      box-shadow: 0 4px 8px rgba(30, 144, 255, 0.5);
    }
    body.dark-mode nav a {
      color: #a0c8ff;
    }
    nav a:focus-visible {
      outline: 2px dashed #fff;
      outline-offset: 3px;
    }

    /* Dark mode toggle button */
    .toggle-switch {
      cursor: pointer;
      width: 40px;
      height: 20px;
      background-color: #cce4ff;
      border-radius: 20px;
      position: relative;
      transition: background-color var(--transition-speed) ease;
      user-select: none;
      border: none;
    }
    body.dark-mode .toggle-switch {
      background-color: #444;
    }
    .toggle-switch::after {
      content: '';
      position: absolute;
      top: 2.5px;
      left: 2.5px;
      width: 15px;
      height: 15px;
      background: white;
      border-radius: 50%;
      transition: transform var(--transition-speed) ease;
      box-shadow: 0 2px 6px rgba(0,0,0,0.2);
    }
    body.dark-mode .toggle-switch::after {
      transform: translateX(20px);
      background: #222;
      box-shadow: 0 2px 6px rgba(255,255,255,0.2);
    }

    /* Main page title and intro */
    main h1 {
      font-family: 'Montserrat', 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      font-size: 2.4rem;
      margin-bottom: 0.5rem;
      color: var(--primary-color);
      user-select: none;
    }
    body.dark-mode main h1 {
      color: #66b1ff;
    }
    main p.intro {
      font-size: 1.15rem;
      margin-bottom: 2rem;
      color: #555;
      user-select: none;
    }
    body.dark-mode main p.intro {
      color: #bbb;
    }

    /* Section headers */
    section h2 {
      font-family: 'Montserrat', 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      color: var(--primary-color);
      margin-top: 2rem;
      margin-bottom: 1rem;
      user-select: none;
    }
    body.dark-mode section h2 {
      color: #66b1ff;
    }

    /* Images container for About Me */
    .images-row {
      display: flex;
      gap: 1rem;
      margin-top: 1rem;
      margin-bottom: 1rem;
      flex-wrap: wrap;
      justify-content: center;
    }
    .images-row img {
      max-width: 48%;
      border-radius: 12px;
      box-shadow: 0 7px 15px rgba(0,0,0,0.15);
      transition: transform 0.3s ease;
    }
    .images-row img:hover,
    .images-row img:focus-visible {
      transform: scale(1.03);
      box-shadow: 0 10px 25px rgba(0,0,0,0.3);
      outline: none;
    }
    @media (max-width: 600px) {
      .images-row img {
        max-width: 100%;
      }
    }

    /* Blog post list */
    ul.post-list {
      list-style: none;
      padding: 0;
      margin: 0;
      display: flex;
      flex-direction: column;
      gap: 1.8rem;
    }
    ul.post-list li {
      background: #e9f0ff;
      border-radius: 12px;
      padding: 1.4rem 1.8rem;
      box-shadow: 0 5px 10px var(--shadow-light);
      transition: background-color var(--transition-speed) ease, box-shadow var(--transition-speed) ease, transform var(--transition-speed) ease;
      cursor: pointer;
      user-select: none;
    }
    ul.post-list li:hover, ul.post-list li:focus-within {
      background: var(--accent-color);
      color: white;
      box-shadow: 0 10px 20px rgba(30,144,255,0.6);
      outline: none;
      transform: translateY(-5px);
    }
    body.dark-mode ul.post-list li {
      background: #222;
      box-shadow: 0 5px 10px var(--shadow-dark);
      color: var(--text-dark);
    }
    body.dark-mode ul.post-list li:hover, body.dark-mode ul.post-list li:focus-within {
      background: var(--accent-color);
      color: white;
      box-shadow: 0 10px 20px rgba(30,144,255,0.8);
    }

    ul.post-list li h3 {
      margin: 0 0 0.4rem 0;
      font-size: 1.4rem;
      font-weight: 700;
    }
    ul.post-list li p {
      margin: 0;
      font-size: 1rem;
      line-height: 1.45;
      user-select: text;
    }
    ul.post-list li a {
      color: inherit;
      text-decoration: none;
      display: block;
      outline-offset: 3px;
    }
    ul.post-list li a:focus {
      outline: 2px dashed #fff;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 1.8rem 1rem;
      font-size: 0.9rem;
      color: #777;
      border-top: 1px solid #ddd;
      user-select: none;
      margin-top: 4rem;
    }
    body.dark-mode footer {
      color: #aaa;
      border-top-color: #444;
    }

    /* Responsive */
    @media (max-width: 600px) {
      nav ul {
        gap: 1rem;
      }
      main h1 {
        font-size: 2rem;
      }
      ul.post-list li h3 {
        font-size: 1.25rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="logo" aria-label="Engineer Brighton Keiser">Brighton Keiser</div>
    <nav aria-label="Primary Navigation">
      <ul>
        <li><a href="#about" tabindex="0">About Me</a></li>
        <li><a href="#education" tabindex="0">Education</a></li>
        <li><a href="#ambitions" tabindex="0">Leadership Ambitions</a></li>
        <li><a href="#vision" tabindex="0">Vision</a></li>
      </ul>
    </nav>
    <button id="darkModeToggle" class="toggle-switch" aria-label="Toggle dark mode" aria-pressed="false"></button>
  </header>

  <main class="container">
    <h1>Brighton Wanjala</h1>
    <p class="intro">Also known as Engineer Brighton Keiser, a visionary civil engineering student and future leader committed to building a better Kenya.</p>

    <section id="about" tabindex="0" aria-label="About Brighton Wanjala">
      <h2>About Me</h2>
      <p>
        Brighton Wanjala, famously known as Engineer Brighton Keiser, is a second-year Civil Engineering student at South Eastern Kenya University. Born in 2004 to Patrick and Mercy Wanjala, Brighton has demonstrated ambition and excellence throughout his academic journey.
      </p>
      <div class="images-row">
        <img src="https://i.ibb.co/5gVZ61G9/image.jpg" alt="Portrait of Brighton Wanjala, Engineer Brighton Keiser" />
        <img src="https://i.ibb.co/vxD0172Y/image.jpg" alt="Portrait of Brighton Wanjala, Engineer Brighton Keiser" />
      </div>
    </section>

    <section id="education" tabindex="0" aria-label="Education of Brighton Wanjala">
      <h2>His Educational Journey</h2>
      <p>
        Brighton's academic path began in 2008 at Uasin-Gishu Primary School. He progressed through Bright Future Academy and St. Joseph’s Primary School before completing his KCPE in 2019. Subsequently, Brighton attended Kiungani High School, where he excelled academically while holding leadership roles including Academic Secretary and Chairperson of the Student Council. He finished his KCSE in 2023 with outstanding results.
      </p>
    </section>

    <section id="ambitions" tabindex="0" aria-label="Leadership and political ambitions of Brighton Wanjala">
      <h2>Professional and Leadership Ambitions</h2>
      <p>
        Currently pursuing his Bachelor of Science in Civil Engineering, Brighton is committed to creating sustainable infrastructure and contributing to Kenya's development. Beyond engineering, he nurtures political ambitions to serve as President of the Republic of Kenya. He aims to champion innovation, education, and inclusive governance while empowering youth leadership in public service.
      </p>
    </section>

    <section id="vision" tabindex="0" aria-label="Vision for the future by Brighton Wanjala">
      <h2>Vision for the Future</h2>
      <p>
        With a blend of technical knowledge, leadership skills, and political drive, Brighton Keiser envisions a future where he makes impactful contributions to his country. His story is one of determination, visionary leadership, and a commitment to excellence.
      </p>
      <p>Thank you for visiting my blog. Follow my journey as I work towards building a better Kenya.</p>
    </section>

    <section aria-label="Latest blog posts by Brighton Wanjala" tabindex="0" style="margin-top:3rem;">
      <h2>Latest Blog Posts</h2>
      <ul class="post-list">
        <li><a href="#post1" tabindex="0">
          <h3>The Path to Leadership: Lessons from My Student Council Journey</h3>
          <p>Insight into early leadership experiences that shaped my vision and skills as a student leader.</p>
        </a></li>
        <li><a href="#post2" tabindex="0">
          <h3>Why Civil Engineering Matters for Kenya’s Future</h3>
          <p>An exploration of infrastructure challenges and the engineer’s role in nation-building.</p>
        </a></li>
        <li><a href="#post3" tabindex="0">
          <h3>Empowering Youth in Politics: My Vision for Inclusive Governance</h3>
          <p>My ambitions to inspire greater youth participation in shaping Kenya’s political landscape.</p>
        </a></li>
      </ul>
    </section>
  </main>

  <footer>
    &copy; 2025 Brighton Wanjala. All rights reserved.
  </footer>

  <script>
    // Dark mode toggle functionality with storage
    const toggleButton = document.getElementById('darkModeToggle');
    toggleButton.addEventListener('click', () => {
      const isDark = document.body.classList.toggle('dark-mode');
      toggleButton.setAttribute('aria-pressed', isDark);
      localStorage.setItem('darkMode', isDark);
    });

    // Load saved preference on page load
    document.addEventListener('DOMContentLoaded', () => {
      const savedMode = localStorage.getItem('darkMode') === 'true';
      if (savedMode) {
        document.body.classList.add('dark-mode');
        toggleButton.setAttribute('aria-pressed', 'true');
      }
    });
  </script>
</body>
</html>
