# Facebook Pages Archive

This file documents FIC's interactions with other Facebook pages, including liked pages, customer relations, admin activity, and sent invites. Data from export JSONs (pages.json, pages_you_are_a_customer_of.json, admin_activity.json, sent_page_invites.json). Raw files migrated to `/resources/social/facebook/raw/`—confirm no PII (e.g., invitee names may need redaction or private placement). Themes: Broadband advocacy, local civics, ISPs, tech/privacy orgs.

## Liked Pages (from pages.json)
Pages liked by FIC (timestamps when liked). Sorted chronologically (earliest first). URLs are FB page IDs—test for live status.

| Page Name                                      | Liked Date (UTC)         | URL (FB Page) |
|------------------------------------------------|--------------------------|---------------|
| Port Jefferson Chamber of Commerce             | 2023-01-25 19:35:20     | https://www.facebook.com/358363414280 |
| Kara Hahn                                      | 2021-10-25 13:28:15     | https://www.facebook.com/175669745812842 |
| LongIsland.com                                 | 2023-01-25 19:28:15     | https://www.facebook.com/214804075200784 |
| Ridge Civic Association                        | 2022-09-25 19:36:56     | https://www.facebook.com/116684895026479 |
| Town of Brookhaven Parks and Recreation        | 2022-01-25 04:35:53     | https://www.facebook.com/165625770194699 |
| Beta NYC                                       | 2021-10-29 16:52:31     | https://www.facebook.com/359140494174913 |
| Fiber Broadband Association                    | 2022-03-24 13:46:29     | https://www.facebook.com/294013917396722 |
| Brooklyn Tech                                  | 2022-04-11 17:57:52     | https://www.facebook.com/275565989305463 |
| Piscataway Township                            | 2022-04-05 17:54:47     | https://www.facebook.com/223986657760216 |
| Honest Internet                                | 2022-10-04 04:57:55     | https://www.facebook.com/114801583638321 |
| Starry                                         | 2023-01-25 21:48:49     | https://www.facebook.com/1905867602972450 |
| Centereach Civic Association                   | 2023-01-25 21:44:00     | https://www.facebook.com/146853195353320 |
| Middle Island Civic Association                | 2022-09-27 15:45:30     | https://www.facebook.com/512973772063361 |
| Electronic Frontier Foundation (EFF)           | 2023-01-25 20:51:51     | https://www.facebook.com/97703891945 |
| The Tor Project                                | 2023-01-25 22:48:52     | https://www.facebook.com/409382919950 |
| NYC Mesh                                       | 2023-01-25 22:23:18     | https://www.facebook.com/778052668920838 |
| ... (full list in raw JSON; truncated for brevity) | ... | ... |

**Notes**: 50+ likes, focused on local NY/LI civics (e.g., Brookhaven, Ridge), broadband (e.g., Fiber Broadband Assoc., Starry, GFiber), tech/privacy (EFF, Tor), and communities (e.g., Beta NYC). Use for network mapping—potential partners for revival.

## Pages as Customer (from pages_you_are_a_customer_of.json)
- Mostly self-referential: References FIC page itself.
- Messenger thread: False
- Last automated follow-up: None (timestamp 0)
- No other customers listed—likely no e-commerce/activity.

## Admin Activity (from admin_activity.json)
- Page: Fair Internet Coalition
- Timestamp: 2023-01-26 01:52:04
- No page contacts or detailed actions—empty dicts.

## Sent Page Invites (from sent_page_invites.json)
Invites sent to people who reacted to FIC posts (2021–2022). ~200+ entries; timestamps when sent/updated. Invites not sent via Messenger; types: "Someone who reacted to a post on the page". Names: Personal (e.g., Gayle Rose, Paul Fabrico)—redact or private for privacy.

| Sent Date (UTC)    | Invitee Name          | Updated Date (UTC) | Page                  | Note/Type |
|--------------------|-----------------------|--------------------|-----------------------|-----------|
| 2022-08-11 15:19:52 | Gayle Rose            | 2022-08-11 15:19:52 | Fair Internet Coalition | "" / "Someone who reacted to a post on the page" |
| 2022-08-09 20:45:25 | Paul Fabrico          | 2022-08-10 11:48:39 | Fair Internet Coalition | "" / "Someone who reacted to a post on the page" |
| ... (truncated; full in raw) | ... | ... | ... | ... |
| 2021-03-23 18:00:05 | Hugo Benoit           | 2021-03-26 20:51:20 | Fair Internet Coalition | "" / "Someone who reacted to a post on the page" |

**Notes**: Invites peaked ~2021–2022 during active advocacy. For repo: Summarize counts/trends (e.g., 150+ in 2022) rather than full names to avoid PII.