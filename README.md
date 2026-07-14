# mc-draw.dev

**Languages:** English | [Español](README.es.md)

Public tracker for bugs, ideas, and feedback for **[MC Draw](https://mc-draw.dev)** — a browser-based Minecraft item model editor.

> **This repository does not contain the source code.**  
> MC Draw is developed in a private item-editing project ([`itemeditor`](https://github.com/83080441/itemeditor)). This repo is only for issues and community discussion.

## What is MC Draw?

[MC Draw](https://mc-draw.dev) lets you design 3D item models from 16×16 textures: drop in a PNG, edit polygons, and preview the result in 3D (GUI, hand, third person, and more).

> **Disclaimer:** MC Draw is **not affiliated** with Mojang Studios, Microsoft, Minecraft, or the Forge project. It is not an official product of any of them.

## Purpose

MC Draw is **not a commercial application**: no ads, no personal profit for the creator, and no monetization focus. Its only goal is free distribution of the tool to help modding communities.

## How it works

The app is served from a server so you can open it in the browser, but it **does not save or back up your work on the network**. There are no accounts, no cloud storage, and no remote sync: everything you edit stays on your device and belongs to you. Export PNG or JSON when you need it; nothing is retained server-side.

## How to contribute

Use the [Issues](https://github.com/83080441/mc-draw.dev/issues) in this repo to:

- Report bugs
- Suggest ideas or improvements
- Share feedback about the tool

Before opening an issue, check whether a similar one already exists.

### Labels

Repo labels are defined in [`.github/labels.yml`](.github/labels.yml) and sync automatically when you push to `main`.

| Label | Use |
| --- | --- |
| `bug` | Something is broken |
| `enhancement` | Idea or improvement |
| `feedback` | General feedback |
| `needs info` | Waiting for more details from the reporter |
| `export` | PNG / JSON (export or import) |
| `desktop` | Desktop / Electron requests |
| `documentation` | Docs / README |
| `question` | Question |
| `duplicate` | Already tracked elsewhere |
| `invalid` | Does not apply |
| `wontfix` | Will not be implemented |
| `good first issue` | Good place to start |
| `help wanted` | Extra help welcome |

Issue templates already apply `bug` or `enhancement` when you create an issue.

## FAQ

**How did MC Draw start?**  
From the need to understand and visually create complex items without having to run the game every few minutes.

**Where is the source code?**  
In a private repository ([`itemeditor`](https://github.com/83080441/itemeditor)). This repo (`mc-draw.dev`) is only the public issue tracker.

**Is it free? Are there ads or subscriptions?**  
Yes, it is free. No ads, paid accounts, or monetization. The project is non-profit.

**Are my models stored on a server?**  
No. There are no network backups: what you edit lives in your browser/device. To keep your work, export the PNG or JSON from the app.

**Do I need an account?**  
No. Open [mc-draw.dev](https://mc-draw.dev) and start.

**What is this GitHub repository for?**  
Reporting bugs, requesting features, and community feedback. It is not the app source code.

**Can I use it in my pack / mod / server?**  
Yes — it is meant to help modding communities. Export your assets and use them in your own project; crediting the author or tool is optional.

**How do I report a useful bug?**  
Open an [issue](https://github.com/83080441/mc-draw.dev/issues) with the **Bug report** template. If you can, attach a screenshot, PNG, or JSON exported from the editor.

**Is there a desktop version?**  
Not for now: MC Draw is web-only. If there is real public demand (issues), I will evaluate an Electron project.

## Links

| Resource | URL |
| --- | --- |
| App | [https://mc-draw.dev](https://mc-draw.dev) |
| Issues | [github.com/83080441/mc-draw.dev/issues](https://github.com/83080441/mc-draw.dev/issues) |
| Source code (private) | [`itemeditor`](https://github.com/83080441/itemeditor) |

## License

MC Draw is licensed under the **[PolyForm Noncommercial License 1.0.0](LICENSE)** (`PolyForm-Noncommercial-1.0.0`).

That means you may use it for **personal and noncommercial** purposes (for example modding, hobby projects, learning). **Commercial use is not allowed** under this license.

- PNG / JSON exports you create with the app remain **yours**.
- This public tracker is for issues and feedback; the application source lives in a private repo but is offered under the same license terms for permitted use of the distributed app at [mc-draw.dev](https://mc-draw.dev).
