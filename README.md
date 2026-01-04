# Online Bank Web Application — System Security Project

This project was developed as part of a System Security course.
It analyzes security threats in online banking web applications
and proposes a secure protocol with authentication, encryption,
session protection, logging, and intrusion monitoring.

## 📌 Project Description

The report studies:
- Architecture of online banking web systems
- Security threats and attack scenarios
- Design requirements (functional + security)
- Threat analysis (confidentiality, integrity, authentication, availability, privacy)

A secure multi-layer protocol is proposed and implemented at a demo level.

## 🛡️ Security Mechanisms Used in the Design

- Two-Factor Authentication (password + OTP)
- RSA public / private key pairs
- Session key exchange
- AES-256 encryption for data confidentiality
- MAC / HMAC for message integrity
- Session timeout and protection against replay attacks
- Audit logging for activities and transactions
- Intrusion Detection alerts for abnormal behavior

## 🔗 Protocol Phases

1) System Initialization  
2) Authentication Phase  
3) Secure Session Establishment  
4) Transaction & Monitoring Phase

## 🧪 Implementation & Testing (Demo)

The implementation demonstrates:

- Normal login + OTP validation
- Encrypted fund transfer
- Replay-attack attempts with invalid MAC
- Multiple failed logins triggering IDS alerts

(It is a simplified client/server demonstration of the proposed protocol.)

## 📄 Project Document (PDF)

The full report includes:
- Related work summaries
- System model diagrams
- Threat analysis
- Protocol design
- Implementation screenshots
- Security analysis & mitigation

👉 Full PDF is included in this repository.
