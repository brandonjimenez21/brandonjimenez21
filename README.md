<div align=center>
    <img src="https://raw.githubusercontent.com/hungpham3112/hungpham3112/main/assets/github.png" alt="github 3d icon" height="200">
</div>
<div align=center>
    <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&duration=4000&pause=500&color=52F7EF&center=true&vCenter=true&width=500&lines=Hi!+I'm+Brandon+Jimenez;Full-Stack+Developer;Backend+%26+Automations" alt="Typing SVG" /></a>
</div>

<p align="center">
	<a href="https://github.com/brandonjimenez21">
		<img src="https://komarev.com/ghpvc/?username=brandonjimenez21&label=Profile%20views&color=0e75b6&style=flat" alt="profile views"/>
	</a>
</p>

<h1> Hello Fellow < Developers/ >! <img src = "https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width = 30px> </h1>

[![Github](https://img.shields.io/github/followers/brandonjimenez21?label=Follow&style=social)](https://github.com/brandonjimenez21)

<div size='20px'> Hi! My name is Brandon Jimenez. Thank You for taking the time to view my GitHub Profile :heart: </div>

## 💼 Professional Experience

### **Co-Founder & Lead Full-Stack Developer** | [*Efisco SAS*](https://efisco.co/) `[April 2026 – Present]`

Multi-tenant B2B SaaS for motorcycle workshop management in Colombia — built from scratch, solo.

- Designed the complete system architecture: app-level multi-tenant isolation (every endpoint validates `workshop_id` against the authenticated session), PostgreSQL RLS as defense-in-depth across 28 tables (audited with Supabase Security Advisor, Jul 2026).
- Built a financial engine with real Colombian fiscal logic: IVA 19%/10%/5%, ReteFuente, ReteICA, ReteIVA, gateway commissions, GMF 4×1000 — 15 ledger movement types in an immutable append-only ledger. Validated with **49 suites / 216 automated tests** (Jest, ESM native, CI via GitHub Actions).
- Integrated electronic invoicing to the DIAN via Dataico (non-blocking, per-workshop sub-account, CUFE stored per order), WhatsApp Cloud API for automated client communication, AWS Textract for async OCR of supplier invoices, and three payment gateways (Mercado Pago, Bold, Addi) with fail-closed webhook verification.
- Implemented a layered security model: 2-layer suspension (login + middleware token invalidation), B2B contract gate with e-signature under Ley 527/1999, staff authorization gate with append-only legal evidence (timestamp + IP), OTP-protected credit score with brute-force limit (5 attempts / 15 min lockout, `crypto.timingSafeEqual`), and scoped IDOR protection on all provider mutations.
- Conducted a full internal security audit (Jul 2026): found and patched 7 critical/high vulnerabilities in one day, including an IDOR + mass assignment on provider endpoints and an open webhook vector allowing anyone to mark orders as paid.

📁 Architecture & documentation: [efiscoDocumentation](https://github.com/brandonjimenez21/efiscoDocumentation)

<h2> About Me </h2>

<img width="45%" align="right" alt="Github" src="https://raw.githubusercontent.com/onimur/.github/master/.resources/git-header.svg" />

- 💻 **Full-Stack Developer** focused on building scalable backend architectures, database optimization, and secure web applications.

- 🛠️ **Deep experience** working with modern stacks: Node.js, Python, Supabase (PostgreSQL), and cloud deployments.

- 🤖 **Passionate about** building automated systems and production-ready integrations (APIs, Webhooks, WhatsApp Business API).
  
- ⚡ **Fun fact:** I like video games

- 📫 **How to reach me:** brandonjimenez.dev@gmail.com

<br>

<h3 align="left">Connect with me:</h3>
<div align="left">

[![image](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/skilledgm/)
[![image](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:brandonjimenez.dev@gmail.com)
  
</div>

<br>

<h3 align="left">Languages and Tools:</h3>

<h4>🧠 Backend & Databases</h4>
<p align="left"> 
  <img src="https://skillicons.dev/icons?i=nodejs,py,go,php,java,mysql,supabase" />
</p>

<h4>🎨 Frontend</h4>
<p align="left"> 
  <img src="https://skillicons.dev/icons?i=js,ts,react,html,css,tailwind" />
</p>

<h4>🛠️ DevOps & Environments</h4>
<p align="left"> 
  <img src="https://skillicons.dev/icons?i=linux,bash,docker,git,github,vscode,idea" />
</p>
