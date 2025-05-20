<p align="center">
  <img src="https://raw.githubusercontent.com/4ian/GDevelop/master/newIDE/GDevelop%20banner.png" alt="GDevelop logo" />
</p>

# GDevelop

**GDevelop** is a **full-featured, no-code, open-source** game development software. Build **2D, 3D, and multiplayer games** for **mobile**, **desktop**, and the **web** with ease. Use an intuitive **event-based system** and **reusable behaviors**—no programming required.

<p align="center">
  <img src="https://raw.githubusercontent.com/4ian/GDevelop/master/newIDE/GDevelop%20screenshot.png" alt="GDevelop editor screenshot" />
</p>

---

## 🚀 Getting Started

| I want to...                                    | What to do |
| ----------------------------------------------- | ---------- |
| 🎮 Make games with GDevelop                     | [Download GDevelop](https://gdevelop.io) |
| ⚙️ Create or improve an extension                | [Guide for extensions](https://wiki.gdevelop.io/gdevelop5/extensions/create) |
| 🧑‍💻 Contribute to the editor or game engine      | [See contribution guide](newIDE/README.md) |
| 👾 Submit a game template                        | [Submit to the Asset Store](https://wiki.gdevelop.io/gdevelop5/community/guide-for-submitting-an-example/) |
| 🎨 Share or sell an asset pack                   | [Submit assets](https://wiki.gdevelop.io/gdevelop5/community/sell-asset-pack-store) |
| 🌐 Help translate GDevelop                       | [Translate on Crowdin](https://crowdin.com/project/gdevelop) |
| 👥 Get commercial or online services support     | [View pricing and services](https://gdevelop.io/pricing) |

> 💡 New contributor? Explore [Good First Issues](https://github.com/4ian/GDevelop/issues?q=is%3Aissue+is%3Aopen+label%3A%22%F0%9F%91%8Cgood+first+issue%22), [Starter Discussions](https://github.com/4ian/GDevelop/discussions/categories/good-first-contribution), and [Easy Tasks on Trello](https://trello.com/b/qf0lM7k8/gdevelop-roadmap?menu=filter&filter=label:Not%20too%20hard%20%E2%9A%BD%EF%B8%8F)

---

## 🕹️ Games Made with GDevelop

- Discover games at [gd.games](https://gd.games)
- View the [GDevelop showcase](https://gdevelop.io/games) (Steam, iOS, Android, Itch.io, etc.)
- [Submit your game to the showcase](https://docs.google.com/forms/d/e/1FAIpQLSfjiOnkbODuPifSGuzxYY61vB5kyMWdTZSSqkJsv3H6ePRTQA/viewform)

[![Games made with GDevelop](https://raw.githubusercontent.com/4ian/GDevelop/master/newIDE/GDevelop%20games.png)](https://gdevelop.io/games)

---

## 🧠 Technical Architecture

GDevelop is composed of:
- **Editor**: Desktop app built with Electron and React
- **Game engine**: Written in TypeScript using PixiJS & Three.js
- **Extensions**: Expand functionality, behavior & objects
- **Online Services**: Asset store, game publishing, analytics, etc.

| Directory     | Description |
| ------------- | ----------- |
| `Core`        | Core game structure and tools |
| `GDJS`        | Game engine (2D/3D rendering with PixiJS and Three.js) |
| `GDevelop.js` | JS bindings for Core, GDJS, and Extensions |
| `newIDE`      | Editor source (React, Electron) |
| `Extensions`  | Built-in and community game engine extensions |

📖 [Architecture Overview](Core/GDevelop-Architecture-Overview.md)  
📚 [Game Engine Documentation](https://docs.gdevelop.io)

---

## ✅ Build & Test Status

| Platform      | Status |
| ------------- | ------ |
| macOS/Linux   | [![CircleCI](https://circleci.com/gh/4ian/GDevelop.svg?style=shield)](https://app.circleci.com/pipelines/github/4ian/GDevelop) |
| Windows       | [![AppVeyor](https://ci.appveyor.com/api/projects/status/84uhtdox47xp422x/branch/master?svg=true)](https://ci.appveyor.com/project/4ian/gdevelop/branch/master) |
| Fast Tests    | [![SemaphoreCI](https://gdevelop.semaphoreci.com/badges/GDevelop/branches/master.svg?style=shields)](https://gdevelop.semaphoreci.com/projects/GDevelop) |
| Ethical Check | [![Good Labs Badge](https://good-labs.github.io/greater-good-affirmation/assets/images/badge.svg)](https://good-labs.github.io/greater-good-affirmation) |

---

## 🌐 Community & Resources

- 🗣️ [Forums](https://forum.gdevelop.io) • [Discord](https://discord.gg/gdevelop)
- 📘 [GDevelop Wiki](https://wiki.gdevelop.io/gdevelop5/start)
- 🌍 [Crowdin Translation](https://crowdin.com/project/gdevelop)
- 🧩 [Extensions](https://github.com/GDevelopApp/GDevelop-extensions) • [Examples](https://github.com/GDevelopApp/GDevelop-examples) • [Tutorials](https://github.com/GDevelopApp/GDevelop-tutorials)

---

## 🗺️ Roadmap

- [Trello Roadmap](https://trello.com/b/qf0lM7k8/gdevelop-roadmap)
- [GitHub Issues](https://github.com/4ian/GDevelop/issues)
- [Feature Discussions](https://github.com/4ian/GDevelop/discussions)

---

## 📄 License

- Code: MIT License (`Core`, `GDJS`, `newIDE`, `Extensions`)
- Logo and name: © Florian Rival

You **can distribute, sell, or publish** games made with GDevelop freely. You are **not required** to make your game open-source.

---

## ⭐ Star History

Help others discover GDevelop by starring the repo!

[![Star History](https://api.star-history.com/svg?repos=4ian/gdevelop&type=Date)](https://star-history.com/#4ian/gdevelop&Date)
