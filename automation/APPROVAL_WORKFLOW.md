# Approval-to-Repository Workflow

This repository is part of the Radhika Loan Kart social media workflow.

## Trigger
When a post or carousel is explicitly approved in ChatGPT, treat that approval as permission to upload the approved asset and its supporting metadata to this repository.

## Required actions after approval
1. Upload the final approved creative asset(s) to the appropriate month/content folder.
2. Upload or update the caption text.
3. Upload or update the alt text.
4. Upload or update post metadata, including date, format, topic, status, and asset filenames.
5. Keep filenames consistent with the Google Drive / Google Sheet naming convention.
6. Update the connected Google Sheet with the GitHub asset URL when available.
7. Keep Google Drive and GitHub versions aligned with the approved version only.

## Folder convention
- `content/YYYY/MM/static-posts/`
- `content/YYYY/MM/carousels/`
- `captions/`
- `alt-text/`
- `metadata/`

## Approval rule
Only assets explicitly approved by the user should be treated as final and uploaded as approved content.

## Public repository note
This repository is public. Any creative, caption, alt text, or metadata committed here is publicly accessible.
