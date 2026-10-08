# BalticTrust Bank — IT Environment

## 1. Overview

BalticTrust Bank operates a hybrid IT environment supporting digital banking, payment processing, customer management, security operations and internal business functions.

The technology environment consists of business applications, infrastructure, security systems, employee endpoints, cloud services and ICT third-party providers.

---

## 2. IT Environment Architecture

The main technology components are organized into the following areas:

1. Customer-facing applications
2. Core banking systems
3. Payment infrastructure
4. Identity and access management
5. Security infrastructure
6. IT infrastructure
7. Data and backup infrastructure
8. Employee endpoints
9. Cloud and SaaS services
10. ICT third-party services

---

## 3. Customer-Facing Systems

### Online Banking Platform

The online banking platform provides customers with access to:

- Account information
- Account transfers
- Payment services
- Transaction history
- Customer profile management

**Criticality:** Critical

---

### Mobile Banking Application

The mobile application provides customers with:

- Account access
- Payment functionality
- Transaction monitoring
- Authentication
- Account management

**Criticality:** Critical

---

## 4. Core Banking System

The Core Banking System is the primary system responsible for managing:

- Customer accounts
- Account balances
- Transactions
- Customer information
- Banking products
- Financial records

**Criticality:** Critical

A disruption or compromise of the core banking system could significantly affect the organization's ability to provide banking services.

---

## 5. Payment Processing System

The payment processing environment supports:

- SEPA payments
- Domestic transfers
- Card transactions
- Payment validation
- Transaction processing

**Criticality:** Critical

---

## 6. Identity and Access Management

The identity and access management environment includes:

- Active Directory
- User accounts
- Privileged accounts
- Authentication mechanisms
- Multi-factor authentication
- Role-based access control

Identity management is considered a critical security capability because compromise of privileged accounts could provide unauthorized access to multiple systems.

---

## 7. Security Infrastructure

BalticTrust Bank uses several security technologies.

### SIEM

The Security Information and Event Management platform collects and analyzes security events from:

- Servers
- Network devices
- Applications
- Authentication systems
- Security tools

**Purpose:** Security monitoring and threat detection.

---

### Endpoint Detection and Response

EDR provides endpoint monitoring and detection capabilities for employee workstations and servers.

**Purpose:**

- Malware detection
- Suspicious activity detection
- Endpoint investigation
- Incident response

---

### Vulnerability Management

The vulnerability management platform is used to:

- Identify vulnerabilities
- Prioritize vulnerabilities
- Track remediation
- Generate vulnerability reports

---

### Network Security

The network security environment includes:

- Firewalls
- Network segmentation
- VPN infrastructure
- Intrusion detection/prevention
- Network monitoring

---

## 8. IT Infrastructure

The infrastructure environment includes:

- Application servers
- Database servers
- Authentication servers
- Network infrastructure
- Storage systems
- Virtualization infrastructure
- Cloud infrastructure

Infrastructure supports the organization's business applications and security services.

---

## 9. Backup and Disaster Recovery

The organization maintains backup infrastructure for critical systems and data.

Backup capabilities include:

- Database backups
- Application backups
- Configuration backups
- Security log backups
- Critical data recovery

A disaster recovery environment is maintained to support recovery of critical banking services following major disruptions.

---

## 10. Employee Endpoints

Employee technology includes:

- Corporate laptops
- Desktop computers
- Administrator workstations
- Mobile devices

Endpoints are protected through:

- Endpoint security
- Device management
- Security policies
- Authentication controls
- Security monitoring

---

## 11. Cloud and SaaS Services

BalticTrust Bank uses cloud and Software-as-a-Service platforms for selected business and technology functions.

Examples include:

- Cloud infrastructure
- Corporate email
- Customer relationship management
- Security services
- Collaboration platforms

Cloud and SaaS providers are subject to ICT third-party risk management.

---

## 12. ICT Third-Party Environment

The organization depends on external ICT providers for several critical services.

| Provider ID | Provider Category | Service | Criticality |
|---|---|---|---|
| TP-001 | Cloud Provider | Cloud Infrastructure | Critical |
| TP-002 | Payment Provider | Payment Processing | Critical |
| TP-003 | SaaS Provider | CRM | High |
| TP-004 | Security Provider | Security Monitoring | High |
| TP-005 | Communication Provider | Corporate Email | Medium |

---

## 13. Major Technology Components

| Component ID | Component | Category | Criticality |
|---|---|---|---|
| IT-001 | Core Banking System | Application | Critical |
| IT-002 | Online Banking Platform | Application | Critical |
| IT-003 | Mobile Banking Application | Application | Critical |
| IT-004 | Payment Processing System | Application | Critical |
| IT-005 | Active Directory | Identity | Critical |
| IT-006 | SIEM | Security | High |
| IT-007 | EDR Platform | Security | High |
| IT-008 | Vulnerability Management Platform | Security | High |
| IT-009 | Firewall Infrastructure | Network Security | Critical |
| IT-010 | Backup Infrastructure | Resilience | Critical |
| IT-011 | CRM Platform | Application | High |
| IT-012 | Corporate Email | SaaS | Medium |
| IT-013 | Employee Laptops | Endpoint | High |
| IT-014 | Database Infrastructure | Infrastructure | Critical |
| IT-015 | Network Infrastructure | Infrastructure | Critical |

---

## 14. Security Monitoring

Security monitoring is performed through a centralized security monitoring capability.

The Security Operations Center (SOC) is responsible for:

- Security event monitoring
- Alert investigation
- Threat detection
- Incident escalation
- Security incident response
- Security reporting

---

## 15. Critical Dependencies

Several business services depend on multiple technology components.

For example:

### Online Banking

```text
Customer
   ↓
Online Banking Platform
   ↓
Identity & Access Management
   ↓
Core Banking System
   ↓
Database
   ↓
Network Infrastructure
