
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Nishanthan Suseekaran | My Website</title>

  <meta name="description"
    content="Welcome to Nishanthan Suseekaran's personal website. Explore his profile, education, work experience and dream of becoming a pilot.">

  <meta name="theme-color" content="#071b36">

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      background: #f4f7fb;
      color: #222;
      line-height: 1.7;
    }

    header {
      background: #071b36;
      color: white;
      padding: 30px 15px;
      text-align: center;
    }

    header h1 {
      color: #62b6ff;
      font-size: 28px;
    }

    nav {
      background: #12345a;
      padding: 12px 5px;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 10;
    }

    nav a {
      color: white;
      text-decoration: none;
      display: inline-block;
      padding: 7px 9px;
    }

    nav a:hover {
      color: #62b6ff;
    }

    section {
      background: white;
      max-width: 900px;
      margin: 22px auto;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 3px 12px #00000010;
      scroll-margin-top: 80px;
    }

    h2 {
      color: #123d70;
      margin-bottom: 15px;
      border-bottom: 2px solid #62b6ff;
      padding-bottom: 7px;
    }

    h3 {
      color: #123d70;
      margin: 12px 0 5px;
    }

    .info {
      margin: 8px 0;
    }

    .profile {
      text-align: center;
    }

    .profile-photo {
      width: 180px;
      height: 180px;
      object-fit: cover;
      border-radius: 50%;
      border: 5px solid #62b6ff;
      margin: 15px auto;
      display: block;
      background: #eaf4ff;
    }

    .plane-photo {
      display: block;
      width: 100%;
      max-width: 750px;
      height: auto;
      max-height: 430px;
      object-fit: cover;
      border-radius: 12px;
      margin: 15px auto;
      background: #eaf4ff;
    }

    .dream {
      background: #eaf4ff;
      border-left: 5px solid #2586d8;
      padding: 15px;
      margin-top: 15px;
      border-radius: 5px;
    }

    .map-link {
      display: inline-block;
      background: #123d70;
      color: white;
      text-decoration: none;
      padding: 10px 16px;
      border-radius: 7px;
      margin-top: 10px;
    }

    .map-link:hover {
      background: #2586d8;
    }

    footer {
      background: #071b36;
      color: white;
      text-align: center;
      padding: 22px 10px;
      margin-top: 30px;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 23px;
      }

      section {
        margin: 15px 10px;
        padding: 18px;
      }

      nav a {
        padding: 6px;
        font-size: 14px;
      }

      .profile-photo {
        width: 150px;
        height: 150px;
      }
    }
  </style>
</head>

<body>

  <header id="home">
    <h1>Nishanthan Suseekaran</h1>
    <p>My Life | My Education | My Dream</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About Me</a>
    <a href="#education">Education</a>
    <a href="#work">Work</a>
    <a href="#dream">My Dream</a>
    <a href="#location">Location</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="profile">
    <h2>Welcome to My Website</h2>

    <!-- PROFILE PHOTO:
         Upload your photo to the same GitHub folder
         and name it profile.jpg -->

    <img
      class="profile-photo"
      src="profile.jpg"
      alt="Nishanthan Suseekaran profile photo"
      onerror="this.style.display='none'; document.getElementById('photo-note').style.display='block';">

    <p id="photo-note" style="display:none;">
      Profile photo will appear here after you upload profile.jpg.
    </p>

    <p>
      Welcome to my personal website.
      This website shares my life, education,
      work experience and future dreams.
    </p>
  </section>

  <section id="about">
    <h2>About Me</h2>

    <p class="info">
      <strong>Name:</strong> Nishanthan Suseekaran
    </p>

    <p class="info"><strong>Age:</strong> 25</p>

    <p class="info">
      <strong>Location:</strong>
      Kaluwanchikudy, Batticaloa, Sri Lanka
    </p>

    <p>
      I am from Sri Lanka. I believe in learning,
      working hard and moving forward in life.
    </p>
  </section>

  <section id="education">
    <h2>My Education</h2>

    <h3>Primary Education</h3>
    <p>Kannapuram Primary School</p>
    <p>Years: 2003–2006</p>

    <br>

    <h3>General Education</h3>
    <p>Kannagipuram Vinayahar Vidiyalayam, Mahiloor</p>
    <p>Years: 2006–2014</p>

    <p>
      <strong>Subjects:</strong>
      Tamil, Mathematics, English, Science, History,
      Art, Geography and Drama.
    </p>

    <br>

    <h3>Higher Education</h3>
    <p>
      BT/PD/Paddiruppu Madya Maha Vidyalayam,
      Kaluwanchikudy
    </p>

    <p>Years: 2019–2020</p>

    <p>
      <strong>Smart Class Subjects:</strong>
      Electrical, Textile, Graphic Design and ICT.
    </p>
  </section>

  <section id="work">
    <h2>My Work Experience</h2>

    <p><strong>Company:</strong> Akshona</p>
    <p><strong>Work:</strong> Tailor Driver</p>
    <p><strong>Country:</strong> Qatar</p>
    <p><strong>Experience:</strong> 9 Months</p>
  </section>

  <section id="dream">
    <h2>My Biggest Dream</h2>

    <!-- AIRPLANE PHOTO:
         Upload an airplane photo into the same folder
         and name it airplane.jpg -->

    <img
      class="plane-photo"
      src="airplane.jpg"
      alt="Airplane representing my dream of becoming a pilot"
      onerror="this.style.display='none'; document.getElementById('plane-note').style.display='block';">

    <p id="plane-note" style="display:none;">
      Airplane photo will appear here after you upload airplane.jpg.
    </p>

    <div class="dream">
      <h3>My Dream Is to Become a Pilot</h3>

      <p>
        Since childhood, I have dreamed of becoming
        a pilot. Although I have faced challenges
        and limited opportunities, my dream is still alive.
        I will continue learning and working towards my future.
      </p>

      <p><strong>Keep Going — My Dream Is Still Alive!</strong></p>
    </div>
  </section>

  <section id="location">
    <h2>My Location</h2>

    <p>Kaluwanchikudy, Batticaloa, Sri Lanka</p>

    <a
      class="map-link"
      href="https://www.google.com/maps/search/?api=1&query=Kaluwanchikudy%2C%20Batticaloa%2C%20Sri%20Lanka"
      target="_blank"
      rel="noopener noreferrer">
      Open My Location in Google Maps
    </a>
  </section>

  <section id="contact">
    <h2>Contact</h2>

    <p>Welcome to my personal website.</p>
    <p>Location: Sri Lanka</p>
    <p>
      My family, personal photos and other website
      sections can be added here later.
    </p>
  </section>

  <footer>
    <p>© 2026 Nishanthan Suseekaran</p>
    <p>Learn • Work • Dream • Achieve</p>
  </footer>

</body>
</html>
