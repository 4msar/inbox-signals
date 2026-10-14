# Inbox Signal

A weekly digest of the newsletters received at newsletter@msar.me. Each issue is a standalone HTML page that collects the linked items worth reading from that week's inbox.

Everything in this repository is published at **https://pockets.msar.me/signals**.

## Issues

| Week ending | Page |
| --- | --- |
| 12 Oct 2026 | [Inbox-Signal-2026-10-12.html](https://pockets.msar.me/signals/Inbox-Signal-2026-10-12.html) |
| 5 Oct 2026 | [Inbox-Signal-2026-10-05.html](https://pockets.msar.me/signals/Inbox-Signal-2026-10-05.html) |
| 28 Sep 2026 | [Inbox-Signal-2026-09-28.html](https://pockets.msar.me/signals/Inbox-Signal-2026-09-28.html) |
| 21 Sep 2026 | [Inbox-Signal-2026-09-21.html](https://pockets.msar.me/signals/Inbox-Signal-2026-09-21.html) |
| 14 Sep 2026 | [Inbox-Signal-2026-09-14.html](https://pockets.msar.me/signals/Inbox-Signal-2026-09-14.html) |
| 7 Sep 2026 | [Inbox-Signal-2026-09-07.html](https://pockets.msar.me/signals/Inbox-Signal-2026-09-07.html) |
| 31 Aug 2026 | [Inbox-Signal-2026-08-31.html](https://pockets.msar.me/signals/Inbox-Signal-2026-08-31.html) |
| 26 Aug 2026 | [Inbox-Signal-2026-08-26.html](https://pockets.msar.me/signals/Inbox-Signal-2026-08-26.html) |

## RSS feed

Every linked item from an issue is also available as an RSS 2.0 feed in `feed/`:

- [feed/rss-2026-10-12.xml](https://pockets.msar.me/signals/feed/rss-2026-10-12.xml) (week of 5–12 Oct 2026)

## Layout

```
Inbox-Signal-YYYY-MM-DD.html   one page per weekly issue, named by the issue date
feed/rss-YYYY-MM-DD.xml        RSS feed of the items in that issue
```

## Adding a new issue

1. Add the new `Inbox-Signal-YYYY-MM-DD.html` (and its `feed/rss-YYYY-MM-DD.xml`, if generated) to the repo root.
2. Add a row to the top of the **Issues** table above, and a line under **RSS feed** if there's a new feed.
3. Commit and push. Once deployed, the new files are available under `https://pockets.msar.me/signals/`.
