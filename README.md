# pfSense VPN Configuration Lab

## Overview

This lab demonstrates the configuration of both IPsec and OpenVPN remote access VPNs within pfSense.

The project covers certificate creation, VPN tunnel configuration, firewall rule implementation, and secure remote access concepts. It was completed as part of a cybersecurity networking and VPN security lab.

## Objectives

- Configure a Certificate Authority (CA)
- Create VPN server certificates
- Configure an IPsec VPN tunnel
- Configure OpenVPN Remote Access
- Implement firewall rules
- Validate VPN functionality
- Understand limitations of VPN security

## Technologies Used

- pfSense
- OpenVPN
- IPsec
- SSL/TLS Certificates
- Certificate Authority (CA)
- Firewall Rules
- VPN Authentication

## Skills Demonstrated

- Network Security
- VPN Administration
- Firewall Configuration
- Certificate Management
- Remote Access Security
- Security Documentation
- Troubleshooting

---

# Part 1: IPsec VPN Configuration

## Certificate Authority Creation

<img width="2048" height="1152" alt="Screenshot 2026-06-02 at 11 49 39 AM" src="https://github.com/user-attachments/assets/8586c8d8-fde0-4216-a4fd-01874c4a0452" />


Created a Certificate Authority (CA) within pfSense to support VPN authentication.

## Server Certificate Creation

<img width="2048" height="1152" alt="Screenshot 2026-06-02 at 11 56 02 AM" src="https://github.com/user-attachments/assets/cbe80fc7-be64-4264-9277-42dc9e1f487a" />


Generated a server certificate for VPN communications.

## Mobile Client Configuration

<img width="2048" height="1152" alt="Screenshot 2026-06-02 at 12 06 52 PM" src="https://github.com/user-attachments/assets/4501d34a-09dc-4f49-8c30-3504d32bcdb2" />


Configured IPsec mobile client settings for remote connectivity.

## Phase 1 Configuration

<img width="2048" height="1152" alt="Screenshot 2026-06-02 at 12 13 58 PM(1)" src="https://github.com/user-attachments/assets/405e73f7-2927-4004-b3e7-67dd2276ffde" />


Configured IPsec Phase 1 settings including authentication and encryption parameters.

## Completed Tunnel

<img width="2048" height="1152" alt="Screenshot 2026-06-02 at 12 15 07 PM" src="https://github.com/user-attachments/assets/c2775769-8dea-4c23-a400-6e38cf232bcb" />


Successfully created and verified the IPsec tunnel.

---

# Part 2: OpenVPN Remote Access

## OpenVPN Certificate Authority

Created a dedicated Certificate Authority for OpenVPN.

## OpenVPN Server Certificate

<img width="2048" height="1152" alt="Screenshot 2026-06-02 at 12 59 03 PM" src="https://github.com/user-attachments/assets/fe4d0755-edfe-481a-968f-671d5217e61e" />


Configured the server certificate used by OpenVPN.

## Client Settings

<img width="2048" height="1152" alt="Screenshot 2026-06-02 at 1 03 16 PM" src="https://github.com/user-attachments/assets/5a8c699d-b9a9-4096-84a3-ba4cd10910aa" />

Configured OpenVPN remote access client settings.

## Firewall Configuration

<img width="2048" height="1152" alt="Screenshot 2026-06-02 at 1 10 41 PM" src="https://github.com/user-attachments/assets/05931b3a-0675-413e-a934-55fda4695c71" />


Created firewall rules allowing OpenVPN traffic.

## Completed Configuration

<img width="2048" height="1152" alt="Screenshot 2026-06-02 at 12 31 36 PM" src="https://github.com/user-attachments/assets/bbe8db8f-5a1c-45e0-872d-52df854a04d4" />


Successfully deployed and validated OpenVPN remote access.

---

# Security Discussion

## Why a VPN Is Not 100% Secure

A VPN encrypts network traffic and significantly improves privacy and security. However, no VPN solution is completely immune to compromise. Risks may still exist through:

- Malware infections
- Stolen credentials
- Software vulnerabilities
- Misconfigurations
- Compromised VPN infrastructure

VPNs reduce risk but should be combined with additional security controls such as MFA, endpoint protection, and strong password policies.

---

## Key Takeaways

This lab provided hands-on experience configuring enterprise VPN technologies using pfSense. The exercise reinforced concepts related to:

- Secure remote access
- Encryption
- Certificate-based authentication
- Firewall management
- Network security best practices<img width="2048" height="1152" alt="Screenshot 2026-06-02 at 11 49 39 AM" src="https://github.com/user-attachments/assets/0eeb91f4-b44b-4187-a301-1a59379d9647" />

