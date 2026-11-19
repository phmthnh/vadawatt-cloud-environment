# Codex Agent Instructions

## 1. Project Overview
This repository supports the design, documentation, configuration development, and isolated testing of the secure network architecture for Building E, Electric Power University (EPU).

The project covers:
- Network topology and architecture
- IP addressing and VLAN planning
- Cisco router and switch configurations
- Firewall policies and access control lists
- VPN, RADIUS, and multi-factor authentication (MFA)
- Wi-Fi security and network access control
- Server Farm and Management Zone
- Network monitoring, logging, and security automation

## 2. Core Operating Principles
1. Read the available project documentation before proposing or making changes.
2. Never invent technical specifications, IP addresses, device models, survey results, or implementation status.
3. Clearly distinguish verified information, documented assumptions, design proposals, and tested results.
4. Identify inconsistencies between documents and report them without silently modifying the original data.
5. Request explicit approval before changing network topology, VLAN assignments, IP addressing, firewall rules, or security architecture.
6. Do not connect to, scan, exploit, or modify any real EPU network or device without explicit authorization.
7. Perform security testing only in isolated, authorized lab environments.
8. Never store credentials, passwords, API keys, private keys, or access tokens in the repository.
9. Validate generated configurations whenever appropriate tools are available.
10. Report test results, limitations, unresolved issues, and recommended next actions.

## 3. Agent Workflow
Analyze -> Plan -> Verify -> Request Approval -> Implement -> Test -> Report

## 4. Change Management
- Propose a plan before substantial modifications.
- Obtain approval before changing critical network configurations.
- Keep changes focused, reversible, and documented.
- Never deploy to production systems without authorization.
- Prefer separate Git branches and pull requests for substantive changes.

## 5. Documentation Policy
- Treat uploaded project documents as the primary project reference.
- Preserve the distinction between observed infrastructure and proposed infrastructure.
- Do not treat simulated results as evidence of real-world deployment.
- Flag missing evidence and conflicting technical information.
- Avoid committing sensitive institutional or personal information.

## 6. Automation and Testing
- Prefer reproducible scripts and automated validation.
- Use Python for network configuration analysis where appropriate.
- Test IP subnet calculations, VLAN mappings, and firewall policy consistency.
- Keep lab configurations separate from production configurations.
- Document required dependencies and verification commands.
