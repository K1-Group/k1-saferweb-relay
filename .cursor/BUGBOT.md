# Bugbot Repository Rules

## Security: Secrets & Authentication

Flag the following as high-severity security issues in any pull request:

1. Hardcoded secrets, API keys, tokens, passwords, or webhook URLs (e.g. Zapier webhooks) committed to the repo.
2. Credentials or connection strings stored in plaintext in code, config files, or environment files that are tracked by git.
3. Authentication or authorization logic that is missing, bypassed, or weakened (e.g. disabled token validation, hardcoded bypass conditions).
4. Sensitive data (PII, financial data, credentials) logged to console or written to logs.
5. Use of insecure or deprecated cryptographic functions for handling secrets or authentication.

When detected, recommend moving secrets to a secrets manager or environment variables (excluded from version control) and enforcing proper authentication checks.
