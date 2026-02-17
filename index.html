<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>JUDAS</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700;900&display=swap" rel="stylesheet">

<style>

/* =========================
   ROOT
========================= */

:root{
  --bg:#050505;
  --text:#fff;
  --primary:#ff2e63;
  --glass:rgba(255,255,255,0.05);
  --glass-border:rgba(255,255,255,0.1);
}

*,
*::before,
*::after{
  box-sizing:border-box;
  margin:0;
  padding:0;
}

body{
  font-family:'Inter',sans-serif;
  background:var(--bg);
  color:var(--text);
  overflow-x:hidden;
}

/* =========================
   HERO
========================= */

.hero{
  position:relative;
  height:100vh;
  display:flex;
  align-items:center;
  justify-content:center;
  overflow:hidden;
}

.hero__title{
  font-size:clamp(4rem,12vw,10rem);
  font-weight:900;
  letter-spacing:-4px;
  text-transform:uppercase;
  will-change:transform;
}

.hero__bg{
  position:absolute;
  inset:0;
  background:url('https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?q=80&w=1974') center/cover;
  filter:blur(20px);
  z-index:-1;
  will-change:transform;
}

/* =========================
   HORIZONTAL
========================= */

.horizontal{
  position:relative;
  height:300vh;
}

.horizontal__track{
  position:sticky;
  top:0;
  display:flex;
  height:100vh;
  width:300vw;
  will-change:transform;
}

.horizontal__panel{
  width:100vw;
  display:flex;
  align-items:center;
  justify-content:center;
  font-size:clamp(2rem,5vw,4rem);
  font-weight:700;
}

/* =========================
   BENTO
========================= */

.bento{
  padding:100px 10vw;
}

.bento__grid{
  display:grid;
  grid-template-columns:repeat(4,1fr);
  gap:30px;
}

.card{
  background:var(--glass);
  backdrop-filter:blur(20px);
  border:1px solid var(--glass-border);
  border-radius:24px;
  padding:40px;
  transition:transform .3s ease;
}

.card:hover{
  transform:translateY(-8px);
}

.card--large{
  grid-column:span 2;
  grid-row:span 2;
}

.cta{
  text-align:center;
  margin-top:80px;
}

.btn{
  padding:20px 60px;
  background:#fff;
  color:#000;
  border:none;
  font-weight:700;
  cursor:pointer;
  transition:.3s;
}

.btn:hover{
  background:var(--primary);
  color:#fff;
  transform:translateY(-4px);
}

/* =========================
   RESPONSIVE
========================= */

@media(max-width:900px){

  .horizontal__track{
    flex-direction:column;
    width:100vw;
  }

  .horizontal{
    height:auto;
  }

  .horizontal__panel{
    height:100vh;
  }

  .bento__grid{
    grid-template-columns:1fr;
  }

}

</style>
</head>
<body>

<header class="hero">
  <div class="hero__bg"></div>
  <h1 class="hero__title" id="heroTitle">JUDAS</h1>
</header>

<section class="horizontal">
  <div class="horizontal__track" id="track">
    <div class="horizontal__panel">RAW</div>
    <div class="horizontal__panel">OBSESSION</div>
    <div class="horizontal__panel">LUST</div>
  </div>
</section>

<section class="bento">
  <div class="bento__grid">
    <div class="card card--large">Premium</div>
    <div class="card">Secret</div>
    <div class="card">Fetish</div>
    <div class="card">Exclusive</div>
  </div>

  <div class="cta">
    <button class="btn">ENTER</button>
  </div>
</section>

<script>

/* =========================
   RAF SCROLL ENGINE
========================= */

const heroBg = document.querySelector('.hero__bg');
const heroTitle = document.getElementById('heroTitle');
const track = document.getElementById('track');

let scrollY = 0;

function update(){
  scrollY = window.scrollY;

  // Parallax
  heroBg.style.transform = `translateY(${scrollY * 0.3}px)`;

  // Horizontal
  const horizontalOffset = track.parentElement.offsetTop;
  const distance = scrollY - horizontalOffset;
  if(distance > 0 && distance < window.innerHeight * 2){
    track.style.transform = `translateX(-${distance}px)`;
  }

  requestAnimationFrame(update);
}

update();

/* Mouse kinetic */

document.addEventListener('mousemove',e=>{
  const x = (window.innerWidth/2 - e.clientX)/40;
  const y = (window.innerHeight/2 - e.clientY)/40;
  heroTitle.style.transform = `translate(${x}px,${y}px)`;
});

</script>

</body>
</html>
