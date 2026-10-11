---
permalink: /about/
title: "About"
layout: single
---

<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Benson Kipsang Kiprotich | Computer Security and Forensics</title>
<link href="https://fonts.googleapis.com/css2?family=Forum&display=swap" rel="stylesheet">
<style>
:root{--teal:#0F6B62;--deep:#0A3D3A;--gold:#FFD400;--orange:#E8603C;--blue:#2F6DB5;--ink:#13212A;--cream:#FBEBD5}
*{box-sizing:border-box}
body{margin:0;font-family:Arial,Helvetica,sans-serif;color:#fff;line-height:1.5;background:#2a1f1b}
h1,h2,h3,p{margin:0}
section{padding:40px 20px}
.wrap{max-width:900px;margin:0 auto}

/* Slide 1 */
.hero{background:#2a1f1b;padding:0}
.hero .wrap{display:grid;grid-template-columns:70px 260px 1fr;gap:0;align-items:start;max-width:1000px}
.strip{background:var(--cream);color:#2a1f1b;writing-mode:vertical-rl;transform:rotate(180deg);text-align:left;padding:20px 0;font-size:1.3rem;letter-spacing:1px;height:300px;display:flex;align-items:center;justify-content:flex-start}
.hero img{width:260px;height:346px;object-fit:cover;display:block}
.hero h1{font-family:Forum,Georgia,serif;font-weight:400;font-size:clamp(2.6rem,7vw,4.8rem);line-height:1.05;text-align:right;padding:20px 20px 0}
.hero .text{grid-column:1/-1;padding:24px 20px 50px;text-align:right}
.hero .text h2{font-weight:400;font-size:1.1rem;margin-bottom:12px}
.hero .text p{margin-bottom:14px;max-width:700px;margin-left:auto}
.hero .text .find{margin-top:20px;color:var(--cream)}

/* Slide 2 */
.s2{background:radial-gradient(circle at 70% 60%,#0b6e7a 0,#08222b 45%,#050b10 100%);padding:0}
.head{background:linear-gradient(90deg,var(--deep),var(--teal));padding:30px 20px 18px;border-bottom:4px solid #e0a53a}
.head h1{font-family:Georgia,serif;font-size:2.2rem}
.head .role{color:#f0b429;font-style:italic;font-weight:bold;margin:4px 0 14px}
.head p{font-size:.9rem;margin-bottom:4px}
.stats{display:grid;grid-template-columns:repeat(4,1fr);border:1px solid #fff;margin:22px 0}
.stats div{padding:10px 12px;font-size:.78rem;border-right:1px solid #fff;border-top:3px solid}
.stats div:last-child{border-right:0}
.stats b{display:block;font-family:Georgia,serif;font-size:1.5rem}
.stats .a{border-top-color:#fff}.stats .b{border-top-color:var(--orange)}.stats .b b,.stats .b span{color:var(--orange)}
.stats .c{border-top-color:var(--blue)}.stats .c b,.stats .c span{color:#4a86d4}
.stats .d{border-top-color:var(--gold)}.stats .d b{color:var(--gold)}
.sec{font-family:Georgia,serif;font-size:1.35rem;color:var(--gold);margin:30px 0 12px;display:flex;align-items:center;gap:12px}
.sec:before{content:"";width:12px;height:22px;background:var(--orange);display:inline-block}
.sec:after{content:"";flex:1;height:1px;background:rgba(255,255,255,.6)}
.edu h3{color:#2fd35b;font-size:1rem}
.edu .meta{color:#2fd35b;font-style:italic;font-size:.8rem;margin:2px 0 6px}
.edu p{color:#2fd35b;font-size:.92rem}
.card{background:#fff;color:var(--ink);border-left:5px solid;padding:14px 18px;margin-bottom:10px;border-radius:2px}
.card h3{font-size:1rem}
.card .tech{font-style:italic;color:#0F6B62;font-size:.8rem;margin:2px 0 6px}
.card p{font-size:.9rem}
.c1{background:#e8f1ee;border-color:var(--teal)}.c2{background:#e6eef8;border-color:var(--blue)}
.c3{background:#fbe5df;border-color:var(--orange)}.c4{background:#fff1d6;border-color:#e0a53a}

/* Slide 3 */
.s3{background:#3a1d17;padding:0 0 40px}
.s3 .bar{background:var(--deep);border-bottom:3px solid #e0a53a;padding:10px 20px;font-family:Georgia,serif;font-weight:bold;font-size:.85rem}
.s3 .wrap{padding:20px}
.s3 .sec:before{background:var(--teal)}
.s3 .sec.o:before{background:var(--orange)}.s3 .sec.b:before{background:var(--blue)}
ul.bul{list-style:none;padding:0;margin:0}
ul.bul li{font-size:.92rem;margin-bottom:6px;padding-left:20px;position:relative}
ul.bul li:before{content:"";position:absolute;left:0;top:.5em;width:8px;height:8px;background:var(--teal)}
.grp{color:var(--gold);font-weight:bold;font-size:.85rem;margin:12px 0 6px}
.pills{display:flex;flex-wrap:wrap;gap:8px}
.pill{border-radius:999px;padding:4px 16px;font-size:.78rem;font-weight:bold;color:#fff}
.t{background:var(--teal)}.bl{background:var(--blue)}.or{background:var(--orange)}
.cert{background:#f7e3be;color:var(--ink)}
.contact{background:var(--deep);border-left:4px solid #e0a53a;padding:18px 22px;margin-top:30px;font-size:1.05rem}
.contact a{color:#8fc7ff}
footer{font-size:.75rem;color:#9a8f89;padding:16px 20px;display:flex;justify-content:space-between;max-width:900px;margin:0 auto}

@media(max-width:700px){
 .hero .wrap{grid-template-columns:50px 1fr}
 .hero img{width:100%;height:auto;max-height:340px}
 .hero h1{grid-column:1/-1;text-align:center}
 .strip{height:auto;min-height:200px}
 .stats{grid-template-columns:1fr 1fr}
 .stats div:nth-child(2){border-right:0}
 .stats div:nth-child(-n+2){border-bottom:1px solid #fff}
}
</style>
</head>
<body>

<section class="hero">
 <div class="wrap">
  <div class="strip">believe in yourself</div>
  <img src="assets/images/benson-profile.jpg" alt="Benson Kipsang Kiprotich">
  <h1>Get To Know Me</h1>
  <div class="text">
   <h2>My Profile</h2>
   <p>Hello I am a Benson , Cybersecurity analyst, a developer and creative director. I am in my final-year Computer Security and Forensics student at Kabarak University in Nakuru. My work sits where cybersecurity, digital forensics, networking and applied machine learning meet. I learn by building: I run my own ethical hacking lab, compete in capture-the-flag challenges, and ship working software, from a fraud detection system for Kenyan health insurance to security tools that use AI to triage scan results.</p>
   <p>Outside the lab I run a water supply business, Smart Water Refill, and serve in my church's youth ministry. Both keep me practical and accountable to real people.</p>
   <p class="find">Find at web bensonsang128.io,</p>
  </div>
 </div>
</section>

<section class="s2">
 <div class="head"><div class="wrap">
  <h1>Benson Kipsang Kiprotich</h1>
  <div class="role">Computer Security and Forensics enthusiast</div>
  <p>Building tools that find fraud and weaknesses before attackers do</p>
  <p>Known as Bens &nbsp;|&nbsp; Nakuru, Kenya &nbsp;|&nbsp; Kabarak University</p>
 </div></div>

 <div class="wrap" style="padding:0 20px 40px">
  <div class="stats">
   <div class="a"><b>Final year</b>BSc Computer Security and Forensics</div>
   <div class="b"><b>6</b><span>professional certifications</span></div>
   <div class="c"><b>2</b><span>CTF platforms competed on</span></div>
   <div class="d"><b>2</b>ML classifiers in HIFDS</div>
  </div>

  <h2 class="sec">Education</h2>
  <div class="edu">
   <h3>BSc Computer Security and Forensics</h3>
   <div class="meta">Kabarak University, Nakuru, Kenya | Final year | Supervisor: Mr. Irvin Kilot</div>
   <p>Coursework and practice cover cybersecurity, digital forensics, networking fundamentals (cabling standards, remote access with PuTTY and RDP, DNS) and machine learning.</p>
  </div>

  <h2 class="sec">Featured projects</h2>
  <div class="card c1"><h3>Health Insurance Fraud Detection System (HIFDS) - final-year project</h3><div class="tech">Python, Flask, MongoDB, Naive Bayes, SVM</div><p>Built a web application that flags suspicious health insurance claims, designed for the Kenyan context (NHIF/SHA). Trained and compared Naive Bayes and Support Vector Machine classifiers and reported performance with standard ML metrics. Wrote the research methodology using Agile/Scrum across four sprints, and handled the full codebase, references and deployment.</p></div>
  <div class="card c2"><h3>AI Vulnerability Triage tool</h3><div class="tech">Flask, nmap, Nikto, Anthropic API</div><p>Parses nmap (XML and plain text) and Nikto output, then uses the Anthropic API to assess severity so findings can be prioritised faster.</p></div>
  <div class="card c3"><h3>Ethical hacking lab (hacklab)</h3><div class="tech">VirtualBox, Kali Linux, Metasploitable2, Mr. Robot CTF machine</div><p>Set up an isolated internal network for safe practice in scanning, exploitation and reporting.</p></div>
  <div class="card c4"><h3>Browser-based security audit checklist</h3><p>Created an interactive audit checklist tool with Claude API integration to guide assessments.</p></div>
 </div>
</section>

<section class="s3">
 <div class="bar">Benson Kipsang Kiprotich</div>
 <div class="wrap">
  <div class="card c1"><h3>NEMA license verification for The Salvation Army Kenya</h3><p>Generated a QR code and deployed a styled verification page through GitHub and Render so a license can be checked on the spot.</p></div>
  <div class="card c2"><h3>Smart Water Refill website</h3><p>Designed, built and hosted the business website, and wrote a formal deployment report. Explored domain registration and WordPress hosting options.</p></div>

  <h2 class="sec">Security practice and competitions</h2>
  <ul class="bul">
   <li>Competed in picoCTF and CyLabs Academy CTF challenges: command injection, SSH file combination, session hijacking, SMB file sharing, byte manipulation and Git server exploitation.</li>
   <li>Work comfortably in Kali Linux, using VS Code as my main editor.</li>
   <li>Engaged with ISO 27001 and NIST frameworks.</li>
  </ul>

  <h2 class="sec o">Technical skills</h2>
  <div class="grp">Forensics and security</div>
  <div class="pills"><span class="pill t">Autopsy</span><span class="pill t">Icat</span><span class="pill t">Binwalk</span><span class="pill t">Nmap</span><span class="pill t">Burp Suite</span><span class="pill t">Wireshark</span><span class="pill t">Metasploit lab work</span></div>
  <div class="grp">Development</div>
  <div class="pills"><span class="pill bl">Python</span><span class="pill bl">Flask</span><span class="pill bl">MongoDB</span><span class="pill bl">Machine learning</span><span class="pill bl">Render deployment</span><span class="pill bl">Naive Bayes</span><span class="pill bl">SVM</span><span class="pill bl">Git and GitHub</span></div>
  <div class="grp">Networking</div>
  <div class="pills"><span class="pill or">Cabling and T568A/B</span><span class="pill or">SSH and PuTTY</span><span class="pill or">RDP</span><span class="pill or">DNS</span></div>

  <h2 class="sec o">Certifications</h2>
  <div class="pills"><span class="pill cert">CyberShujaa / Serianu</span><span class="pill cert">EC-Council: MITRE ATT&amp;CK</span><span class="pill cert">Internet Society: Cybersecurity Governance</span><span class="pill cert">Cisco: Ethical Hacker</span><span class="pill cert">IBM: Cybersecurity Fundamentals</span><span class="pill cert">Atingi: Digital Safety</span></div>

  <h2 class="sec b">Languages and other work</h2>
  <ul class="bul">
   <li>Worked on Swahili language and linguistics in an AI training context, and translated academic templates into Kiswahili.</li>
   <li>Interested in online business and content creation, including AI chatbot services and video scripting.</li>
  </ul>

  <h2 class="sec">Leadership and enterprise</h2>
  <ul class="bul">
   <li><b>Founder and operator, Smart Water Refill:</b> a water supply business serving customers in Nakuru.</li>
   <li><b>Church youth ministry:</b> active involvement in youth ministry.</li>
  </ul>

  <div class="contact">
   <div>Contact me at : phone number 0112491667</div>
   <div>email : <a href="mailto:bensonsng128@gmail.com">bensonsng128@gmail.com</a></div>
   <div>linkedin : <a href="https://linkedin.com/bensonsang">linkedin.com/bensonsang</a></div>
   <div>twitter : <a href="https://twitter.com/bensonsang">twitter.com/bensonsang</a></div>
  </div>
 </div>
 <footer><span>Profile | Computer Security and Forensics enthusiast</span></footer>
</section>

</body>
</html>