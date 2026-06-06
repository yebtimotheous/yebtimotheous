# Hi, I'm Yeb 👋

📍 **Remote** | 🔬 **Post-Quantum Cryptography Researcher** | 🚀 **Blockchain Systems Engineer**

Specializing in post-quantum cryptographic engineering, consensus protocol design, and low-level blockchain execution architectures. Focused on migrating distributed networks to quantum-resistant standards (NIST PQC).

![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![C](https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)

## Start Here

- 🧬 **[pq-dilithium-c](https://github.com/yebtimotheous/pq-dilithium-c)** (2.4k+ stars) - High-performance C implementation of the NIST ML-DSA (Dilithium) signature scheme optimized for execution speed
- ⚡ **[evm-c](https://github.com/yebtimotheous/evm-c)** (2.8k+ stars) - Lightweight EVM state execution engine written in C for high-speed local simulations
- ⛓️ **[p2p-consensus](https://github.com/yebtimotheous/p2p-consensus)** (2.1k+ stars) - Custom BFT consensus and libp2p networking stack implementation in Go
- 🐚 **[bash-pqc-keygen](https://github.com/yebtimotheous/bash-pqc-keygen)** (620+ stars) - Shell utilities for generating and managing NIST-compliant PQ keys and certificate authorities locally
- 🧪 **[pqc-node-bench](https://github.com/yebtimotheous/pqc-node-bench)** (1.2k+ stars) - Go-based benchmarking suite simulating validator network throughput with PQC signatures
- 🐍 **[rollup-sequencer-sim](https://github.com/yebtimotheous/rollup-sequencer-sim)** (980+ stars) - Python framework simulating different ordering policies (FIFO, PBS, MEV-Share) on rollups
- 🔒 **[pqc-rpc-proxy](https://github.com/yebtimotheous/pqc-rpc-proxy)** (1.8k+ stars) - Go-based hybrid post-quantum TLS proxy securing validator RPC connections using ML-KEM-768 key exchange
- 🛡️ **[hybrid-hsm-enclave](https://github.com/yebtimotheous/hybrid-hsm-enclave)** (1.4k+ stars) - Simulated HSM enclave API in C/C++ implementing constant-time hybrid ECDSA/ML-DSA key signatures
- 🧩 **[pqc-sig-aggregator](https://github.com/yebtimotheous/pqc-sig-aggregator)** (1.6k+ stars) - Decoupled signature compression and aggregation simulator in Go for ML-DSA validator payloads
- 🔬 **[lattice-zk-prover](https://github.com/yebtimotheous/lattice-zk-prover)** (1.9k+ stars) - Parallelized C++ math engine computing post-quantum lattice polynomial commitments for ZK proving systems

## Architectural Expertise & Sub-fields

### 1. Post-Quantum & Cryptographic Engineering
- **NIST PQC Standards**: Implementation and optimization of lattice-based signature algorithms, focusing on ML-DSA (Dilithium) and ML-KEM (Kyber).
- **Hybrid Cryptography**: Designing transition states for signature layers combining classical ECDSA/Ed25519 with post-quantum primitives.
- **TSS & Multi-Party Computation**: Adapting Threshold Signature Schemes (TSS) for post-quantum algorithms to secure distributed validator sets.

### 2. Consensus & P2P Networking
- **State Machine Replication**: Design and integration of BFT consensus engines (CometBFT, HotStuff) resilient to signature verification latency.
- **P2P Transport Protocols**: Optimizing libp2p packet sizes for larger post-quantum public keys and signatures.
- **Mempool Design**: Transaction propagation and priority fee markets optimized for larger payload sizes.

### 3. Execution Engines & Virtual Machines
- **Interpreter Architecture**: Low-level optimization of state transition interpreters (EVM, WASM) using C/C++.
- **State Access & Storage**: Performance tuning of key-value databases (RocksDB, LevelDB) for Merkle Patricia Trie lookups.
- **Gas Economics**: Designing predictable fee markets and execution gas meters.

### 4. Scaling & Layer 2 Architecture
- **Sequencer Design**: Building transaction-ordering services for modular rollups.
- **Data Availability**: Integration with DA networks (Celestia, EigenDA) to minimize off-chain transaction cost overhead.

## Selected Systems Projects

- 🧬 **[pq-dilithium-c](https://github.com/yebtimotheous/pq-dilithium-c)** - Highly optimized C library for ML-DSA (Dilithium) signatures, focusing on low-latency verification.
- ⚡ **[evm-c](https://github.com/yebtimotheous/evm-c)** - C implementation of the EVM execution spec, focusing on minimal memory footprint and fast opcode processing.
- ⛓️ **[p2p-consensus](https://github.com/yebtimotheous/p2p-consensus)** - Go-based custom BFT consensus engine and libp2p networking stack for validator block propagation.
- 🐚 **[bash-pqc-keygen](https://github.com/yebtimotheous/bash-pqc-keygen)** - Automation scripts for local PQC key pair generation, key encoding, and validation testing.
- 🧪 **[pqc-node-bench](https://github.com/yebtimotheous/pqc-node-bench)** - Go-based benchmarking suite simulating validator network throughput with PQC signatures.
- 🐍 **[rollup-sequencer-sim](https://github.com/yebtimotheous/rollup-sequencer-sim)** - Python framework simulating different ordering policies (FIFO, PBS, MEV-Share) on rollups.
- 🔒 **[pqc-rpc-proxy](https://github.com/yebtimotheous/pqc-rpc-proxy)** - Reverse proxy wrapping blockchain JSON-RPC nodes inside hybrid ML-KEM-768 / ECDH secure TLS tunnels.
- 🛡️ **[hybrid-hsm-enclave](https://github.com/yebtimotheous/hybrid-hsm-enclave)** - Secure memory enclaves (`mlock`) in C/C++ to verify hybrid classical/PQC signatures with constant-time security.
- 🧩 **[pqc-sig-aggregator](https://github.com/yebtimotheous/pqc-sig-aggregator)** - Go engine simulating consensus validator signatures aggregation to compress large lattice-based block payloads.
- 🔬 **[lattice-zk-prover](https://github.com/yebtimotheous/lattice-zk-prover)** - Optimized C++ solver using OpenMP thread parallelization to accelerate lattice-based polynomial commitment computations.

---

## Get in Touch

- 📬 **Email**: [yeb.timotheous@proton.me](mailto:yeb.timotheous@proton.me)
- 💬 **Telegram**: [@yebtimothy](https://t.me/yebtimothy)
- 💼 **LinkedIn**: [Yeb Timotheous](https://www.linkedin.com/in/yeb-timotheous/)
- 🐦 **Twitter**: [@yebtimothy](https://twitter.com/yebtimothy)
