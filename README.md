<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Mohd Sageer — Resume</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg: #0f172a;       /* slate-900 */
      --card: #111827;     /* gray-900 */
      --text: #e5e7eb;     /* gray-200 */
      --muted: #9ca3af;    /* gray-400 */
      --accent: #60a5fa;   /* blue-400 */
      --line: #1f2937;     /* gray-800 */
    }
    * { box-sizing: border-box; }
    body {
      margin: 0; background: radial-gradient(1200px 600px at 20% -10%, #1f2937 0%, #0b1223 30%, var(--bg) 70%);
      color: var(--text); font-family: Inter, system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
    }
    .wrap {
      max-width: 980px; margin: 48px auto; padding: 0 20px;
    }
    .card {
      background: linear-gradient(180deg, rgba(255,255,255,0.05), rgba(255,255,255,0) 18%), var(--card);
      border: 1px solid var(--line);
      border-radius: 18px; box-shadow: 0 20px 60px rgba(0,0,0,0.35);
      overflow: hidden;
    }
    header {
      display: grid; grid-template-columns: 140px 1fr; gap: 24px; align-items: center;
      padding: 28px 28px 6px 28px; border-bottom: 1px solid var(--line);
    }
    .photo {
      width: 140px; height: 140px; border-radius: 16px; overflow: hidden; border: 1px solid var(--line);
      background: #0b1223;
    }
    .photo img { width: 100%; height: 100%; object-fit: cover; }
    .title h1 { margin: 0; font-size: 28px; font-weight: 700; letter-spacing: 0.2px; }
    .contact { margin-top: 8px; display: flex; flex-wrap: wrap; gap: 8px 16px; font-size: 14px; color: var(--muted);}
    .contact a { color: var(--text); text-decoration: none; border-bottom: 1px dashed transparent; }
    .contact a:hover { color: var(--accent); border-bottom-color: var(--accent); }
    main { padding: 18px 28px 28px 28px; display: grid; grid-template-columns: 1fr; gap: 18px; }
    section { padding-top: 6px; }
    h2 {
      margin: 0 0 10px; font-size: 16px; font-weight: 700; text-transform: uppercase; letter-spacing: 0.8px;
      color: var(--accent);
    }
    .two-col { display: grid; grid-template-columns: 1fr 1fr; gap: 18px; }
    .item { margin-bottom: 8px; }
    .item b { font-weight: 600; }
    ul { margin: 6px 0 0 18px; padding: 0; }
    li { margin: 6px 0; color: var(--text); }
    .pill-list { display: flex; flex-wrap: wrap; gap: 8px; }
    .pill {
      border: 1px solid var(--line); background: rgba(255,255,255,0.03);
      padding: 6px 10px; border-radius: 999px; font-size: 13px; color: var(--text);
    }
    footer {
      border-top: 1px solid var(--line); margin-top: 8px; padding: 14px 28px; font-size: 13px; color: var(--muted);
    }
    @media (max-width: 720px) {
      header { grid-template-columns: 96px 1fr; }
      .photo { width:96px; height:96px; border-radius:12px; }
      .two-col { grid-template-columns: 1fr; }
    }
  </style>
</head>
<body>
  <div class="wrap">
    <div class="card">
      <header>
        <div class="photo">
          <!-- Replace the src with your file name (ensure it’s in the same folder) -->
          <img src="1000126892.jpg" alt="Mohd Sageer portrait" />
        </div>
        <div class="title">
          <h1>Mohd Sageer</h1>
          <div class="contact">
            <span>📞 7780900423, 954177226</span>
            <span>📧 <a href="mailto:sageerqureshi143@gmail.com">sageerqureshi143@gmail.com</a></span>
            <span>🔗 <a href="https://www.linkedin.com/in/mohd-sageer-55355a215">LinkedIn</a></span>
            <span>📍 33°19'02.4"N 74°14'07.7"E</span>
          </div>
        </div>
      </header>

      <main>
        <section>
          <h2>Professional summary</h2>
          <p>Motivated Computer Science and Business Systems student with foundational knowledge in Information Technology. Skilled in application design, troubleshooting, and problem-solving. Passionate about exploring innovative ideas and contributing to impactful IT projects.</p>
        </section>

        <section class="two-col">
          <div>
            <h2>Education</h2>
            <div class="item"><b>B.Tech — CSBS</b>, Sairam Engineering College <br />Expected Graduation: 2027</div>
            <div class="item"><b>Coursework</b>: Information Technology, Computer Science Engineering (CSE)</div>
          </div>
          <div>
            <h2>Work experience</h2>
            <div class="item">
              <b>Software Engineer (Trainee)</b> — Infosys (Feb 2025 – Present) <br />
              - Managing Director, Data Analytics (student trainee role) <br />
              - Assisted in data-driven decision-making and analytics projects <br />
              - Supported technical troubleshooting and system improvements
            </div>
          </div>
        </section>

        <section class="two-col">
          <div>
            <h2>Skills</h2>
            <div class="pill-list">
              <span class="pill">Hardware Resetting</span>
              <span class="pill">System Assembly</span>
              <span class="pill">Application Design</span>
              <span class="pill">Web Development</span>
              <span class="pill">Error Identification</span>
              <span class="pill">Technical Glitch Resolution</span>
              <span class="pill">Problem-Solving</span>
              <span class="pill">Innovative Thinking</span>
            </div>
          </div>
          <div>
            <h2>Projects</h2>
            <ul>
              <li><b>Personal Webpage (11th Standard):</b> Designed and developed a functional webpage showcasing early interest in web technologies.</li>
            </ul>
          </div>
        </section>

        <section>
          <h2>Interests</h2>
          <ul>
            <li>Exploring new ideas and innovative solutions in technology</li>
            <li>Creative application design and problem-solving</li>
          </ul>
        </section>
      </main>

      <footer>
        Built with a clean, accessible layout for quick recruiter scanning.
      </footer>
    </div>
  </div>
</body>
</html>
