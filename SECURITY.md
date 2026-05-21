# Security Policy

## Supported Versions

| Version | Supported |
|---------|-----------|
| v2.x    | ✅ Active  |
| v1.x    | ❌ End of life |

## Reporting a Vulnerability

**Do NOT open a public issue for security vulnerabilities.**

Instead:

1. Email: security@opensecdevops.dev (or use GitHub's private vulnerability reporting)
2. Include:
   - Description of the vulnerability
   - Steps to reproduce
   - Potential impact
   - Suggested fix (if any)

### Response Timeline

- **Acknowledgment**: Within 48 hours
- **Initial assessment**: Within 5 business days
- **Fix timeline**: Depends on severity
  - Critical: 7 days
  - High: 14 days
  - Medium: 30 days
  - Low: Next release

## Security Practices

OSDO follows security best practices:

- All dependencies scanned with OSDO's own tools
- Signed releases (Cosign/Sigstore)
- SBOM generated for every release
- SLSA Level 2 provenance (planned)
- Regular security audits

## Acknowledgments

We thank all security researchers who responsibly disclose vulnerabilities.
