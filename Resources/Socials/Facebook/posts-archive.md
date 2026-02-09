# Facebook Posts and Media Archive

This file extends the Facebook archive summary with posts, edits, photos, albums, and other activity from the export JSONs. Focus on public/FIC-relevant content (e.g., advocacy posts, surveys, events). Sanitized: Removed or noted private details (e.g., IPs, exact user agents). Raw JSONs in private repo `fic-admin-private`.

## Posts Timeline (from profile_posts_1.json)
Key posts from the page (chronological, starting 2021). Attachments are mostly links or photos (URIs point to export media folders—upload images to `/resources/social/facebook/media/` if sharing publicly). Titles indicate action (e.g., "shared a link").

| Date (UTC)         | Title                                      | Post Content / Description / Link Excerpt                                      |
|--------------------|--------------------------------------------|--------------------------------------------------------------------------------|
| 2023-01-31 18:48:28 | Fair Internet Coalition shared a link.     | Link: https://fairinternetcoalition.org/complaint-forms/                       |
| 2023-02-23 16:20:52 | Fair Internet Coalition shared a link.     | Link: https://investors.alticeusa.com/news-events/press-releases/detail/161/altice-usa-announces-new-appointments-to-its-leadership |
| 2023-03-07 22:24:38 | Fair Internet Coalition shared a link.     | Link: https://www.axios.com/2023/03/07/fcc-nomination-biden-gigi-sohn          |
| 2023-03-20 20:02:39 | Fair Internet Coalition shared a post.     | (Empty URL—possible shared post; check export for details)                     |
| 2023-03-20 20:07:18 | Fair Internet Coalition shared a link.     | Link: https://www.whec.com/top-news/nys-assembly-proposes-streaming-tax/       |
| 2023-03-21 20:35:18 | Fair Internet Coalition shared a link.     | Link: https://www.townshipjournal.com/home/planet-networks-expects-to-cover-sussex-county-by-end-of-2024-EK2396521?mibextid=5zvaxg |
| ... (truncated for brevity; full list in raw JSON) | ... | ... |
| 2022-11-24 16:34:38 | Fair Internet Coalition added a new photo. | "From all of us at FIC, we hope you have a happy and healthy Thanksgiving!" (with photo) |
| 2022-12-23 21:34:38 | Fair Internet Coalition added a new photo. | "We at FIC wish all our followers a very Happy Holidays!" (with holiday photo) |
| 2022-12-26 16:01:45 | Fair Internet Coalition added a new photo. | "FOR IMMEDIATE RELEASE\n\nLOCAL INTERNET PROVIDER FILES PETITION WITH NY PSC, CLAIMING VERIZON ENGAGED IN ILLEGAL ANTI-COMPETITIVE PRACTICES\n\nhttps://fairinternetcoalition.org/2022/12/26/ocg-v-verizon/\n\n#digitaldivide #broadbandforall #internetforall #internetserviceprovider #broadband" (with photo) |

**Notes**: 
- Many posts are shares of external links (e.g., news on FCC, Altice leadership, streaming taxes, Planet Networks expansion).
- Advocacy themes: Surveys, OCG fiber votes, Verizon petitions, holiday messages.
- Truncated entries in export (e.g., full post text cut off)—cross-reference with images/descriptions in uncategorized_photos.json.
- For revival: These show outreach patterns (e.g., hashtags like #canceloptimum, #broadbandforall).

## Post Edits (from edits_you_made_to_posts.json)
Edits to existing posts (timestamps indicate edit time).

| Edit Date (UTC)    | Post ID          | Edited Text                                                                    |
|--------------------|------------------|--------------------------------------------------------------------------------|
| 2023-12-07 15:24:28 | 747309160722078  | "I have reached 100 followers! Thank you for your continued support. I could not have done it without each of you. 🙏🤗🎉" |
| 2023-03-21 12:38:01 | 593994699386859  | "Exciting news from our friends @[492357730953876:274:Planet Networks]! If you live in the North NJ area and are looking for a competitive option for High-Speed FIBER internet service, make sure to sign up!\n\nhttps://www.townshipjournal.com/home/planet-networks-expects-to-cover-sussex-county-by-end-of-2024-EK2396521" |

## Photos and Albums (from uncategorized_photos.json, 0.json, 1.json, 2.json, 3.json, 4.json)
Summarized albums and uncategorized photos. URIs are export paths—rename/upload actual images (e.g., PNG/JPG) to repo subfolder like `/resources/social/facebook/media/`. Descriptions often tie to advocacy (e.g., surveys, events, memes).

### Uncategorized Photos (uncategorized_photos.json)
| Creation Date (UTC)| URI Path (export)                              | Description / Hashtags                                                         |
|--------------------|------------------------------------------------|--------------------------------------------------------------------------------|
| 2021-04-01 16:26:06 | your_posts/113458727504849.png                 | (No desc; possible meme or graphic)                                            |
| 2021-04-06 16:56:31 | your_posts/116364597214262.png                 | "@[998319860688646:69:Tri-State Coalition for Fair Internet Service] wants YOU to help fight for fair and transparent internet service on Long Island. \n\nOptimum/Altice cannot control a monopoly of service forever." |
| 2021-04-09 23:48:37 | your_posts/117798207070901.png                 | "Have you had a bad experience with Optimum/Altice Internet/TV Service? Are you tired of being stuck in a monopoly? We want to hear about it! \n\nComplete the survey linked below and share your comments. Help us build a case to show the extent of these issues!\n\nhttps://tscfis.org/optimum-survey/" |
| ... (truncated)    | ...                                            | ...                                                                            |
| 2023-03-30 12:52:48 | your_posts/599038462215816.jpg                 | "On March 30th at 5:30pm, Brookhaven Town will be voting on a license agreement with OCG Communication for a new FIBER NETWORK on Long Island!\n\nhttps://fairinternetcoalition.org/2023/03/24/brookhaven-voting-on-ocg-license/\n\nPlease consider attending to show your support!\n\nSee the calendar on our website for meeting details." |
| 2023-03-30 15:19:15 | your_posts/599091082210554.jpg                 | (No desc; possible event photo)                                                |
| 2023-03-30 21:35:55 | your_posts/599306762188986.jpg                 | "Present!" (likely at Brookhaven meeting)                                      |

### Albums Summary
- **Cover Photos (0.json)**: 4 entries (2021–2023), evolving banners (e.g., initial PNG, later JPGs).
- **Instagram Photos (1.json)**: 3 photos (2021), e.g., "#alticeiscancelled" in locations like Ronkonkoma, Centereach; event promo for YouTube.
- **Mobile Uploads (2.json)**: 6 photos (2021–2023), e.g., HughesNet ad critique, Spectrum monopoly graphic, Optimum outage confirmations, 100 followers milestone.
- **Photos (3.json)**: 20+ entries (2021–2023), heavy on advocacy (e.g., NJBPU updates, TV antenna lawsuit, survey promos, Biden infrastructure, Starlink, OCG fiber).
- **Profile Pictures (4.json)**: 1 recent PNG (2023-01-25), plus historical.

**Upload Tip**: For images, commit to GitHub with messages like "Added Facebook media exports: profile pics and advocacy graphics". Use subfolders (e.g., `/media/cover/`, `/media/posts/`).

## Other Activity
- **Host Q&A (your_host_q&a.json)**: Single entry (2021-04-18): Message "Did you complete the survey? We need your help!" (update 2025-05-01—possible error).
- **Places Tagged (places_you_have_been_tagged_in.json)**: 5 locations (2021–2025), e.g., Brookhaven Town Hall (2023-03-30, Android), Bridgeport CT (2024-07-04, iPhone). Ties to events (e.g., meetings).
- **Facebook Editor Responses (facebook_editor.json)**: 16 edits/questions answered (2021–2023) on pages like Drive Electric Long Island (addresses), Sagamore Hills (duplicates), Internet Society NY (website/category), Out of Spec Reviews (website/sales). Shows community involvement.

Create as `/resources/social/facebook/posts-archive.md`. For images in next reply: Paste file names or small previews if needed; I'll suggest organization.