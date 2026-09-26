# Team time

Four recurring Monday–Sunday calendars on GitHub Pages, with green (free), yellow (maybe), and red (unavailable) ranges.

## Use

Select an unclaimed calendar, enter your name, and choose **Claim this calendar via GitHub**. Submit the prefilled issue, return, and refresh. The first GitHub author owns that calendar. Subsequent submissions from any other account are ignored, including attempted access restores.

After claiming, drag empty calendar space to create ranges, drag ranges to move them, and drag their top/bottom edges to resize. Click a range to change its color or remove it. Choose the paint color above the calendars. Click **Save via GitHub**, submit the issue, and refresh to share changes.

The browser remembers an editing identifier. Claimed calendars are locked in other browsers. The owner can choose **Restore my editing access via GitHub** and submit using the original GitHub account. This transfers editing access to the new browser. The identifier controls UI access; GitHub issue authorship is the authority for shared updates, not the identifier. No GitHub tokens are embedded or requested.

## Weekly timezones

Schedules repeat weekly in the timezone used when saved. The view converts them to the selected timezone for the current week, including Sunday/Monday boundaries. There is no date navigation. Device timezone detection requires no location permission. Daylight-saving gaps are omitted for that week; ambiguous repeated times use the occurrence resolved by the timezone conversion.

Schedules and names are public. GitHub API read limits apply. Refresh retrieves shared changes; drafts stay on the device. The earliest valid weekly claim in issue creation order determines ownership. Avoid editing old issue bodies; submit new updates. Repo owners can moderate claims by removing their issues. This is a simple public planner, not a private calendar service.

GitHub Pages deploys the repository root from `main`. No build or dependencies.
