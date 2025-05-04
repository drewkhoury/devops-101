# 🧰 Docker for Software Development

| Project | Description | Link |
|---------|-------------|------|
| **DevOps 101** | A foundational guide for DevOps practices | [GitHub](https://github.com/drewkhoury/devops-101) |
| **Software for Mac** | Personal desktop setup and tools for macOS | [GitHub](https://github.com/drewkhoury/desktop-setup) |
| **Docker 101 with Python App** | Beginner Docker example with a simple Python app | [GitHub](https://github.com/drewkhoury/docker) |
| **Static Site with AWS CDK (Python)** | S3, CloudFront, and Route53 deployment with containerized workstation | [GitHub](https://github.com/drewkhoury/static-site) |
| **Containerized AWS CDK (TypeScript)** | AWS CDK setup using Docker and the 3 Musketeers pattern | [GitHub](https://github.com/drewkhoury/aws-cdk-typescript-3-musketeers) |
| **GSD Hello World (Golang + Docker)** | Example Golang app wrapped in Docker for good software delivery practices | [GitHub](https://github.com/drewkhoury/gsd-hello-world) |
| **GCP Dev Container** | Google Cloud SDK container with extended libraries for GAE local dev | [GitHub](https://github.com/drewkhoury/gcp-dev) |
| **Golang App** | Basic "Hello World" Golang application | [GitHub](https://github.com/drewkhoury/hello-world-go) |
| **Communities Framework** | Framework and example repo to build your own online community | [GitHub](https://github.com/drewkhoury/communities) |
| **3 Musketeers Python App** | Dockerized Python app using a Makefile and 3 Musketeers setup | [GitHub](https://github.com/drewkhoury/3-musketeers-base) |
| **GAE with Docker** | Google App Engine example deployed using Docker | [GitHub](https://github.com/drewkhoury/gae-demo) |
| **3 Musketeers Master Class** | Explanation and demo of the 3 Musketeers pattern with Docker | [GitHub](https://github.com/drewkhoury/3musketeers-master-class) |
| **Container Security** | Docker container security examples and best practices | [GitHub](https://github.com/drewkhoury/container-security) |

---

# 🔐 Security, and other Tools for the Modern Software Delivery Pipeline

A curated list of key tools for integrating security and best practices into software pipelines.

### 🛡️ Snyk
- **What it does**: Developer-first platform for SAST, SCA, container, and IaC security.
- **Why it's good**: Actionable remediation, Git/CI/CD/IDE integrations, great developer experience.
- **Security features**: SAST, open source CVE scanning, policy gates, license checks, auto-fix.
- **Link**: [https://snyk.io](https://snyk.io)

---

### 🚩 LaunchDarkly
- **What it does**: Enables progressive delivery, kill switches, and targeting.
- **Why it's good**: Control rollout of risky code, minimize blast radius.
- **Security features**: Role-based access, audit logs, encryption, quick rollbacks.
- **Link**: [https://launchdarkly.com](https://launchdarkly.com)

---

### 🤝 PactFlow (SmartBear)
- **What it does**: Validates service contracts (Pact) to prevent integration errors.
- **Why it's good**: Prevents data exposure and service breakages in distributed systems.
- **Security features**: Centralized broker, secure API contract storage, access control.
- **Link**: [https://pactflow.io](https://pactflow.io)

---

### 🔍 Veracode
- **What it does**: Enterprise-grade SAST, DAST, and SCA.
- **Why it's good**: Proven in large orgs; supports governance, certifications.
- **Security features**: Advanced SAST, dynamic runtime testing (DAST), policy automation.
- **Link**: [https://www.veracode.com](https://www.veracode.com)

Note: Can have slower runtimes and less API/pipeline integration compared with Snyk

---

### 🧬 Checkmarx
- **What it does**: Offers SAST, SCA, IAST, and container security.
- **Why it's good**: Strong for enterprise code governance and compliance.
- **Security features**: Deep language support, CI/CD enforcement, results correlation.
- **Link**: [https://checkmarx.com](https://checkmarx.com)

---

### 🔐 HashiCorp Vault
- **What it does**: Secure storage and access of credentials, keys, tokens.
- **Why it's good**: Prevents secrets from leaking into source code.
- **Security features**: Role-based access, dynamic secrets, encryption, full audit trail.
- **Link**: [https://www.hashicorp.com/products/vault](https://www.hashicorp.com/products/vault)

---

## Trivy 

- Container & IaC Scanning
- Scans containers, filesystems, and IaC for vulnerabilities and misconfigurations
- Lightweight and easy to integrate in CI/CD

## Terrascan

- IaC Scanning
- Static code analyzer for Terraform, CloudFormation, and Kubernetes
- Helps catch misconfigurations early

## Zed Attack Proxy (ZAP)	

- DAST
- OWASP-supported tool for active and passive web vulnerability scanning
- Free, scriptable, well-documented

## BOM tool (CycloneDX / SPDX)	

- SBOM Generation
- Creates standardized Software Bill of Materials
- Increasingly mandated for compliance (e.g., by NIST, US EO)

## Kube-bench	

- Kubernetes Security
- Checks clusters against CIS Kubernetes Benchmarks
- Identifies misconfigurations and security gaps

---

# ✅ BDD & Testing Tools for Secure Software Delivery

While not strictly "security tools," these frameworks help prevent logic flaws, improve collaboration, and enforce security-related behaviors via automated testing.

| Tool | Category | What it Does | Security/Quality Role | Link |
|------|----------|---------------|------------------------|------|
| **Cucumber** | BDD | Write human-readable test cases in Gherkin syntax tied to step definitions | Aligns product, dev, test, and security for shared understanding | [https://cucumber.io](https://cucumber.io) |
| **SpecFlow** | BDD (.NET) | Gherkin-based BDD framework for .NET and Visual Studio | Enables BDD in Microsoft ecosystems | [https://specflow.org](https://specflow.org) |
| **Behave** | BDD (Python) | BDD testing for Python using Gherkin-style syntax | Consistent BDD for Python codebases | [https://behave.readthedocs.io](https://behave.readthedocs.io) |
| **Gauge** | BDD / Functional Testing | Markdown-based test automation framework by ThoughtWorks | Simpler alternative to Cucumber with strong plugin support | [https://gauge.org](https://gauge.org) |
| **Karate** | API Testing + BDD | Combines API tests, mocks, and performance testing using a DSL | Great for API validation and security behavior regression | [https://karatelabs.io](https://karatelabs.io) |
| **TestCafe** | E2E Testing | End-to-end web testing framework for modern browsers | Useful for testing authentication, sessions, access control | [https://testcafe.io](https://testcafe.io) |
| **Cypress** | E2E Testing | Fast, modern testing framework for front-end apps | Test critical security paths like login, logout, and redirects | [https://www.cypress.io](https://www.cypress.io) |
| **Playwright** | E2E Testing | Cross-browser automation with headless and CI-friendly setup | Enables secure UI behavior validation | [https://playwright.dev](https://playwright.dev) |
| **OWASP ZAP BDD Hooks** | Security + BDD | Allows ZAP scanning to be integrated with BDD flows | Embeds passive security scanning into acceptance tests | [https://owasp.org/www-project-zap](https://owasp.org/www-project-zap) |
| **Gherkin + Pact** | Contract + BDD | Combine BDD syntax with consumer-driven contract testing | Prevents insecure or breaking API changes | [https://docs.pact.io](https://docs.pact.io) |

---

## 🛡️ Example Gherkin for Security Acceptance

```gherkin
Scenario: Unauthenticated user cannot access admin panel
  Given I am not logged in
  When I try to access /admin
  Then I should receive a 401 Unauthorized error
```

Use BDD scenarios like this to formalize and test security rules early and automatically.
