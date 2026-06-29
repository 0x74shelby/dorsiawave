<!--
  README.md — 0x74shelby Security Engineer Portfolio
  GitHub: 0x74shelby
-->

<h1 align="center">0x74shelby — Security Engineer Portfolio</h1>

<p align="center">
  <em>Penetration testing · Red teaming · CTF writeups · Malware research</em><br/>
  <sub>Built &amp; maintained by <a href="https://github.com/0x74shelby">@0x74shelby</a></sub>
</p>

<p align="center">
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/>
  <img alt="TailwindCSS" src="https://img.shields.io/badge/Tailwind-38BDF8?style=flat-square&logo=tailwindcss&logoColor=white"/>
  <img alt="Static Site" src="https://img.shields.io/badge/Build-Static%20%2F%20No%20Deps-0a0a0a?style=flat-square"/>
  <img alt="SEO" src="https://img.shields.io/badge/SEO-Optimized-3366ff?style=flat-square"/>
</p>

---

## About

Hey — I'm **0x74shelby**. I've spent the last three years doing offensive security: black-box, grey-box, and white-box pentesting, Active Directory attacks, web-app exploitation, and the occasional malware deep-dive when something old and weird catches my attention (the 1986 Brain virus post in `/blog` started exactly that way).

This repo is the source for [**0x74shelby.pages.dev**](https://0x74shelby.pages.dev) — a hand-coded static site. No framework, no build step, no tracking. Every page is a single HTML file you can open in a browser and read. I wanted the code to be as honest as the writeups.

Four entry points:

- 🏠 **Home** → hero, capabilities, pentest projects → [`index.html`](https://0x74shelby.pages.dev/index.html)
- 📝 **Blog** → long-form malware &amp; security research → [`blog.html`](https://0x74shelby.pages.dev/blog.html)
- 🎯 **CTF Writeups** → rooted machines, step-by-step → [`ctf.html`](https://0x74shelby.pages.dev/ctf.html)
- 📚 **Learn** → security knowledge base, attack concepts, fundamentals → [`learn.html`](https://0x74shelby.pages.dev/learn.html)

---

## Highlighted posts

| Post | Category | Status |
|---|---|---|
| [The Brain Virus (1986): Two Brothers, Lahore, and the First PC Virus](https://0x74shelby.pages.dev/blog-worlds-first-virus.html) | Malware history · Case study | Published |
| _More malware &amp; red-team posts in progress_ | — | Queued |

---

## Security Knowledge Base

[`learn.html`](https://0x74shelby.pages.dev/learn.html) is a growing reference covering every concept I actually use in the field — not textbook theory, but practical notes from real engagements and CTF labs.

| Topic | Category | Level |
|---|---|---|
| [Linux Fundamentals](https://0x74shelby.pages.dev/learn/learn-linux-fundamentals.html) | Foundations | Beginner |
| [Network Foundations](https://0x74shelby.pages.dev/learn/learn-network-foundations.html) | Foundations | Beginner |
| [Nmap](https://0x74shelby.pages.dev/learn/learn-nmap.html) | Enumeration | Beginner |
| [DNS Enumeration](https://0x74shelby.pages.dev/learn/learn-dns-enumeration.html) | Enumeration | Intermediate |
| [Footprinting](https://0x74shelby.pages.dev/learn/learn-footprinting.html) | Enumeration | Intermediate |
| [Bash Scripting](https://0x74shelby.pages.dev/learn/learn-bash-scripting.html) | Scripting | Intermediate |
| [Web Fuzzing](https://0x74shelby.pages.dev/learn/learn-web-fuzzing.html) | Web | Intermediate |
| [SQL Injection](https://0x74shelby.pages.dev/learn/learn-sql-injection.html) | Web | Intermediate |
| [XSS](https://0x74shelby.pages.dev/learn/learn-xss.html) | Web | Intermediate |
| [File Inclusion](https://0x74shelby.pages.dev/learn/learn-file-inclusion.html) | Web | Intermediate |
| [File Upload Attacks](https://0x74shelby.pages.dev/learn/learn-file-upload.html) | Web | Intermediate |
| [Command Injection](https://0x74shelby.pages.dev/learn/learn-command-injection.html) | Web | Intermediate |
| [Shells and Payloads](https://0x74shelby.pages.dev/learn/learn-shells-payloads.html) | Access | Intermediate |
| [Password Attack Techniques](https://0x74shelby.pages.dev/learn/learn-password-attacks.html) | Access | Intermediate |
| [Network Pivoting and Tunneling](https://0x74shelby.pages.dev/learn/learn-network-pivoting.html) | Access | Advanced |
| [Linux Privilege Escalation](https://0x74shelby.pages.dev/learn/learn-linux-privesc.html) | Post-Exploitation | Advanced |
| [Windows Privilege Escalation](https://0x74shelby.pages.dev/learn/learn-windows-privesc.html) | Post-Exploitation | Advanced |
| [Buffer Overflow](https://0x74shelby.pages.dev/learn/learn-buffer-overflow.html) | Exploitation | Advanced |
| [Active Directory Fundamentals](https://0x74shelby.pages.dev/learn/learn-active-directory.html) | Active Directory | Advanced |
| [Active Directory Attack Techniques](https://0x74shelby.pages.dev/learn/learn-ad-attacks.html) | Active Directory | Advanced |
| [Android Security](https://0x74shelby.pages.dev/learn/learn-android-security.html) | Mobile | Advanced |
| [Hardware Attacks](https://0x74shelby.pages.dev/learn/learn-hardware-attacks.html) | Hardware | Advanced |

---

## Pentest assessments

Three recent engagements — full PDF reports on my [Reports repo](https://github.com/0x74shelby/pentestreports):

| Project | Type | Difficulty | What it tested |
|---|---|---|---|
| [Blinders](https://0x74shelby.pages.dev/post-blinders.html) | Black box | Medium | OSINT → credential reuse → privesc |
| [Demon](https://0x74shelby.pages.dev/post-demon.html) | Grey box | Hard | Vhost discovery, Jenkins RCE, sudo misconfig, rbash escape |
| [KGF](https://0x74shelby.pages.dev/post-kgf.html) | White box | Hard | SNMP enum, IMAPS creds, r-services pivot, dual-host root |
| [VulnCMS](https://0x74shelby.pages.dev/post-vulncms.html) | VulnHub | Medium | Drupalgeddon2 RCE, journalctl GTFObins |

---

## CTF machines — UTM virtualization guide

A lot of people ask me how I run my CTF boxes locally on Apple Silicon without dragging a full VMware or VirtualBox install onto the machine. Short answer: **UTM**. It's the free QEMU-based virtualizer for macOS / iPadOS, and once you get the hang of it, it's honestly the cleanest way to spin up a vulnerable VM for practice.

Instead of rewriting everything here, I put together a small walk-through site covering the setup, network modes, and the gotchas I hit early on:

**📖 Guide:** [utm.dorisa74964.workers.dev](https://utm.dorisa74964.workers.dev/) — still on the old Workers subdomain; not renamed since this rebrand only covers the pages.dev site

Give it a read before you attempt any of the writeups in [`/ctf.html`](https://0x74shelby.pages.dev/ctf.html) — a lot of the "why can't I reach the box" questions I get are just network-mode issues the guide already answers.

> ⚠️ Anything you boot in a CTF context is intentionally vulnerable. Keep it on a host-only / NAT interface. Don't bridge it to your LAN and definitely don't expose it to the open internet.

---

## Running the site locally

No build step. Pick whichever you have handy:

```bash
# Python (ships with macOS / most Linux)
python3 -m http.server 8080

# Node
npx serve .
```

Then open <http://localhost:8080>.

---

## Contact

- 🌐 **Site** — [0x74shelby.pages.dev](https://0x74shelby.pages.dev)
- 💻 **GitHub** — [@0x74shelby](https://github.com/0x74shelby)
- 💼 **LinkedIn** — [in/0x74shelby](https://www.linkedin.com/in/0x74shelby)
- 🐦 **Twitter / X** — [@0x74shelby](https://x.com/0x74shelby)
- 📄 **Reports archive** — [github.com/0x74shelby/pentestreports](https://github.com/0x74shelby/pentestreports)

DMs on LinkedIn are open — red-team work, pentest engagements, or if you just want to ask how I rooted KGF.

---

<p align="center">
  <sub>© 2026 0x74shelby — All writeups &amp; posts are my own work.</sub>
</p>
