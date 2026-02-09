# Facebook Events Archive

This file summarizes FIC's event-related activity from the Facebook export JSONs (event_responses.json, your_event_invitation_links.json, events.json, events_you_hosted.json). FIC hosted/joined events focused on advocacy meetings, live streams (FIC.TV), public hearings (e.g., fiber licenses), and webinars (e.g., BEAD funding). Raw JSONs migrated to `/resources/social/facebook/raw/events/`—no PII apparent (event names/descriptions public). Timestamps up to 2023; events likely dormant now.

## Hosted Events (from events_you_hosted.json)
Events created/hosted by FIC. Includes status, onboarding flag, and completed actions (e.g., sharing, discussions). Sorted by creation timestamp (descending).

| Event Name                                      | Creation Date (UTC)      | Start/End (UTC)          | Status         | Onboarding? | Actions Completed                          | Host                  |
|-------------------------------------------------|--------------------------|--------------------------|----------------|-------------|--------------------------------------------|-----------------------|
| Brookhaven Town Voting on New Fiber provider    | 2023-03-30 15:22:48      | 2023-03-30 17:30:00 / N/A | Dismissed      | Yes        | Add cover photo, Share on Page, Start discussion, Share in Group, Pin to Featured | Fair Internet Coalition |
| FIC.TV - LIVE                                   | 2022-05-22 20:30:11      | 2022-12-27 00:00:00 / 2022-12-27 01:00:00 | Started        | Yes        | Share on Page, Start discussion, (other completed) | Fair Internet Coalition |
| TSCFIS General Membership Meeting - Casual Meet&Greet | 2021-09-30 20:53:36    | 2021-09-30 21:00:00 / 2021-09-30 22:00:00 | Started        | Yes        | Share on Page, Start discussion, (other completed) | Fair Internet Coalition |
| TSCFIS LIVE! - Featuring Jessica Singleton, Liaison for NY-46 | 2021-04-12 20:42:16 | 2021-04-12 21:00:00 / 2021-04-12 22:00:00 | Completed      | Yes        | Share on Page, Start discussion, (other completed) | Fair Internet Coalition |
| ... (full list in raw; truncated for brevity—many FIC.TV streams, TSCFIS meetings) | ... | ... | ... | ... | ... | ... |

**Notes**: Actions show promotion efforts (e.g., sharing to groups/pages). Descriptions (from events.json) detail agendas: Guest speakers (e.g., Senator liaisons), survey updates, fiber advocacy. For "Brookhaven": Public hearing on OCG license.

## Joined Events (from event_responses.json and events.json)
Events FIC joined/created (overlaps with hosted). Detailed descriptions extracted—focus on advocacy (e.g., NTIA BEAD funding, PSC hearings, local civics).

| Event Name                                      | Creation Date (UTC)      | Start/End (UTC)          | Location / Place                          | Description Excerpt |
|-------------------------------------------------|--------------------------|--------------------------|-------------------------------------------|---------------------|
| Brookhaven Town Voting on New Fiber provider    | 2023-03-30 15:22:48      | 2023-03-30 17:30:00 / N/A | Brookhaven Town Hall (40.84362, -73.01558; 1 Independence Hl, Brookhaven, NY 11738) | "NOTICE IS HEREBY GIVEN... public hearing... License Agreement between the Town of Brookhaven and Optical Communications Group, Inc., for... fiber-based internet network." |
| FIC.TV - LIVE                                   | 2022-12-26 21:00:00      | 2022-12-27 00:00:00 / 2022-12-27 01:00:00 | Online (livestream)                      | "On our May 23rd Livestream, we'll be having a guest speaker... As always, please join us on YouTube..." (recurring series on surveys, advocacy) |
| TSCFIS General Membership Meeting - Casual Meet&Greet | 2021-09-30 20:53:36    | 2021-09-30 21:00:00 / 2021-09-30 22:00:00 | Online (Zoom/Discord)                    | "Come join us for a casual meet and greet... Discuss the future of TSCFIS and how we can help..." |
| TSCFIS LIVE! - Featuring Jessica Singleton, Liaison for NY-46 | 2021-04-12 20:42:16 | 2021-04-12 21:00:00 / 2021-04-12 22:00:00 | Online (livestream)                      | "The Office of Senator Michelle Hinchey... meeting with Jessica Singleton... first attempt at a livestream..." |
| TSCFIS General Membership Meeting               | 2021-04-26 16:35:00      | 2021-04-26 17:00:00 / N/A | Online                                   | "If you'd like to join us... volunteering... Skills: Web Design, Marketing..." |
| ... (truncated; many FIC.TV episodes on topics like Optimum surveys, Biden infrastructure, Starlink, PSC hearings) | ... | ... | ... | ... |

**Notes**: Events span 2021–2023; many online (YouTube/Discord/Zoom). Recurring: FIC.TV for updates, TSCFIS for membership/outreach.

## Event Invitation Links (from your_event_invitation_links.json)
~100+ links (all still valid as per export). Duplicates for key events—likely shared multiple times. Grouped by unique event.

| Event Name                                      | Sample FBID              | Notes |
|-------------------------------------------------|--------------------------|-------|
| July 5, 2023 – How Did NTIA’s Allocation of BEAD Funding Compare? | 1337527943543719        | Webinar on broadband funding; most entries (~80). |
| TSCFIS General Membership Meeting - Casual Meet&Greet | 936495303834755         | Casual advocacy meetup; ~10 entries. |
| TSCFIS LIVE! - Featuring Jessica Singleton, Liaison for NY-46 | 826567114606678         | Senator liaison meeting; ~5 entries. |
| ... (full in raw; others like FIC.TV streams, local hearings) | ... | ... |

**Notes**: Links for promotion—e.g., shared in groups/pages. For revival: Test links; archive descriptions/screenshots if live.

**Revival Tips**: Events were core to outreach (e.g., Brookhaven fiber vote, PSC testimony). If restarting, recreate similar on new platforms (e.g., YouTube, Discord). Upload any event media (e.g., livestream clips) to `/resources/media/events/`.