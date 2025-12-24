# CI/CD Security Guidance

This repository controls automated processes that move code from development to production.
Errors in these processes can spread quickly if not controlled.

---

## Raising a security concern
If you notice a security issue in any workflow or pipeline,
do not report it in public issues or comments.
Share the concern directly with the CI/CD maintainers.
Keep the explanation clear and limited to what is needed.

---

## Information to provide
- Which workflow or job is involved
- Where the issue occurs in the process
- What behavior seems unsafe or unexpected
- Whether releases could be affected

---

## Rules to follow
- Do not store secrets in pipeline files
- Do not weaken checks to speed up delivery
- Do not run unapproved changes on production pipelines

---

## How issues are handled
Maintainers will check the issue, decide on a safe fix, 
and apply changes after review to keep deliveries stable and under control.
