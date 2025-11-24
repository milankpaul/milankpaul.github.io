<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Milan Paul — Electronics Hardware Specialist</title>
<meta name="description" content="Milan Paul — electronics hardware specialist. Portfolio of PCB, schematic, and system design projects." />
<link rel="icon" href="data:;base64,iVBORw0KGgo=">
<style>
  :root{--accent:#2563eb;--muted:#6b7280;--bg:#ffffff;--card:#f8fafc}
  *{box-sizing:border-box}body{font-family:Inter,system-ui,Segoe UI,Arial,sans-serif;line-height:1.5;margin:0;background:var(--bg);color:#0f172a}
  .container{max-width:980px;margin:40px auto;padding:0 20px}
  header{display:flex;align-items:center;justify-content:space-between;gap:16px}
  h1{margin:0;font-size:28px}
  .subtitle{color:var(--muted);margin-top:6px}
  .hero{display:grid;grid-template-columns:1fr 320px;gap:24px;margin:28px 0;align-items:center}
  .card{background:var(--card);padding:18px;border-radius:12px;box-shadow:0 4px 12px rgba(15,23,42,.04)}
  .btn{display:inline-block;padding:10px 14px;border-radius:8px;background:var(--accent);color:white;text-decoration:none}
  .projects{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:16px;margin-top:18px}
  .proj img{width:100%;height:160px;object-fit:cover;border-radius:8px}
  footer{margin:40px 0;color:var(--muted);font-size:14px;text-align:center}
  @media(max-width:820px){.hero{grid-template-columns:1fr}}
</style>
</head>
<body>
  <div class="container">
    <header>
      <div>
        <h1>Milan Paul</h1>
        <div class="subtitle">Electronics Hardware Specialist — PCB design · System bring-up · Functional safety</div>
      </div>
      <nav>
        <a href="#projects">Work</a> · <a href="#about">About</a> · <a href="#contact">Contact</a>
      </nav>
    </header>

    <section class="hero">
      <div>
        <div class="card">
          <h2>Hi — I design reliable hardware that ships.</h2>
          <p class="subtitle">I build schematics, PCBs, and perform board bring-up for consumer & industrial systems. Select projects: mixed-signal power, BMS gate drivers, TFT backlight drivers.</p>
          <p><a class="btn" href="#projects">View work</a> <a style="margin-left:8px" href="/Milan_Paul_Resume.pdf">Resume (PDF)</a></p>
        </div>

        <section id="projects">
          <h3 style="margin-top:20px">Selected projects</h3>
          <div class="projects">
            <article class="card proj">
              <img src="https://via.placeholder.com/640x360.png?text=Project+1" alt="Project 1 screenshot">
              <h4>High-efficiency LED driver</h4>
              <p class="subtitle">Design, simulation, and validation of a boost converter for LED backlighting. Tools: LTspice, Altium.</p>
              <p><small>Role: Schematic & PCB · Year: 2024</small></p>
            </article>

            <article class="card proj">
              <img src="https://via.placeholder.com/640x360.png?text=Project+2" alt="Project 2 screenshot">
              <h4>BMS gate-driver circuit</h4>
              <p class="subtitle">Gate/driver design for Li-ion pack balancing and safety features. Included thermal and worst-case analysis.</p>
              <p><small>Role: Hardware lead · Year: 2023</small></p>
            </article>

            <!-- Add more project cards -->
          </div>
        </section>
      </div>

      <aside>
        <div class="card">
          <h4 id="about">About</h4>
          <p class="subtitle">Hardware specialist with experience at LTTS. Focus on robust design, test, and documentation for manufacturing.</p>
          <p><strong>Skills:</strong><br>PCB layout · Schematic capture · WCCA · Thermal analysis · Lab bring-up</p>
          <p style="margin-top:12px"><a class="btn" href="#contact">Contact me</a></p>
        </div>
      </aside>
    </section>

    <section id="contact" class="card" style="padding:20px;margin-top:12px">
      <h3>Contact</h3>
      <p>Email: <a href="mailto:milan.paul@example.com">milan.paul@example.com</a></p>
      <p>GitHub: <a href="https://github.com/yourhandle">yourhandle</a> · LinkedIn: <a href="https://linkedin.com/in/yourprofile">in/yourprofile</a></p>
      <p style="font-size:13px;color:var(--muted)">Tip: replace placeholder links and images with real ones. Host images in `/images/` folder and optimize for web.</p>
    </section>

    <footer>
      © <span id="year"></span> Milan Paul · Built with HTML & CSS
    </footer>
  </div>

<script>document.getElementById('year').textContent=new Date().getFullYear();</script>
</body>
</html>
