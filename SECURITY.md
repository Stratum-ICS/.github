# Security Policy

## Supported Versions

| Version | Supported |
|---|---|
| Latest `master` | ✅ |
| Older releases | ⚠️ Best effort |

## Reporting a Vulnerability

**Do not open a public GitHub issue for security vulnerabilities.**

Report privately via one of:
- **Email**: security@stratum-ics.org
- **GitHub private vulnerability reporting**: Security → Report a vulnerability (in the `stratum` repo)

Include in your report:
- Description of the vulnerability
- Steps to reproduce
- Potential impact
- Suggested fix if you have one

## Response Timeline

| Step | Target |
|---|---|
| Acknowledgement | Within 48 hours |
| Initial assessment | Within 5 business days |
| Fix or mitigation | Depends on severity — critical issues prioritized |
| Public disclosure | After fix is released, coordinated with reporter |

## Scope

In scope:
- Authentication and authorization bypass
- Data exposure (vault contents, user data, tokens)
- Remote code execution
- SQL injection or data corruption

Out of scope:
- Issues in dependencies (report upstream)
- Denial-of-service via resource exhaustion on self-hosted instances
- Social engineering

## Credits

We thank security researchers who responsibly disclose vulnerabilities. Contributors will be acknowledged in release notes unless they prefer anonymity.
