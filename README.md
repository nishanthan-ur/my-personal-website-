<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Nishanthan Suseekaran | My Profile</title>
<style>
*{box-sizing:border-box}
body{
  margin:0;
  font-family:Arial,sans-serif;
  background:#eef4fa;
  color:#243247;
  line-height:1.7;
}
header{
  background:linear-gradient(135deg,#061b38,#1266a8);
  color:white;
  text-align:center;
  padding:55px 18px;
}
header h1{font-size:32px;margin:10px 0}
header p{margin:6px}
.plane{font-size:48px}
nav{
  background:#082746;
  padding:14px;
  text-align:center;
}
nav a{
  color:white;
  text-decoration:none;
  margin:0 10px;
  display:inline-block;
}
main{max-width:850px;margin:25px auto;padding:0 15px}
section{
  background:white;
  padding:24px;
  margin:18px 0;
  border-radius:14px;
  box-shadow:0 4px 14px #0000000d;
}
h2{color:#1266a8;margin-top:0}
footer{
  background:#061b38;
  color:white;
  text-align:center;
  padding:22px;
}
</style>
</head>
<body>

<header>
  <div class="plane">✈️</div>
  <h1>Nishanthan Suseekaran</h1>
  <p>My Personal Profile</p>
  <p>Dream Big • Work Hard • Keep Moving Forward</p>
</header>

<nav>
  <a href="#about">About Me</a>
  <a href="#dream">My Dream</a>
  <a href="#education">Education</a>
  <a href="#work">Work</a>
</nav>

<main>
  <section id="about">
    <h2>About Me</h2>
    <p>Hello! My name is Nishanthan Suseekaran.</p>
    <p>I am from Kaluwanchikudy, Batticaloa, Sri Lanka.
    I believe in learning new things, working hard, and
    building a better future.</p>
  </section>

  <section id="dream">
    <h2>My Dream — To Become a Pilot ✈️</h2>
    <p>Since childhood, I have dreamed of becoming a pilot.
    Although I have faced challenges and limited opportunities,
    I have not given up on my dream.</p>
    <p>I want to continue learning about aircraft, aviation,
    and English, one step at a time.</p>
  </section>

  <section id="education">
    <h2>Basic Education – Primary School</h2>
    <p><strong>School:</strong> Kannapuram Primary School</p>
    <p><strong>Location:</strong> 35 Village, Kannapuram, Vaikala</p>
    <p><strong>Years:</strong> 2003–2006</p>
    <p>During my primary education, I learned reading, writing,
    mathematics, and other basic subjects. I also enjoyed sports
    and doing my best in school.</p>
    <p>I am grateful to my teachers for their guidance,
    encouragement, and support during my early education.</p>
  </section>

  <section id="work">
    <h2>Work Experience</h2>
    <p><strong>Company:</strong> Axona</p>
    <p><strong>Location:</strong> Qatar</p>
    <p><strong>Experience:</strong> 9 months</p>
    <p>My work experience has helped me develop responsibility,
    patience, and a willingness to learn.</p>
  </section>

  <section>
    <h2>My Future Goals</h2>
    <p>My goals are to improve my English, continue learning
    about aviation, gain useful skills, and work towards
    a better future.</p>
  </section>
</main>

<footer>
  <p>© 2026 Nishanthan Suseekaran</p>
  <p>My Journey • My Dreams • My Future</p>
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="ta">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Love Story ❤️</title>
<style>
*{box-sizing:border-box}
body{margin:0;font-family:Georgia,serif;background:linear-gradient(150deg,#020817,#071c42,#160b2c);color:#fff0f5;text-align:center;min-height:100vh}
header{padding:45px 18px 25px}
.rose{font-size:48px}
h1{font-size:clamp(32px,8vw,52px);color:#ffb6cf;margin:12px 0}
.sub{color:#c9d8ff;font-size:17px}
main{max-width:760px;margin:auto;padding:12px 18px 50px}
.card{background:#0b1734dd;border:1px solid #713955;border-radius:20px;padding:24px;margin:18px 0;box-shadow:0 8px 30px #0005}
h2{color:#ffc0d7}
input,textarea{width:100%;padding:13px;margin:8px 0;background:#071126;color:white;border:1px solid #826080;border-radius:10px;font-size:16px}
textarea{min-height:170px;resize:vertical}
button{background:#9e315f;color:white;border:0;border-radius:10px;padding:12px 20px;margin:7px;cursor:pointer;font-size:16px}
button:hover{background:#c44c7e}
#preview{max-width:100%;max-height:350px;border-radius:15px;margin-top:15px;display:none}
.story{white-space:pre-wrap;text-align:left;line-height:1.8}
footer{padding:25px;color:#c9d8ff}
</style>
</head>
<body>
<header>
<div class="rose">🌹 ❤️ 🌹</div>
<h1>My Love Story</h1>
<p class="sub">என் காதல் கதை · My heart, my story</p>
<p>சில நினைவுகள் என்றும் அழியாது…<br>Some memories live forever in the heart.</p>
</header>
<main>
<section class="card">
<h2>💌 Our Love Story | நம் காதல் கதை</h2>
<p>உன் மனதில் இருக்கும் கதையை இங்கே எழுது.</p>
<p>Write your special memories here.</p>
<textarea id="story" placeholder="தமிழில் அல்லது English-ல் உன் காதல் கதையை எழுது..."></textarea>
<button onclick="saveStory()">கதையைச் சேமி | Save Story</button>
<button onclick="showStory()">கதையைப் பார் | View Story</button>
<div id="saved" class="story"></div>
</section>
<section class="card">
<h2>📸 Our Special Memory</h2>
<p>உனக்குப் பிடித்த புகைப்படத்தைத் தேர்ந்தெடு.</p>
<input type="file" id="photo" accept="image/*">
<img id="preview" alt="Selected memory">
</section>
<section class="card">
<h2>❤️ A Message From My Heart</h2>
<p>“உண்மையான அன்பு இதயத்தில் வாழும்.”</p>
<p>“True love lives in the heart.”</p>
</section>
</main>
<footer>Made with ❤️ · My Love Story 🌹</footer>
<script>
const story=document.getElementById('story');
const saved=document.getElementById('saved');
function saveStory(){saved.textContent=story.value;alert('இந்தப் பக்கத்தில் கதை காட்டப்பட்டுள்ளது. நிரந்தரமாகச் சேமிக்க, உங்கள் கதையை மீண்டும் இங்கே எழுதலாம்.');}
function showStory(){saved.textContent=story.value;}
document.getElementById('photo').addEventListener('change',function(){
const file=this.files[0];if(!file)return;
const reader=new FileReader();
reader.onload=function(e){const img=document.getElementById('preview');img.src=e.target.result;img.style.display='inline-block';};
reader.readAsDataURL(file);
});
</script>
</body>
</html>
