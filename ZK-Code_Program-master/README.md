# {ZK-Pay: An Anonymous Payment System Based on Zero-Knowledge Proof}

ZK-Pay is a secure and anonymous payment system using Zero-Knowledge Proofs to protect user privacy while enabling verifiable transactions in modern finance.

## Team Information
**Group:** [4]

**Members**

- Name: Nguyễn Văn Lâm
  - Discord Username: Lamnguyen103
  - Github Username: lamnv103
  - Role: Leader

- Name: Phạm Viết Chi Luân 
  - Discord Username: chiluan1511
  - Github Username: Luan1511
  - Role: member


## Technical Report

Problem Statement and Motivation
In the digital age, secure and private transactions are a critical concern, especially in decentralized finance (DeFi) and digital banking. Traditional payment systems often expose sensitive user information, such as sender and receiver identities, and transaction details. This lack of privacy can lead to surveillance, data leakage, and financial profiling. While blockchain-based systems provide transparency, they often fail to ensure anonymity.

Project Motivation
To address these challenges, ZK-Pay proposes an anonymous payment system leveraging Zero-Knowledge Proofs (ZKP) to protect transaction privacy while maintaining security and decentralization. Our system allows users to prove a valid transaction occurred without revealing any private information, ensuring both trust and confidentiality.

Approach and Solution
ZK-Pay applies the Zero-Knowledge Proof mechanism to allow users to transfer funds without exposing the sender’s, receiver’s identity, or transaction amount. The system works by generating cryptographic proofs that verify the transaction validity without revealing underlying data.

Key features:

Sender creates a ZK proof of the transaction

The network verifies the proof without knowing the actual data

Transactions are recorded anonymously on the blockchain

This ensures that all transactions are verifiable but completely private.

Technical Components
Circom: Used to design and compile the ZK circuits for transfer validation.

SnarkJS: Handles the generation and verification of zk-SNARK proofs.

Node.js + Express: Backend server to process transaction requests and proof generation.

ReactJS + TailwindCSS: Frontend interface for users to initiate private transfers.

MYSQL: Stores transaction metadata and user state securely (non-sensitive).

Zero-Knowledge Protocol: Applied for privacy-preserving computation.

Summary
ZK-Pay offers a practical solution for anonymous digital payments by integrating zero-knowledge proof technology. It empowers users to perform private, secure, and verifiable transactions, contributing to the evolution of privacy-first financial systems.

## Project Outcomes and Reflections

 Impact and Benefits of the Project
The project successfully delivers a decentralized, anonymous payment system leveraging Zero-Knowledge Proofs (ZKPs). It enhances privacy, protects user identity during transactions, and presents a scalable solution applicable in digital banking and DeFi ecosystems.

🔍 Key Insights and Notable Learnings
Throughout the development, we discovered the powerful flexibility of ZKP in preserving privacy while maintaining verifiability. It was especially fascinating to observe how cryptographic proofs could validate transactions without revealing any underlying data, opening doors for a new wave of secure financial applications.

⚠️ Challenges Encountered
We faced multiple technical challenges, including implementing ZK circuits efficiently, optimizing transaction speed, and ensuring system scalability. Overcoming these required deep exploration of tools like Circom, SnarkJS, and low-level cryptographic primitives. We also needed to balance between performance and proof size. These experiences deepened our understanding of applied cryptography and real-world blockchain integration.

💬 Reflections on Zero-Knowledge Proofs and Their Applications
ZKPs represent one of the most promising breakthroughs in secure computation and privacy-preserving systems. The ability to prove a statement without revealing any information is both intellectually elegant and practically revolutionary. From privacy in finance to anonymous voting systems and secure identity verification, the real-world applications of ZKPs are vast and impactful. We are excited about the potential and plan to further explore zk-SNARKs, zk-STARKs, and their role in building the future of trustless systems.



## References

zkSNARKs Explained – Vitalik Buterin’s article explaining zk-SNARKs

Zero-Knowledge Proofs — Introduction – Zcash’s guide to zk-SNARKs

circom Documentation – Official documentation for Circom circuit compiler

snarkjs Documentation – JavaScript library for zkSNARKs

ZK-Pay GitHub Source Code – Project repository

Ethereum & ZK-Rollups – Official Ethereum documentation on scaling with zk-rollups

Zero-Knowledge University Course – A course for learning ZK fundamentals

## Presentaion Slide
(https://www.canva.com/design/DAGukMEmdY4/sBEKaqWtfx9j1nq_Ik8DsA/edit?utm_content=DAGukMEmdY4&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

## Video Demo 

https://drive.google.com/file/d/1sjgNU9pGogpUaALqbKIVZ3HITdAITc16/view?usp=sharing