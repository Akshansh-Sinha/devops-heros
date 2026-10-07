# Session 17: Complete CI/CD & DevSecOps

This session focuses on shifting security left by integrating automated security scans, vulnerability checks, and policy gates directly into CI/CD pipelines.

---

## Key Modules & Topics

1. **Secret Scanning:**
   - Preventing hardcoded API keys, tokens, and credentials from entering source control.
   - Tools: Gitleaks, TruffleHog.
   - Related Directory: [`06-secret-scanning/`](file:///home/akshanshsinha/DevOps/devops-heros/session-17-devsecops/06-secret-scanning)

2. **Static Application Security Testing (SAST):**
   - Analyzing source code for known security flaws, injection vectors, and anti-patterns before compilation.
   - Tools: Semgrep, SonarQube, Bandit.
   - Related Directory: [`04-sast/`](file:///home/akshanshsinha/DevOps/devops-heros/session-17-devsecops/04-sast)

3. **Software Composition Analysis (SCA):**
   - Auditing open-source dependencies and package manifests (`package.json`, `requirements.txt`) for CVEs.
   - Tools: Snyk, OWASP Dependency-Check, npm audit.
   - Related Directory: [`05-sca/`](file:///home/akshanshsinha/DevOps/devops-heros/session-17-devsecops/05-sca)

4. **Container Image Scanning:**
   - Scanning base OS layers and application packages inside Docker container images for vulnerabilities.
   - Tools: Trivy, Grype, Docker Scout.
   - Related Directory: [`07-container-image-scanning/`](file:///home/akshanshsinha/DevOps/devops-heros/session-17-devsecops/07-container-image-scanning)

5. **Security Quality Gates:**
   - Enforcing automated pass/fail thresholds in CI/CD (e.g. fail pipeline on CRITICAL or HIGH vulnerabilities).
   - Related Directory: [`08-security-gates/`](file:///home/akshanshsinha/DevOps/devops-heros/session-17-devsecops/08-security-gates)

6. **Secure Container Registry & Kubernetes Deployment:**
   - Image signing, pull secrets, and least-privilege runtime security contexts.
   - Related Directories: [`02-container-registry/`](file:///home/akshanshsinha/DevOps/devops-heros/session-17-devsecops/02-container-registry), [`03-kubernetes-deployment/`](file:///home/akshanshsinha/DevOps/devops-heros/session-17-devsecops/03-kubernetes-deployment)

7. **End-to-End DevSecOps Demo Project:**
   - Complete GitHub Actions pipeline running SAST, SCA, Secret Scanning, and Trivy container scan on the `hey-cicd` application.
   - See [demo/README.md](file:///home/akshanshsinha/DevOps/devops-heros/session-17-devsecops/demo/README.md) for full setup instructions.
