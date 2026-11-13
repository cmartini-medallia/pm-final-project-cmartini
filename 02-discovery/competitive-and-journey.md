# Competitive Analysis & Journey Map (Module 2)

## Responses
- **Role, who are you solving for? (the specific user segment or profile):** A dispatcher coordinating a regional delivery fleet in real time, day or night shift, at a mid-size 3PL or enterprise account.
- **Goal, what is this user ultimately trying to achieve?:** Absorb same-day disruptions and keep every driver on the right stop from a single board she can trust.
- **Friction, the main barrier (moment of misery) stopping them from succeeding:** She reassigns a route, and it takes 8 to 15 minutes to reach the driver, with no notification, so drivers head the wrong way before the change lands (BUG-2044, UXR-02). In the other direction, her board shows completed stops as “in progress” for up to an hour (BUG-2072, UXR-09). She can’t trust RouteLogic in either direction during the moments it exists for. That’s why a WhatsApp group has become what one dispatcher calls “the real system.”
- **External tools, the outside platforms or tools the user is forced to use:** Two sets of outside tools show up in the research: the dispatcher’s own channels, and the drivers’ fallbacks that she ends up supporting.

Her own channels:

WhatsApp group: the live coordination channel (UXR-02).
Phone calls: to drivers, including the office reading stops aloud after a crash (UXR-03).
Texts from drivers: confirming deliveries outside the app (UXR-01).

Driver fallbacks she has to support:

Paper manifests: five of seven drivers keep one (UXR-12).
Morning route screenshots: used on rural routes (UXR-06).
- **The process, the 3 to 5 manual steps the user takes to get the job done:** Reassign in RouteLogic as the record. When a disruption hits, she makes the change in RouteLogic first, because it’s the system of record.
Repeat it in WhatsApp or by phone. The change takes 8 to 15 minutes to land and sends no alert (BUG-2044), so she posts it in the group or calls the driver directly.
Track real status from messages, not the board. Drivers confirm deliveries by text instead of the three-screen flow (UXR-01, BUG-2055). Her dashboard lags 20 to 60 minutes (BUG-2072), so she reconstructs where everyone is from the chat.
Talk drivers through failures by phone. When the app crashes on a long route, the office reads the remaining stops aloud (UXR-03, BUG-2031).
Reconcile RouteLogic afterward. Updates that happened in messages get entered later, if at all. This step is inferred from the texting behavior, not observed directly.
- **Core frustration, the exact moment the process feels most “broken”:** The minutes right after a reassignment. She can’t tell whether the driver has the new route, and the board still shows stops finished an hour ago.
- **The evidence, a specific quote or behavior from the research that proves this:** A mid-size 3PL dispatcher says drivers don’t see reassignments for 10 to 15 minutes and drive the wrong way in the meantime, so the team’s WhatsApp group has become “the real system” (UXR-02, BUG-2044).
- **Your journey map, a shareable link, or the map file you committed (e.g. journey-map.html):** uploaded alongside the prompt
