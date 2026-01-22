cat << 'EOF' > README.md
# 🚀 Google Dorkware Pro — Advanced OSINT & Recon Tool

Google Dorkware Pro is an advanced, browser-based OSINT and reconnaissance automation platform built for penetration testers, bug bounty hunters, and cybersecurity learners.
It helps in discovering hidden endpoints, exposed files, vulnerable parameters, and security misconfigurations using advanced Google Dorking techniques and OWASP Top-25 parameter patterns.

🌐 Live Demo:
https://dharmendrastm.github.io/GoogleDorkware/

---

## 📌 Project Description

Reconnaissance is the most critical phase of penetration testing and bug bounty hunting.
Google Dorkware Pro simplifies and accelerates this phase by automating:

- Google Dork discovery
- Parameter hunting
- Vulnerability-focused endpoint enumeration

Instead of manually writing hundreds of Google search queries, users can simply enter a target domain and execute pre-built recon modules with one click.
This allows security researchers to spend more time on manual testing, exploitation, and business logic analysis.

⚠️ This tool performs reconnaissance only and does not exploit vulnerabilities.

---

## ✨ Features

### 🔍 Advanced Google Dork Engine
- 250+ curated Google Dorks
- 24+ vulnerability categories:
  - Admin & Login Panels
  - SQL Injection
  - Cross-Site Scripting (XSS)
  - Local File Inclusion (LFI)
  - Server-Side Request Forgery (SSRF)
  - Open Redirect
  - Exposed Databases
  - Backup & Config Files
  - API Endpoints
  - Cloud Storage Buckets
  - Git Repositories
  - Directory Listings
  - WordPress Security and more

### 🛡 OWASP Top-25 Parameter Scanner
- 150+ high-risk URL parameters
- Covers:
  - SSRF
  - LFI
  - SQL Injection
  - Open Redirect
  - XSS
  - Remote Code Execution (RCE)
- One-click Google query generation

### ⚡ Professional Recon Workflow
- Severity-based categorization (Low / Medium / High / Critical)
- Automated Google search execution
- Bug bounty optimized methodology
- Cyber-themed professional UI

### 🌐 Fully Client-Side
- No backend required
- No user data collection
- Works directly in browser
- Easy deployment using GitHub Pages

---

## 🧠 How It Works

1. Enter your authorized target domain  
   Example:
   testphp.vulnweb.com

2. Select any Google Dork category or OWASP scanner module

3. The tool automatically opens optimized Google searches like:
   site:example.com inurl:login
   site:example.com inurl:id=
   site:example.com filetype:env

4. Perform manual testing using:
   - Burp Suite
   - Browser Developer Tools
   - Manual payload injection
   - Business logic testing

---

## 🧰 Technology Used

### 🌐 Frontend
- HTML5 — Semantic structure and accessibility-friendly markup
- CSS3 — Cyber-themed UI design, animations, gradients, and responsive layout
- JavaScript (Vanilla JS) — Dynamic rendering, event handling, and Google query automation

### 🎨 UI & UX Enhancements
- Google Fonts (Orbitron & JetBrains Mono)
- Font Awesome Icons
- HTML5 Canvas API (Matrix background animation)

### 🔍 Security & OSINT Concepts
- Google Search Operators:
  site:, inurl:, intitle:, filetype:
- OWASP Testing Guide parameter patterns for:
  SQLi, XSS, LFI, SSRF, Open Redirect, RCE

### 🚀 Deployment
- GitHub Pages
- Client-side only architecture (no backend)

---

## 🎯 Project Purpose

The primary goal of Google Dorkware Pro is to accelerate reconnaissance during web security testing by providing:

- Faster discovery of hidden URLs and parameters
- Structured vulnerability-based recon workflow
- Reduced manual searching effort
- Learning support for cybersecurity students

This tool bridges the gap between OSINT techniques and real-world pentesting methodology.

---

## ⚠️ Legal Disclaimer

This tool is intended only for educational purposes and authorized security testing.

Do NOT use this tool on websites without proper written permission.
Unauthorized testing is illegal and punishable by law.

The developer is not responsible for any misuse of this tool.

---

## 👨‍💻 Developer

Dharmendra Singh  
Penetration Tester | Security Researcher

Portfolio: https://dharmendrastm.github.io/PortfolioWebsite/  
GitHub: https://github.com/Dharmendrastm  
LinkedIn: https://www.linkedin.com/in/dharmendrastm/  
Medium: https://dharmendrastm.medium.com/

Aliases:
dharmendrastm | dharmendrahacker | dharmendracyberhack

---

## ⭐ Support & Contribution

If you find this project useful:

- Star the repository
- Fork and improve it
- Report bugs
- Suggest new dorks and parameters

Contributions are always welcome.

---

## 🛣 Roadmap

- [ ] Wayback URL integration
- [ ] Subdomain enumeration
- [ ] Parameter brute-force module
- [ ] Result export feature
- [ ] Recon notes and reporting system

---

## ✅ Conclusion

Google Dorkware Pro demonstrates how OSINT and Google Dorking can be effectively automated to improve reconnaissance workflows.
It reflects real-world penetration testing practices and serves as a strong portfolio project for careers in cybersecurity.

Use it responsibly and help make the internet safer.

EOF
