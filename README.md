<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Divya Sai Prathyusha — Profile</title>
<style>
  :root{
    --bg:#0a0e17;
    --card:#111827;
    --card-border:#1e293b;
    --chip:#141c2e;
    --chip-border:#26324a;
    --cyan:#22d3ee;
    --muted:#94a3b8;
    --purple:#8b5cf6;
  }
  *{box-sizing:border-box;}
  body{
    margin:0;
    background:var(--bg);
    color:#e5e7eb;
    font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;
    display:flex;
    justify-content:center;
    padding:32px 16px 64px;
  }
  .page{width:100%;max-width:560px;}

  /* ---------- New hero / banner ---------- */
  .hero{
    position:relative;
    border-radius:16px;
    overflow:hidden;
    padding:44px 30px 36px;
    text-align:center;
    background:
      radial-gradient(circle at 20% 20%, rgba(139,92,246,0.25), transparent 45%),
      radial-gradient(circle at 85% 75%, rgba(34,211,238,0.18), transparent 50%),
      linear-gradient(160deg,#0d1424 0%,#151933 55%,#1b1340 100%);
    border:1px solid #232a44;
  }
  .hero::before{
    content:"";
    position:absolute; inset:0;
    background-image:
      linear-gradient(rgba(255,255,255,0.035) 1px, transparent 1px),
      linear-gradient(90deg, rgba(255,255,255,0.035) 1px, transparent 1px);
    background-size:26px 26px;
    mask-image: radial-gradient(ellipse at center, black 40%, transparent 80%);
    pointer-events:none;
  }
  .hero-avatar{
    width:74px;height:74px;border-radius:50%;
    margin:0 auto 16px;
    border:2px solid rgba(139,92,246,0.6);
    position:relative; z-index:1;
    background:radial-gradient(circle at 30% 30%, #93c5fd, #3b82f6 70%);
  }
  .hero-eyebrow{
    position:relative; z-index:1;
    font-size:12px; letter-spacing:2.5px; text-transform:uppercase;
    color:var(--cyan); font-weight:600; margin-bottom:10px;
  }
  .hero h1{
    position:relative; z-index:1;
    margin:0 0 10px;
    font-size:28px; font-weight:700; color:#f8fafc;
    letter-spacing:-0.3px;
  }
  .hero p{
    position:relative; z-index:1;
    margin:0; color:var(--muted); font-size:14.5px;
  }

  /* Buttons */
  .buttons{display:flex;justify-content:center;gap:12px;margin:22px 0 34px;}
  .btn{
    display:flex;align-items:center;gap:8px;
    padding:10px 20px;border-radius:8px;
    font-size:14px;font-weight:600;text-decoration:none;color:#fff;
  }
  .btn-github{background:#1f2430;border:1px solid #2c3446;}
  .btn-gmail{background:#d93025;}

  /* Section headers */
  h2.section{
    display:flex;align-items:center;gap:8px;
    font-size:17px;color:#f8fafc;margin:0 0 16px;
  }
  h2.section::before{
    content:"";width:8px;height:8px;border-radius:50%;
    background:var(--cyan);display:inline-block;
  }

  /* Tech chips */
  .chips{display:flex;flex-wrap:wrap;gap:10px;margin-bottom:36px;}
  .chip{
    display:flex;align-items:center;gap:7px;
    background:var(--chip);border:1px solid var(--chip-border);
    padding:8px 14px;border-radius:8px;font-size:13px;color:#e2e8f0;
  }
  .dot{width:9px;height:9px;border-radius:2px;display:inline-block;}

  /* Stats card */
  .graph-card{
    background:var(--card);border:1px solid var(--card-border);
    border-radius:12px;padding:18px 18px 10px;margin-bottom:14px;
  }
  .graph-label{color:var(--muted);font-size:13px;margin-bottom:2px;}
  .graph-sublabel{color:#5b6b85;font-size:11.5px;margin-bottom:10px;}
  .axis-label{fill:#5b6b85;font-size:9px;font-family:inherit;}

  .stat-row{display:flex;gap:12px;margin-bottom:36px;}
  .stat-card{
    flex:1;background:var(--card);border:1px solid var(--card-border);
    border-radius:12px;padding:16px 14px;
  }
  .stat-num{font-size:22px;font-weight:700;color:#f8fafc;}
  .stat-label{font-size:12px;color:var(--muted);margin-top:4px;}

  /* About */
  .about{display:flex;gap:18px;align-items:flex-start;margin-bottom:40px;}
  .avatar{
    width:64px;height:64px;border-radius:50%;flex-shrink:0;
    background:radial-gradient(circle at 30% 30%, #93c5fd, #3b82f6 70%);
  }
  .about p{margin:0;color:#cbd5e1;font-size:14.5px;line-height:1.7;}
  .about b{color:#f8fafc;}

  /* Projects */
  .project-card{
    background:var(--card);border:1px solid var(--card-border);
    border-radius:12px;padding:16px 16px;margin-bottom:12px;
    display:flex;gap:12px;align-items:flex-start;
  }
  .icon-sq{
    width:30px;height:30px;border-radius:7px;flex-shrink:0;
    display:flex;align-items:center;justify-content:center;font-size:15px;
  }
  .project-card h3{margin:0 0 6px;font-size:14.5px;color:#f8fafc;}
  .project-card p{margin:0;font-size:13.5px;color:var(--muted);line-height:1.55;}

  .divider{height:1px;background:var(--card-border);margin:32px 0 24px;}
  .quote{text-align:center;font-style:italic;color:#cbd5e1;font-size:14.5px;margin-bottom:18px;line-height:1.6;}
  .footer-line{text-align:center;color:var(--cyan);font-size:14px;font-weight:600;}
</style>
</head>
<body>
<div class="page">

  <div class="hero">
    <div class="hero-avatar"></div>
    <div class="hero-eyebrow">Full-Stack Developer · API Developer · AI Engineer</div>
    <h1>Divya Sai Prathyusha</h1>
    <p>Building multi-agent systems &amp; LLM-powered applications</p>
  </div>

  <div class="buttons">
    <a class="btn btn-github" href="https://github.com/prathuysha35905-tech" target="_blank" rel="noopener">GitHub</a>
    <a class="btn btn-gmail" href="mailto:prathuysha35905@gmail.com" target="_blank" rel="noopener">Gmail</a>
  </div>
  <div style="text-align:center;margin:-24px 0 34px;color:#5b6b85;font-size:12.5px;">prathuysha35905@gmail.com</div>

  <h2 class="section">Technologies</h2>
  <div class="chips">
    <div class="chip"><span class="dot" style="background:#9ca3af"></span>C</div>
    <div class="chip"><span class="dot" style="background:#f89820"></span>Java</div>
    <div class="chip"><span class="dot" style="background:#3776ab"></span>Python</div>
    <div class="chip"><span class="dot" style="background:#e34f26"></span>HTML</div>
    <div class="chip"><span class="dot" style="background:#2965f1"></span>CSS</div>
    <div class="chip"><span class="dot" style="background:#f0db4f"></span>JavaScript</div>
    <div class="chip"><span class="dot" style="background:#3178c6"></span>TypeScript</div>
    <div class="chip"><span class="dot" style="background:#61dafb"></span>React</div>
    <div class="chip"><span class="dot" style="background:#05998b"></span>FastAPI</div>
    <div class="chip"><span class="dot" style="background:#38bdf8"></span>Tailwind</div>
    <div class="chip"><span class="dot" style="background:#7c3aed"></span>Bootstrap</div>
    <div class="chip"><span class="dot" style="background:#f05033"></span>Git</div>
    <div class="chip"><span class="dot" style="background:#9ca3af"></span>GitHub</div>
    <div class="chip"><span class="dot" style="background:#2f7bd6"></span>VS Code</div>
  </div>

  <h2 class="section">Statistics</h2>
  <div class="graph-card">
    <div class="graph-label">Weekly Commit Activity</div>
    <div class="graph-sublabel">Last 24 weeks</div>
    <svg viewBox="0 0 500 170" width="100%" height="150" preserveAspectRatio="none">
      <defs>
        <linearGradient id="barGrad" x1="0" y1="0" x2="0" y2="1">
          <stop offset="0%" stop-color="#a78bfa"/>
          <stop offset="100%" stop-color="#6d28d9"/>
        </linearGradient>
      </defs>
      <line x1="0" y1="20" x2="500" y2="20" stroke="#1e293b" stroke-width="1"/>
      <line x1="0" y1="65" x2="500" y2="65" stroke="#1e293b" stroke-width="1"/>
      <line x1="0" y1="110" x2="500" y2="110" stroke="#1e293b" stroke-width="1"/>
      <g id="bars"></g>
      <text x="0" y="165" class="axis-label">Apr</text>
      <text x="120" y="165" class="axis-label">Jun</text>
      <text x="240" y="165" class="axis-label">Aug</text>
      <text x="360" y="165" class="axis-label">Oct</text>
      <text x="475" y="165" class="axis-label">Dec</text>
    </svg>
  </div>

  <div class="stat-row">
    <div class="stat-card"><div class="stat-num">8.75</div><div class="stat-label">CGPA / 10</div></div>
    <div class="stat-card"><div class="stat-num">3rd</div><div class="stat-label">Year · Class of 2028</div></div>
    <div class="stat-card"><div class="stat-num">3</div><div class="stat-label">Featured Projects</div></div>
  </div>

  <h2 class="section">About Me</h2>
  <div class="about">
    <div class="avatar"></div>
    <p>Hello! I'm <b>Divya</b>, a Full-Stack Developer and AI Engineer pursuing a B.Tech in Information Technology at Andhra University. My focus areas include <b>multi-agent systems</b>, <b>LLM orchestration</b>, and <b>REST API design &amp; integration</b> — from authentication and token management to connecting AI services with frontend and backend layers — alongside hands-on exploration of model inference and agentic workflows, while continuously strengthening my data structures and algorithms foundation in Java.</p>
  </div>

  <h2 class="section">Featured Projects</h2>

  <div class="project-card">
    <div class="icon-sq" style="background:#4c1d3d;">🔀</div>
    <div>
      <h3>Cinq — Intelligent Multi-Agent Router</h3>
      <p>An AI orchestration layer that analyzes incoming requests and delegates them to specialized agents. Built with a modular architecture and prompt-engineered logic for request classification and routing.</p>
    </div>
  </div>

  <div class="project-card">
    <div class="icon-sq" style="background:#3b2159;">🎬</div>
    <div>
      <h3>Luki — AI Movie Recommender</h3>
      <p>An end-to-end recommendation engine that turns movie data and user preferences into relevant, personalized suggestions through a connected frontend and backend.</p>
    </div>
  </div>

  <div class="project-card">
    <div class="icon-sq" style="background:#123a2a;">✅</div>
    <div>
      <h3>Cortex — AI To-Do Assistant</h3>
      <p>A full-stack TypeScript application with token-based authentication, protected routes, and REST APIs powering AI-assisted task management.</p>
    </div>
  </div>

  <div class="divider"></div>

  <div class="quote">"Going deeper into model inference and agentic workflows — one commit at a time."</div>
  <div class="footer-line">Looking for an SDE / AI Engineering internship</div>

</div>

<script>
  // Deterministic, organic-looking bar heights (not a smooth sine wave)
  const values = [8,14,6,20,26,15,32,22,38,45,30,52,60,40,55,48,62,58,44,50,65,36,28,18];
  const svg = document.getElementById('bars');
  const n = values.length;
  const gap = 4;
  const barW = (500 / n) - gap;
  const maxV = Math.max(...values);
  const floorY = 140;
  values.forEach((v, i) => {
    const h = (v / maxV) * 110;
    const x = i * (barW + gap);
    const y = floorY - h;
    const rect = document.createElementNS("http://www.w3.org/2000/svg", "rect");
    rect.setAttribute("x", x);
    rect.setAttribute("y", y);
    rect.setAttribute("width", barW);
    rect.setAttribute("height", h);
    rect.setAttribute("rx", "2");
    rect.setAttribute("fill", "url(#barGrad)");
    rect.setAttribute("opacity", (0.55 + (v/maxV)*0.45).toFixed(2));
    svg.appendChild(rect);
  });
</script>
</body>
</html>
