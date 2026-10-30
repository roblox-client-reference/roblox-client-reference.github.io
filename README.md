# Roblox Client Reference

An independent reference index of client-side runtime tools for Roblox.
Each entry collects what public records state, separates verified data from
unverified fields, and keeps the caveats attached.

**Live site:** https://roblox-client-reference.github.io/

---

## About

This repository hosts a static reference index. It does not distribute,
host, or mirror any software. Every profile links to a third-party
documentation page and summarizes what that page records.

The index is not affiliated with Roblox Corporation. Modifying the Roblox
client violates Roblox Terms of Use.

---

## Profiles

| Tool | Entry |
|---|---|
| Wave | [View profile](https://reference-1.gitbook.io/roblox-wave/) |
| Volt | [View profile](https://reference-1.gitbook.io/roblox-volt/) |
| Solara | [View profile](https://reference-1.gitbook.io/roblox-solara/) |

---

## Structure

```
.
├── index.html      # reference index (GitHub Pages entry point)
├── README.md       # this file
├── sitemap.xml     # single-URL sitemap for the index page
└── robots.txt      # crawl policy
```

---

## How entries are written

Each profile follows the same rules:

- **Verified vs unverified** — a field is either traced to a public record
  or explicitly marked as untraced. No guessed values are presented as facts.
- **Coverage ≠ safety** — a function coverage score describes implemented
  functions, not whether a build is safe.
- **Detection note ≠ malware verdict** — a tracker flag records an
  observation, not a binary analysis.
- **No binaries** — no entry executes, sandboxes, or inspects any file.

---

## Disclaimer

This repository is provided for informational and research purposes only.
It is not affiliated with, endorsed by, or sponsored by Roblox Corporation
or any tool developer. Modifying the Roblox client violates Roblox Terms of
Use. Readers are responsible for their own compliance with applicable
policies.
