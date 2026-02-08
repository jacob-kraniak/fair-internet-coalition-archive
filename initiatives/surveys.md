# ISP Satisfaction Surveys Initiative

## Purpose & Scope
Collect consumer feedback on major ISPs to highlight issues with reliability, affordability, transparency, and service quality. Focus: Tri-State area (Long Island/NY emphasis on Optimum/Altice monopoly), but open to all providers nationwide.

Surveys aimed to support advocacy, PSC hearings, local votes (e.g., Brookhaven fiber), and consumer education on alternatives.

## Implementation Details
- Hosted via WordPress sub-pages (e.g., /isp-satisfaction-surveys/altice-survey/, /xfinity-comcast-survey/).
- Forms: Google Forms requiring Google login for identity validation (prevent duplicates/fakes).
- Promotion: Site links, Reddit (r/OPTIMUM), Facebook groups (Optimum/Altice Dilemmas), X/Twitter bot (ended 2023), Instagram posts.
- NY-specific: Directed residents to Empire State Broadband PSC survey[](https://www.empirestatebroadband.com/).

## Response Milestones (Historical)
- Optimum/Altice: 745 total submissions by September 2022 (after ~18 months; 400+ early from Reddit).
- Other providers: Low volume (e.g., Cox: 9, Spectrum: 2, Comcast: 0 as of Sep 2022)—likely due to less awareness.

## Public Data Dashboards (Looker Studio)
Results visualized in public Google Looker Studio dashboards (created 2022). These are read-only share links; data frozen post-collection.

- **Optimum/Altice Dashboard** (primary): [View here](https://datastudio.google.com/s/qQArBJKyIxM)
- **Cox Communications**: [View here](https://datastudio.google.com/s/hvkKuC5hC1E)
- **Spectrum/Charter**: [View here](https://datastudio.google.com/s/lvYvtaR9lds)
- **Xfinity/Comcast**: [View here](https://datastudio.google.com/s/iwybTNtauEU)

**Notes on Access/Preservation**:
- Visit links directly (may prompt Google sign-in for viewing).
- Before spinning down Google Workspace: Export dashboards as PDF reports or CSV data sources via Looker Studio interface (File > Download > PDF/CSV). Upload exports to private repo (`fic-admin-private`) or sanitized versions here.
- If links break (e.g., ownership transfer needed), recreate from any raw Google Form responses preserved in Drive.
- Current site (/isp-satisfaction-surveys/) lists only Xfinity/Comcast prominently—no embeds or results shown anymore.

## Revival Tips
- Reactivate forms if reviving (update Google Forms links).
- Add new providers or refresh data collection.
- Consider migrating to open tools (e.g., Typeform + Metabase) for easier long-term access.