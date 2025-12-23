# CI/CD Repository

# What this repository is for
This repository is used to manage **CI/CD (Continuous Integration and Continuous Deployment) configurations**.
The purpose of this repository is to keep deployment logic

---

# What type of changes are allowed
- Pipeline configuration files
- Build, test, and deployment workflow definitions
- Environment-specific CI/CD settings
- Documentation explaining pipeline behavior
- Small, focused changes that affect one pipeline logic

---

# What changes are NOT allowed
- Application source code
- Infrastructure provisioning files
- Secrets, tokens, passwords, or credentials
- One-time manual fixes or temporary scripts
- Experimental changes without documentation

---

# Who owns this repository
This repository is owned by the **DevOps team**.
Only authorized maintainers can approve and merge changes to the main branch.

---

# Risk if this repository is misused
If wrong pipeline rules are merged, broken or untested code can reach production.
This may cause release failures, downtime, or urgent rollbacks at critical times.
Careful reviews and clear rules help keep deployments safe and stable.

---

# Final note
CI/CD changes directly affect production.
Make changes carefully and always consider failure scenarios.
