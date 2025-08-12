<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Saraswati Vidya Mandir, Damanjodi — Batch 2024-26</title>
  <style>
    :root{
      --accent:#1e6f8a;
      --accent-2:#f2a541;
      --muted:#6b7280;
      --bg:#f7fafc;
      --card:#ffffff;
      --glass: rgba(255,255,255,0.6);
      font-family: Inter, "Segoe UI", Roboto, Arial, sans-serif;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      background:linear-gradient(180deg, #eef7fb 0%, var(--bg) 100%);
      color:#0f172a;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
    }
    header{
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap:20px;
      padding:20px;
      max-width:1200px;
      margin:18px auto;
    }
    .brand{
      display:flex;
      gap:14px;
      align-items:center;
    }
    .logo{
      width:72px;
      height:72px;
      border-radius:10px;
      background:linear-gradient(135deg,var(--accent),var(--accent-2));
      display:flex;
      align-items:center;
      justify-content:center;
      color: #fff;
      font-weight:700;
      font-size:20px;
      box-shadow:0 6px 18px rgba(30,111,138,0.14);
    }
    .title{
      line-height:1;
    }
    .title h1{margin:0;font-size:18px}
    .title p{margin:0;font-size:13px;color:var(--muted)}
    nav a{
      margin-left:14px;
      text-decoration:none;
      color:var(--muted);
      font-weight:600;
      font-size:14px;
    }
    main{
      max-width:1200px;
      margin:0 auto 60px;
      padding:0 20px;
    }
    .hero{
      background:linear-gradient(90deg, rgba(30,111,138,0.06), rgba(242,165,65,0.03));
      border-radius:14px;
      padding:22px;
      display:flex;
      gap:20px;
      align-items:center;
      box-shadow:0 6px 20px rgba(8,15,25,0.03);
    }
    .hero-left{
      flex:1;
    }
    .hero-right{
      width:220px;
      text-align:center;
    }
    .badge{
      display:inline-block;
      background:var(--accent);
      color:#fff;
      padding:6px 10px;
      border-radius:999px;
      font-weight:700;
      font-size:13px;
    }
    .grid{
      margin-top:18px;
      display:grid;
      grid-template-columns: 1.8fr 1fr;
      gap:18px;
    }
    .card{
      background:var(--card);
      border-radius:12px;
      padding:16px;
      box-shadow:0 8px 18px rgba(15,23,42,0.04);
    }
    .section-title{
      display:flex;
      justify-content:space-between;
      align-items:center;
      margin-bottom:10px;
    }
    .section-title h3{margin:0;font-size:16px}
    .small{font-size:13px;color:var(--muted)}
    /* Memories gallery */
    .mem-grid{
      display:grid;
      grid-template-columns: repeat(3,1fr);
      gap:8px;
    }
    .mem{
      height:90px;
      border-radius:8px;
      background:linear-gradient(135deg,#fff 0%, #f3f7fa 100%);
      display:flex;
      align-items:center;
      justify-content:center;
      color:var(--muted);
      font-weight:700;
      font-size:12px;
      overflow:hidden;
    }
    /* Right column blocks */
    .list{display:flex;flex-direction:column;gap:10px}
    .list-item{
      display:flex;
      justify-content:space-between;
      align-items:center;
      padding:10px;
      border-radius:10px;
      background:linear-gradient(180deg,#fff,#fbfdff);
      border:1px solid rgba(15,23,42,0.03);
      font-weight:600;
    }
    .pill{background:var(--accent-2);color:#fff;padding:6px 8px;border-radius:999px;font-size:12px}
    /* Tabs for fun groups */
    .tabs{display:flex;gap:8px;flex-wrap:wrap}
    .tab{padding:8px 12px;border-radius:10px;background:var(--glass);cursor:pointer;font-weight:700}
    .tab.active{background:var(--accent);color:#fff}
    /* footer */
    footer{max-width:1200px;margin:30px auto;padding:0 20px 60px;color:var(--muted);font-size:13px}
    /* responsive */
    @media (max-width:880px){
      .grid{grid-template-columns:1fr; }
      .hero{flex-direction:column;align-items:flex-start}
      .hero-right{width:100%}
      .mem-grid{grid-template-columns:repeat(2,1fr)}
    }
  </style>
</head>
<body>
  <header>
    <div class="brand">
      <div class="logo">SVM</div>
      <div class="title">
        <h1>Saraswati Vidya Mandir, Damanjodi</h1>
        <p>Batch 2024–26 • Our Collected Memories</p>
      </div>
    </div>
    <nav>
      <a href="#memories">Memories</a>
      <a href="#topers">Topers</a>
      <a href="#backbenchers">Backbenchers</a>
      <a href="#members">Members</a>
    </nav>
  </header>

  <main>
    <section class="hero card" aria-label="Hero">
      <div class="hero-left">
        <span class="badge">Batch 2024‑26</span>
        <h2 style="margin:10px 0 6px">Our Collected Memories — Classmates, Moments, Mischief</h2>
        <p class="small">A lively archive for Saraswati Vidya Mandir alumni — photos, lists, events and the friendly rivalries that shape our stories.</p>
        <div style="margin-top:12px; display:flex; gap:8px; flex-wrap:wrap">
          <button onclick="scrollToId('memories')" style="padding:10px 14px;border-radius:10px;border:0;background:var(--accent);color:#fff;cursor:pointer;font-weight:700">View Memories</button>
          <button onclick="scrollToId('topers')" style="padding:10px 14px;border-radius:10px;border:1px solid rgba(15,23,42,0.06);background:transparent;cursor:pointer">Topers & Lists</button>
        </div>
      </div>
      <div class="hero-right">
        <div style="font-weight:800;font-size:20px">Batch Highlights</div>
        <div class="small" style="margin-top:8px">Members: <strong>50</strong></div>
        <div class="small">Events: <strong>5</strong></div>
        <div style="margin-top:12px"><span class="pill">Theatre • Music • Games</span></div>
      </div>
    </section>

    <div class="grid" style="margin-top:18px">
      <div>
        <section id="memories" class="card" aria-label="Memories">
          <div class="section-title">
            <h3>Our Collected Memories</h3>
            <div class="small">image, quotes & short clips</div>
          </div>
          <div class="mem-grid" id="memGrid">  
	    <img src="E:\HIGH QUALITY PHOTO/guitar.jpeg"HEIGHT="200"WIDTH="300">   
            <div class="mem">Photo 3</div>
            <div class="mem">Photo 4</div>
            <div class="mem">Photo 5</div>
            <div class="mem">Photo 6</div>
	    <div class="mem">photo 1</div>
            <div class="mem">Photo 2</div>
            <div class="mem">Photo 3</div>
            <div class="mem">Photo 4</div>
            <div class="mem">Photo 5</div>
            <div class="mem">Photo 6</div>
          </div>

          <div style="margin-top:12px; display:flex; gap:8px;">
            <input id="upload" type="file" accept="image/*" style="display:none" />
            <button onclick="document.getElementById('upload').click()" style="padding:8px 12px;border-radius:10px;border:0;background:var(--accent);color:#fff;cursor:pointer">Add Memory</button>
            <button onclick="shuffleMemories()" style="padding:8px 12px;border-radius:10px;border:1px solid rgba(15,23,42,0.06);background:transparent;cursor:pointer">Shuffle</button>
          </div>
        </section>

        <section id="topers" class="card" style="margin-top:14px">
          <div class="section-title">
            <h3>Topper List</h3>
            <div class="small">Academic achievers — batch 2024‑26</div>
          </div>
          <ol style="margin:0;padding-left:18px">
            <li><strong>A.</strong> AKHIL — SCIENCE — Score</li>
            <li><strong>B.</strong> SILU — SCIENCE — Score</li>
            <li><strong>C.</strong> RAMA — SCIENCE — Score</li>
          </ol>
          <p class="small" style="margin-top:10px">Want to edit the list? Click <span style="font-weight:700;color:var(--accent);cursor:pointer" onclick="editTopers()">here</span>.</p>
        </section>

        <section id="theatre" class="card" style="margin-top:14px">
          <div class="section-title">
            <h3>Theatre </h3>
            <div class="small">Upcoming plays & sign-ups</div>
          </div>
          <div style="display:flex;gap:12px;flex-wrap:wrap">
            <div style="flex:1;min-width:200px">
              <div style="font-weight:800">Annual Drama Night</div>
              <div class="small">Date: 10 Oct 2025 • Venue: School Auditorium</div>
              <div style="margin-top:8px"><button class="pill" onclick="alert('Sign-up feature demo')">Sign Up</button></div>
            </div>
            <div style="flex:1;min-width:200px">
              <div style="font-weight:800">Short Skits Evening</div>
              <div class="small">Date: 20 Sep 2025 • Rehearsals on weekends</div>
            </div>
          </div>
        </section>
      </div>

      <aside>
        <section class="card">
          <div class="section-title">
            <h3>Backbenchers</h3>
            <div class="small">The legends at the back row</div>
          </div>
          <div class="list">
            <div class="list-item"><span>Rohit</span><span class="small">Mischief King</span></div>
            <div class="list-item"><span>Asha</span><span class="small">Jokes</span></div>
            <div class="list-item"><span>Vikram</span><span class="small">Pranks</span></div>
          </div>
        </section>

        <section class="card" style="margin-top:12px">
          <div class="section-title">
            <h3>Phone User</h3>
            <div class="small">Contact points / admins</div>
          </div>
          <div class="list">
            <div class="list-item"><span>Batch Rep</span><span class="small">+91 </span></div>
            <div class="list-item"><span>Alumni Co‑ord</span><span class="small">+91 97xxxxxx</span></div>
          </div>
        </section>

        <section class="card" style="margin-top:12px">
          <div class="section-title">
            <h3>Musicians</h3>
            <div class="small">Band & solo performers</div>
          </div>
          <div class="list">
            <div class="list-item"><span>keyboard — BHARAT & PRUTHVI</span><span class="small">Lead</span></div>
            <div class="list-item"><span>CONGO — GLADSON</span><span class="small">Percussion</span></div>
            <div class="list-item"><span>Vocals — ALOK</span><span class="small">Side singer</span></div>
	    <div class="list-item"><span>Vocals — PRUTHVI</span><span class="small">Lead Singer</span></div>
          </div>
        </section>

        <section class="card" style="margin-top:12px">
          <div class="section-title">
            <h3>Gang War</h3>
            <div class="small">Friendly rival groups & competitions</div>
          </div>
          <div class="small" style="margin-bottom:8px">Pick a side — sports day, tug‑of‑war & classroom banter</div>
          <div class="tabs" id="gangTabs">
            <div class="tab active" onclick="setGang('Red Lions')">Red Lions</div>
            <div class="tab" onclick="setGang('Blue Hawks')">Blue Hawks</div>
            <div class="tab" onclick="setGang('Green Tigers')">Green Tigers</div>
          </div>
          <div id="gangDesc" style="margin-top:10px;font-weight:700">Red Lions — Known for spirit & football mastery.</div>
        </section>
      </aside>
    </div>
  </main>

  <footer>
    <div style="max-width:1200px;margin:0 auto;display:flex;justify-content:space-between;align-items:center">
      <div>© Saraswati Vidya Mandir, Damanjodi — Batch 2024‑26</div>
      <div class="small">Designed with ❤ for the memories</div>
    </div>
  </footer>

  <script>
    function scrollToId(id){
      document.getElementById(id).scrollIntoView({behavior:'smooth', block:'start'});
    }
    function shuffleMemories(){
      const grid = document.getElementById('memGrid');
      for(let i=grid.children.length; i>=0; i--){
        grid.appendChild(grid.children[Math.random()*i|0]);
      }
    }
    function editTopers(){
      const name = prompt('Edit Topper list entry (sample): Enter "1. Name — Stream — Score"');
      if(name){ alert('Demo saved: ' + name); }
    }
    function setGang(txt){
      document.querySelectorAll('.tab').forEach(t=>t.classList.remove('active'));
      event.target.classList.add('active');
      document.getElementById('gangDesc').innerText = txt + ' — Friendly rivalry; prepared for sports day!';
    }
    // basic keyboard accessibility: focus first mem on load
    window.addEventListener('load', ()=> {
      const first = document.querySelector('.mem');
      if(first) first.tabIndex = 0;
    });
  </script>
</body>
</html>
