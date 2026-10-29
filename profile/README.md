<div align="center">

<img src="https://raw.githubusercontent.com/Blackshield-Company/.github/main/profile/assets/banner.png" alt="Blackshield Company: black shield, red cross, steel frame" width="640">

# Blackshield Company

**Steel over spectacle.**

Independent studio building open-source AI coding tools, forensics and privacy software, mesh networking, games, themes and Skyrim mods.

<img src="https://raw.githubusercontent.com/Blackshield-Company/.github/main/profile/blackshield.png" alt="The Blackshield knight" width="256" height="224">

[Studio site](https://blackshield-company.pages.dev/) &nbsp;|&nbsp; [Skyrim mods on Nexus](#skyrim-mods) &nbsp;|&nbsp; [Sponsor](https://github.com/sponsors/synthalorian) &nbsp;|&nbsp; [Ko-fi](https://ko-fi.com/synthalorian) &nbsp;|&nbsp; [Contact](mailto:blackshield@mail.grokbot.com)

</div>

## What we make

Local-first, offline where it can be, and built to hold. Most projects are small, single-purpose and open source. Everything below lives in this organization, and each project says in its own README how mature it is.

## Featured

- [**OpenShield**](https://github.com/Blackshield-Company/openshield): An open-source AI coding harness in Rust, with a desktop app, an Android companion and a browser extension. Prebuilt binaries ship for Linux and macOS.
- [**VoidEngine**](https://github.com/Blackshield-Company/voidengine) and [**Void Mercs**](https://github.com/Blackshield-Company/void-mercs-demo): An Odin and SDL2 game engine with hot reload, and a free playable demo of the game built on it.
- [**agentbench**](https://github.com/Blackshield-Company/agentbench), [**sentryclaw**](https://github.com/Blackshield-Company/sentryclaw), [**wireclaw**](https://github.com/Blackshield-Company/wireclaw): A benchmark runner for AI coding agents, a self-hosted AI code review bot, and a local proxy for capturing and replaying API traffic.
- [**beacon**](https://github.com/Blackshield-Company/beacon), [**custody**](https://github.com/Blackshield-Company/custody), [**exifguard**](https://github.com/Blackshield-Company/exifguard): Evidence tools for victims, investigators and defense teams: preservation guide, chain-of-custody log, EXIF verifier.
- [**Blackshield Company**](https://www.nexusmods.com/skyrimspecialedition/mods/194203): A Skyrim SE/AE mercenary-company mod, and the first of fifteen free mods we publish on Nexus.

## AI coding tools

| Project | What it is | License |
|---|---|---|
| [`openshield`](https://github.com/Blackshield-Company/openshield) | Open-source AI coding harness in Rust. Prebuilt binaries for Linux and macOS. | Apache&#8209;2.0 |
| [`openshield-desktop`](https://github.com/Blackshield-Company/openshield-desktop) | GUI companion for OpenShield: sessions, streaming chat, tool approvals, swarm monitor. Tauri 2 + SvelteKit. | MIT |
| [`openshield-mobile`](https://github.com/Blackshield-Company/openshield-mobile) | OpenShield Pocket: Android port of the desktop app. Pairs to `openshield serve` over LAN. | MIT |
| [`openshield-extension`](https://github.com/Blackshield-Company/openshield-extension) | Firefox and Chrome remote for OpenShield: send pages and selections into a session, approve tool calls. | Apache&#8209;2.0 |
| [`agentbench`](https://github.com/Blackshield-Company/agentbench) | Self-hostable benchmark runner for AI coding agents. Pluggable harnesses, TUI and web dashboard. Rust. | Apache&#8209;2.0 |
| [`sentryclaw`](https://github.com/Blackshield-Company/sentryclaw) | Self-hosted AI code review bot. No cloud, no API keys. Rust, Axum, local LLMs. | Apache&#8209;2.0 |
| [`ghostbin`](https://github.com/Blackshield-Company/ghostbin) | AI-assisted reverse engineering suite. Rust, Capstone, goblin, optional local LLM analysis. Fully offline. | Apache&#8209;2.0 |

## Developer tools

| Project | What it is | License |
|---|---|---|
| [`wireclaw`](https://github.com/Blackshield-Company/wireclaw) | Local HTTP proxy for API traffic capture, replay and inspection. Rust CLI and TUI. | Apache&#8209;2.0 |
| [`tapeworm`](https://github.com/Blackshield-Company/tapeworm) | TUI log analyzer: live tail, grep, aggregation, histograms, anomaly detection. Rust. | Apache&#8209;2.0 |
| [`trackerclaw`](https://github.com/Blackshield-Company/trackerclaw) | Privacy-first time tracker. Local, no cloud, no accounts. TUI and web dashboard. | Apache&#8209;2.0 |
| [`splice`](https://github.com/Blackshield-Company/splice) | Minimalist Git alternative for binary assets: content-addressable storage, delta compression, lazy checkout. C. | Apache&#8209;2.0 |
| [`shieldwall`](https://github.com/Blackshield-Company/shieldwall) | Paste your setup, get a hardening checklist. Open-source security audit tool. | Apache&#8209;2.0 |
| [`bounty-mcp`](https://github.com/Blackshield-Company/bounty-mcp) | MCP server that searches paid bounties on GitHub and Opire. | MIT |

## Forensics and privacy

| Project | What it is | License |
|---|---|---|
| [`beacon`](https://github.com/Blackshield-Company/beacon) | Interactive evidence-preservation and reporting guide for victims of cybercrime. | Apache&#8209;2.0 |
| [`custody`](https://github.com/Blackshield-Company/custody) | Tamper-evident chain-of-custody log for digital evidence. | Apache&#8209;2.0 |
| [`exifguard`](https://github.com/Blackshield-Company/exifguard) | Batch forensic EXIF verifier for evidence photos. | Apache&#8209;2.0 |
| [`timeline`](https://github.com/Blackshield-Company/timeline) | Evidence timeline builder for investigators and defense attorneys. | Apache&#8209;2.0 |
| [`docket`](https://github.com/Blackshield-Company/docket) | Local-first case file organizer for public defenders. | Apache&#8209;2.0 |
| [`blotter`](https://github.com/Blackshield-Company/blotter) | Normalizer and explorer for public crime and incident data. | Apache&#8209;2.0 |
| [`scamshield`](https://github.com/Blackshield-Company/scamshield) | Offline scam pattern detector protecting elderly users and families. | Apache&#8209;2.0 |

## Games and engines

| Project | What it is | License |
|---|---|---|
| [`voidengine`](https://github.com/Blackshield-Company/voidengine) | Game engine with hot reload and data-driven design. Odin and SDL2. | Apache&#8209;2.0 |
| [`voidengine-level-editor`](https://github.com/Blackshield-Company/voidengine-level-editor) | Visual tilemap and entity level editor for VoidEngine. | Apache&#8209;2.0 |
| [`void-mercs-demo`](https://github.com/Blackshield-Company/void-mercs-demo) | Free playable demo of Void Mercs, built on VoidEngine. | Free demo license (all rights reserved) |
| [`chronos-engine`](https://github.com/Blackshield-Company/chronos-engine) | Genre-agnostic ECS game engine in Rust. Zero dependencies in the core. Deterministic by design. | Apache&#8209;2.0 |
| [`rift`](https://github.com/Blackshield-Company/rift) | Cross-engine game asset pipeline manager. Rust CLI and Rails dashboard. | Apache&#8209;2.0 |

## Audio

| Project | What it is | License |
|---|---|---|
| [`kicks`](https://github.com/Blackshield-Company/kicks) | Open-source guitar and bass tone shaping with native DSP. Rust, Tauri 2, React. | Apache&#8209;2.0 |
| [`Open-Amp`](https://github.com/Blackshield-Company/Open-Amp) | Cross-platform guitar amplifier and effects processor with real-time DSP. Linux, Android, iOS. | Apache&#8209;2.0 |

## Themes and customization

| Project | What it is | License |
|---|---|---|
| [`omarchy-blackshield`](https://github.com/Blackshield-Company/omarchy-blackshield) | Blackshield theme and ultrawide kit for Omarchy Linux. | Apache&#8209;2.0 |
| [`omarchy-blackshield-theme`](https://github.com/Blackshield-Company/omarchy-blackshield-theme) | Black Steel theme for Omarchy 4: near-black steel with a crimson edge. | MIT |
| [`omarchy-steel-and-ember-theme`](https://github.com/Blackshield-Company/omarchy-steel-and-ember-theme) | Steel & Ember: a dark forged-steel theme for Omarchy 4. | MIT |
| [`cachyos-blackshield`](https://github.com/Blackshield-Company/cachyos-blackshield) | CachyOS theme pack: KDE Plasma livery, terminals, nvim colorscheme, boot splash, wallpapers. | MIT |
| [`glyphsmith-themes`](https://github.com/Blackshield-Company/glyphsmith-themes) | Tested Omarchy 4 themes with a one-line picker. | MIT |
| [`palette-forge`](https://github.com/Blackshield-Company/palette-forge) | One Omarchy `colors.toml` in, matching themes for ten apps out. | MIT |
| [`ricecard`](https://github.com/Blackshield-Company/ricecard) | Turn a desktop screenshot and an Omarchy theme into showcase images. | MIT |
| [`livewall`](https://github.com/Blackshield-Company/livewall) | Live wallpapers for Omarchy and Hyprland. Battery- and fullscreen-aware. | MIT |
| [`blackshield-icon-pack`](https://github.com/Blackshield-Company/blackshield-icon-pack) | Full-coverage Android icon pack: dark steel tiles, bone glyphs, one blood accent. | Apache&#8209;2.0 |
| [`blackshield-clock-widget`](https://github.com/Blackshield-Company/blackshield-clock-widget) | Gothic medieval clock widget for Android. | Apache&#8209;2.0 |

## Skyrim mods

Fifteen free mods, published on Nexus Mods as synthalorian. All are ESL plugins and none need SKSE. Every one is in early beta, so expect rough edges, and please send bug reports.

| Mod | Nexus | Source | License |
|---|---|---|---|
| **Blackshield Company**<br>Join a mercenary company, take radiant contracts, rise from Recruit to Commander. | [Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/194203) | [`blackshield-company`](https://github.com/Blackshield-Company/blackshield-company) | MIT |
| **Daedric Ledger: Bounties of Oblivion**<br>Radiant Daedric Prince tasks with favor, rivalries, blessings and gifts. | [Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/194204) | [`bounties-of-oblivion`](https://github.com/Blackshield-Company/bounties-of-oblivion) | MIT |
| **Contract Hunter**<br>Solo bounty hunting: named outlaws, Notice/Wanted/Dread tiers, deadlines, per-hold standing. | [Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/194206) | [`contract-hunter`](https://github.com/Blackshield-Company/contract-hunter) | MIT |
| **Steel Oath**<br>Warrior's oaths: detectable vows, growing blessings, oathbreaker penalties. | [Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/194208) | [`steel-oath`](https://github.com/Blackshield-Company/steel-oath) | MIT |
| **Ember Smithing**<br>Heat-tempering tiers for vanilla weapons and engraved vanilla armor. | [Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/194210) | [`ember-smithing`](https://github.com/Blackshield-Company/ember-smithing) | MIT |
| **The Gray-Mane Debt**<br>Eorlund Gray-Mane's stolen Skyforge pattern and an old debt. Three endings. | [Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/194214) | [`the-gray-mane-debt`](https://github.com/Blackshield-Company/the-gray-mane-debt) | MIT |
| **Blackshield Codex**<br>Integration plugin linking the first five Blackshield mods. | [Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/194216) | [`blackshield-codex`](https://github.com/Blackshield-Company/blackshield-codex) | MIT |
| **War Banners**<br>Craftable war standards that rally you and your followers when planted. | [Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/194220) | [`war-banners`](https://github.com/Blackshield-Company/war-banners) | MIT |
| **Roadwarden**<br>Rare, level-scaled road encounters. | [Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/194222) | [`roadwarden`](https://github.com/Blackshield-Company/roadwarden) | MIT |
| **Sellsword Roster**<br>A rotating roster of named sellswords with traits and daily wages. | [Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/194224) | [`sellsword-roster`](https://github.com/Blackshield-Company/sellsword-roster) | MIT |
| **The Turncoat Contract**<br>Quest mod. | [Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/194333) | [`the-turncoat-contract`](https://github.com/Blackshield-Company/the-turncoat-contract) | MIT |
| **The Ledger of Ash**<br>Quest mod. | [Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/194334) | [`the-ledger-of-ash`](https://github.com/Blackshield-Company/the-ledger-of-ash) | MIT |
| **Oathbreaker's Price**<br>Quest mod. | [Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/194335) | [`oathbreakers-price`](https://github.com/Blackshield-Company/oathbreakers-price) | MIT |
| **Champion's Reforge**<br>Quest mod. | [Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/194336) | [`champions-reforge`](https://github.com/Blackshield-Company/champions-reforge) | MIT |
| **The Barrow-Iron Pact**<br>Quest mod. | [Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/194337) | [`barrow-iron-pact`](https://github.com/Blackshield-Company/barrow-iron-pact) | MIT |

More mods, built from the same series. Source is here, and they are not on the Nexus list above:

| Project | What it is | License |
|---|---|---|
| [`company-quartermaster`](https://github.com/Blackshield-Company/company-quartermaster) | Hireable quartermaster: supplies, bulk junk sales, follower refits and stashes. | MIT |
| [`scarred-steel`](https://github.com/Blackshield-Company/scarred-steel) | Weapon and armor wear with grindstone and workbench repair. | MIT |
| [`rival-companies`](https://github.com/Blackshield-Company/rival-companies) | Four rival mercenary companies camped across Skyrim. Early beta, not yet playtested in game. | MIT |

### Skyrim tooling

| Project | What it is | License |
|---|---|---|
| [`skyrim-mod-manager`](https://github.com/Blackshield-Company/skyrim-mod-manager) | Native Linux mod manager for Skyrim SE/AE under Proton: conflict-first, hardlink deploy, plugin checks. | MIT |
| [`modforge`](https://github.com/Blackshield-Company/modforge) | Free Skyrim SE load-order and conflict checker for Linux. Read-only: it does not modify the game. | Apache&#8209;2.0 |
| [`mod-release-bot`](https://github.com/Blackshield-Company/mod-release-bot) | Turns a GitHub release of a Blackshield mod into review-ready drafts (Nexus changelog, description block, post text). Drafts only. | MIT |

## Studio

| Project | What it is | License |
|---|---|---|
| [`blackshield-site`](https://github.com/Blackshield-Company/blackshield-site) | Source of the studio website. Plain HTML and CSS, no build step. | not stated |
| [`blackshield-knight-sprite`](https://github.com/Blackshield-Company/blackshield-knight-sprite) | The Blackshield knight sprite atlas: 9 states, 6 frames each, generator included. | MIT |
| [`.github`](https://github.com/Blackshield-Company/.github) | This profile. | not stated |

## Mesh networking

Our Reticulum mesh projects ([reticulum-hub](https://github.com/synthalorian/reticulum-hub), [reticulum-beacon](https://github.com/synthalorian/reticulum-beacon), [reticulum-wave](https://github.com/synthalorian/reticulum-wave), [reticulumchat](https://github.com/synthalorian/reticulumchat)) live under the maintainer's account at [github.com/synthalorian](https://github.com/synthalorian).

## Support and contact

Blackshield software is free and open source. If it saves you time you can support the work through [GitHub Sponsors](https://github.com/sponsors/synthalorian) or [Ko-fi](https://ko-fi.com/synthalorian). Donations are optional.

Questions and bug reports: open an issue on the project, or write to [blackshield@mail.grokbot.com](mailto:blackshield@mail.grokbot.com).

<sub>Licenses are listed from each repository's LICENSE file. Where a repository has no LICENSE file it says "not stated".</sub>
