<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nishanthan Suseekaran | Personal Website</title>
  <meta name="description" content="Welcome to the personal website of Nishanthan Suseekaran. Learn about his life, education, work and dream of becoming a pilot.">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      background: #f4f7fb;
      color: #172033;
      line-height: 1.7;
    }

    header {
      background: #071b35;
      color: white;
      padding: 18px 6%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      gap: 12px;
    }

    .logo {
      font-size: 21px;
      font-weight: bold;
    }

    nav {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-size: 14px;
    }

    nav a:hover {
      color: #65d5ff;
    }

    .hero {
      background: linear-gradient(135deg, #071b35, #164e79);
      color: white;
      padding: 65px 20px;
      text-align: center;
    }

    .profile {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 4px solid white;
      background: #dceeff;
      color: #c4flf2;
      display: inline-flex;
      justify-content: center;
      align-items: center;
      font-size: 35px;
      font-weight: bold;
      margin-bottom: 20px;
      object-fit: cover;
    }

    .hero h1 {
      font-size: clamp(28px, 5vw, 42px);
      margin-bottom: 10px;
    }

    .hero p {
      max-width: 650px;
      margin: 8px auto;
    }

    .tag {
      display: inline-block;
      border: 1px solid #8ddfff;
      border-radius: 25px;
      padding: 5px 15px;
      margin-top: 15px;
      color: #d5f4ff;
    }

    .button {
      display: inline-block;
      background: #ffffff;
      color: #071b35;
      text-decoration: none;
      padding: 10px 22px;
      border-radius: 8px;
      margin: 18px 6px 0;
      font-weight: bold;
    }

    .button:hover {
      background: #d8f1ff;
    }

    main {
      max-width: 1000px;
      margin: auto;
      padding: 25px 16px;
    }

    section {
      background: white;
      padding: 25px;
      margin: 22px 0;
      border-radius: 14px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.05);
      scroll-margin-top: 20px;
    }

    section h2 {
      color: #104a76;
      margin-bottom: 12px;
      font-size: 24px;
    }

    .card {
      border-left: 4px solid #7a28b8;
      padding: 12px 16px;
      margin-top: 15px;
      background: #f5f9fd;
      border-radius: 5px;
    }

    .dream {
      background: #eaf6ff;
      border-left: 4px solid #1683bd;
    }

    .family-link {
      display: inline-block;
      color: #075b91;
      font-weight: bold;
      margin-top: 12px;
    }

    footer {
      text-align: center;
      background: #071b35;
      color: white;
      padding: 25px 15px;
      margin-top: 25px;
    }

    @media (max-width: 600px) {
      header {
        justify-content: center;
        text-align: center;
      }

      nav {
        justify-content: center;
      }

      section {
        padding: 20px;
      }
    }
  </style>
</head>

<body>

  <header>
    <div class="logo">Nishanthan Suseekaran</div>

    <nav>
      <a href="#home">Home</a>
      <a href="#about">About Me</a>
      <a href="#education">Education</a>
      <a href="#work">Work</a>
      <a href="#dream">My Dream</a>
      <a href="#family">My Family</a>
    </nav>
  </header>

  <div class="hero" id="home">
    <img
      class="profile"
      src="IMG-20261016-WA0009.jpg"
      alt="Nishanthan Suseekaran"
      onerror="this.style.display='none'"
    >


    <p>Welcome to My Personal Website</p>

    <p>
      My Life • My Education • My Work • My Dreams
    </p>

    <span class="tag">Dreaming of Becoming a Pilot</span>

    <div>
      <a class="button" href="#about">About Me</a>
      <a class="button" href="#dream">My Dream</a>
    </div>
  </div>

  <main>

    <section id="about">
      <h2>About Me</h2>

      <p>
        Hello! My name is Nishanthan Suseekaran.
        I am from Kaluwanchikudy, Batticaloa,
        Sri Lanka.
      </p>

      <p>
        This website is a place to share my life,
        education, work experience, family memories
        and my future dreams.
      </p>

      <div class="card">
        <strong>My Location</strong>
        <p>Kaluwanchikudy, Batticaloa, Sri Lanka</p>
      </div>
    </section>

    <section id="education">
      <h2>Education</h2>

      <div class="card">
        <h3>Basic Education – Primary School</h3>

        <p><strong>School:</strong>
          Kannapuram Primary School
        </p>

        <p><strong>Address:</strong>
          35 Village, Kannapuram, Vaikala
        </p>

        <p><strong>Years:</strong> 2003–2006</p>

        <p>
          My primary education helped me develop
          basic reading, writing, mathematics and
          general learning skills.
        </p>

        <p>
          I also enjoyed sports and school activities.
          My school days remain an important part
          of my life.
        </p>
      </div>

      <p style="margin-top:15px;">
        I am grateful to my teachers for their
        guidance, patience and encouragement
        during my early education.
      </p>
    </section>

    <section id="work">
      <h2>Work Experience</h2>

      <div class="card">
        <h3>Work Experience in Qatar</h3>

        <p><strong>Company:</strong> Axona
          (please confirm the official spelling)
        </p>

        <p><strong>Duration:</strong> 9 months</p>

        <p>
          My work experience has helped me learn
          responsibility, discipline and the
          importance of working hard.
        </p>
      </div>
    </section>

    <section id="dream" class="dream">
      <h2>My Dream – To Become a Pilot</h2>

      <p>
        Since childhood, I have dreamed of becoming
        a pilot. Although I did not have the
        opportunity and resources to study aviation
        earlier, my dream remains important to me.
      </p>

      <p>
        I am learning about aircraft, flight
        controls, aviation knowledge and the world
        of flying step by step.
      </p>

      <p>
        I believe that learning and determination
        can help me move closer to my dream.
      </p>
    </section>

    <section id="family">
      <h2>My Family</h2>

      <p>
        Family is an important part of life.
        This section is dedicated to family love,
        photographs, special memories and the people
        who make life meaningful.
      </p>

      <p>
        More family photographs, names and stories
        can be added here.
      </p>

      <a class="family-link" href="my-family.html">
        Visit My Family Page →
      </a>
    </section>

    <section id="contact">
      <h2>Thank You for Visiting</h2>

      <p>
        Thank you for visiting my personal website
        and learning about my journey, my family
        and my dream of becoming a pilot.
      </p>
    </section>

  </main>

  <footer>
    <p>© 2026 Nishanthan Suseekaran</p>
    <p>My Life • My Journey • My Dreams</p>
  </footer>

</body
