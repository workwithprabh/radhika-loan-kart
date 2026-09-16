# Radhika Loan Kart

Content operations repository for Radhika Loan Kart social media.

## Workflow

1. Content is planned in the master Google Sheet.
2. Creatives are produced and reviewed.
3. Approved files are stored in Google Drive.
4. Approved metadata, captions, alt text and publishing references can be mirrored here for automation.
5. Publishing automation should only consume approved content.

## Repository Structure

- `content/2026/september/static-posts/` — static post metadata and references
- `content/2026/september/carousels/` — carousel metadata and references
- `content/2026/september/captions/` — approved captions
- `content/2026/september/alt-text/` — approved accessibility text
- `content/2026/september/metadata/` — publishing metadata and manifests
- `automation/` — automation notes, scripts and workflow configuration

## Status Model

`Planned → Draft Created → Needs Changes / Pending → Approved → Scheduled → Published`

## Important

Do not commit passwords, tokens, API secrets, customer documents, loan applications, personal financial information or other sensitive data to this repository.
