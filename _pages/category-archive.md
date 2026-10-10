---
title: "Portfolio"
permalink: /portfolio/
layout: single
author_profile: false
classes: "home-background portfolio-page wide"
---

<div class="home-intro">

<div class="home-hero">
<h1 class="home-title">My Portfolio</h1>
<p class="home-eyebrow">Projects <span aria-hidden="true">·</span> CTF Write-ups <span aria-hidden="true">·</span> Labs <span aria-hidden="true">·</span> Certifications</p>
<p class="home-lead">Everything I have built, practised and learned in one place.</p>
<nav class="pf-nav" aria-label="Portfolio sections">
<a href="#projects">Projects</a>
<a href="#ctf-writeups">CTF Write-ups</a>
<a href="#labs">Labs</a>
<a href="#certifications">Certifications</a>
<a href="#notes">Notes</a>
<a href="#skills">Skills</a>
</nav>
</div>

<div class="home-panel pf-panel">
<h2 class="home-heading" id="projects">Projects</h2>

<div class="pf-card" markdown="1">
### Health Insurance Fraud Detection System (HIFDS)
<p class="pf-tech">Final-year project · Python, Flask, MongoDB, Naive Bayes, SVM</p>
Built a web application that flags suspicious health insurance claims, designed for the Kenyan context (NHIF/SHA). Trained and compared Naive Bayes and Support Vector Machine classifiers and reported performance with standard ML metrics. Wrote the research methodology using Agile/Scrum across four sprints, and handled the full codebase, references and deployment.
</div>

<div class="pf-card" markdown="1">
### AI Vulnerability Triage tool
<p class="pf-tech">Flask, nmap, Nikto, Anthropic API</p>
Parses nmap (XML and plain text) and Nikto output, then uses the Anthropic API to assess severity so findings can be prioritised faster.
</div>

<div class="pf-card" markdown="1">
### Browser-based security audit checklist
Created an interactive audit checklist tool with Claude API integration to guide assessments.
</div>

<div class="pf-card" markdown="1">
### NEMA license verification for The Salvation Army Kenya
Generated a QR code and deployed a styled verification page through GitHub and Render so a license can be checked on the spot.
</div>

<div class="pf-card" markdown="1">
### Smart Water Refill website
Designed, built and hosted the business website, and wrote a formal deployment report. Explored domain registration and WordPress hosting options.
</div>

{% assign items = site.categories.projects %}{% if items.size > 0 %}<ul class="pf-posts">{% for post in items %}<li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> <span>{{ post.date | date: "%b %d, %Y" }}</span></li>{% endfor %}</ul>{% endif %}
</div>

<div class="home-panel pf-panel">
<h2 class="home-heading" id="ctf-writeups">CTF Write-ups</h2>
<div class="pf-card" markdown="1">
Competed in picoCTF and CyLabs Academy CTF challenges: command injection, SSH file combination, session hijacking, SMB file sharing, byte manipulation and Git server exploitation.
</div>
{% assign items = site.categories["ctf-writeups"] %}{% if items.size > 0 %}<ul class="pf-posts">{% for post in items %}<li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> <span>{{ post.date | date: "%b %d, %Y" }}</span></li>{% endfor %}</ul>{% endif %}
</div>

<div class="home-panel pf-panel">
<h2 class="home-heading" id="labs">Labs</h2>
<div class="pf-card" markdown="1">
### Ethical hacking lab (hacklab)
<p class="pf-tech">VirtualBox, Kali Linux, Metasploitable2, Mr. Robot CTF machine</p>
Set up an isolated internal network for safe practice in scanning, exploitation and reporting. I work comfortably in Kali Linux, using VS Code as my main editor.
</div>
{% assign items = site.categories.labs %}{% if items.size > 0 %}<ul class="pf-posts">{% for post in items %}<li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> <span>{{ post.date | date: "%b %d, %Y" }}</span></li>{% endfor %}</ul>{% endif %}
</div>

<div class="home-panel pf-panel">
<h2 class="home-heading" id="certifications">Certifications</h2>
<div class="pf-pills">
<span class="pf-pill pf-pill--cert">CyberShujaa / Serianu</span>
<span class="pf-pill pf-pill--cert">EC-Council: MITRE ATT&amp;CK</span>
<span class="pf-pill pf-pill--cert">Internet Society: Cybersecurity Governance</span>
<span class="pf-pill pf-pill--cert">Cisco: Ethical Hacker</span>
<span class="pf-pill pf-pill--cert">IBM: Cybersecurity Fundamentals</span>
<span class="pf-pill pf-pill--cert">Atingi: Digital Safety</span>
</div>
{% assign items = site.categories.certifications %}{% if items.size > 0 %}<ul class="pf-posts">{% for post in items %}<li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> <span>{{ post.date | date: "%b %d, %Y" }}</span></li>{% endfor %}</ul>{% endif %}
</div>

<div class="home-panel pf-panel">
<h2 class="home-heading" id="notes">Notes</h2>
<div class="pf-card" markdown="1">
Networking fundamentals (cabling standards T568A/B, remote access with PuTTY and RDP, SSH, DNS) and engagement with the ISO 27001 and NIST frameworks.
</div>
{% assign items = site.categories.notes %}{% if items.size > 0 %}<ul class="pf-posts">{% for post in items %}<li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> <span>{{ post.date | date: "%b %d, %Y" }}</span></li>{% endfor %}</ul>{% endif %}
</div>

<div class="home-panel pf-panel">
<h2 class="home-heading" id="skills">Skills at a Glance</h2>
<p class="pf-group">Forensics and security</p>
<div class="pf-pills">
<a class="pf-pill" href="/tags/#autopsy">autopsy</a><a class="pf-pill" href="/tags/#binwalk">binwalk</a><a class="pf-pill" href="/tags/#nmap">nmap</a><a class="pf-pill" href="/tags/#burp-suite">burp-suite</a><a class="pf-pill" href="/tags/#wireshark">wireshark</a><a class="pf-pill" href="/tags/#metasploit">metasploit</a>
</div>
<p class="pf-group">Development</p>
<div class="pf-pills">
<a class="pf-pill" href="/tags/#python">python</a><a class="pf-pill" href="/tags/#flask">flask</a><a class="pf-pill" href="/tags/#mongodb">mongodb</a><a class="pf-pill" href="/tags/#machine-learning">machine-learning</a><a class="pf-pill" href="/tags/#github">github</a>
</div>
<p class="pf-group">Topics</p>
<div class="pf-pills">
<a class="pf-pill" href="/tags/#digital-forensics">digital-forensics</a><a class="pf-pill" href="/tags/#penetration-testing">penetration-testing</a><a class="pf-pill" href="/tags/#networking">networking</a><a class="pf-pill" href="/tags/#fraud-detection">fraud-detection</a>
</div>
<p class="pf-more"><a href="/categories/">All categories</a> · <a href="/tags/">All tags</a></p>
</div>

<div class="home-hero">
<h2 class="home-heading" style="margin-bottom:1rem">Contact Me</h2>
<p class="home-lead" style="margin-bottom:1.2rem">Email: <a href="mailto:bensonsng128@gmail.com">bensonsng128@gmail.com</a><br>LinkedIn: <a href="https://linkedin.com/bensonsang">linkedin.com/bensonsang</a><br>Twitter: <a href="https://twitter.com/bensonsang">twitter.com/bensonsang</a></p>
<a class="home-cta" href="/cv/">Explore my CV <span aria-hidden="true">→</span></a>
</div>

</div>