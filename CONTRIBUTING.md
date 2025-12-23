# CI/CD Contribution Guide

This repository is responsible for build, test, and deployment pipelines.
Changes here directly affect how code moves to different environments.

Please be careful and follow the guidelines below.

# What you can work on

- Workflow files used for build and deployment
- Automation steps for testing and releases
- Pipeline-related scripts and helpers

# What you should not add

- Application or frontend code
- Infrastructure provisioning files

# Contribution process

1. Create a new branch for every change
2. Focus on one pipeline change only
3. Make sure the pipeline logic is correct
4. Keep commits clear and easy to understand
5. Open a Pull Request with full context

# Pull Request expectations

- Each PR must solve a single problem
- Explain why the pipeline change is needed
- Reviews are required before merge
- Direct changes to `main` are blocked

Careful changes keep delivery smooth and reliable.
