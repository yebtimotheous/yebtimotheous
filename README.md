# Yeb Timotheous

<p align="center">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 200" width="100%" height="200">
    <defs>
      <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" style="stop-color:#0f172a;stop-opacity:1" />
        <stop offset="50%" style="stop-color:#1e1b4b;stop-opacity:1" />
        <stop offset="100%" style="stop-color:#0f172a;stop-opacity:1" />
      </linearGradient>
      <linearGradient id="textGrad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" style="stop-color:#38bdf8;stop-opacity:1" />
        <stop offset="100%" style="stop-color:#818cf8;stop-opacity:1" />
      </linearGradient>
      <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
        <path d="M 40 0 L 0 0 0 40" fill="none" stroke="rgba(99, 102, 241, 0.04)" stroke-width="1"/>
      </pattern>
    </defs>
    
    <!-- Background -->
    <rect width="800" height="200" fill="url(#grad1)" rx="10"/>
    <rect width="800" height="200" fill="url(#grid)" rx="10"/>
    
    <!-- Decorative Glows -->
    <circle cx="100" cy="100" r="80" fill="#38bdf8" opacity="0.05" filter="blur(20px)" />
    <circle cx="700" cy="100" r="80" fill="#818cf8" opacity="0.05" filter="blur(20px)" />

    <!-- Code elements -->
    <text x="30" y="40" font-family="monospace" font-size="11" fill="#64748b" opacity="0.4">const engineer = { name: 'Yeb Timotheous', field: 'PQC &amp; Blockchain Systems' };</text>
    <text x="30" y="180" font-family="monospace" font-size="11" fill="#64748b" opacity="0.4">import { dilithium, kyber } from '@pqc/nist-standards';</text>

    <!-- Main Typography -->
    <text x="50" y="105" font-family="system-ui, -apple-system, sans-serif" font-weight="800" font-size="34" fill="url(#textGrad)">YEB TIMOTHEOUS</text>
    <text x="50" y="140" font-family="system-ui, -apple-system, sans-serif" font-weight="500" font-size="15" fill="#94a3b8" letter-spacing="1.5">PQC RESEARCHER &amp; SYSTEMS ENGINEER</text>
    
    <!-- Status Tag -->
    <g transform="translate(620, 25)">
      <rect width="150" height="26" rx="13" fill="#1e293b" stroke="#334155" stroke-width="1"/>
      <circle cx="18" cy="13" r="4" fill="#10b981"/>
      <text x="32" y="17" font-family="system-ui, -apple-system, sans-serif" font-size="11" font-weight="600" fill="#e2e8f0">Active in Research</text>
    </g>
  </svg>
</p>

### 📜 Professional Summary

I design and build low-level blockchain infrastructure, consensus protocols, and post-quantum cryptographic systems. Currently focusing on hardware-accelerated lattice primitives (NIST PQC) and execution runtime optimization.

---

### ⚡ Technical Ledger

| Category | Technologies & Tools |
| :--- | :--- |
| **Languages & Kernels** | Go, C, OpenCL (`.cl`), Python, Bash, Rust |
| **PQC Standards** | ML-DSA (Dilithium), ML-KEM (Kyber), SPHINCS+, Falcon |
| **Consensus & P2P** | CometBFT, HotStuff, Raft, `libp2p`, `devp2p` |
| **Execution & VM** | EVM (Ethereum Virtual Machine), WASM, RocksDB, LevelDB |
| **Scaling & L2** | Modular Sequencers, Data Availability (Celestia, EigenDA) |

---

### 🔬 Post-Quantum & Cryptographic Engineering

- **NIST PQC Implementations**: Engineering lattice-based signature schemes, specifically **ML-DSA (Dilithium)** and **ML-KEM (Kyber)**.
- **GPU Acceleration**: Offloading bottleneck signature verifications using custom **OpenCL (`.cl`)** kernels.
- **Hybrid Security**: Deploying dual-signature wrappers linking classical ECDSA/Ed25519 with post-quantum algorithms.
- **TSS & MPC**: Adapting Threshold Signature Schemes (TSS) for post-quantum algorithms to secure distributed validator sets.

---

### 🛠️ Selected Engineering Achievements

#### 1. dilithium-cl (GPU PQC Accelerator)
*OpenCL kernel acceleration suite for parallel lattice-based key generation and high-throughput signature verification.*
- Offloaded bottleneck signature verifications using custom OpenCL (`.cl`) kernels.
- Achieved significant execution speedups for batch transaction verification in high-throughput environments.
- Optimized memory layout to fit GPU threads and minimize overhead.

#### 2. evm-c (Execution Interpreter)
*Lightweight EVM state execution engine written in C for high-speed local simulations.*
- Designed a custom stack and gas-metering interpreter focusing on minimal memory footprint and fast opcode processing.
- Optimized state storage lookups using LevelDB integrations.
- Created a pipeline for contract deployment testing without starting full node nodes.

#### 3. p2p-consensus (Go Networking & Consensus Engine)
*Custom BFT consensus and libp2p networking stack implementation in Go.*
- Evaluated performance of BFT consensus engines (CometBFT) when signature payloads are increased to post-quantum sizes.
- Configured dynamic gas adjustment based on verification times.
- Optimized node transport buffers to minimize congestion under heavy verification loads.

---

### 📊 Github Metrics

<p align="center">
  <img src="https://bad-apple-github-readme.vercel.app/api?username=yebtimotheous&show_icons=true&count_private=true&line_height=20&icon_color=38bdf8&theme=dark&title_color=38bdf8" height="150" alt="Github Stats" />
  <img src="https://github-readme-mwendwa.vercel.app/api/top-langs/?username=yebtimotheous&layout=compact&count_private=true&theme=dark&title_color=38bdf8" height="150" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=yebtimotheous&count_private=true&theme=dark&title_color=38bdf8" alt="Streak Stats" />
</p>

---

### ✉️ Get in Touch

<p align="left">
  <a href="mailto:yeb.timotheous@proton.me"><img alt="Email" src="https://img.shields.io/badge/ProtonMail-8B89CC?style=for-the-badge&logo=protonmail&logoColor=white" /></a>
  <a href="https://wa.me/233208562771"><img alt="WhatsApp" src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/yeb-timotheous/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://twitter.com/yebtimothy"><img alt="Twitter" src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" /></a>
  <a href="https://t.me/yebtimothy"><img alt="Telegram" src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" /></a>
</p>
