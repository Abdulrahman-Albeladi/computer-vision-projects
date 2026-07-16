# Security policy

## Reporting

If you discover a security issue, exposed credential, or personal data in this repository, report it privately to the repository owner and do not disclose it publicly.

## Current repository posture

Validation evidence for the current repository state reports:
- 0 secret findings and 0 privacy findings from the recorded secret/privacy scan
- `detect-secrets` passed
- `bandit` passed

`gitleaks` was not run successfully because the tool was not installed.

## Handling sensitive material

Do not commit:
- API keys, tokens, passwords, or private keys
- student identifiers or personal data
- restricted research or course data
- notebook outputs containing sensitive information

If sensitive material is found after commit, remove it from the repository history before any release decision.
