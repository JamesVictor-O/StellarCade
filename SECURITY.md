# Security Policy

## Supported Versions

We currently support the following versions of Stellarcade:

| Version | Supported |
| ------- | --------- |
| 1.0.x   | ✅ Yes    |
| < 1.0   | ❌ No     |

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues.**

If you discover a potential security vulnerability in Stellarcade (either in smart contracts or backend), please send an email to [security@stellarcade.example.com](mailto:security@stellarcade.example.com) with the details.

### What to include:

- A clear description of the vulnerability.
- Steps to reproduce (proof of concept).
- Potential impact.
- Any suggested fixes.

We will acknowledge your report within 48 hours and provide a timeline for a resolution. We request that you follow responsible disclosure practices and give us time to address the issue before making it public.

## Security Best Practices

- **Never publish private keys**: Ensure `.env` files are never committed.
- **Contract Audits**: All production contracts should undergo a professional audit.
- **Dependency Management**: Regularly run `npm audit` and `cargo audit`.

## Bug Bounty

We are currently setting up a formal bug bounty program. In the meantime, significant security contributions may be recognized on our "Security Wall of Fame."

---

_Security is a top priority for Stellarcade._
