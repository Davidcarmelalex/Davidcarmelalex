# Security Policy

## Supported Projects

This profile repository references several active projects under the Voltex Network / FCRI umbrella. Security disclosures for specific projects should be directed to those repositories. For cross-cutting or profile-level concerns, use the process below.

| Project | Security Contact |
|---------|-----------------|
| AZRAEL (Cyber Defense) | security@fcri.science |
| FCRI / NRLink | security@fcri.science |
| VoltexBazar | security@voltexbazar.io |
| All others | security@fcri.science |

## Reporting a Vulnerability

**Do not report security vulnerabilities through public GitHub issues.**

Please report security issues via email to **security@fcri.science** with:

1. A description of the vulnerability and affected component
2. Steps to reproduce or proof-of-concept (if possible)
3. Potential impact assessment
4. Your suggested remediation (optional)

You will receive an acknowledgment within **48 hours** and a status update within **7 days**.

## Disclosure Policy

We follow coordinated disclosure:

- Vulnerabilities are investigated and patched before public disclosure
- Reporters are credited (unless they prefer anonymity)
- We target a 90-day remediation window for critical issues

## Scope

In scope for responsible disclosure:

- Authentication and authorization flaws
- Data exposure or leakage
- Injection vulnerabilities (SQL, command, SSRF)
- Cryptographic weaknesses in AZRAEL or NRLink
- Logic flaws in financial settlement (NRLink / Web3 components)

Out of scope:

- Denial-of-service attacks
- Social engineering of team members
- Issues in third-party dependencies already publicly disclosed upstream
- Findings from automated scanners without demonstrated exploitability

## AZRAEL — Cyber Defense Platform

AZRAEL handles sensitive investigative workflows and evidence chains. Any potential vulnerability affecting evidence integrity, chain-of-custody (Proof-of-Justice), or investigative data confidentiality is treated as **Critical Priority** and escalated immediately.

## Bug Bounty

There is currently no formal bug bounty program. Exceptional security contributions may be recognized publicly and rewarded at our discretion.
