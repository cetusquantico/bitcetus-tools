# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability in Bitcetus Tools, please report it responsibly:

### 🔒 How to Report

1. **DO NOT** open a public issue
2. Email: [seu-email@exemplo.com]
3. Use encrypted communication if possible (PGP key available upon request)
4. Include:
   - Description of the vulnerability
   - Steps to reproduce
   - Potential impact
   - Suggested fix (if any)

### ⏱️ Response Time

- Initial response: Within 48 hours
- Status update: Within 7 days
- Fix timeline: Depends on severity

### 🏆 Recognition

Security researchers who report valid vulnerabilities will be:
- Credited in SECURITY.md (with permission)
- Acknowledged in release notes
- Added to our Hall of Fame

## Security Best Practices

When using Bitcetus Tools:

1. **Never share private keys** recovered during testing
2. **Only analyze your own wallets** or data you have permission to audit
3. **Use on isolated systems** when handling sensitive data
4. **Verify tool integrity** before use (check commit hashes)

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| 3.0.x   | ✅ Yes            |
| < 3.0   | ❌ No             |

## Known Limitations

- Tools run client-side in browser (potential XSS if malicious data injected)
- No rate limiting on computational attacks
- Educational tools - not intended for production security systems

## Security Principles

Bitcetus Tools follows these security principles:

1. **Client-side only** - No data leaves your browser
2. **Open source** - All code is auditable
3. **Educational focus** - Designed for learning, not exploitation
4. **Responsible disclosure** - We report vulnerabilities we discover

---

**Last updated:** 2025-01-01
