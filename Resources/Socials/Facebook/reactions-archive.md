# Facebook Comments and Likes/Reactions Archive

This file summarizes the final batch of FIC's Facebook activity from the export JSONs (comments.json, likes_and_reactions.json, likes_and_reactions_1.json). Covers comments posted by FIC and likes/reactions on other content. Raw JSONs migrated to `/resources/social/facebook/raw/comments-likes/`—no PII (e.g., author names are public/group-based). Data spans 2021–2024; focuses on advocacy interactions (e.g., Optimum complaints, Planet Networks, local politics).

## Comments (from comments.json)
Comments/replies by FIC. Sparse; mostly in groups/pages related to ISPs/broadband.

| Date (UTC)         | Title / Context                                | Comment Content |
|--------------------|------------------------------------------------|-----------------|
| 2021-12-28 19:32:58 | Fair Internet Coalition replied to a comment.  | (No text; possible reply—check raw for attachments) |
| 2023-03-24 21:05:52 | Fair Internet Coalition commented on New Jersey Board of Public Utilities's photo. | "Planet Networks" (likely tagging/recommending) |
| 2023-05-01 15:54:38 | Fair Internet Coalition commented on Planet Networks's post. | "Fair Internet Coalition ♥♥♥ Planet Networks !" (heart reactions; endorsement) |
| 2023-11-23 00:01:27 | Fair Internet Coalition commented on their own photo. | "Juan Sandoval Brookhaven Town voted in favor of the Business License for OCG!\n\nhttps://twitter.com/1fairInternet/status/1641598468899708935?t=Ri8GMZKduueSCQQYoq0dtw&s=19" (update on fiber vote with X link) |
| 2023-11-23 17:45:05 | Fair Internet Coalition replied to their own comment. | "Juan Sandoval they're already built out across Middle Country Rd and LIE. I hear they're now building on Long Island Ave.\n\nI would reach out to them directly for inquiries. \n\nsales@ocgcom.com" (OCG buildout details) |

**Notes**: Comments tie to key initiatives (e.g., OCG fiber, Planet Networks promo). Attachments: One X link (use x_thread_fetch if needed for full post).

## Likes and Reactions (from likes_and_reactions.json)
Likes/reactions by FIC on posts/photos. Format: Mostly "Like"; includes URLs/groups/authors.

| Date (UTC)         | Reaction | URL / Context                                  | Group/Page/Author |
|--------------------|----------|------------------------------------------------|-------------------|
| 2024-02-01 19:29:00 | Like     | https://www.facebook.com/groups/optimumalticedilemmas/permalink/3620631761526766/ | Optimum/Altice Dilemmas / Kevin Melberger |
| ... (truncated; ~100 entries) | Like | https://www.facebook.com/photo.php?fbid=642827414509213&set=a.290469796411645&type=3 | Brookhaven Town Clerk Kevin J. LaValle |
| 2023-02-08 19:32:51 | Like     | https://www.facebook.com/KevinJLaValle/posts/pfbid0DYwj9uTtzCh6sg7LeEhBXLC2oYFrXMBR4JaonyuNvD8JeK3VZMGP18aBjocAneCTl | Brookhaven Town Clerk Kevin J. LaValle |
| ... | ... | ... | ... |

**Notes**: Focus on local politics (e.g., Brookhaven officials), ISP groups (Optimum/Altice Dilemmas), and advocacy (e.g., Planet Networks posts). Many in 2023–2024.

## Likes and Reactions Timeline (from likes_and_reactions_1.json)
Chronological reactions (e.g., LIKE/NONE). "NONE" may indicate unreacted or errors.

| Date (UTC)         | Reaction | Title / Context                                |
|--------------------|----------|------------------------------------------------|
| 2021-03-23 13:11:59 | NONE     | Fair Internet Coalition reacted to Planet Networks's post. |
| 2021-03-24 11:39:40 | NONE     | Fair Internet Coalition reacted to a post.     |
| 2021-03-27 16:24:12 | NONE     | Fair Internet Coalition reacted to Frank Kanter's post. |
| ... (truncated; ~200 entries) | LIKE | Fair Internet Coalition liked Planet Networks's post. |
| 2024-02-01 19:28:59 | LIKE     | Fair Internet Coalition liked Planet Networks's post. |
| 2024-02-01 19:29:00 | LIKE     | Fair Internet Coalition liked Kevin Melberger's post. |

**Notes**: Overlaps with previous; many LIKES on advocacy content (e.g., Jacob Kraniak/Tim Jonson posts, Planet Networks).

## Uploaded Image: Brookhaven Meeting
The image shows a town hall auditorium with attendees, a stage with officials/flags, and a hand sanitizer station. Matches the "Brookhaven Town Voting on New Fiber provider" event (2023-03-30). Low attendance; speaker at podium.

- **Suggested Repo Placement**: Upload as `/resources/media/events/brookhaven-meeting-2023.jpg` (rename for clarity).
- **Alt Text**: "Photo of Brookhaven Town Hall during public hearing on OCG fiber license, showing sparse audience and council stage."
- **Reference**: Link in `/initiatives/legal-advocacy.md` or events-archive.md: `![Brookhaven Meeting](./media/events/brookhaven-meeting-2023.jpg)`

**Final Notes**: This completes the FB export parsing—repo now has comprehensive social archives. Suggest creating a master `/resources/social/facebook/README.md` indexing all summaries (profile, posts, groups, pages, events, comments-likes). For Obsidian: Add these MDs to your vault; use plugins like dataview for timelines. If ready, add a CONTRIBUTING.md for future contributors.