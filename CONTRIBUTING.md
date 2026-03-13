# Contributing

Thanks for your interest in improving RSVP Speed Reader.

## Ways to contribute

- **Bug reports** — Open an issue with steps to reproduce
- **ORP improvements** — The focal position algorithm is based on the Spritz patent; if you have access to more recent eye-tracking research with better breakpoints, PRs are welcome
- **New file format parsers** — EPub, RTF with better fidelity, HTML stripping
- **Accessibility** — `aria-live` announcements, high-contrast mode

## Development

No build step required:

```bash
git clone https://github.com/your-username/rsvp-speed-reader.git
cd rsvp-speed-reader
open index.html   # or any static server
```

## Code style

- Vanilla JS only for core logic (no frameworks)
- Add a comment explaining *why* for any non-obvious decision
- Keep the single-file architecture for `speed-reader.html`

## Pull request checklist

- [ ] Tested in Chrome, Firefox, and Safari
- [ ] Works offline for TXT input (no CDN dependency in core path)
- [ ] Code comments explain the *why*, not just the *what*
