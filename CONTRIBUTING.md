Overview
LendCircle is an AI‑powered peer‑to‑peer lending platform. Security, privacy, and responsible data handling are core to the project. This policy outlines how to report vulnerabilities, how we handle security issues, and what contributors must follow when working with sensitive financial or user data.

Reporting a Vulnerability
If you discover a security issue, please report it responsibly:

Email the maintainers privately

Do not open a public GitHub issue for sensitive vulnerabilities

Provide clear reproduction steps

Include environment details (browser, OS, API version, etc.)

Allow maintainers reasonable time to investigate and patch

We will acknowledge your report within 48 hours and provide a remediation timeline when possible.

Scope
This policy applies to:

The LendCircle backend (Supabase, API routes, authentication)

The AI decision‑support modules

The frontend application

Any integrations that handle user identity, financial data, or lending workflows

Security Expectations for Contributors
All contributors must:

Avoid introducing insecure code, dependencies, or configurations

Follow secure coding practices (validation, sanitization, least privilege)

Never commit secrets, API keys, or credentials

Use environment variables for sensitive configuration

Report suspicious behavior or potential vulnerabilities immediately

Respect user privacy and data protection laws (GDPR, CCPA, etc.)

Data Protection Requirements
Because LendCircle handles financial and identity‑related data, contributors must:

Encrypt sensitive data in transit and at rest

Avoid logging personal or financial information

Use secure authentication and authorization patterns

Prevent unauthorized access to lending workflows or user accounts

Ensure AI modules do not expose private data through outputs

Prohibited Actions
The following are strictly forbidden:

Attempting to exploit the platform

Introducing malware, backdoors, or harmful code

Using LendCircle for fraud, scraping, or financial manipulation

Circumventing authentication or authorization systems

Sharing private vulnerability details publicly before a fix is released

Remediation Process
When a vulnerability is confirmed:

It is documented internally

A patch is developed and tested

A fix is deployed

A security advisory may be published if appropriate

Thank You
We appreciate responsible disclosure and contributions that help keep LendCircle safe for all users.
