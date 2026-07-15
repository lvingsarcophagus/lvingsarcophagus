<!-- CUSTOM INLINE SVG HEADER BANNER -->
<p align="center">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 200" width="100%">
    <defs>
      <!-- Background Gradient -->
      <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#0b0f19" />
        <stop offset="50%" stop-color="#111827" />
        <stop offset="100%" stop-color="#020617" />
      </linearGradient>
      
      <!-- Accent Gradients -->
      <linearGradient id="textGrad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#38bdf8" /> <!-- sky-400 -->
        <stop offset="50%" stop-color="#818cf8" /> <!-- indigo-400 -->
        <stop offset="100%" stop-color="#34d399" /> <!-- emerald-400 -->
      </linearGradient>

      <linearGradient id="glow" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#38bdf8" stop-opacity="0.25" />
        <stop offset="100%" stop-color="#34d399" stop-opacity="0" />
      </linearGradient>
    </defs>

    <!-- Background -->
    <rect width="100%" height="100%" rx="12" fill="url(#bg)" stroke="#1e293b" stroke-width="1.5" />

    <!-- Decorative Grid Pattern -->
    <g stroke="#1e293b" stroke-width="0.5" opacity="0.3">
      <path d="M 0,40 L 800,40 M 0,80 L 800,80 M 0,120 L 800,120 M 0,160 L 800,160" />
      <path d="M 100,0 L 100,200 M 200,0 L 200,200 M 300,0 L 300,200 M 400,0 L 400,200 M 500,0 L 500,200 M 600,0 L 600,200 M 700,0 L 700,200" />
    </g>

    <!-- Glowing Cyber Rings -->
    <circle cx="700" cy="100" r="130" fill="url(#glow)" />
    <circle cx="700" cy="100" r="90" fill="none" stroke="#38bdf8" stroke-width="1.2" stroke-dasharray="6,12" opacity="0.35" />
    <circle cx="700" cy="100" r="50" fill="none" stroke="#34d399" stroke-width="1" opacity="0.2" />

    <!-- Node Network Visuals (Web3 / Security theme) -->
    <g stroke="#38bdf8" stroke-width="1.2" opacity="0.5">
      <line x1="640" y1="60" x2="680" y2="120" />
      <line x1="680" y1="120" x2="740" y2="85" />
      <line x1="740" y1="85" x2="710" y2="150" />
      <line x1="710" y1="150" x2="640" y2="60" />
    </g>
    <g fill="#34d399">
      <circle cx="640" cy="60" r="4.5" />
      <circle cx="680" cy="120" r="3.5" />
      <circle cx="740" cy="85" r="4.5" fill="#38bdf8" />
      <circle cx="710" cy="150" r="3.5" />
    </g>

    <!-- Header Text -->
    <text x="50" y="85" font-family="'Outfit', 'Inter', -apple-system, sans-serif" font-size="38" font-weight="800" fill="url(#textGrad)" letter-spacing="1.5">
      NAYAN JOSHY
    </text>

    <text x="50" y="125" font-family="'Inter', -apple-system, sans-serif" font-size="16" font-weight="600" fill="#94a3b8" letter-spacing="1">
      CYBERSECURITY &amp; WEB3 SECURITY ENGINEER
    </text>

    <text x="50" y="160" font-family="'Inter', -apple-system, sans-serif" font-size="12" font-weight="500" fill="#64748b" letter-spacing="0.5">
      Smart Contracts • Auditing • Deep Sandboxes • Vulnerability Research
    </text>
  </svg>
</p>

---

### 🧬 About Me

I specialize at the intersection of **Cybersecurity** and **Web3 Security**. From auditing smart contract attack surfaces to building production-grade DeFi analytics engines, I focus on constructing secure, resilient blockchain systems. 

I hold a **BSc in Information Systems and Cybersecurity** from Vilnius University and blend traditional security concepts (penetration testing, SIEM log analysis, network recon) with state-of-the-art Web3 development. I move fast, work autonomously, and leverage AI tooling to write secure, optimized code.

---

### 🚀 Featured Projects

#### 🦀 [Photon](https://github.com/lvingsarcophagus/photon)
*Rust-native multi-engine smart contract security scanner*
* **Static Analysis:** Rayon-parallel AST analysis checking 50+ reentrancy, access control, and oracle manipulation rules.
* **Symbolic Verification:** Lowers Solidity ASTs to SSA CFG/DFG intermediate representation and validates properties via Z3 SMT solver.
* **Dynamic Verification:** Invariant fuzzer running under standard EVM implementations (`revm`).
* **On-Chain Attestations:** Integrated with Chainlink Functions to query contract risk scores natively on-chain.
* *Tech Stack: Rust, Z3 SMT, revm, solang-parser, Chainlink Functions, Solidity*

#### 🛡️ [SentinelBridge](https://github.com/lvingsarcophagus/SentinelBridge)
*AI-powered cross-chain bridge security and auto-pause layer*
* **AI Risk Profiler:** Utilizes LLaMA-3.1-8B via Groq APIs for real-time threat classification of incoming transaction patterns.
* **Circuit Breakers:** Solidity 0.8.20 smart contracts that automatically halt bridges when AI confidence flags threat risks over 80%.
* Submitted to the **Chainlink Convergence Hackathon 2026** (Risk & Compliance track).
* *Tech Stack: Solidity, Go, Groq LLaMA-3.1-8B, Chainlink, Foundry*

#### 📊 [TokenomicsLab](https://tokenomiclab.app)
*Production DeFi analytics platform & risk quantification engine*
* **Scam Score Algorithmic Engine:** Quantifies risk by correlating liquidity locks, holder distributions, mint/burn triggers, and deployer behavior.
* **Architecture:** Robust multichain indexers feeding a dynamic dashboard UI. Built completely solo from zero to production.
* *Tech Stack: TypeScript, React, Next.js, Firebase, Firestore, Ethers.js*

#### 💳 [NovaPay](file:///c:/Users/nayan/OneDrive/Desktop/NJ_PROJ/theoretical_walkthrough.md)
*Unified Payment Orchestration Layer & routing engine*
* **Smart Routing Engine:** Runs deterministic decision trees based on geographic origin, payment method, fees, and real-time auth rates.
* **Architecture:** Full payment orchestration platform with auto-failover, fallback gateway routing, and structured Firestore transaction state logging.
* *Tech Stack: Next.js, Node.js, Firestore, Tailwind CSS, Stripe/Adyen APIs*

---

### 🛠️ Tooling & Tech Stack

| Domain | Technologies |
| :--- | :--- |
| **Languages** | ![Rust](https://img.shields.io/badge/Rust-EA4A1D?style=flat-square&logo=rust&logoColor=white) ![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white) |
| **Web3 & Auditing** | ![Foundry](https://img.shields.io/badge/Foundry-1E293B?style=flat-square) ![Hardhat](https://img.shields.io/badge/Hardhat-FFF100?style=flat-square&logo=hardhat&logoColor=black) ![Chainlink](https://img.shields.io/badge/Chainlink-375BD2?style=flat-square&logo=chainlink&logoColor=white) ![EVM](https://img.shields.io/badge/EVM-3C3C3D?style=flat-square&logo=ethereum&logoColor=white) `revm` `Z3 Solver` `Slither` `Mythril` |
| **Cybersecurity** | ![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white) ![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square&logo=metasploit&logoColor=white) ![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white) ![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white) ![Nmap](https://img.shields.io/badge/Nmap-214478?style=flat-square) `Adversary Simulation` `IDS/IPS` |
| **Backend & Infrastructure** | ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white) |

---

### 🎓 Education & Certifications

* **BSc in Information Systems and Cybersecurity** — Vilnius University (2022–2026) · *GPA 7.93/10*
* **Google Cybersecurity Certificate** — Google (Dec 2025)
* **Junior Cybersecurity Analyst Career Path** — Cisco (Aug 2025)

---

### 📊 GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=lvingsarcophagus&show_icons=true&theme=tokyonight&count_private=true" alt="GitHub Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=lvingsarcophagus&layout=compact&theme=tokyonight" alt="Top Languages" width="48%" />
</p>

---

### 📫 Contact & Collaborations

* 📧 **Email:** [nayanjoshymaniyathjoshy@gmail.com](mailto:nayanjoshymaniyathjoshy@gmail.com)
* 🌐 **Personal Website:** [livingsarcophagus.tech](https://livingsarcophagus.tech/)
* 💼 **Freelance Audits & DeFi Contracts:** Available for Web3 security audits, smart contract penetration testing, and secure Solidity/Rust development. Reach out via Email or my website.
