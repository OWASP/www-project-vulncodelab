---

layout: col-sidebar
title: OWASP VulnCodeLab
tags: example-tag
level: 2
type: code
pitch: A very brief, one-line description of your project

---

VulnCodeLab is a purpose-built, intentionally vulnerable full-stack web application designed to train developers, security engineers in manual secure source code review. Unlike existing OWASP projects like Juice Shop (focused on exploitation), VulnCodeLab targets white-box auditing skills — scanning for code-level bugs, security misconfigurations, and business logic flaws across a realistic codebase.
The app simulates an e-commerce platform using Next.js (frontend) and Django REST Framework (backend) and includes vulnerabilities across 10+ categories, including OWASP Top 10 and CWE-mapped logic.
VulnCodeLab helps:

* Teach secure coding practices
* Train for real-world code audits
* Test AppSec and dev team skills
* Improve internal secure SDLC workflows

### Road Map
Phase 1: MVP Release

* Build minimal viable e-commerce app (login, product list, cart, checkout)
* Inject 30+ real vulnerabilities (XSS, IDOR, SQLi, SSTI, SSRF,etc.)
* Add CWE/OWASP mapping with fix guidance
* Dockerized deployment
* Publish GitHub repo 
* Submit as OWASP Project

Phase 2: Expansion

* Add advanced vulns (like Race conditions, etc.)
* Multi-role support (admin, vendor, customer)
* Add frontend-specific bugs (Next.js bundle, SSR flaws)
* CI pipeline integration example for SAST training

Phase 3: Ecosystem Growth

* Collabration and continuous development
* Cover new attack vectors if introduced in OWASP TOP 10 2025
