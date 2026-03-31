# Kenyan proptech system  — Kenyan Residential Property Management Platform

> A production-grade residential property management software system 
> built for the Kenyan market. Currently in the system design and 
> pre-development phase.

---

## Project Status

**Current Phase:** System Design, Architecture, and Pre-Development Research  
**Target Market:** Kenya (East African expansion planned)  
**Pri-development phase:** development timeline subject to resource availability .

---

## What This System Is

The Kenyan Proptech is a full-stack residential property management 
platform designed specifically for the Kenyan rental market. It addresses 
the gap between manual, fragmented property management practices common 
in Kenya today and the need for a secure, compliant, and intelligent 
digital management system.

The system serves five user roles: the System Administrator who maintains platform infrastructure and security, Property Owners who oversee their portfolios, Property Managers and Caretakers who handle daily operations, and Tenants who manage their tenancy — each with a purpose-built interface, dedicated dashboard, and strictly controlled access permissions enforced at three independent layers simultaneously.

---

## The Problem Being Solved

Kenya's residential rental market manages millions of tenants and 
landlords, yet most property management today relies on:

- Cash and informal M-Pesa transfers with no audit trail
- WhatsApp groups and phone calls for maintenance requests
- Manual spreadsheets for rent tracking and financial reporting
- No formal lease management or document storage
- No data protection compliance under the Kenya Data Protection Act 2019

Existing Kenyan property management platforms have begun addressing 
these problems, but gaps remain in full M-Pesa Daraja lifecycle 
integration, machine learning-based payment prediction, verifiable 
regulatory compliance, and offline-capable caretaker tooling.

---

## Core Features (Planned)

- **M-Pesa Daraja 3.0 Integration** — Full C2B Paybill collection, 
  automated payment matching, STK Push, and B2C refund processing
- **AI-Powered Assistant** — RAG architecture chatbot trained on 
  Kenyan residential property management context
- **Machine Learning Payment Prediction** — Per-tenant arrears risk 
  scoring built on platform transaction data
- **Offline-First Caretaker Mobile App** — Android application that 
  functions without internet and syncs when reconnected
- **Regulatory Compliance by Design** — Kenya Data Protection Act 2019, 
  ODPC registration, and OWASP Top Ten 2025 security standards built in 
  from the first line of code
- **Diaspora Property Owner Portal** — Multi-currency display and 
  time-zone-aware notifications for Kenyan property owners abroad
- **Digital Lease Management** — OTP-verified digital signatures with 
  full audit trail, legally sufficient under the Kenya Electronic 
  Transactions Act

---

## Technology Stack

| Layer | Technology |
|---|---|
| Frontend Web | React with TypeScript |
| Mobile | React Native (Android priority) |
| Backend | Node.js with Express or Python with FastAPI |
| Database | PostgreSQL with Row-Level Security |
| Authentication | Auth0 or AWS Cognito |
| File Storage | AWS S3 with KMS encryption (regulated docs) |
| AI and ML | RAG architecture with OpenAI or Anthropic API |
| Payments | M-Pesa Daraja 3.0 API |
| Infrastructure | AWS or Google Cloud Platform |
| CI/CD | GitHub Actions with Snyk security scanning |

---

## System Architecture

The system follows a modular monolith architecture with seven core modules:

1. User Management and Authentication
2. Property and Unit Management
3. Tenancy and Lease Management
4. Finance and Payment Management
5. Maintenance Management
6. Communication and Notifications
7. Compliance and Data  Governance 

Advanced capabilities including an AI-powered tenant assistant, 
machine learning payment prediction, diaspora property owner portal, 
and offline-first caretaker mobile tooling are built into the 
relevant modules above rather than operating as separate components.

Access control is enforced at three independent layers simultaneously: 
the user interface layer, the application logic layer, and the database 
layer using PostgreSQL Row-Level Security policies.

---

## Security Approach

Security is a design requirement, not an afterthought. 
The system is being built in full compliance with and 
defended against the following standards and frameworks 
from the first line of code:

- OWASP Top Ten 2025 — all ten vulnerability categories 
  addressed by design
- Kenya Data Protection Act 2019 — full compliance with 
  ODPC registration, consent management, data subject 
  rights, and breach notification requirements
- Central Bank of Kenya payment processing regulations — 
  compliant payment architecture for M-Pesa transaction handling
- PCI DSS v4.0 — payment data handling standards met through 
  compliant third-party payment processing
- JSON Web Token security with strict token revocation 
  mechanisms preventing unauthorized session continuation
- Multi-Factor Authentication enforced for all user account 
  roles without exception
- PostgreSQL Row-Level Security policies enforced at the 
  database engine level to prevent cross-portfolio data access

---

## Regulatory Compliance

The system is being designed to comply with:

- **Kenya Data Protection Act No. 24 of 2019** — ODPC registration, 
  consent management, data subject rights, and breach notification
- **National Payment System Act 2011** — CBK payment architecture 
  compliance
- **Rent Restriction Act (Cap 296)** — Lease template compliance
- **Kenya Electronic Transactions Act** — Digital signature validity
- **OWASP Top Ten 2025** — Full security coverage

---

## Current Repository Contents

- `/docs` — System design documents, architecture decisions, and 
  research foundation
- `/research` — Competitive landscape analysis, user research, and 
  Kenyan proptech market research
- `README.md` — This file

*Code repositories will be added when development begins.*

---

## About This Project

This system has been in research and planning since early 2026. 
The pre-development phase includes a full technical audit, competitive 
analysis, security threat modelling, regulatory compliance mapping, 
and iterative development roadmap.

The goal is not only to build a working system but to build one that 
is secure, legally compliant, and genuinely useful to Kenyan property 
managers, owners, and tenants from day one.

---

## Developer

**KENNETH CERUULO**  
Computer Science Student | Kenya  
Interested in proptech, fintech, secure system architecture, and 
building software that solves real African market problems.

[LinkedIn](https://www.linkedin.com/in/kenneth-ceruulo-dev) | kennethceruulo@gmail.com

---

*This project is in active pre-development. Architecture and feature 
decisions are being finalised before development begins.*
