# Contributing to the Federal Republic of Kabylia Digital Ecosystem

Thank you for your interest in contributing to the official digital infrastructure of the Federal Republic of Kabylia. This project relies on open collaboration, technical rigor, and civic engagement to build transparent, resilient, and sovereign digital tools for public interest.

---

## 📜 Code of Conduct

By participating in this project, you agree to maintain a constructive, inclusive, and professional environment.

- **Respect and Civility**: Focus on constructive technical discussion, collaboration, and mutual respect.
- **Public Interest**: Contributions must prioritize public safety, digital accessibility, and user privacy.
- **Integrity**: Malicious code, intentional vulnerabilities, spam, or disruptive behavior will result in an immediate block.

---

## 🛠️ How You Can Contribute

Contributions are welcome across technical and non-technical fields:

### 1. Code & System Engineering
- Develop and maintain public web applications (`gov-portal`, `design-system`).
- Implement secure protocols for digital identity and open standards (`digital-identity`, `standards`).
- Optimize performance, write unit tests, and improve developer experience.

### 2. Design & User Experience
- Improve UI components in accordance with WCAG 2.1 accessibility guidelines.
- Refine brand assets, vector graphics, and design token libraries (`brand-assets`).

### 3. Localization & Language Support
- Translate interfaces, documentation, and metadata across **Kabyle**, **French**, and **English**.
- Help standardize digital and technological terms in Kabyle (`kabyle-language`).

### 4. Cybersecurity & Policy
- Audit repositories and help improve resilience strategies (`security-policy`).
- Review legal and administrative data formats for interoperability (`constitution`, `official-journal`).

---

## 🔄 Contribution Workflow

### Step 1: Pick or Create an Issue
Before submitting code:
- Check existing issues in the relevant repository.
- Look for `good first issue` or `help wanted` tags.
- If proposing a major feature or restructuring, open a new issue to discuss it first.

### Step 2: Fork and Branch
1. Fork the target repository to your GitHub account.
2. Create a dedicated feature or bugfix branch:
   ```bash
   git checkout -b feat/add-kabyle-translation
   # or
   git checkout -b fix/navigation-menu-overflow
   ```

### Step 3: Commit Format
Write clear, descriptive commit messages following the Conventional Commits convention:
- `feat: add multilingual toggle to gov-portal navigation`
- `fix: resolve color contrast issue in design-system buttons`
- `docs: update API setup instructions in standards repo`

### Step 4: Submit a Pull Request (PR)
1. Ensure your code passes all linting and test suites.
2. Push your branch to GitHub and create a Pull Request to the main repository.
3. Complete the PR template, describing your changes and referencing related issues (e.g., `Closes #12`).
4. Maintainers will review your PR and provide feedback if adjustments are required.

---

## 🔒 Security Vulnerabilities

Security is crucial for state digital public infrastructure.

> **DO NOT open public GitHub issues for security vulnerabilities.**

To report security concerns, please refer to the security policy inside the [`security-policy`](https://github.com/Federal-Republic-of-Kabylia/security-policy) repository or contact our security coordination team as specified in that repository.

---

## 📄 Licensing & Sign-off

By contributing to any repository within the **Federal Republic of Kabylia** organization, you agree that your contributions will be licensed under the open-source license governing that repository (e.g., MIT, Apache 2.0, or CC-BY 4.0 for legal/textual assets).

All commits must include a Developer Certificate of Origin (DCO) sign-off line:

```text
Signed-off-by: Your Name <your.email@example.com>
```

*(You can automatically sign your commits using `git commit -s`)*.
