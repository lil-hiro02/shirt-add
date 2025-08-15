<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>COMTECH 2 B PALARO SHIRT ENTRY</title>
  <style>
    :root {
      --bg: #0b0b0f;
      --card: #13131a;
      --text: #e8e8ee;
      --muted: #a3a3b2;
      --accent: #71e6a8;
      --accent-2: #7aa2ff;
      --ring: rgba(113,230,168,.35);
    }
    * { box-sizing: border-box; }
    html, body { height: 100%; }
    body {
      margin: 0;
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
      background: radial-gradient(1200px 800px at 10% -10%, #162030 0%, rgba(22,32,48,0) 60%),
                  radial-gradient(1200px 800px at 110% 10%, #1c1f36 0%, rgba(28,31,54,0) 60%),
                  var(--bg);
      color: var(--text);
      line-height: 1.5;
    }
    header {
      position: sticky; top: 0; z-index: 50; backdrop-filter: blur(10px);
      background: linear-gradient(0deg, rgba(19,19,26,.8), rgba(19,19,26,.8));
      border-bottom: 1px solid rgba(255,255,255,.06);
    }
    .wrap { max-width: 1100px; margin: 0 auto; padding: 16px 20px; }
    .title { display: flex; align-items: center; justify-content: space-between; gap: 12px; }
    .title h1 { font-size: clamp(20px, 4vw, 36px); margin: 0; letter-spacing: .5px; }
    .hero { padding: 28px 20px 8px; text-align: center; }
    .hero p { color: var(--muted); margin: 8px 0 0; }
    .slider { position: relative; width: min(100%, 960px); margin: 18px auto; aspect-ratio: 16/9;
      background: #0f1117; border-radius: 20px; overflow: hidden; box-shadow: 0 10px 40px rgba(0,0,0,.45);
      border: 1px solid rgba(255,255,255,.06); }
    .slides { display: flex; height: 100%; transition: transform .6s ease; }
    .slide { flex: 0 0 100%; position: relative; }
    .slide img { width: 100%; height: 100%; object-fit: cover; display: block; }
    .caption { position: absolute; inset: auto 0 0 0; padding: 14px 18px; background: linear-gradient(180deg, rgba(0,0,0,0), rgba(0,0,0,.6));
      color: #fff; font-size: 14px; text-align: left; }
    .ctrl { position: absolute; top: 50%; transform: translateY(-50%);
      width: 42px; height: 42px; border: 1px solid rgba(255,255,255,.2); border-radius: 50%;
      background: rgba(19,19,26,.5); display: grid; place-items: center; cursor: pointer; user-select: none;
      transition: transform .15s ease, background .2s ease; backdrop-filter: blur(6px); }
    .ctrl:hover { background: rgba(19,19,26,.8); transform: translateY(-50%) scale(1.05); }
    .prev { left: 10px; } .next { right: 10px; }
    .ctrl svg { width: 22px; height: 22px; stroke: white; }
    .dots { position: absolute; left: 50%; bottom: 10px; transform: translateX(-50%); display: flex; gap: 8px; }
    .dot { width: 10px; height: 10px; border-radius: 50%; background: rgba(255,255,255,.35); border: 1px solid rgba(255,255,255,.5); cursor: pointer; }
    .dot.active { background: linear-gradient(90deg, var(--accent), var(--accent-2)); border-color: transparent; box-shadow: 0 0 0 6px var(--ring); }
    .card { max-width: 960px; margin: 18px auto 40px; background: var(--card); border: 1px solid rgba(255,255,255,.06);
      border-radius: 20px; padding: 18px; display: grid; gap: 16px; box-shadow: 0 10px 30px rgba(0,0,0,.35); }
    .grid { display: grid; grid-template-columns: 1fr; gap: 14px; }
    @media (min-width: 760px) { .grid { grid-template-columns: 1fr 1fr; } }
    .btn { appearance: none; border: none; padding: 12px 16px; border-radius: 999px; font-weight: 700; cursor: pointer; }
    .btn-ghost { color: var(--text); background: transparent; border: 1px solid rgba(255,255,255,.2); }
    footer { text-align: center; color: var(--muted); padding: 24px 10px 40px; font-size: 14px; }
    a { color: inherit; }
  </style>
</head>
<body>
  <header>
    <div class="wrap title">
      <h1>COMTECH 2 B PALARO SHIRT ENTRY</h1>
    </div>
  </header>

  <section class="hero">
    <div class="wrap">
      <h2 style="margin:0;font-size:clamp(18px,3vw,22px)">Pack Strong, Fear None✨</h2>
      <p>this wolf theme describe the entire BINDTECH DEPARTMENT. fighting and protecting each and everyone  .</p>
    </div>
  </section>

  <div class="slider" aria-label="Shirt image slider">
    <div class="slides" id="slides">
      <figure class="slide">
        <img src="add.png" alt="Front view mockup" />
        <figcaption class="caption">#1 FIERCE LOOK</figcaption>
      </figure>
      <figure class="slide">
        <img src="PALARO1.png" alt="Back print detail" />
        <figcaption class="caption">NORM</figcaption>
      </figure>
      <figure class="slide">
        <img src="PALARO1.png" alt="Close-up fabric" />
        <figcaption class="caption">DESIGN LAY OUT</figcaption>
      </figure>
    </div>
    <button class="ctrl prev" id="prev"><svg viewBox="0 0 24 24" fill="none" stroke-width="2"><path d="M15 6l-6 6 6 6"/></svg></button>
    <button class="ctrl next" id="next"><svg viewBox="0 0 24 24" fill="none" stroke-width="2"><path d="M9 6l6 6-6 6"/></svg></button>
    <div class="dots" id="dots"></div>
  </div>

  <section class="card">
    <div class="grid">
      <div>
        <h3 style="margin:0 0 6px">Designed by ALWAYNE</h3>
        <div class="cta">
          <a class="btn btn-ghost" href="https://www.facebook.com/Alwayne1125">Contact Me</a>
        </div>
      </div>
    </div>
  </section>

  <footer>
    Designed for the COMTECH 2 B Palaro Shirt Entry
  </footer>

  <script>
    (function(){
      const slides = document.getElementById('slides');
      const dotsWrap = document.getElementById('dots');
      const prev = document.getElementById('prev');
      const next = document.getElementById('next');
      const total = slides.children.length;
      let index = 0; let timer = null;
      for (let i = 0; i < total; i++) {
        const d = document.createElement('button');
        d.className = 'dot' + (i === 0 ? ' active' : '');
        d.addEventListener('click', () => go(i));
        dotsWrap.appendChild(d);
      }
      const dots = dotsWrap.children;
      function go(n) {
        index = (n + total) % total;
        slides.style.transform = `translateX(${-index * 100}%)`;
        [...dots].forEach((el, i) => el.classList.toggle('active', i === index));
        restart();
      }
      function nextSlide(){ go(index + 1); }
      function prevSlide(){ go(index - 1); }
      next.addEventListener('click', nextSlide);
      prev.addEventListener('click', prevSlide);
      let startX = 0; let dx = 0; let isDown = false;
      slides.addEventListener('pointerdown', (e)=>{ isDown = true; startX = e.clientX; dx = 0; });
      slides.addEventListener('pointermove', (e)=>{ if(!isDown) return; dx = e.clientX - startX; });
      slides.addEventListener('pointerup', ()=>{ if(!isDown) return; isDown = false; if (dx > 40) prevSlide(); else if (dx < -40) nextSlide(); });
      slides.addEventListener('pointerleave', ()=>{ isDown = false; });
      function start(){ timer = setInterval(nextSlide, 4500); }
      function stop(){ if (timer) clearInterval(timer); }
      function restart(){ stop(); start(); }
      slides.addEventListener('mouseenter', stop);
      slides.addEventListener('mouseleave', start);
      start();
    })();
  </script>
</body>
</html>
