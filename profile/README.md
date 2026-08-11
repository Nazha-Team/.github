<div align="center">

<img src="https://i.postimg.cc/7Z4ddSxZ/greenlogo.png" width="120" alt="Nazha Logo" />

# Nazha

**A free, full-featured Discord music bot.**

No paywalls. No vote locks. No limits.

<br/>

<img src="https://img.shields.io/badge/servers-1,000%2B-FFD700?style=flat-square&labelColor=1a1a2e" />
<img src="https://img.shields.io/badge/users-400K%2B-FFA500?style=flat-square&labelColor=1a1a2e" />
<img src="https://img.shields.io/badge/uptime-99.9%25-FFD700?style=flat-square&labelColor=1a1a2e" />
<img src="https://img.shields.io/badge/features-70%2B-FF8C00?style=flat-square&labelColor=1a1a2e" />
<img src="https://img.shields.io/badge/license-MIT-FFD700?style=flat-square&labelColor=1a1a2e" />

<br/><br/>

[**Invite Nazha**](https://nazha.online) · [**Website**](https://nazha.netlify.app) · [**Support Server**](https://discord.gg/8a8EPeu8)

</div>

---

## About

Nazha is a Discord music bot built for reliability and speed, with every feature available to every server at no cost. There are no premium tiers, no vote requirements, and no artificial limits — just music.

## Features

- **Multi-platform playback** — YouTube, Spotify, SoundCloud, Apple Music, Deezer, Bandcamp, Twitch, and direct links
- **High-quality audio** — up to 320kbps streaming with low-latency playback
- **Audio effects** — bass boost, nightcore, vaporwave, 8D, karaoke, tremolo, vibrato, speed/pitch control
- **Smart queue** — shuffle, loop (track/queue), skip, seek, reorder, and history
- **Playlists** — create, save, share, and import playlists across servers
- **24/7 mode** — continuous playback with automatic reconnect on disconnects
- **Live lyrics** — synced lyrics for the currently playing track
- **DJ controls** — role-based permissions for moderated servers
- **Multi-language interface** — commands and responses in multiple languages

## Tech Stack

| Layer | Technology |
|---|---|
| Runtime | Bun |
| Language | TypeScript |
| Framework | Seyfert |
| Database | SQLite (Turso) via Drizzle ORM |
| Caching | Redis |
| Audio Engine | In-house streaming pipeline |

## Commands

<details>
<summary><b>Music</b></summary>

```
/play <song>        Play a track from any supported platform
/pause / /resume     Pause or resume playback
/skip / /previous    Move through the queue
/stop                Stop playback and clear the queue
/queue               View the current queue
/nowplaying          Show the currently playing track
/volume <0-200>      Adjust playback volume
/seek <time>         Jump to a timestamp
/shuffle             Shuffle the queue
/loop                Toggle loop mode
/remove <#> / /move  Edit the queue
/clear               Clear the queue
```
</details>

<details>
<summary><b>Effects</b></summary>

```
/bassboost <level>   none / low / medium / high / extreme
/nightcore           Speed-up effect
/vaporwave           Slow-down effect
/8d                  Surround effect
/karaoke             Vocal reduction
/tremolo / /vibrato  Modulation effects
/speed <0.5-2.0>     Playback speed
/pitch <0.5-2.0>     Pitch adjustment
/reset               Clear all active filters
/filters             List available filters
```
</details>

<details>
<summary><b>Playlists & Favorites</b></summary>

```
/playlist create <name>
/playlist add <name>
/playlist remove <name> <#>
/playlist load <name>
/playlist list
/playlist delete <name>
/playlist share <name>
/favorites add / list / play
```
</details>

<details>
<summary><b>Settings</b></summary>

```
/247              Toggle 24/7 mode
/autoplay         Toggle automatic recommendations
/lyrics           Show synced lyrics
/history          View playback history
/dj setup         Configure DJ role
/announce         Toggle track announcements
/language <lang>  Set interface language
/setup            Run the server configuration wizard
```
</details>

<details>
<summary><b>Info</b></summary>

```
/help       Interactive help menu
/stats      Bot performance statistics
/ping       Check bot latency
/invite     Get the invite link
/support    Join the support server
/about      About Nazha
```
</details>

## Getting Started

1. [Invite Nazha](https://nazha.online) to your server
2. Join a voice channel
3. Run `/play <song name>`

Nazha requires: **Connect**, **Speak**, **Send Messages**, **Embed Links**, **Use Slash Commands**, **Use Voice Activity**.

## FAQ

**Is Nazha really free?**
Yes — all features are free for every server, permanently.

**Do I need to vote to unlock anything?**
No. Voting is optional and unlocks nothing; every feature is already available.

**Can Nazha play 24/7?**
Yes, via `/247` — no subscription required.

## Team

| | | |
|---|---|---|
| **Oxeey** — Owner | **Razi** — Lead Developer | **H3** — UI/UX Designer |
| [GitHub](https://github.com/oxckyalive) · [Discord](https://discord.com/users/1050593287590920232) | [GitHub](https://github.com/knownasrazi) · [Discord](https://discord.com/users/875402851986325504) | [GitHub](https://github.com/H3-GaminG) · [Discord](https://discord.com/users/1107939269957406821) |
| **Wrox** — Backend & Infrastructure | **Snake** — Core Architecture & Backend | |
| [GitHub](https://github.com/WroxExm) | [GitHub](https://github.com/snakkeeh) | |

Thanks to everyone who contributes bug reports, translations, moderation, and testing.

## Support

Join the [Discord support server](https://discord.gg/8a8EPeu8) or reach out at [addnazha4@gmail.com](mailto:addnazha4@gmail.com).

## License

Licensed under the [MIT License](LICENSE).

<div align="center">
<br/>

© 2024 [Nazha Creators](https://github.com/nazha-creators)

</div>
