# Security Policy

## Supported Versions

Use this section to tell people about which versions of your project are currently being supported with security updates.

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |
| 0.9.x   | :x:                |
| 0.8.x   | :white_check_mark: |
| < 0.8   | :x:                |

## Reporting a Vulnerability

We take the security of Nexalo seriously. If you have discovered a security vulnerability in our project, we appreciate your help in disclosing it to us in a responsible manner.

### Reporting Process

1. **Do not** report security vulnerabilities through public GitHub issues.

2. Instead, please send an email to [dev.hridoy2002@gmail.com](mailto:dev.hridoy2002@gmail.com) with the subject "Security Vulnerability Report".

3. Include the following information in your report:
   - Type of vulnerability
   - Full paths of source file(s) related to the manifestation of the vulnerability
   - The location of the affected source code (tag/branch/commit or direct URL)
   - Any special configuration required to reproduce the issue
   - Step-by-step instructions to reproduce the issue
   - Proof-of-concept or exploit code (if possible)
   - Impact of the vulnerability, including how an attacker might exploit it

4. Allow up to 48 hours for an initial response to your report. We'll try to keep you informed about our progress towards a fix and full announcement.

### What to Expect

- We will acknowledge your email within 48 hours, and will send a more detailed response within 72 hours indicating the next steps in handling your report.
- After the initial reply to your report, the security team will endeavor to keep you informed of the progress towards a fix and full announcement, and may ask for additional information or guidance.
- We will treat your report with strict confidentiality, and not pass on your personal details to third parties without your permission.

### Bug Bounty Program

At this time, we do not offer a paid bug bounty program. We are grateful for your efforts in disclosing vulnerabilities responsibly and will publicly acknowledge your contribution if you so desire.

## Security Best Practices for Nexalo Users

1. **Keep Your Bot Token Secret**: Never share your bot token publicly or commit it to version control.

2. **Use Environment Variables**: Store sensitive information like API keys and database credentials in environment variables, not in your code.

3. **Regularly Update Dependencies**: Keep all project dependencies up to date to benefit from the latest security patches.

4. **Implement Rate Limiting**: To prevent abuse, implement rate limiting on your bot's commands and API endpoints.

5. **Validate User Input**: Always validate and sanitize user input to prevent injection attacks.

6. **Use Secure Connections**: When connecting to external services or databases, always use secure, encrypted connections (HTTPS, SSL/TLS).

7. **Principle of Least Privilege**: When setting up bot permissions in Telegram, only request the minimum permissions necessary for your bot to function.

8. **Regular Security Audits**: Periodically review your code and dependencies for potential security vulnerabilities.

## Commitment to Security

The Nexalo team is committed to resolving security issues in a responsible and timely manner. We appreciate the efforts of security researchers and the broader community in helping us maintain a secure environment for all our users.

Thank you for helping keep Nexalo and its users safe!
