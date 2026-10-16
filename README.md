
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nishanthan Suseekaran - Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <!-- FontAwesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
</head>
<body>

    <!-- Header / Navbar -->
    <header class="navbar">
        <div class="logo">
            <i class="fa-solid fa-plane"></i>
            <span>Nishanthan Suseekaran</span>
        </div>
        <nav>
            <ul class="nav-links">
                <li><a href="#" class="active">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Education</a></li>
                <li><a href="#">Work</a></li>
                <li><a href="#">My Family</a></li>
                <li><a href="#">My Love Story</a></li>
                <li><a href="#">Gallery</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero-section">
        <div class="hero-content">
            <div class="profile-container">
                <!-- உங்கள் போட்டோ பெயரைக் கொடுக்கவும் (எ.கா: profile.jpg) -->
                <img src="profile.jpg" alt="Nishanthan Suseekaran" class="profile-img">
            </div>
            <div class="intro-text">
                <span class="greeting">Hello! I'm</span>
                <h1>Nishanthan <span class="highlight">Suseekaran</span></h1>
                <p class="tagline">Dreamer <span class="dot">|</span> Learner <span class="dot">|</span> Future Pilot</p>
                <div class="location">
                    <i class="fa-solid fa-location-dot"></i> Kaluwanchikudy / Batticaloa / Sri Lanka
                </div>
                <blockquote class="quote">
                    "Sky is not the limit,<br>it's just the beginning." <i class="fa-solid fa-plane-up"></i>
                </blockquote>
            </div>
        </div>
    </section>

    <!-- About Me Section -->
    <section class="about-section">
        <div class="about-container">
            <!-- Left About Text -->
            <div class="about-text-box">
                <h2><i class="fa-solid fa-user-astronaut"></i> About <span class="highlight">Me</span></h2>
                <p>
                    Hi! I'm Nishanthan Suseekaran. I'm 25 years old and from Sri Lanka. My biggest dream since childhood is to become a pilot. Although I faced many challenges and lacked the proper opportunities, facilities and resources to study aviation, my dream is still alive. I am now working hard, learning step by step, and building my future. This website is a small step towards my big dream and a way to share my journey, life and achievements.
                </p>
                <p class="cursive-quote">Keep Going... My Dream is Still Alive...</p>
            </div>

            <!-- Right Info Card -->
            <div class="about-card">
                <div class="card-item">
                    <i class="fa-solid fa-user"></i>
                    <div>
                        <span class="label">Name</span>
                        <span class="value">Nishanthan Suseekaran</span>
                    </div>
                </div>
                <div class="card-item">
                    <i class="fa-solid fa-calendar-days"></i>
                    <div>
                        <span class="label">Age</span>
                        <span class="value">25</span>
                    </div>
                </div>
                <div class="card-item">
                    <i class="fa-solid fa-location-dot"></i>
                    <div>
                        <span class="label">Location</span>
                        <span class="value">Kaluwanchikudy / Batticaloa / Sri Lanka</span>
                    </div>
                </div>
                <div class="card-item">
                    <i class="fa-solid fa-briefcase"></i>
                    <div>
                        <span class="label">Current Job</span>
                        <span class="value">Tailor Driver (Akshona)<br>Qatar (9 Months)</span>
                    </div>
                </div>
                <div class="card-item">
                    <i class="fa-solid fa-bullseye"></i>
                    <div>
                        <span class="label">Dream</span>
                        <span class="value">Become a Pilot</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Bottom Navigation Icons -->
    <footer class="footer-nav">
        <div class="footer-item">
            <i class="fa-solid fa-plane"></i>
            <h3>Pilot Journey</h3>
            <p>Learn • Fly • Achieve</p>
        </div>
        <div class="footer-item">
            <i class="fa-solid fa-book-open"></i>
            <h3>Education</h3>
            <p>Knowledge Builds Future</p>
        </div>
        <div class="footer-item">
            <i class="fa-solid fa-suitcase"></i>
            <h3>Work Experience</h3>
            <p>Growth & Learning</p>
        </div>
        <div class="footer-item">
            <i class="fa-solid fa-users"></i>
            <h3>My Family</h3>
            <p>My Strength</p>
        </div>
        <div class="footer-item">
            <i class="fa-solid fa-heart"></i>
            <h3>My Love Story</h3>
            <p>A Beautiful Chapter</p>
        </div>
        <div class="footer-item">
            <i class="fa-solid fa-image"></i>
            <h3>Gallery</h3>
            <p>Moments & Memories</p>
        </div>
    </footer>

</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

body {
    background-color: #050b14;
    color: #ffffff;
    overflow-x: hidden;
}

/* Navbar */
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 50px;
    background-color: #050b14;
    border-bottom: 1px solid rgba(255, 255, 255, 0.05);
}

.logo {
    display: flex;
    align-items: center;
    gap: 10px;
    font-weight: 600;
    font-size: 18px;
    color: #3b82f6;
}

.logo i {
    font-size: 20px;
}

.nav-links {
    list-style: none;
    display: flex;
    gap: 25px;
}

.nav-links a {
    text-decoration: none;
    color: #94a3b8;
    font-size: 14px;
    font-weight: 500;
    transition: 0.3s;
}

.nav-links a:hover, .nav-links a.active {
    color: #ffffff;
}

.nav-links a.active {
    border-bottom: 2px solid #3b82f6;
    padding-bottom: 4px;
}

/* Hero Section */
.hero-section {
    position: relative;
    background: linear-gradient(rgba(5, 11, 20, 0.6), rgba(5, 11, 20, 0.9)), url('bg-airplane.jpg') no-repeat center center/cover;
    /* குறிப்பு: விமானம் மற்றும் சூரிய அஸ்தமனம் உள்ள பேக்ரவுண்ட் படத்திற்கு 'bg-airplane.jpg' என பெயரிடலாம் */
    padding: 80px 50px;
    min-height: 500px;
    display: flex;
    align-items: center;
}

.hero-content {
    display: flex;
    align-items: center;
    gap: 60px;
    max-width: 1200px;
    margin: 0 auto;
    width: 100%;
}

.profile-container {
    width: 250px;
    height: 250px;
    border-radius: 50%;
    border: 4px solid #3b82f6;
    overflow: hidden;
    box-shadow: 0 0 25px rgba(59, 130, 246, 0.4);
    flex-shrink: 0;
}

.profile-img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.intro-text .greeting {
    font-size: 28px;
    color: #ffffff;
    font-weight: 300;
    font-style: italic;
}

.intro-text h1 {
    font-size: 42px;
    font-weight: 700;
    margin: 5px 0;
}

.highlight {
    color: #3b82f6;
}

.tagline {
    font-size: 16px;
    color: #94a3b8;
    margin-bottom: 15px;
    letter-spacing: 1px;
}

.dot {
    color: #3b82f6;
    margin: 0 5px;
}

.location {
    font-size: 14px;
    color: #cbd5e1;
    margin-bottom: 20px;
    display: flex;
    align-items: center;
    gap: 8px;
}

.location i {
    color: #3b82f6;
}

.quote {
    font-style: italic;
    color: #94a3b8;
    font-size: 15px;
    border-left: 3px solid #3b82f6;
    padding-left: 12px;
    line-height: 1.5;
}

.quote i {
    color: #3b82f6;
    font-size: 12px;
    margin-left: 5px;
}

/* About Section */
.about-section {
    background-color: #07101e;
    padding: 80px 50px;
}

.about-container {
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    gap: 50px;
    align-items: flex-start;
}

.about-text-box {
    flex: 1.2;
}

.about-text-box h2 {
    font-size: 32px;
    margin-bottom: 20px;
    display: flex;
    align-items: center;
    gap: 12px;
}

.about-text-box h2 i {
    color: #3b82f6;
    font-size: 28px;
}

.about-text-box p {
    color: #94a3b8;
    line-height: 1.8;
    font-size: 15px;
    margin-bottom: 20px;
}

.cursive-quote {
    font-family: 'Brush Script MT', cursive, sans-serif;
    font-size: 26px;
    color: #3b82f6 !important;
    margin-top: 30px;
}

/* About Card Right */
.about-card {
    flex: 1;
    background-color: #0b1629;
    border: 1px solid rgba(59, 130, 246, 0.2);
    border-radius: 16px;
    padding: 25px;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
}

.card-item {
    display: flex;
    align-items: center;
    gap: 20px;
    padding: 15px 0;
    border-bottom: 1px solid rgba(255, 255, 255, 0.05);
}

.card-item:last-child {
    border-bottom: none;
}

.card-item i {
    font-size: 22px;
    color: #3b82f6;
    width: 30px;
    text-align: center;
}

.card-item .label {
    display: block;
    font-size: 12px;
    color: #64748b;
    text-transform: uppercase;
    letter-spacing: 0.5px;
}

.card-item .value {
    font-size: 14px;
    color: #ffffff;
    font-weight: 500;
}

/* Footer Nav Icons */
.footer-nav {
    background-color: #040811;
    padding: 40px 50px;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
    gap: 20px;
    border-top: 1px solid rgba(255, 255, 255, 0.05);
    text-align: center;
}

.footer-item {
    padding: 20px;
    border-radius: 10px;
    transition: 0.3s;
}

.footer-item:hover {
    background-color: rgba(59, 130, 246, 0.05);
}

.footer-item i {
    font-size: 24px;
    color: #3b82f6;
    margin-bottom: 10px;
}

.footer-item h3 {
    font-size: 15px;
    font-weight: 600;
    margin-bottom: 5px;
    color: #ffffff;
}

.footer-item p {
    font-size: 12px;
    color: #64748b;
}
