# Security Policy BRAINSAIT LTD

## Supported Versions

We are committed to maintaining security for the following versions of our CI/CD workflow setup:

## Reporting a Vulnerability

If you discover a vulnerability within our self-hosted macOS runner CI/CD workflow, please report it promptly. We aim to address all valid security concerns quickly to ensure a safe and secure environment.

**To report a vulnerability:**
1. **Contact:** [security@brainSAIT.com]
2. **Provide details:** Clearly describe the issue, including steps to reproduce the vulnerability, potential impact, and any relevant log files.
3. **Acknowledgment:** We will acknowledge the receipt of the report within 48 hours.
4. **Resolution:** Security patches will be prioritized, with updates rolled out once verified and tested.

## Security Measures

We follow best practices to ensure the security and integrity of our CI/CD workflow, including but not limited to:

1. **Access Control:**
   - Use of SSH keys and GitHub tokens for secure authentication.
   - Restricting access to self-hosted runners and ensuring they are only triggered by authorized users.
   - Regularly rotating access tokens and secrets.

2. **Network Security:**
   - Limiting inbound and outbound network traffic to essential services.
   - Using secure connections (HTTPS, SSH) for data transfers.
   - Keeping macOS systems behind a firewall.

3. **Environment Security:**
   - Regularly updating the macOS operating system and installed software to mitigate vulnerabilities.
   - Running automated security scans to detect and resolve vulnerabilities.
   - Using sandboxed environments for running build and test processes.

4. **Data Protection:**
   - Encrypting sensitive data stored on the runner and during data transmission.
   - Securing environment variables used in workflows.
   - Ensuring logs do not contain sensitive information.

5. **Monitoring & Logging:**
   - Implementing monitoring to detect unusual activity or unauthorized access.
   - Keeping logs for audit purposes, regularly reviewed for security insights.

## Vulnerability Management

- We are committed to quickly responding to newly discovered vulnerabilities and following responsible disclosure practices.
- Patches are released as soon as fixes are available, with full testing to ensure stability.
- Automated patch management systems are utilized where possible to minimize risk.

## Additional Information

- **Continuous Improvement:** We actively monitor and improve our security processes.
- **Security Training:** Regular training is provided to our team on secure coding practices and incident response.
- **Third-Party Dependencies:** All dependencies are regularly reviewed and updated to address potential security risks.
