# Inbox Signal

A weekly digest of the newsletters received at newsletter@msar.me. Each issue is a standalone HTML page that collects the linked items worth reading from that week's inbox.

Everything in this repository is published at **https://pockets.msar.me/signals**.

## Issues

| Week ending | Page |
| --- | --- |
| 12 Oct 2026 | [Inbox-Signal-2026-10-12.html](https://pockets.msar.me/signals/?file=Inbox-Signal-2026-10-12.html) |
| 5 Oct 2026 | [Inbox-Signal-2026-10-05.html](https://pockets.msar.me/signals/?file=Inbox-Signal-2026-10-05.html) |
| 28 Sep 2026 | [Inbox-Signal-2026-09-28.html](https://pockets.msar.me/signals/?file=Inbox-Signal-2026-09-28.html) |
| 21 Sep 2026 | [Inbox-Signal-2026-09-21.html](https://pockets.msar.me/signals/?file=Inbox-Signal-2026-09-21.html) |
| 14 Sep 2026 | [Inbox-Signal-2026-09-14.html](https://pockets.msar.me/signals/?file=Inbox-Signal-2026-09-14.html) |
| 7 Sep 2026 | [Inbox-Signal-2026-09-07.html](https://pockets.msar.me/signals/?file=Inbox-Signal-2026-09-07.html) |
| 31 Aug 2026 | [Inbox-Signal-2026-08-31.html](https://pockets.msar.me/signals/?file=Inbox-Signal-2026-08-31.html) |
| 26 Aug 2026 | [Inbox-Signal-2026-08-26.html](https://pockets.msar.me/signals/?file=Inbox-Signal-2026-08-26.html) |

## RSS feed

Every linked item from an issue is also available as an RSS 2.0 feed in `feed/`:

- [feed/rss-2026-10-12.xml](https://pockets.msar.me/signals/feed/rss-2026-10-12.xml) (week of 5–12 Oct 2026)

### Feed format

Each feed is RSS 2.0 and contains one `<item>` per link in the issue:

| Element | Value |
| --- | --- |
| `<title>` | The link's headline as shown in the issue |
| `<link>` | The article URL, exactly as in the issue |
| `<description>` | The one-line summary from the issue, when there is one |
| `<source>` | The newsletter the item came from (e.g. `TLDR Dev`) |
| `<guid isPermaLink="true">` | Same as `<link>` |
| `<pubDate>` | The newsletter email's date in RFC 822 format, Asia/Dhaka time (e.g. `Sun, 11 Oct 2026 08:00:00 +0600`) |

The channel `<link>` is the issue's file name only (e.g. `Inbox-Signal-2026-10-12.html`). Feeds never contain local directory paths or `file://` URLs. The feed date is the issue's run date in Asia/Dhaka time.

## Layout

```
Inbox-Signal-YYYY-MM-DD.html   one page per weekly issue, named by the issue date
feed/rss-YYYY-MM-DD.xml        RSS feed of the items in that issue
```

## Adding a new issue

1. Add the new `Inbox-Signal-YYYY-MM-DD.html` to the repo root and its `feed/rss-YYYY-MM-DD.xml` to `feed/`.
2. Add a row to the top of the **Issues** table above, and a line under **RSS feed** if there's a new feed.
3. Commit and push. Once deployed, the new files are available under `https://pockets.msar.me/signals/`.
