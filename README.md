# Who am I?

Thanks for checking out my profile. I'm Logan, and I hold a bachelor's in **Cybersecurity & Information Assurance from WGU**, which I finished in 11 months.

That degree gave me a broad foundation across technology, systems, networks, and security, and along the way it reinforced something I've always known: **I genuinely enjoy figuring out how things work.** Whether it's software, hardware, operating systems, networks, or security, I like taking things apart, understanding them, and seeing what I can build with that knowledge.

I'm passionate about technology and always have been. (As you can see from my pfp, I'm always by a computer.) I'll work on anything from my grandma's flip phone to a homelab server, and I genuinely enjoy the learning part.

Most people have a caffeine addiction; mine is to figuring out how things work.

PCs, laptops, monitors, phones, Pis, I've worked on all of it. The tools I build come directly out of that: **when I've done something manually enough times to know it's worth automating, I automate it.**

---

# What have I built?

### [ISOx](https://github.com/logjxn/ISOx) — A CLI tool for safer Linux downloads

I experiment with Linux across a lot of distributions, and I was doing it often enough that I almost started skipping checksum verification because it was, well, annoying.

That's exactly the step you shouldn't skip, so I built the tool that does it for me.

**ISOx** races the available mirrors to find the fastest one, downloads the ISO from it, then verifies the file against the checksum published by the distribution's own server, not the mirror that served the bytes.

A mirror that can hand you a modified ISO can hand you a matching hash just as easily, so splitting those two sources is the whole point.

I've built a test suite (**150+ tests**), CI/CD pipelines, and automated PyPI publishing for this project as well.

**15 distributions supported**, and adding another is usually a config entry rather than a code change.

Published on PyPI:

```bash id="a4s7nq"
pip install isox
```

I use it every day I work with Linux.

### [sb-audit](https://github.com/logjxn/sb-audit) — Audits Windows boot posture

A read-only Windows boot security posture auditor that checks **Secure Boot, TPM, and firmware mode**, then explains what's blocking what.

Rather than reporting a flat checklist, it presents the results as an **ordered dependency chain**. You can't enable Secure Boot until the firmware is in UEFI mode, so the tool tells you where you actually are and what to do first.

**PowerShell extracts, Python interprets.**

The tool refuses to run without administrator rights rather than risk returning a wrong answer.

---

# What are my goals?

**Keep learning, keep building, and keep understanding technology from both sides of the equation.**

My background is in cybersecurity, and I'm interested in improving my skills and knowledge everyday. Whether that's professional experience, certification study, or online platforms like THM or HTB, I aim to continuously learn and improve.

I'm particularly interested in the intersection between **building technology and understanding how to protect it**.

---

# Tools

* Python
* Wireshark
* nmap
* Git
* GitHub Actions
* Bash
* Metasploit
* Burp Suite
* Linux

# Certifications

* CompTIA CySA+
* CompTIA PenTest+
* CompTIA A+
* CompTIA Network+
* CompTIA Security+
* Linux Essentials (LPI)
* CompTIA Project+
* ITIL 4 Foundation
* CompTIA Data+
