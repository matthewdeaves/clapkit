# Security Policy

## Supported Versions

| Version | Supported |
|---------|-----------|
| Latest on main | Yes |

## Reporting a Vulnerability

If you discover a security vulnerability in this project, please report it responsibly:

1. **Do NOT open a public GitHub issue.**
2. Use [GitHub Security Advisories](https://github.com/matthewdeaves/clapkit/security/advisories/new) to privately report the vulnerability.
3. Include steps to reproduce if possible.
4. You will receive an acknowledgment within 48 hours.

## Scope

ClapKit is a C library targeting Classic Mac OS (System 6/7). Security considerations include:

- Memory safety issues in C code (buffer overflows, use-after-free, etc.)
- Supply-chain integrity of GitHub Actions used in CI/CD
- Integrity of generated documentation deployed to GitHub Pages
- The `peaceiris/actions-gh-pages` action has write access to the repository via GITHUB_TOKEN
