# Data Preservation Notes – Especially Survey/Looker Studio Assets

## Google Workspace Migration Priority
Since Workspace is being spun down:

1. **Looker Studio Dashboards**:
   - Ownership tied to your Google account—transfer or export before cancellation.
   - Steps: Open each dashboard → File → Share → Add people (if collaborators) or Download as PDF/CSV (for visuals/data extracts).
   - Save exports to local drive → Upload to `fic-admin-private` repo (raw data) and sanitized summaries to public repo.

2. **Google Forms Responses**:
   - Linked to Forms in Drive → Export responses as CSV/Google Sheets.
   - Anonymize if sharing publicly (remove personal identifiers per privacy practices).

3. **Other**:
   - Drive folders with survey-related Docs/Sheets → Download/transfer.
   - Gmail filters/labels for survey notifications → Export via Google Takeout.

## Status Check
- Dashboard links still resolve (as of Feb 2026 indexes).
- If inaccessible post-spin-down, note in repo: "Data preserved offline; contact repo owner for access."
- Backup tip: Use Obsidian to link local copies of PDFs/CSVs (embed or attach in vault synced to repo).

This ensures revival folks can access historical insights without live Workspace.