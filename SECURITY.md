# Security Policy

This repository is intended to store agent rules, workflow notes, and progress logs only.
Do not commit private keys, API keys, tokens, passwords, certificates, or other secrets.

## What Not to Commit

- Private keys such as `id_rsa`, `id_ed25519`, `.pem`, `.p12`, or `.pfx`
- Environment files such as `.env` or `.env.*`
- API keys, access tokens, client secrets, or session secrets
- Credential exports, service account files, or other sensitive configuration dumps

## Before You Commit

1. Check `git status`.
2. Review new or changed files for secrets.
3. Make sure secret values are not hard-coded into Markdown or config files.
4. Prefer placeholders and examples over real credentials.

## If a Secret Was Exposed

- Remove the secret from the repository immediately.
- Rotate or revoke the exposed credential.
- Update any related documentation so the secret is not reintroduced.

## Reporting Concerns

If you find a secret or suspect one was committed, treat it as urgent and remove it before pushing changes.

