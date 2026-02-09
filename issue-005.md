Raw JSON files from the FB export have been migrated, but some may contain PII (e.g., personal names in invites, device IDs, IPs).

**Acceptance Criteria**
- Scan files in `/resources/social/facebook/raw/` for:
  - Personal names (invites, comments authors if not public figures)
  - IPs, device IDs, hardware info
  - Any emails/phones beyond public FIC ones
- Move truly sensitive files to `fic-admin-private` repo
- Create a `raw/README.md` explaining what each file contains and why kept private/public
- Commit sanitized versions or summaries where appropriate

**Why**: Ensures public repo remains clean and compliant.

**Estimated effort**: 30–60 minutes (depending on volume)
**Assignee**: @jacob-kraniak