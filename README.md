# Awesome-Decentralized-Identity

## Top Decentralized Identity (DID) Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Self-Sovereign Identity, Verifiable Credentials, Digital Wallets & Decentralized Identifiers*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Decentralized Identity (DID)**. These tools help organizations and individuals issue, hold, and verify tamper-proof digital credentials without relying on centralized identity providers—returning control of identity data to the user.



**Examples** include Spruce ID, Privado ID, Dock, Veramo, Affinidi, Fractal ID, Cheqd, Civic, Sphereon, and Polygon ID (the category leaders).



**Open-source emphasis**: Decentralized identity has a **rich and standards-driven open-source ecosystem** anchored by W3C specifications. **CREDEBL** is a Linux Foundation Decentralized Trust project and UN-endorsed Digital Public Good, used to build national digital ID infrastructure for the Royal Government of Bhutan and Papua New Guinea . **walt.id** provides an all-in-one Community Stack with Issuer, Verifier, and Wallet APIs supporting SD-JWT VC, W3C VC, and ISO 18013-5 mDL formats . **Veramo** is the open-source JavaScript framework successor to uPort, supporting multiple DID methods . The **swiyu** programme from the Swiss Confederation publishes its full trust infrastructure—wallets, issuer, verifier, and DID tooling—under open-source licences . This section documents these production-grade solutions.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Spruce ID](https://www.spruceid.com/)**

  Open-source W3C identity toolkit provider. Offers decentralized identity infrastructure and verifiable credential tooling for enterprises and governments .



- **[Privado ID](https://privado.id/)**

  Zero-knowledge identity protocol (formerly Iden3) with absolute data minimization. Built on Circom ZK circuits enabling mathematical privacy proofs—no personal data ever collected or stored by the protocol. Integrated with Polygon ecosystem. Open-source codebase with formal verification of cryptographic circuits .



- **[Dock](https://www.dock.io/)**

  Blockchain-based platform for issuing and verifying credentials with selective disclosure. Certs platform enables organizations to issue tamper-proof digital credentials. Built on Substrate blockchain with proof-of-stake consensus. Core credential verification is decentralized and user-controlled .



- **[Affinidi](https://www.affinidi.com/)**

  Decentralized identity and verifiable data platform. Provides tools for issuing, sharing, and verifying credentials with a focus on developer experience.



- **[Fractal ID](https://www.fractal.id/)**

  Decentralized identity and KYC platform for Web3. Provides reusable identity verification for DeFi, NFT, and blockchain applications.



- **[Cheqd](https://cheqd.io/)**

  Network for trusted data and decentralized identity. Provides infrastructure for issuing and verifying credentials with a focus on payment rails for trust.



- **[Civic](https://www.civic.com/)**

  Blockchain-based identity verification with user-controlled credential wallet. Civic Pass enables on-chain identity verification for DeFi, NFT, and Web3 without centralized biometric storage .



- **[Sphereon](https://sphereon.com/)**

  Decentralized identity and verifiable credential solutions. Provides SSI SDK, OID4VC modules, and wallet tooling for enterprises .



- **[Polygon ID](https://polygonid.com/)**

  Zero-knowledge identity protocol on Polygon. Enables users to interact with smart contracts using ZK proofs based on off-chain Verifiable Credentials, without revealing personal information .



## Open-Source GitHub Projects



### Full-Stack Identity Platforms



- **[CREDEBL](https://github.com/credebl/platform)**

  **Open-source Decentralized Identity & Verifiable Credentials Management Platform—a Linux Foundation Decentralized Trust project and UN-endorsed Digital Public Good.** Used to build the **Decentralized National Digital ID for the Royal Government of Bhutan and Papua New Guinea**, and the Sovio.id Platform by AYANWORKS . **Built on W3C DID and VC specifications**, with contributions from DIF, Trust over IP, Hyperledger Indy, and Aries. **Micro-services architecture** for population-scale SSI implementations. **Platform** provides scalable services for managing decentralized identity and VC systems. **Studio** is a web front-end built with Astro, React, Flowbite, and Tailwind CSS. **Aries Agent** uses Credo & ACA-Py for peer-to-peer interactions, with shared or dedicated agent options. **Mobile SDK** is a React-Native SDK for building SSI features into mobile apps. Supports **multiple ledger options** (Indy, Polygon) and **ledger-less issuance** (did:web, did:key, did:peer) .



- **[walt.id Community Stack](https://github.com/walt-id/waltid-identity)**

  **All-in-one open-source identity and wallet toolkit.** **Kotlin Multiplatform** libraries supporting Kotlin/Java, JavaScript, and more . **Three main APIs**: **Issuer API** (issue VCs and mdocs via OID4VCI); **Verifier API** (verify credentials via OID4VP); **Wallet API** (collect, store, manage, and share credentials). **White-label web applications**: Web Issuer, Web Verifier, Web Wallet (PWA) . **Credential formats supported**: SD-JWT VC (IETF), W3C Verifiable Credentials 1.1+ and 2.0, ISO 18013-5 mDL, and custom formats . **Protocols**: OID4VCI (Draft 11, 13, V1), OID4VP (Draft 14, 20, V1), ISO/IEC 18013-7 . **DID methods**: did:key, did:jwk, did:web, did:cheqd, and more . **Quick start with docker-compose** .



- **[swiyu (Swiss Confederation)](https://github.com/swiyu-admin-ch)**

  **Swiss Trust Infrastructure published under open-source licences.** Repositories span the full stack: **open-source Android and iOS wallets** for the Swiss e-ID; **Generic Verifier** for OID4VP credential verification; **Generic Issuer** for OID4VCI credential issuance; **DID Toolbox** for creating and managing DIDs; **DID Resolver** for did:tdw identifiers (Rust library with Java, Swift, Kotlin bindings) . **Documentation hub** with architecture overviews, cookbooks, and integration guides. **DIDAS** (Digital Identity and Data Sovereignty Association) provides ecosystem resources and Launchpad support .



- **[Cardano Foundation Identity Wallet](https://github.com/cardano-foundation/cf-identity-wallet)**

  **Open-source mobile application for securely storing, managing, and sharing identifiers and verifiable credentials.** Developed by the Cardano Foundation .



### Developer Frameworks & SDKs



- **[Veramo](https://github.com/uport-project/veramo)**

  **Open-source JavaScript framework for verifiable data and decentralized identity.** Successor to uPort . Built on **W3C DID and Verifiable Credentials standards**. **Zero biometric collection, no central server, no data retention**. Users control their own identity data stored exclusively in their own wallets. Supports **multiple DID methods** including did:web, did:key, and did:ethr. True self-sovereign identity .



- **[Sphereon SSI-SDK](https://github.com/Sphereon-Opensource/SSI-SDK)**

  **Self Sovereign Identity SDK** in TypeScript. Includes modules for **OID4VC** (issuers, holders, RPs), **SIOP-OID4VP**, and wallet capabilities . Actively maintained with recent pushes .



- **[Transmute](https://github.com/transmute-industries/transmute)**

  **Open-source Decentralized Identifiers and Verifiable Credentials infrastructure and tooling** .



### Wallets & Agents



- **[BCGov Traction](https://github.com/bcgov/traction)**

  **API-first architecture layered on Hyperledger Aries Cloud Agent Python (ACA-Py)** for sending and receiving digital credentials. Designed for governments and organizations .



- **[BCGov Aries VCR](https://github.com/bcgov/aries-vcr)**

  **Hyperledger Aries Verifiable Credential Registry (VCR)**—application-level software components to accelerate trustworthy entity-to-entity communications .



- **[impierce/identity-wallet](https://github.com/impierce/identity-wallet)**

  **A Tauri-based Identity Wallet for managing Decentralized Identities and Verifiable Credentials.** Rust-based .



- **[Procivis One Wallet](https://github.com/procivis/one-wallet)**

  **Digital wallet with eIDAS 2.0 compliancy, ISO 18013-5 mdocs, IETF SD-JWT VC, OID4VC, and W3C VCs** .



- **[Paradym Wallet](https://github.com/animo/paradym-wallet)**

  Seamlessly manage and present digital credentials .



### Additional Strong Open-Source Options



- **Full Platforms**: **CREDEBL** (Linux Foundation, Digital Public Good, national ID infrastructure) , **walt.id** (all-in-one Community Stack, multi-format) , **swiyu** (Swiss Confederation full stack) .

- **Developer Frameworks**: **Veramo** (JavaScript, self-sovereign) , **Sphereon SSI-SDK** (TypeScript, OID4VC modules) , **Transmute** (infrastructure tooling) .

- **Wallets**: **Cardano Foundation Identity Wallet** (mobile) , **impierce/identity-wallet** (Tauri/Rust) , **Procivis One Wallet** (eIDAS 2.0) , **Paradym Wallet** .

- **Agents**: **BCGov Traction** (ACA-Py API) , **BCGov Aries VCR** (registry) .



**Frameworks for building custom systems**: Combine **CREDEBL** for population-scale SSI platform with multi-ledger support, **walt.id Community Stack** for all-in-one issuer/verifier/wallet APIs with multi-format support, **Veramo** for JavaScript-based verifiable data frameworks, and **Sphereon SSI-SDK** for OID4VC protocol modules. Add **Hyperledger Indy** or **Polygon** for ledger anchoring, **PostgreSQL** for metadata persistence, and **Docker** for deployment.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Decentralized identity platforms handle sensitive identity and credential data; ensure compliance with GDPR, eIDAS, and applicable regional identity regulations.

- **Open-source reality**: The open-source ecosystem for decentralized identity is **mature and standards-driven**. **CREDEBL** is a Linux Foundation project and UN-endorsed Digital Public Good used for national digital ID infrastructure in Bhutan and Papua New Guinea . **walt.id** provides an all-in-one Community Stack supporting SD-JWT VC, W3C VC, and ISO 18013-5 mDL formats . **swiyu** from the Swiss Confederation publishes its full trust infrastructure under open-source licences . **Veramo** provides a true self-sovereign JavaScript framework with zero data retention . However, **commercial platforms** (Spruce ID, Privado ID, Dock, Affinidi) provide **managed infrastructure, enterprise support, and specialized tooling** that open-source alternatives require additional operational investment to match. The open-source path is **genuinely viable** for organizations building SSI solutions, particularly for government and public sector deployments.
