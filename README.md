# Diego Bertola
**Applied Cryptography & Security Researcher**

I am a Computer Science researcher focusing on **Provable Security**, **Formal Verification**, and **End-to-End Encryption (E2EE)** architectures. My work bridges the gap between mathematical protocol modeling and low-level source code auditing. 

Currently pursuing an MSc in Cybersecurity at Università degli Studi di Torino, with the goal of advancing research in Applied Cryptography and Post-Quantum protocols.

---

### 🔬 Featured Research

**[Verification and Analysis of Stick Protocol (Signal-based E2EE)](#)** *(Under Embargo / Coordinated Disclosure)*
Conducted a complete formal verification and source-level audit of an E2EE protocol designed for social networks.
* **Formal Methods:** Authored 10 models in **ProVerif** (translated and hardened from Verifpal) to test correspondence and secrecy properties under Dolev-Yao attacker models.
* **Key Finding:** Designed a causal protocol ablation demonstrating that forward secrecy in the X3DH handshake critically depends on the $DH_4$ term, a property violated in the implementation.
* **Code Audit:** Audited the cryptographic implementations across Android (Java), iOS (Swift), and Server (Python/Django) components, discovering **11 High-Severity zero-days** (including deterministic key/IV reuse and ciphertext splicing).

---

### ⚔️ Offensive Security & Cryptanalysis
* **Applied Cryptanalysis:** Active solver on [CryptoHack (@sdigs)](https://cryptohack.org/user/sdigs/), tackling advanced challenges in mathematics, symmetric ciphers, and public-key cryptography.
* **CyberChallenge.IT Alumni:** Competed in Italy's premier cybersecurity training program, specializing in Cryptography and Binary Exploitation (Pwn).
* **Exploitation Tooling:** Developed custom exploits and scripts for cryptographic attacks (RSA, AES, Diffie-Hellman), buffer overflows, and binary reversing. 
* **Core Stack:** `C`, `Python`, `x86_64 Assembly`, `Pwntools`, `GDB (pwndbg)`, `IDA Pro`, `Burp Suite`, `Wireshark`.

---

### ⚙️ Current Focus & Tooling
* **Formal Verification:** `ProVerif` (Current) ➔ Migrating to `Tamarin Prover` for state-aware modeling.
* **Applied Crypto:** Game-based cryptographic proofs, Lattice-based cryptography (PQC / LWE).
* **System Environment:** `Arch Linux` / `Ubuntu` multi-boot, heavily customized CLI workflows (`Zsh`, `Starship`).

📫 **Reach out:** [diego.bertola@edu.unito.it](mailto:diego.bertola@edu.unito.it)


