# PortWatch VI — Privacy Policy

_Last updated: 25 November 2026_

PortWatch VI is a Chrome extension that displays the GTA VI PC port leaderboard published at portwatch-vi.xyz.

## What the extension stores

All storage happens inside your browser:

- **The last leaderboard snapshot** — a copy of the public tracker data, kept so the badge and popup can render instantly without a network call.
- **Your watchlist** — the projects you star. This is stored with `chrome.storage.sync` so it follows your Chrome profile if you enable Chrome Sync.
- **Your preferences** — notification toggles.
- **The archive** — the last known score, peak, stage and dates for each project seen, kept so that deleted projects remain visible.

## What the extension sends

One outbound request every 15 minutes: a `GET` to `https://portwatch-vi.xyz/data/tracker.json`.

That request carries no identifiers, no cookies are read, and no body is sent. It is the same public file any visitor to the site can download. No other host is contacted.

## What the extension collects

Nothing. There is no account, no analytics, no telemetry, no crash reporting, no advertising and no third-party SDK. The developer receives no data about you or your usage.

## Permissions and why

| Permission | Reason |
|---|---|
| `storage` | Save the snapshot, watchlist, preferences and archive |
| `alarms` | Run the 15-minute background refresh |
| `notifications` | Alert you when a watched project changes |
| `https://portwatch-vi.xyz/*` | Fetch the public tracker feed |

## Third parties

The only third party involved is portwatch-vi.xyz, which serves the public data. Its own privacy policy governs that server's logs, not this extension.

## Removing your data

Uninstalling the extension deletes everything it stored locally. A synced watchlist can also be cleared from Chrome's sync settings.

## Changes

Any change to this policy will be published at the same URL with an updated date.

## Contact

Open an issue on the project's repository, or write to the address listed on the extension's store page.

---

PortWatch VI is an unofficial fan project. It is not affiliated with Rockstar Games, Take-Two Interactive or Microsoft.
