### Nicholas Vormack

Independent IT consultant — ten years supporting small
businesses and private clients: Windows, networking, security, hardware, data.
B.S. Computer Science, MBA. I build tools to understand problems properly, then
document them so the next person does not have to reverse-engineer my thinking.

---

## What to look at first

### [VECTOR](https://github.com/NicholasVormack/vector-terminal) · [live demo](https://nicholasvormack.github.io/vector-terminal/)

A research terminal for markets that never got one: Old School and RS3 Grand Exchange
items, crypto and graded collectibles, every gp figure also priced in dollars. The
candles, axes, crosshair and heatmap are hand-written SVG — no charting library — and
the same event-driven engine backs four venues with their real costs: 2% GE tax and buy
limits, 10bps taker fees, whole-unit item sizing against fractional coin sizing. When a
metric has no data behind it the panel says so instead of printing a zero.

`TypeScript` `React` `Vite` — no charting, UI or CSS library

### [WallStreetVerse](https://github.com/NicholasVormack/WallStreetVerse) · [live demo](https://nicholasvormack.github.io/WallStreetVerse/)

A multiplayer trading-floor world with a server-authoritative simulation engine.
Three connected zones on a 20 Hz tick loop: client prediction and reconciliation,
snapshot interpolation, and portal-based zone transfers gated behind single-use
Redis tokens.

`TypeScript` `Phaser 3` `Colyseus` `Node` `PostgreSQL` `Redis`

### [ReconX](https://github.com/NicholasVormack/ReconX)

A dependency-free network surface scanner that explains what it finds. Every open
port carries a severity and a one-line rationale, the host gets a letter grade,
and results export to JSON, CSV, Markdown or a self-contained HTML report. Optional
Nmap enrichment, TLS certificate inspection, and no third-party packages at all.

`Python` `sockets` `concurrency` `security` — 55 unit tests

### [NoteMaster](https://github.com/NicholasVormack/NoteMaster) · [live demo](https://notemaster-6b0lj3.freebuff.site)

A note-taking app for video-anchored notes: rich-text editing against a YouTube
timestamp, server-side search, tags and pinning. The interesting part is the
cleanup — a leaked database password, a login that issued tokens for wrong
passwords, and a missing ownership check on every note route, each documented in
the README with the fix. The live demo runs the same client against a Workers + D1
build of the API, so it works without a MongoDB instance behind it.

`React` `Node` `Express` `MongoDB` `Cloudflare Workers` `D1`

## How I work

I care about the parts that are easy to skip: making the failure modes explicit,
writing the README before the polish, and being honest in documentation about what
is finished and what is not.

📫 [n.vormack@gmail.com](mailto:n.vormack@gmail.com) · [LinkedIn](https://linkedin.com/in/nvorm)
