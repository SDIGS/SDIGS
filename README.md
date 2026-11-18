# Diego Bertola
**Applied Cryptography & Security Researcher**

<div align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white" alt="Swift" />
  <img src="https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white" alt="Arch Linux" />
  <img src="https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white" alt="Burp Suite" />
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" alt="Wireshark" />
</div>
<br>

I am a Computer Science researcher focusing on **Provable Security**, **Formal Verification**, and **End-to-End Encryption (E2EE)** architectures. My work bridges the gap between mathematical protocol modeling and low-level source code auditing. 

I hold a BSc in Computer Science from the University of Turin (110/110 cum laude), earned with a thesis on formal verification and security auditing of E2EE protocols. Currently pursuing an MSc in Cybersecurity, continuing research in Applied Cryptography and Post-Quantum protocols.

---

### 🔬 Featured Research

**[Verification and Analysis of Stick Protocol (Signal-based E2EE)](https://github.com/SDIGS/stick-protocol)** *(Under Embargo / Coordinated Disclosure)*  
Conducted a complete formal verification and source-level audit of an E2EE protocol designed for social networks.
- **Formal Methods:** Authored 10 models in **ProVerif** (translated and hardened from Verifpal) to test correspondence and secrecy properties under Dolev-Yao attacker models.
- **Key Finding:** Designed a causal protocol ablation demonstrating that forward secrecy in the X3DH handshake critically depends on the $DH_4$ term, a property violated in the implementation.
- **Code Audit:** Audited the cryptographic implementations across Android (Java), iOS (Swift), and Server (Python/Django) components, identifying **11 High-Severity findings**, reported to the maintainer under a 90-day coordinated-disclosure window (technical detail withheld until the embargo lifts).

---

### ⚔️ Offensive Security & Cryptanalysis
- **Applied Cryptanalysis:** Active solver on [CryptoHack (@sdigs)](https://cryptohack.org/user/sdigs/), tackling advanced challenges in mathematics, symmetric ciphers, and public-key cryptography.
- **CyberChallenge.IT Alumni:** Competed in Italy's premier cybersecurity training program, specializing in Cryptography and Binary Exploitation (Pwn).
- **Exploitation Tooling:** Developed custom exploits and scripts for cryptographic attacks (RSA, AES, Diffie-Hellman), buffer overflows, and binary reversing. 
- **Core Stack:** `C`, `Python`, `x86_64 Assembly`, `Pwntools`, `GDB (pwndbg)`, `IDA Pro`, `Burp Suite`, `Wireshark`.

---

### ⚙️ Current Focus & Tooling
- **Formal Verification:** `ProVerif` (Current) ➔ Migrating to `Tamarin Prover` for state-aware modeling.
- **Applied Crypto:** Game-based cryptographic proofs, Lattice-based cryptography (PQC / LWE).
- **System Environment:** `Arch Linux` / `Ubuntu` multi-boot, heavily customized CLI workflows (`Zsh`, `Starship`).
