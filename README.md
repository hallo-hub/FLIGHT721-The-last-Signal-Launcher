# ✈️ FLIGHT 721: THE LAST SIGNAL

**A survival experience where the flight ends — but the mystery begins.**

> **FLIGHT 721: THE LAST SIGNAL** is a first-person survival and psychological mystery game set on a remote tropical island after a catastrophic plane crash.

---

## 🎮 About the Game

You are a passenger aboard **Flight 721**.

What begins as a normal flight quickly changes when severe weather and technical problems affect the aircraft.

The flight loses control.

The aircraft crashes.

You survive.

But the island is not as empty as it first appears.

Your goal is to survive, explore the island and uncover what happened — while strange radio signals, unexplained sounds, abandoned structures and mysterious traces slowly reveal that there may be more behind the crash.

---

## 🌴 Game Features

### 🏝️ Open Tropical Environment

Explore a large tropical island containing:

- 🌊 Beaches and coastline
- 🌴 Dense jungle
- 🏞️ Rivers and water sources
- ⛰️ Hills and rocky areas
- 🕳️ Caves
- 🏚️ Abandoned ruins
- ✈️ Plane wreckage
- 🔦 Hidden locations and discoveries

The island is designed to encourage exploration rather than simply following a linear path.

---

### 🥤 Survival

Staying alive is part of the experience.

The game includes survival mechanics such as:

- 💧 Thirst
- 🍖 Hunger
- ❤️ Health
- ⚡ Stamina
- 🌡️ Temperature
- 🔥 Fire
- 🏕️ Shelter
- 🎒 Inventory
- 🛠️ Crafting

Resources have to be discovered and managed while exploring the island.

---

## 🌧️ Dynamic Environment

The island is not always the same.

The game features:

- ☀️ Day and night cycle
- 🌧️ Weather changes
- 🌫️ Atmospheric conditions
- 🌴 Environmental sounds
- 🐾 Wildlife
- 🌊 Water and environmental effects

The environment is an important part of the atmosphere.

---

## 📻 The Mystery

The survival system is only part of the game.

While exploring, you may encounter:

- 📻 Strange radio transmissions
- 🔊 Unexplained sounds
- 💡 Distant lights
- 🏚️ Abandoned structures
- 👣 Traces of other people
- ✈️ Evidence around the crash site
- 🗺️ Locations that raise more questions than answers

Not everything you encounter is immediately explained.

The player has to investigate and connect the clues.

---

## 🎯 Your Goal

There is more than simply surviving.

Your objectives are to:

1. Survive the crash.
2. Find water and food.
3. Establish a temporary shelter.
4. Explore the island.
5. Investigate the aircraft wreckage.
6. Discover strange radio signals.
7. Investigate the island's unexplained locations.
8. Find out what happened.
9. Uncover the truth behind the signals.

---

# 🚀 FLIGHT 721 Launcher

The project includes a dedicated launcher for the Windows version of the game.

The launcher automatically checks for updates before starting the game.

### The launcher can:

- 🔎 Check the current game version
- 📦 Download missing files
- 🔄 Update changed files
- 🔐 Verify files using SHA-256
- 💾 Preserve the `saves` folder
- 🎮 Start the game directly
- 📊 Show download and update progress

The launcher uses a manifest-based update system.

---

# 📥 Installation

## Windows

### 1. Download the launcher

Download:

**`FLIGHT721-The last Signal Launcher.exe`**

from the latest GitHub Release.

### 2. Start the launcher

Double-click the EXE.

No separate .NET installation is required.

### 3. Let the launcher update the game

The launcher checks the required game files automatically.

Missing or changed files are downloaded automatically.

### 4. Start the game

Once the update is complete, click:

**`Spiel starten`**

---

# 🔄 How the Update System Works

The launcher uses a `manifest.json` file containing information about the current game files.

For each file, the manifest stores:

```text
File path
File size
SHA-256 hash
```

When the launcher starts, it compares the local files with the manifest.

Example:

```text
Local file
     ↓
Size check
     ↓
SHA-256 check
     ↓
Matches?
  ↙       ↘
YES       NO
 ↓         ↓
Skip     Download
```

This means unchanged files do not need to be downloaded again.

### Example

If a new version only changes:

```text
FLIGHT.721.-.The.Last.Signal.pck
```

the launcher does not download the other unchanged files again.

---

# 💾 Save Data

Game saves are kept separately from update files.

The launcher protects the:

```text
saves/
```

directory from being overwritten by game updates.

This means installing an update should not remove your existing save data.

---

# 🛠️ Development

The launcher is developed using:

- **C#**
- **.NET 9**
- **Windows Forms**
- **GitHub Releases**
- **GitHub-hosted update manifest**

The launcher is published as a:

**Self-contained Windows x64 single-file application.**

---

# 📁 Project Structure

The repository contains the launcher source code and development files.

```text
FLIGHT721-Launcher/
│
├── MainForm.cs
├── Program.cs
├── LauncherSettings.cs
├── SettingsForm.cs
├── GitHubUpdateService.cs
│
├── SWGSurvivors-Patcher.csproj
├── SWGSurvivors-Patcher.sln
│
├── build.bat
├── README.md
└── .gitignore
```

Build output is intentionally excluded from the source repository.

---

# 🧪 Current Status

**Development Status: Prototype / Early Development**

The launcher and basic update system are functional.

Current systems include:

- ✅ Windows launcher
- ✅ Automatic update checking
- ✅ File verification
- ✅ SHA-256 verification
- ✅ Changed-file downloads
- ✅ Save protection
- ✅ Game launching
- ✅ Self-contained launcher build
- 🚧 Further gameplay development
- 🚧 Additional story content
- 🚧 More island locations
- 🚧 More survival systems
- 🚧 More mystery events

Features may change during development.

---

# 🗺️ Roadmap

### Version 1.x

- [x] Initial playable version
- [x] Windows launcher
- [x] Automatic game updates
- [x] File integrity verification
- [x] Basic survival systems
- [x] Tropical island environment
- [x] Crash site
- [x] Radio mystery
- [ ] More exploration areas
- [ ] More story events
- [ ] More environmental events
- [ ] Expanded crafting
- [ ] Additional wildlife
- [ ] More mysteries and discoveries

Future versions may introduce additional systems and content.

---

# ⚠️ Development Notice

**FLIGHT 721: THE LAST SIGNAL is an independent game project currently under development.**

The game is not finished.

Gameplay, mechanics, story elements, visuals and systems may change significantly during development.

Bugs and unfinished features are expected in development builds.

---

# 🐛 Bug Reports

If you encounter a bug, please provide:

- Game version
- Windows version
- What happened
- Steps to reproduce the problem
- Screenshots or video if possible
- Relevant launcher logs

Please do not include personal information in bug reports.

---

# 💡 Suggestions

Ideas and suggestions are welcome.

Useful suggestions include:

- Gameplay mechanics
- Survival systems
- Exploration ideas
- Story ideas
- Atmosphere
- UI improvements
- Performance improvements
- Launcher improvements

---

# 📜 License

This project is currently developed as an independent game project.

Unless explicitly stated otherwise, the game's code, assets, characters, story, names and other original content are **not licensed for redistribution or commercial use**.

Third-party assets, libraries and dependencies remain subject to their respective licenses.

---

# ✈️ FLIGHT 721

**The flight is over.**

**The island is waiting.**

**Find the signal.**
