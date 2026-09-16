# Automation

This folder is reserved for automation that connects the Radhika Loan Kart approval workflow with publishing systems.

## Intended flow

Google Sheet status = Approved
→ approved creative stored in Google Drive
→ approved metadata/caption/alt text mirrored to GitHub
→ publishing automation consumes approved records only
→ publishing status is written back to the tracking system

## Rules

- Never store API keys, access tokens, passwords or customer financial data in GitHub.
- Use environment variables or platform secret stores for credentials.
- Only publish records explicitly marked Approved.
- Keep file names tied to the content calendar Post ID where possible.
