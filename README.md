# zkID Wallet 

Welcome to the official GitHub Organization for **zkID Wallet** — a cutting-edge project that combines **privacy, compliance, and decentralization** in blockchain transactions through **Zero-Knowledge Proofs** and **eIDAS digital signatures**.

> This project was originally developed as a university thesis and hosted at [paolo9921/zkCF_Wallet](https://github.com/paolo9921/zkCF_Wallet).  
> It now continues its evolution within this organization to foster collaboration, modularization, and broader community adoption.
---

## 🌍 Mission

We aim to build a **new paradigm for digital identity and secure blockchain transactions** by integrating advanced cryptographic techniques (ZKPs) with legally recognized identity frameworks (eIDAS). Our vision is to enable **privacy-preserving yet compliant on-chain interactions**, empowering users to maintain control over their data without sacrificing security or regulatory requirements.

---

## 🔐 What is zkCF Wallet?

**zkID Wallet** is an Ethereum-based wallet system that allows users to:
- Authenticate transactions using their **national identity id** (e.g., Italian *Codice Fiscale*).
- Sign operations via **eIDAS-compliant digital signatures** (e.g., CIE).
- Maintain **self-sovereign control** over assets without managing private keys directly.
- Leverage **Zero-Knowledge Proofs (ZKPs)** to ensure data privacy and reduce on-chain gas costs.
- Achieve **eIDAS and GDPR compliance** through off-chain signature verification.

The system uses:
- **RISC Zero zkVM** to verify digital signatures off-chain.
- **Bonsai proving service** to generate cryptographic proofs efficiently.
- **Smart contracts in Solidity** to verify ZKPs and manage Ethereum transactions securely.

---

## 🏗️ Architecture Overview

The project architecture is composed of three core layers:
1. **Application Layer** (Rust CLI + Libraries)
2. **zkVM Layer** (RISC Zero guest program for signature verification)
3. **Smart Contracts** (Solidity contracts for proof verification and fund transfers)

> Zero-knowledge computation ensures that verification is cryptographically proven without revealing the input (e.g., your identity or the content of your signature).

---

## 📦 Repositories

This organization contains modular components to promote reusability and scalability:
- [`zkID_Wallet`](https://github.com/zkIDWallet/zkID_Wallet) — Main wallet logic and application
- [`CMS_Parser`](https://github.com/zkIDWallet/cms-pkcs7-parser) — Independent library for parsing PKCS#7 digital signatures

---

## ✨ Why it matters

- ✅ **Legal Compliance**: Aligns with eIDAS standards for digital identity.
- 🔐 **Data Privacy**: Protects user identity and PII through ZKPs and off-chain computation.
- ⚡ **Gas Optimization**: Minimizes on-chain verification costs.
- 🧱 **Modular Architecture**: Enables broader integration (e.g., ERC-4337, Layer 2s, etc).
<!--- 📈 **Real Impact**: Demonstrated on Sepolia testnet with working proof-of-concept.-->

---

## 💡 Contributing

We are actively expanding this project and contribution are welcome

Start by checking the [open issues](https://github.com/zkIDWallet/zkID_Wallet/issues) and feel free to fork, suggest features, or start a discussion.

---

## 🔭 Future Roadmap

<!--- [ ] Layer 2 integration (ZK-Rollups)-->
- [ ] CA registry optimization with Merkle Trees
- [ ] Proof batching and gas cost minimization
- [ ] zkID Wallet GUI
- [ ] ERC-4337 account abstraction integration

---

## 🧠 Background & References

- 🔗 [eIDAS Regulation (EU)](https://eur-lex.europa.eu/eli/reg/2014/910/oj)
- 🔗 [RISC Zero zkVM](https://www.risczero.com/)
- 🔗 [RFC 5652 - Cryptographic Message Syntax (CMS)](https://datatracker.ietf.org/doc/html/rfc5652)
- 🔗 [EIP-4337 - Account Abstraction](https://eips.ethereum.org/EIPS/eip-4337)

---

## 🤝 Let's build a privacy-first future.

> *“In a world where users are the product, zkID Wallet reclaims digital identity ownership.”*

---

<!--© zkID Wallet Organization – Founded by [Paolo Moser](https://github.com/paolo9921)-->
