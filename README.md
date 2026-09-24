<img src="anim_dusk_sub1mb.png" width="200" align="right" alt="Animated pixel-art sea at dusk">

# Eric Jingryd

Software engineer in Gothenburg, Sweden. I build secure, well-tested software,
mostly in Rust, with TypeScript and Python where they fit the job better.
Looking for a software engineering role in Gothenburg, Stockholm, hybrid or
remote.

More on [ericjingryd.com](https://ericjingryd.com) and
[LinkedIn](https://www.linkedin.com/in/eric-jingryd/).

## Open source

### Security

| Project | What it is |
|---|---|
| [linux-hardener](https://github.com/tidynest/linux-hardener) | Scans and hardens Linux systems, maps findings to ten compliance frameworks and rolls changes back from Ed25519-signed checkpoints. 2,300+ tests, six distributions, on the [AUR](https://aur.archlinux.org/packages/linux-hardener). |
| [raven-nest-mcp](https://github.com/tidynest/raven-nest-mcp) | MCP server that gives AI assistants controlled access to 22 security tools behind six safety layers. Listed in the official MCP Registry. |
| [raven-nest-client](https://github.com/tidynest/raven-nest-client) | TypeScript and Bun client for it, with 112 tests. |
| [security_toolkit](https://github.com/tidynest/security_toolkit) | CLI for password checks, file hashing and TCP port scans. |

### Systems

| Project | What it is |
|---|---|
| [hypr-keybind-manager](https://github.com/tidynest/hypr-keybind-manager) | GTK4 keybinding manager for Hyprland with conflict detection. On the [AUR](https://aur.archlinux.org/packages/hypr-keybind-manager). |
| [lanner](https://github.com/tidynest/lanner) | Records one region of the screen on wlroots compositors. Everything outside the region stays dimmed while you select it, and the overlay never shows up in the video. |
| [CommandVault](https://github.com/tidynest/CommandVault) | Desktop app for storing, searching and copying shell commands, built with iced. |
| [tv-tabla](https://github.com/tidynest/tv-tabla) | Desktop TV guide for Swedish television, built with Tauri and SolidJS. |
| [system_monitor](https://github.com/tidynest/system_monitor) | Live CPU, memory, disk, network and process dashboard, with Actix-web and HTMX over Server-Sent Events. |

### Automation

| Project | What it is |
|---|---|
| [headless-wayland-harness](https://github.com/tidynest/headless-wayland-harness) | Runs a Wayland GUI app inside an isolated headless sway, so an agent or CI job can click, type and take screenshots without touching the desktop you are using. |
| [gitbye](https://github.com/tidynest/gitbye) | Keeps a history of your GitHub follow graph and unfollows accounts that followed you, collected the follow-back and then left. |
| [web_scraper](https://github.com/tidynest/web_scraper) | CLI that crawls a site breadth-first and exports titles, links, headers and meta tags as text, JSON, HTML, CSV or XML. |
| [repo_exporter](https://github.com/tidynest/repo_exporter) | Exports a GitHub repository to a single Markdown file. |

### Algorithms

| Project | What it is |
|---|---|
| [bitnet-toy](https://github.com/tidynest/bitnet-toy) | BitNet b1.58 written from scratch in Rust: autograd, a transformer and CUDA kernels, no ML libraries. |
| [rust-chess-engine](https://github.com/tidynest/rust-chess-engine) | Chess GUI and terminal CLI that play against Stockfish over UCI, with engine analysis lines, opening names and PGN import. |
| [pixel-sea](https://github.com/tidynest/pixel-sea) | Bakes a seamless pixel-art sea into an animated PNG, with `png` as its only dependency. It made the sea at the top of this page: seven wave components, a 20-second loop, no JavaScript. |

### Learning

| Project | What it is |
|---|---|
| [learning-c-and-cs](https://github.com/tidynest/learning-c-and-cs) | My C23, algorithms and secure-coding curriculum, compiled with sanitisers and `-Werror`. |

## Closed source

| Project | What it is |
|---|---|
| [Hamnkapten](https://ericjingryd.com/projects?project=hamnkapten) | Sauna booking system for the Gothenburg boatyard where I work. Guests book in a Leptos web app and staff run the schedule from a Slint desktop admin. A PostgreSQL exclusion constraint rules out double bookings. 14 crates around an axum API, 1,100+ tests. In development. |
| [Constraint engine](https://ericjingryd.com/projects?project=constraint-engine) | Constraint-satisfaction solver in Rust behind an Actix-web service. AC-3 propagation, MRV and LCV heuristics, parallel backtracking over bitset domains. Median solve time cut from 42 s to 140 ms, 1,000+ tests. |
