# Yeb Timotheous

**Post-Quantum Cryptographic Engineer & Distributed Systems Developer**
*Remote | yeb.timotheous@proton.me | Reddit: [u/yebtimothy](https://www.reddit.com/user/yebtimothy)*

Specializing in low-level implementations of NIST PQC standards (FIPS 203/204), SIMD-accelerated zero-knowledge provers, and consensus state execution engines.

---

## Active Repositories

### Post-Quantum & Cryptographic Engineering
* **[pq-dilithium-c](https://github.com/yebtimothy/pq-dilithium-c)** `C` — High-performance C implementation of the NIST ML-DSA (Dilithium) signature scheme optimized for execution speed.
* **[pqc-rpc-proxy](https://github.com/yebtimothy/pqc-rpc-proxy)** `Go` — Hybrid post-quantum TLS proxy securing validator JSON-RPC connections using native ML-KEM-768/X25519 key agreements.
* **[hybrid-hsm-enclave](https://github.com/yebtimothy/hybrid-hsm-enclave)** `C++` — HSM wallet enclave simulator using `mlock` page locking, guard pages (`mprotect`), and constant-time hybrid ECDSA/ML-DSA signature verification.
* **[bash-pqc-keygen](https://github.com/yebtimothy/bash-pqc-keygen)** `Go/Shell` — Automated local PQC key generation and root certificate authority (CA) utility suite.

### Zero-Knowledge & Consensus Systems
* **[lattice-zk-prover](https://github.com/yebtimothy/lattice-zk-prover)** `C++/OpenMP` — SIMD-parallelized polynomial commitment solver in negacyclic quotient rings $R_q = \mathbb{Z}_q[x] / (x^n + 1)$ for lattice-based ZK-provers.
* **[pqc-sig-aggregator](https://github.com/yebtimothy/pqc-sig-aggregator)** `Go` — Decoupled consensus signature aggregation simulator evaluating Merkle registries, bitmaps, and recursive ZK-SNARK pre-commit compressions.
* **[p2p-consensus](https://github.com/yebtimothy/p2p-consensus)** `Go` — Custom BFT consensus engine and libp2p networking stack optimized for larger PQC key payload propagation.

### Virtual Machines & Execution
* **[evm-c](https://github.com/yebtimothy/evm-c)** `C` — Lightweight, zero-dependency EVM state transition execution interpreter written in pure C.
* **[pqc-node-bench](https://github.com/yebtimothy/pqc-node-bench)** `Go` — Benchmark suite measuring validator throughput and network latency under post-quantum signature verification overhead.
* **[rollup-sequencer-sim](https://github.com/yebtimothy/rollup-sequencer-sim)** `Python` — Simulator evaluating modular rollup transaction-ordering policies (FIFO, PBS, MEV-Share).

---

## Active Research & R&D

* **[pq-hd-wallet](https://github.com/yebtimothy/pq-hd-wallet)** `C++` — Noise-stable Hierarchical Deterministic (HD) key derivation for lattice-based public keys (BIP-32 PQC extension) utilizing Secure Enclaves.
* **[goldilocks-simd-ntt](https://github.com/yebtimothy/goldilocks-simd-ntt)** `C++/AVX-512` — SIMD-vectorized Goldilocks field $\mathbb{F}_p$ ($p=2^{64}-2^{32}+1$) solver executing accelerated NTTs via Shoup reduction for L2 recursive provers.
* **[pq-threshold-mempool](https://github.com/yebtimothy/pq-threshold-mempool)** `C++` — Post-quantum threshold decryption engine (Threshold ML-KEM-768) utilizing noise-flooding and Lagrange interpolation to mitigate front-running (MEV) in validator pools.

---

## Technical Index

* **Languages**: C, C++, Go, Python, Assembly (x86_64 SIMD), Shell.
* **Systems**: POSIX Memory Management (`mlock`, `mprotect`), OpenMP, OpenSSL EVP, libp2p, Go Worker Pools.
* **Primitives**: ML-KEM-768, ML-DSA-65, ECDSA P-256/SECP256r1, negacyclic NTT, Goldilocks.
