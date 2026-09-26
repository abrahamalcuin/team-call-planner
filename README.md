# Team time

Four shared weekly availability calendars, hosted on GitHub Pages. No build or dependencies.

Choose a calendar, enter your name, add exact start/end times, and select **Save via GitHub**. Green means completely free, yellow means maybe/flexible, and red means unavailable. Blank means not set. Click a range or use the range list to edit it. New ranges replace overlapping statuses. Submit the prefilled issue, return to the planner, and refresh. First valid submission claims a calendar for its GitHub author; only subsequent issues by that author update it. Names and availability are public. GitHub login is required to share changes, but viewing requires no login.

Timezone switching converts the same absolute instants for every calendar. **My timezone** uses the device timezone without requiring location permission. All 24 hours are available by scrolling. Daylight-saving gaps are rejected; ambiguous repeated times use the occurrence resolved by the timezone conversion. The wall-clock display compresses daylight-saving repeated hours.

Availability persists in GitHub issues. Drafts and display preferences persist locally. Each submission replaces that member's schedule. Avoid editing one member's schedule on multiple devices at once; discard old drafts and refresh before editing elsewhere. Past blocks older than 35 days are dropped on save. Do not edit or delete historical schedule issue bodies; submit a new schedule instead. Repository owners can moderate incorrect claims by removing the corresponding issues. No account tokens are embedded or requested by the site.

## Deployment

GitHub Pages publishes the root of the `main` branch. Public GitHub API read limits apply; use Refresh to retrieve updates. This is a simple public team planner, not a private calendar service.
