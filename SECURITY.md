# Security Policy

## Reporting a Vulnerability

Please do not disclose security vulnerabilities through a public issue. Contact the project owner privately through the contact method listed on the project owner's GitHub profile.

## Public Repository Rules

The following must never be committed:

- `.env` files;
- API keys or access tokens;
- Supabase service-role credentials;
- database passwords or connection strings;
- real learner, educator, employee, or institutional data;
- authentication cookies or session values;
- confidential documents or proprietary integrations.

## If a Secret Is Exposed

Deleting a file is not sufficient because the value may remain in Git history. Revoke or rotate the exposed credential immediately, remove it from repository history, and review access logs.
