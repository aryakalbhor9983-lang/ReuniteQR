# Security Policy

## Supported Versions

The following versions of ReuniteQR are currently supported with security updates:

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |
| < 1.0   | :x:                |

## Reporting a Vulnerability

The ReuniteQR team takes security vulnerabilities seriously. If you discover a security issue, please follow the process below.

### How to Report

**Please do NOT report security vulnerabilities through public GitHub issues.**

Instead, report them privately by:

1. Emailing the maintainer at: **[aryakalbhor9983@gmail.com.com]**
2. Including the following information:
   - Type of vulnerability (e.g., XSS, authentication bypass, data exposure)
   - Full path of the affected file(s)
   - Step-by-step instructions to reproduce
   - Proof-of-concept or exploit code (if possible)
   - Potential impact of the vulnerability

### What to Expect

- **Acknowledgment:** Within 48 hours of your report
- **Assessment:** Within 5 business days, we will confirm the vulnerability and determine its severity
- **Fix Timeline:** Critical issues will be patched within 7 days; others within 30 days
- **Credit:** We will credit you in the release notes (unless you prefer to remain anonymous)

### Scope

The following are in scope for security reports:

- Authentication and authorization flaws
- Data exposure of user profiles or emergency contacts
- QR code tampering or spoofing
- Firestore security rule bypasses
- Cross-site scripting (XSS) or injection attacks
- Sensitive data leakage via client-side code

### Out of Scope

- Denial of Service (DoS) attacks
- Social engineering
- Issues in third-party dependencies (report these upstream)
- Missing security headers without a demonstrated exploit

## Security Best Practices for Deployers

If you are self-hosting ReuniteQR, ensure you:

- Never commit `.env.local` or Firebase credentials
- Configure Firestore security rules before going live
- Enable Firebase App Check for production
- Restrict authorized domains in Firebase Authentication
- Use HTTPS only
- Regularly update dependencies (`npm audit fix`)

Thank you for helping keep ReuniteQR and its users safe.
