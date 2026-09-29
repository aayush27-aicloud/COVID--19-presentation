
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>COVID-19 | College Presentation</title>
<style>
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{font-family:Arial,Helvetica,sans-serif;line-height:1.6;color:#18324a;background:#f4f9fc}
nav{position:fixed;top:0;left:0;right:0;z-index:1000;background:#073b5c;color:white;display:flex;justify-content:center;gap:8px;padding:12px;box-shadow:0 2px 10px #0002}
nav a{color:white;text-decoration:none;padding:8px 12px;border-radius:8px;font-size:14px}
nav a:hover{background:#0b6e99}
section{min-height:100vh;padding:95px 8% 55px;display:flex;flex-direction:column;justify-content:center}
.hero{background:linear-gradient(135deg,#073b5c,#0b7fab);color:white;text-align:center}
.hero h1{font-size:clamp(48px,9vw,90px);letter-spacing:3px}
.hero h2{font-size:clamp(22px,4vw,36px);margin:8px 0 25px}
.hero p{font-size:19px}
.badge{display:inline-block;background:#ffffff22;border:1px solid #ffffff55;padding:9px 18px;border-radius:30px;margin-bottom:20px}
h2.title{font-size:42px;color:#073b5c;margin-bottom:18px;text-align:center}
.subtitle{text-align:center;max-width:800px;margin:0 auto 35px;color:#547084}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:20px;max-width:1050px;width:100%;margin:auto}
.card{background:white;border-radius:18px;padding:24px;box-shadow:0 8px 25px #073b5c12;border:1px solid #dcecf4}
.card h3{color:#0b6e99;margin-bottom:8px;font-size:21px}
.card .icon{font-size:35px;margin-bottom:8px}
.highlight{background:#e8f7fb;border-left:6px solid #0b7fab;padding:20px;border-radius:10px;max-width:900px;margin:20px auto}
ul{padding-left:22px}
li{margin:8px 0}
.stat{font-size:38px;font-weight:bold;color:#0b7fab}
footer{text-align:center;padding:25px;background:#073b5c;color:white}
button{border:0;background:#0b7fab;color:white;padding:12px 20px;border-radius:8px;cursor:pointer;font-size:16px;margin-top:15px}
button:hover{background:#095d80}
@media(max-width:700px){nav{overflow-x:auto;justify-content:flex-start}.hero h1{font-size:52px}h2.title{font-size:32px}section{padding-left:5%;padding-right:5%}}
</style>
</head>
<body>

<nav>
<a href="#home">Home</a>
<a href="#intro">Introduction</a>
<a href="#spread">Transmission</a>
<a href="#symptoms">Symptoms</a>
<a href="#impact">Social Impact</a>
<a href="#nursing">Nursing</a>
<a href="#prevention">Prevention</a>
<a href="#conclusion">Conclusion</a>
</nav>

<section id="home" class="hero">
  <div class="badge">B.Sc. Nursing • 1st Semester</div>
  <h1>COVID-19</h1>
  <h2>A College Presentation</h2>
  <p><strong>Presented by:</strong> Aayush</p>
  <p>Satya College of Nursing</p>
  <button onclick="document.querySelector('#intro').scrollIntoView()">Start Presentation ↓</button>
</section>

<section id="intro">
  <h2 class="title">Introduction</h2>
  <p class="subtitle">COVID-19 is an infectious disease caused by the SARS-CoV-2 virus. It emerged in late 2019 and spread worldwide, leading to a major global public-health emergency.</p>
  <div class="grid">
    <div class="card"><div class="icon">🦠</div><h3>Cause</h3><p>SARS-CoV-2, a coronavirus, causes COVID-19.</p></div>
    <div class="card"><div class="icon">🌍</div><h3>Global Impact</h3><p>The pandemic affected healthcare, education, employment and everyday social life.</p></div>
    <div class="card"><div class="icon">🏥</div><h3>Healthcare</h3><p>Healthcare systems and frontline workers faced extraordinary demands.</p></div>
  </div>
</section>

<section id="spread">
  <h2 class="title">Transmission</h2>
  <p class="subtitle">The virus mainly spreads through respiratory particles released when an infected person breathes, talks, coughs or sneezes.</p>
  <div class="grid">
    <div class="card"><div class="icon">💨</div><h3>Respiratory Particles</h3><p>Close contact and shared indoor air can increase the chance of transmission.</p></div>
    <div class="card"><div class="icon">👥</div><h3>Close Contact</h3><p>Risk can increase when people are close together for prolonged periods.</p></div>
    <div class="card"><div class="icon">🏠</div><h3>Indoor Spaces</h3><p>Poorly ventilated indoor environments can facilitate spread.</p></div>
  </div>
</section>

<section id="symptoms">
  <h2 class="title">Signs & Symptoms</h2>
  <p class="subtitle">Symptoms can range from mild to severe, and some infected people may have no symptoms.</p>
  <div class="grid">
    <div class="card"><div class="icon">🤒</div><h3>Common</h3><ul><li>Fever or chills</li><li>Cough</li><li>Sore throat</li><li>Fatigue</li><li>Headache</li></ul></div>
    <div class="card"><div class="icon">🫁</div><h3>Respiratory</h3><ul><li>Shortness of breath</li><li>Difficulty breathing</li><li>Chest discomfort</li></ul></div>
    <div class="card"><div class="icon">⚠️</div><h3>Seek Medical Care</h3><p>Severe breathing difficulty, persistent chest pain, confusion or other emergency warning signs require urgent medical attention.</p></div>
  </div>
</section>

<section id="impact">
  <h2 class="title">Social Impact of COVID-19</h2>
  <p class="subtitle">The pandemic was not only a health crisis; it also changed social relationships, education, work and community life.</p>
  <div class="grid">
    <div class="card"><div class="icon">🎓</div><h3>Education</h3><p>School and college closures shifted many learners toward online education and created access challenges.</p></div>
    <div class="card"><div class="icon">💼</div><h3>Employment</h3><p>Lockdowns and economic disruption affected jobs, businesses and household income.</p></div>
    <div class="card"><div class="icon">🧠</div><h3>Mental & Social Well-being</h3><p>Isolation, uncertainty, bereavement and disruption affected social and emotional well-being.</p></div>
    <div class="card"><div class="icon">🤝</div><h3>Community</h3><p>Communities organized support, public-health measures and assistance for vulnerable people.</p></div>
  </div>
</section>

<section id="nursing">
  <h2 class="title">Role of Nurses</h2>
  <p class="subtitle">Nurses played an essential role in patient care, prevention, education and community health during the pandemic.</p>
  <div class="grid">
    <div class="card"><div class="icon">🩺</div><h3>Patient Care</h3><p>Monitor patients, provide nursing care and communicate changes in condition to the healthcare team.</p></div>
    <div class="card"><div class="icon">🧤</div><h3>Infection Prevention</h3><p>Follow appropriate hand hygiene, PPE and infection-control procedures.</p></div>
    <div class="card"><div class="icon">📢</div><h3>Health Education</h3><p>Teach patients and families about prevention, symptoms, treatment and when to seek care.</p></div>
    <div class="card"><div class="icon">❤️</div><h3>Emotional Support</h3><p>Support patients and families while maintaining compassionate and safe communication.</p></div>
  </div>
</section>

<section id="prevention">
  <h2 class="title">Prevention</h2>
  <p class="subtitle">Public-health measures help reduce respiratory virus transmission and protect people at higher risk.</p>
  <div class="grid">
    <div class="card"><div class="icon">🧼</div><h3>Hand Hygiene</h3><p>Clean hands regularly, especially before eating and after coughing, sneezing or touching potentially contaminated surfaces.</p></div>
    <div class="card"><div class="icon">😷</div><h3>Masks</h3><p>Use a well-fitting mask in situations where respiratory-virus precautions are appropriate.</p></div>
    <div class="card"><div class="icon">💉</div><h3>Vaccination</h3><p>Follow current vaccination recommendations from qualified health authorities.</p></div>
    <div class="card"><div class="icon">🌬️</div><h3>Ventilation</h3><p>Improve indoor ventilation and avoid crowded, poorly ventilated spaces when respiratory-virus activity is high.</p></div>
  </div>
</section>

<section id="conclusion">
  <h2 class="title">Conclusion</h2>
  <div class="highlight">
    <p>COVID-19 demonstrated how an infectious disease can affect not only individual health but also families, communities, education, employment and healthcare systems. Nurses and other healthcare professionals have an important role in prevention, patient care, education and community support.</p>
  </div>
  <div class="card" style="max-width:900px;margin:20px auto">
    <h3>Key Message</h3>
    <p><strong>Prevention, responsible health practices, timely medical care and community cooperation are important parts of managing respiratory infectious diseases.</strong></p>
  </div>
  <div class="card" style="max-width:900px;margin:20px auto">
    <h3>References</h3>
    <ul>
      <li>World Health Organization (WHO) — COVID-19 resources</li>
      <li>Centers for Disease Control and Prevention (CDC) — COVID-19 guidance</li>
      <li>Ministry of Health & Family Welfare, Government of India</li>
    </ul>
  </div>
</section>

<footer>
  <p>COVID-19 College Presentation • Aayush • Satya College of Nursing</p>
</footer>

<script>
const links=document.querySelectorAll('nav a');
links.forEach(a=>a.addEventListener('click',()=>window.scrollTo));
</script>
</body>
</html>
