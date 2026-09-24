# Security Policy

The Federal Republic of Kabylia is committed to building sovereign, resilient, and secure public digital infrastructure. The safety of public services, citizen data, and institutional identity depends on rigorous security practices and open collaboration with the security community.

---

## 🛡️ Supported Versions

We actively maintain and support security updates for all official public repositories. Please ensure you are referencing or working with the latest main branch of any repository.

| Repository / Project Area | Security Support Status |
| ------------------------- | ----------------------- |
| `gov-portal`              | 🟢 Active Support        |
| `digital-identity`        | 🟢 Active Support        |
| `digital-infrastructure`  | 🟢 Active Support        |
| `standards`               | 🟢 Active Support        |
| `design-system`           | 🟢 Active Support        |
| Legacy / Archived Repos   | 🔴 Unsupported          |

---

## 🚨 Reporting a Vulnerability

**DO NOT report security vulnerabilities through public GitHub issues, discussions, or pull requests.**

If you discover a security vulnerability, configuration flaw, or potential threat affecting any repository or digital asset under this organization, please follow our coordinated disclosure process:

### How to submit a report

1. **GitHub Security Advisory (Preferred)**:
   - Navigate to the **Security** tab of the relevant repository.
   - Click on **Report a vulnerability** to submit a private advisory directly to the security team.

2. **Direct Security Contact**:
   - If private vulnerability reporting is unavailable, send an encrypted message or email to our security team at:  
     `security@kabylie-gouv.org`
   - Include `[SECURITY]` in the subject line.

### What to include in your report

To help us investigate and address the issue efficiently, please include:

- **Type of issue**: (e.g., authentication bypass, XSS, exposed secrets, dependency vulnerability, API misconfiguration).
- **Affected Repository / Asset**: URL or component name.
- **Steps to reproduce**: Clear instructions, proof-of-concept (PoC) code, or screenshots.
- **Impact Assessment**: Your estimate of the potential impact and severity.
- **Contact Info**: How we can reach you for follow-up or clarification.

---

## ⏱️ Response Timelines

Our security coordination team will review reports according to the following target response windows:

| Stage | Target Timeline |
| ----- | --------------- |
| Initial Response & Acknowledgment | Within 48 hours |
| Vulnerability Assessment & Triage | Within 5 business days |
| Remediation & Patch Release | Priority-based (Target: 14–30 days) |
| Public Disclosure Coordinated | After patch deployment |

---

## 🔒 Security Principles & Best Practices for Contributors

All contributors working on public repositories must adhere to the following principles:

1. **No Hardcoded Credentials**: Never commit secrets, private keys, API tokens, or internal credentials. Use environment variables and secrets management.
2. **Dependency Management**: Keep dependencies updated and minimize unnecessary third-party packages.
3. **Least Privilege**: Configure identity management and API permissions using strict principle of least privilege.
4. **Data Privacy**: No personal citizen data or sensitive operational telemetry should be committed to public repositories.

---

## 📜 Safe Harbor & Responsible Disclosure

We appreciate the efforts of security researchers who help protect public digital infrastructure. 

If you make a good-faith effort to comply with this policy during your security research:

- We will consider your research authorized and work collaboratively with you to validate and resolve the issue.
- We will not pursue legal action related to your security research.
- We ask that you give us reasonable time to resolve the issue before disclosing details publicly.

---

<p align="center">
  <em>Thank you for helping secure the public technology of the Federal Republic of Kabylia.</em>
</p>
