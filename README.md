# Hi, I'm Yeb 👋

> **Remote** | **Post-Quantum Cryptography Researcher** | **Blockchain Systems Engineer**
>
> I design and build low-level blockchain infrastructure, consensus protocols, and post-quantum cryptographic systems. Currently focusing on hardware-accelerated lattice primitives (NIST PQC) and execution runtime optimization.

---

### 🛠️ Technical Stack & Languages

<p align="left">
  <img src="https://img.shields.io/badge/Go-%2300ADD8.svg?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/C-%23A8B9CC.svg?style=flat-square&logo=c&logoColor=black" alt="C" />
  <img src="https://img.shields.io/badge/OpenCL_(.cl)-%23E05243.svg?style=flat-square&logo=khronosgroup&logoColor=white" alt="OpenCL" />
  <img src="https://img.shields.io/badge/Python-%233776AB.svg?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Bash-%234EAA25.svg?style=flat-square&logo=gnu-bash&logoColor=white" alt="Bash" />
  <img src="https://img.shields.io/badge/Rust-%23000000.svg?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
</p>

---

### 🧬 Featured Work

#### ⚡ **[pq-dilithium-c](https://github.com/yebtimotheous/pq-dilithium-c)** (2.4k+ stars)
*High-performance C implementation of the NIST ML-DSA (Dilithium) signature scheme optimized for execution speed.*

#### 🌐 **[dilithium-cl](https://github.com/yebtimotheous/dilithium-cl)** (1.8k+ stars)
*OpenCL (`.cl`) kernel acceleration suite for parallel lattice-based key generation and high-throughput signature verification.*

#### ⛓️ **[p2p-consensus](https://github.com/yebtimotheous/p2p-consensus)** (2.1k+ stars)
*Custom BFT consensus engine and libp2p networking stack implemented in Go.*

#### 🐚 **[bash-pqc-keygen](https://github.com/yebtimotheous/bash-pqc-keygen)** (620+ stars)
*Shell utilities for generating and managing NIST-compliant PQ keys and certificate authorities locally.*

---

### 📐 Architectural Focus

#### 🔬 **Post-Quantum Cryptography & Hardware Acceleration**
- **NIST PQC Implementations**: Engineering lattice-based signature schemes, specifically **ML-DSA (Dilithium)** and **ML-KEM (Kyber)**.
- **GPU Acceleration**: Offloading bottleneck signature verifications using custom **OpenCL (`.cl`)** kernels.
- **Hybrid Security**: Deploying dual-signature wrappers linking classical ECDSA/Ed25519 with post-quantum algorithms.

#### ⛓️ **Consensus & P2P Networking**
- **State Machine Replication**: Designing custom BFT systems (CometBFT, HotStuff) tuned for PQC verification constraints.
- **Transport Engineering**: Optimizing P2P network topologies and frame buffers to handle larger PQ payloads over `libp2p`.

#### ⚙️ **Execution Engines & Runtimes**
- **Virtual Machine Design**: Optimizing state transition interpreters (EVM, WASM) using C/C++.
- **Storage Layer**: LevelDB and RocksDB performance tuning for state-trie updates.

---

### 🧪 Systems Projects

| Project | Stack | Description |
| :--- | :--- | :--- |
| **[dilithium-cl](https://github.com/yebtimotheous/dilithium-cl)** | OpenCL, C | Parallelized signature verification & lattice key gen kernels (`.cl`). |
| **[pq-dilithium-c](https://github.com/yebtimotheous/pq-dilithium-c)** | C, Assembly | Low-latency ML-DSA signature reference library. |
| **[p2p-consensus](https://github.com/yebtimotheous/p2p-consensus)** | Go, libp2p | Modular BFT consensus engine simulation. |
| **[rollup-sequencer-sim](https://github.com/yebtimotheous/rollup-sequencer-sim)** | Python | Transaction ordering simulator evaluating PBS and FIFO policies. |
| **[bash-pqc-keygen](https://github.com/yebtimotheous/bash-pqc-keygen)** | Bash, OpenSSL | Local post-quantum PKI and root certificate manager. |

---

### ✉️ Get in Touch

- 📬 **Email**: [yeb.timotheous@proton.me](mailto:yeb.timotheous@proton.me)
- 💬 **Telegram**: [@yebtimothy](https://t.me/yebtimothy)
- 💼 **LinkedIn**: [Yeb Timotheous](https://www.linkedin.com/in/yeb-timotheous/)
- 🐦 **Twitter**: [@yebtimothy](https://twitter.com/yebtimothy)
