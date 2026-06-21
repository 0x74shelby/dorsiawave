<h1 align="center">0x74shelby — Security Engineer, Penetration Tester &amp; Red Teamer</h1>

<p align="center">
  <em>Penetration testing · Red team operations · CTF writeups · Malware research</em><br/>
  <sub>Built &amp; maintained by <a href="https://github.com/0x74shelby">@0x74shelby</a> </sub>
</p>

<p align="center">
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/>
  <img alt="TailwindCSS" src="https://img.shields.io/badge/Tailwind-38BDF8?style=flat-square&logo=tailwindcss&logoColor=white"/>
  <img alt="Static Site" src="https://img.shields.io/badge/Build-Static%20%2F%20No%20Deps-0a0a0a?style=flat-square"/>
  <img alt="OSCP/CPTS/CEH" src="https://img.shields.io/badge/Certified-CPTS%20%7C%20CEH-0a0a0a?style=flat-square"/>
</p>

---

## About

I'm **0x74shelby** — a security engineer based in Bangalore, doing penetration testing and red team work. Three years in, and I've stopped counting the apps, networks, and Active Directory forests I've gone through. The job is simple to describe and hard to do well: find what a real attacker would find, before they do, and prove it with a clean repro instead of a guess.

CPTS (Hack The Box, 2026) and CEH (EC-Council, 2023) are the two certs I'll actually point you to. I don't treat them as trophies. They're just proof I've been tested on the stuff I claim to know. Outside of paid engagements, you'll usually find me knee-deep in a CTF box or chasing an old malware sample down a rabbit hole — the [Brain virus post](https://dorsiawave-me.pages.dev/blog/blog-worlds-first-virus.html) below started exactly that way.

This repo is the source for my **[security engineer portfolio](https://dorsiawave-me.pages.dev/)** — a hand-coded static site, no framework, no build step, no tracking. Every page is one HTML file you can open and read top to bottom. I wanted the code to be as honest as the writeups.

Three entry points:

- 🏠 **Home** — hero, capabilities, pentest assessments → [`index.html`](https://dorsiawave-me.pages.dev/)
- 📝 **Blog** — malware analysis, cybercrime history, threat research → [`blog.html`](https://dorsiawave-me.pages.dev/blog)
- 🎯 **CTF Writeups** — rooted machines, full walkthroughs → [`ctf.html`](https://dorsiawave-me.pages.dev/ctf)

---

## Arsenal

What's actually in the kit, not just the logo wall:

`Burp Suite Pro` · `Metasploit` · `Nmap` / `Nessus` · `BloodHound` · `Wireshark`

**Focus areas:** Web application security · Active Directory pentesting · Network security · Privilege escalation · Lateral movement · OSINT

---

## Pentest assessments

Four engagements, each with the full PDF report on my [Reports archive](https://github.com/0x74shelby/pentestreports):

| Engagement | Type | Difficulty | What it tested |
|---|---|---|---|
| [Blinders](https://dorsiawave-me.pages.dev/writeups/post-blinders.html) | Black box | Medium | OSINT recon, username-anarchy generation, credential reuse, GTFObins privesc |
| [Demon](https://dorsiawave-me.pages.dev/writeups/post-demon.html) | Grey box | Hard | Vhost enumeration, Jenkins Groovy console RCE, rbash escape, sudo misconfig |
| [KGF](https://dorsiawave-me.pages.dev/writeups/post-kgf.html) | White box | Hard | SNMP enum, IMAPS credential extraction, r-services pivot, dual-host root |
| [VulnCMS](https://dorsiawave-me.pages.dev/post-vulncms) | VulnHub | Medium | Drupalgeddon2 RCE, journalctl GTFObins |

Blinders taught me something I keep relearning: the weakest link is rarely technical. It's a reused password. Demon's whole engagement turned on one hidden Jenkins instance nobody remembered was running. KGF is still my favorite — full white-box access didn't make the dual-host pivot any less satisfying to land.

---

## Intel Feed — recent posts

Malware analysis, cybercrime history, and the occasional tech-fraud teardown:

| Post | Category | Date |
|---|---|---|
| [BellTroX & Dark Basin: The Delhi Hack-for-Hire Shop Exposed](https://dorsiawave-me.pages.dev/blog/blog-belltrox-dark-basin.html) | Cybercrime History | 17 May 2026 |
| [REvil: Inside the Ransomware-as-a-Service Empire](https://dorsiawave-me.pages.dev/blog/blog-revil-raas.html) | Cybercrime History | 13 May 2026 |
| [The ATM Boy: Dan Saunders & the AU$1.6M NAB Glitch](https://dorsiawave-me.pages.dev/blog/blog-atm-glitch-dan-saunders.html) | Cybercrime History | 09 May 2026 |
| [Builder.ai: The $450M Fake AI Company That Was Just People Typing Fast](https://dorsiawave-me.pages.dev/blog/blog-builder-ai-fake.html) | Tech Fraud | 03 May 2026 |
| [Vladimir Levin vs. Citibank (1994) — The First Online Bank Heist](https://dorsiawave-me.pages.dev/blog/blog-online-bank-robbery.html) | Cybercrime History | 26 Apr 2026 |
| [Brain (1986): How Two Brothers From Lahore Wrote the First PC Virus](https://dorsiawave-me.pages.dev/blog/blog-worlds-first-virus.html) | Malware Analysis | 19 Apr 2026 |

Full archive on the [blog page](https://dorsiawave-me.pages.dev/blog.html).

---

## CTF writeups

Rooted machines with the actual thought process included — dead ends and all:

| Writeup | Type | Difficulty | Path |
|---|---|---|---|
| [Blinders](https://dorsiawave-me.pages.dev/writeups/post-blinders.html) | Linux, custom VM | Medium | OSINT → Hydra brute force → Sherlock recon → MySQL creds → GTFObins root |
| [KGF](https://dorsiawave-me.pages.dev/writeups/post-kgf.html) | Linux, custom VM | Hard | SNMP enum → IMAPS creds → r-services pivot → root on both hosts |
| [Demon](https://dorsiawave-me.pages.dev/writeups/post-demon.html) | Linux, custom VM | Hard | Vhost enum → Jenkins RCE → XLSX hash cracking → rbash escape → root |

Full archive on the [CTF page](https://dorsiawave-me.pages.dev/ctf.html).

---

## Contact

- 🌐 **Portfolio** — [dorsiawave-me.pages.dev](https://dorsiawave-me.pages.dev/)
- 💻 **GitHub** — [@0x74shelby](https://github.com/0x74shelby)
- 📄 **Reports archive** — [github.com/0x74shelby/pentestreports](https://github.com/0x74shelby/pentestreports)

Open to red team work and pentest engagements — reach out if you want to talk shop or just ask how I rooted KGF.

---

<p align="center">
  <sub>© 0x74shelby — All writeups &amp; posts are my own work.</sub>
</p>
