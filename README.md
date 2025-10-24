<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Your Name — Economics & Finance</title>
  <meta name="description" content="Research, teaching, and working papers." />
  <style>
    :root { --w: 860px; --fg:#111; --muted:#666; --link:#0a66c2; --bg:#fff; }
    * { box-sizing: border-box; }
    body { margin: 0; font: 16px/1.6 system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, sans-serif; color: var(--fg); background: var(--bg); }
    header, main, footer { width: min(100%, var(--w)); margin: 0 auto; padding: 24px; }
    nav { display:flex; gap:16px; flex-wrap: wrap; margin-top: 8px; }
    nav a { text-decoration: none; color: var(--link); font-weight: 500; }
    h1 { font-size: 1.9rem; margin: 0 0 6px; }
    h2 { font-size: 1.35rem; margin-top: 28px; }
    p { margin: 6px 0 12px; }
    .muted { color: var(--muted); }
    .pill { display:inline-block; padding:4px 10px; border:1px solid #ddd; border-radius:999px; font-size:0.9rem; color:#333; text-decoration:none; }
    .grid { display:grid; gap: 10px; }
    ul { padding-left: 18px; margin: 8px 0 0; }
    li + li { margin-top: 6px; }
    hr { border: none; border-top: 1px solid #eee; margin: 24px 0; }
    footer { color: var(--muted); font-size: 0.95rem; }
    @media (prefers-color-scheme: dark) {
      :root { --bg:#0b0b0c; --fg:#e8e8ea; --muted:#a0a0a9; --link:#61a8ff; }
      .pill { border-color: #333; color:#e8e8ea; }
      hr { border-top-color:#222; }
    }
  </style>
</head>
<body>
  <header>
    <h1>Jeremy Sutanto</h1>
    <p class="muted">Economics &amp; Finance — University of Leeds.</p>
    <nav>
      <a href="#jmp">Job Market Paper</a>
      <a href="#working-papers">Working Papers</a>
      <a href="#wip">Work in Progress</a>
      <a href="#teaching">Teaching</a>
      <a class="pill" href="assets/CV.pdf">Download CV</a>
      <!-- Put your CV later at /assets/CV.pdf -->
    </nav>
  </header>

  <main>
    <section id="intro">
      <p>
        I am a BSc (Economics &amp; Finance) graduate from the University of Leeds. I will join Warwick Business School for an MSc in Business &amp; Finance in Autumn 2025. 
        My interests include asset management, asset pricing, machine learning, and sustainable finance. 
        Contact: <a href="mailto:you@university.edu">you@university.edu</a>
      </p>
      <hr />
    </section>

    <section id="jmp">
      <h2>Job Market Paper</h2>
      <p><strong>Asset Demand Systems via Data Augmentation: Competition and Differentiation in Asset Management</strong> — 
        <a href="#">Paper</a> &middot; <a href="#">Slides</a></p>
      <p class="muted">
        Presentations: UC San Diego, Baruch College, Erasmus University Rotterdam (Econometric Institute), Warwick Business School, ESADE, University of Bonn, University of Glasgow, NEOMA, Hi! Paris Summer School, HEC Paris PhD Workshop, HEC Paris Brown Bag.
      </p>
      <p>
        <em>Abstract.</em> Many institutional investors hold concentrated portfolios, making individual demand estimation noisy.
        I propose a data augmentation technique that creates interpretable synthetic assets, acting as adaptive nonlinear shrinkage and improving out-of-sample performance. Using this, I construct an investor-differentiation measure and, exploiting the 2002 Morningstar ratings reform as a shock to competition for alpha, show funds escape competition by differentiating.
      </p>
    </section>

    <section id="working-papers">
      <h2>Working Papers</h2>
      <ul>
        <li><strong>Carbon Information, Pricing, and Bans. Evidence from a Field Experiment</strong> (with Coauthor Name). 
          <a href="#">Paper</a> · <a href="#">Media</a>
          <div class="muted">Awards: HEC Foundation Impact Award 2024 · Featured: Le Monde, Les Echos · Talks: NTHU-UNSW Symposium*, ESCP-UNEP*, TSE*, HKUST*, HEC Foundation Meeting, etc. *presented by co-author.</div>
        </li>
        <li><strong>Mutual Fund Holdings and Innovative Investment Strategies</strong> (solo). 
          <a href="#">Paper</a>
          <div class="muted">Talks: HEC Paris Brown Bag Seminar.</div>
        </li>
      </ul>
    </section>

    <section id="wip">
      <h2>Work in Progress</h2>
      <ul>
        <li><em>Escape Competition Effect in Hedge Fund Industry</em>.</li>
      </ul>
    </section>

    <section id="teaching">
      <h2>Teaching</h2>
      <ul>
        <li><strong>Data Analysis in Finance</strong> (MSc) — Tutorial Instructor, 2024, HEC Paris / École Polytechnique</li>
        <li><strong>Financial Economics</strong> (MIM) — Lecturer, 2021; Tutorial Instructor, 2020, HEC Paris</li>
      </ul>
    </section>
  </main>

  <footer>
    © <span id="y"></span> Your Name · Hosted on GitHub Pages
  </footer>
  <script>document.getElementById('y').textContent = new Date().getFullYear();</script>
</body>
</html>
