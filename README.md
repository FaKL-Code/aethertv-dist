<div align="center">

<img src="icon.png" alt="AetherTV" width="150" />

# AetherTV

**Watch YouTube videos & livestreams together — right inside Final Fantasy XIV.**

A Dalamud plugin that projects video onto an in‑game minion's screen, perfectly
synced from a host to everyone in the room. Paste a link, hit play, watch together.

[![Website](https://img.shields.io/badge/website-aethertv.cloud-3aa0ff?style=for-the-badge)](https://aethertv.cloud)
[![Status](https://img.shields.io/badge/status-in%20testing-e0a83a?style=for-the-badge)](#%EF%B8%8F-disclaimer)
[![Report a bug](https://img.shields.io/badge/report%20a%20bug-GitHub%20Issues-30363d?style=for-the-badge&logo=github)](https://github.com/FaKL-Code/aethertv-dist/issues/new)

</div>

---

## ✨ What it does

- 🎬 **Watch together, in sync** — the host broadcasts; everyone else just watches, perfectly synchronized.
- 📺 **On a real in‑game screen** — the video plays on your minion's screen, with true in‑world occlusion.
- 🔗 **Any source** — YouTube, Twitch, Kick, livestreams, even local files. Paste a link, hit play.
- 📜 **Playlists** — queue videos, skip forward and back.
- 👑 **Host controls everything** — only the host sets things up; peers just enjoy the show.

> 👀 See it in action on **[aethertv.cloud](https://aethertv.cloud)**.

---

## 📥 Install

1. In‑game, open Dalamud settings — type `/xlsettings` in chat.
2. Go to **Experimental → Custom Plugin Repositories**, add this URL, then **Save**:
   ```text
   https://repo.aethertv.cloud/pluginmaster.json
   ```
3. Open the plugin installer, search for **AetherTV**, and install.
4. **Install the minion‑screen mod** (required) — [XIV Mod Archive #112306](https://www.xivmodarchive.com/modid/112306), loaded via Penumbra. It gives your minion the flat screen the video is projected onto.
5. Open AetherTV in‑game with `/atv` (or `/aethertv`).

> Requires FFXIV running in **DirectX 11**.

---

## 🕹️ Usage

| Command | What it does |
| --- | --- |
| `/atv` · `/aethertv` | Open / close the main window |
| `/atv play <url>` | Load & play a video, livestream, or local file |
| `/atv pause` · `stop` | Pause / stop |
| `/atv next` · `prev` | Playlist navigation |
| `/atv minion` | Apply / remove the screen on your minion |
| `/atv host` · `join <code>` | Host a room / join one with a code |

**Watch together:** the host runs `/atv host`, shares the room code, and presses
play — everyone who joined watches in sync.

---

## ❓ FAQ

<details>
<summary><b>Do my friends need to set anything up?</b></summary><br>

They need this plugin and the minion‑screen mod. The host shares the stream — peers just join the room and watch.
</details>

<details>
<summary><b>Why does it need a mod?</b></summary><br>

The mod gives your minion a flat screen with the correct shape for video to be projected onto. Without it, the video won't display correctly.
</details>

<details>
<summary><b>Does it support livestreams?</b></summary><br>

Yes — YouTube / Twitch / Kick livestreams and VODs, plus local files.
</details>

<details>
<summary><b>It crashed or froze.</b></summary><br>

AetherTV is in active testing and may have rough edges. Please <a href="https://github.com/FaKL-Code/aethertv-dist/issues/new">open an issue</a> describing what you were doing — it genuinely helps.
</details>

---

## 🐛 Found a bug?

Open a **[GitHub issue](https://github.com/FaKL-Code/aethertv-dist/issues/new)** — tell us what happened and what you were doing. Screenshots and logs are very welcome.

## ☕ Support

If AetherTV makes your hangouts better, you can [**buy me a coffee**](https://buymeacoffee.com/fkl.dev) — thank you! 💙

---

## ⚠️ Disclaimer

AetherTV is a community fan project and is **in testing** — expect occasional
crashes. Third‑party plugins are against Square Enix's Terms of Service; use at
your own risk, with **public content only**. Not affiliated with or endorsed by
Square Enix. *Final Fantasy XIV* is a trademark of Square Enix Holdings Co., Ltd.

<div align="center"><sub>Made with aether &amp; late nights by <b>FKL dev</b> · <a href="https://aethertv.cloud">aethertv.cloud</a></sub></div>
