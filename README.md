# NEXUS Terminal Bible

Interactive, gated terminal command reference by AntManThePro. 125+ curated
commands across FUN, VISUAL, ASCII ART, GAMES, AUDIO, SYS INFO, NETWORK,
SYSADMIN, SEC / HACKING, CURL TRICKS, ONE-LINERS and WIZARDRY — with live
search, category filtering, one-click copy, and a directions guide.

- **Access:** gated. The gate hashes the entry code with SHA-256 (Web Crypto
  API) and remembers the unlock in sessionStorage only. The entry code is
  **GODMODE** — it is printed on the gate screen, in the page meta, and in
  this README by the author's own design. It is a theatrical gate for a
  reference app, not a credential to any real system; there is no account,
  no backend, and nothing to protect.
- **Offline:** yes, apart from Google Fonts (Share Tech Mono / Orbitron /
  Exo 2, with system fallbacks). No fetch/XHR calls, no analytics, no
  tracking. All command data is embedded in the page.
- **Saves:** none — the only storage is the sessionStorage unlock flag.
- **License:** MIT (see LICENSE).

## Which variant this is

Six Terminal Bible files exist across the phone and Drive batches. This build
is the newest and most complete: `index.html` from
`nexus-terminal-bible-github-ready.zip` (65,383 bytes, "v4 HUGE EDITION",
title "NEXUS // Terminal Bible"), dated Aug 8, 2026. It already had zero
banned-branding hits, a proper web manifest, an SVG icon, and MIT licensing
— unlike the other variants:

- `NexusTerminalBible.html` / v2 zip `index.html` (64,731 bytes, "Mega
  Terminal Bible", 130 commands claimed) — same command data (39 diff
  lines), but 3 godmode2025.net hits and no PWA manifest.
- `TerminalBible.html` / `Terminal_Bible.bin` (48,333 bytes, "Mega Terminal
  Bible — Full Preview") — older, smaller preview; 2 banned hits.
- `NexusTerminalBiblePreview.html` / `nexushtml.html` (47,414 bytes) — same
  preview lineage; 2–3 banned hits.
- `nexus-mega-bible1.html` (50,960 bytes, "MEGA TERMINAL BIBLE") — 4 banned
  hits.
- `real-nexus-terminal-bible-v1.html` / `nexus-terminal-bible-v1.html`
  (31,126 bytes, "Hidden Ones") — a different, smaller lore/reference
  variant, not the command bible; 1 banned hit.

No code changes were needed for this build: only icon/manifest links were
added to `<head>` (PNG icon set in `icons/`, `manifest.json` alongside the
original `manifest.webmanifest`), and the original `icon.svg` is kept.

## Live

https://terminal-bible.netlify.app/

## How to use

1. Open the live site and enter the access code printed on the gate screen.
2. Search any command, or filter by category (FUN, GAMES, NETWORK, SEC / HACKING…).
3. Tap a card to copy the command, then paste it in your own terminal.
4. Open the directions guide in-app for WSL, dual-boot, and safety commandments.

## Links

- Live site: https://terminal-bible.netlify.app/
- NEXUS World Hub: https://nexus-world-hub.netlify.app/
- Repo: https://github.com/AntManThePro/terminal-bible
