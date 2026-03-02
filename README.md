<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows-0078D6?style=flat-square&logo=windows" />
  <img src="https://img.shields.io/badge/.NET-8.0-512BD4?style=flat-square&logo=dotnet" />
  <img src="https://img.shields.io/badge/WPF-Desktop-68217A?style=flat-square" />
  <img src="https://img.shields.io/badge/WebView2-Leaflet.js-199900?style=flat-square&logo=leaflet" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" />
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square" />
</p>

<h1 align="center">
  🛰️ N01D :: OVERWATCH
</h1>

<p align="center">
  <strong>Real-time Middle East & Global Conflict Intelligence Dashboard</strong>
  <br/>
  <em>OSINT aggregation • Flight tracking • Maritime awareness • War ops monitoring • Missile defense mapping • Eclipse warfare analysis</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/RSS_Feeds-82+-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Aircraft_IDs-160+-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Geo_Locations-70+-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Threat_Categories-7-purple?style=for-the-badge" />
</p>

---

## ⚡ What is N01D Overwatch?

**N01D Overwatch** is a Windows desktop intelligence dashboard that aggregates open-source intelligence (OSINT) from dozens of real-time sources into a single, unified command interface. Built for researchers, analysts, journalists, and anyone tracking geopolitical events in conflict zones.

Think of it as your personal **situation awareness terminal** — pulling live data from RSS feeds, flight trackers, ship transponders, missile site databases, and war operations monitoring — all rendered on an interactive dark-themed map with XChat-inspired aesthetics.

> **No API keys required.** Uses publicly available OSINT feeds and the OpenSky Network.

---

## 🎯 Core Capabilities

### 📡 Multi-Source Intelligence Aggregation
| Source | Count | Coverage |
|--------|-------|----------|
| **RSS/OSINT Feeds** | 82+ | Reuters, AP, BBC, Al Jazeera, CENTCOM, Bellingcat, Janes, Liveuamap, The War Zone, ACLED, Airwars... |
| **Flight Tracking** | 160+ callsign prefixes | Military aircraft identification via OpenSky Network — drones, tankers, AWACS, fighters, SOF, aggressor squadrons |
| **War Ops Monitoring** | 34 dedicated feeds | SIGACT, Sanctions, Cyber Operations, Proxy/Militia activity tracking |
| **Missile/Defense Sites** | 24 tracked installations | IRGC ballistic missiles, Iron Dome, Arrow-2/3, THAAD, S-300/400, Patriot |
| **Eclipse Warfare** | 11 events (2025-2028) | Military significance analysis for ME-visible eclipses |
| **Maritime Awareness** | AIS ship tracking | Vessel movements in Strait of Hormuz, Red Sea, Persian Gulf |

### ⚔️ WAR OPS — 4-Category Threat Monitor

| Category | What It Tracks | Key Feeds |
|----------|---------------|-----------|
| **🔴 SIGACT** | Drone strikes, airstrikes, artillery, ground ops, naval engagements, airspace closures | CENTCOM, Liveuamap, Bellingcat, The War Zone, ACLED, Airwars, SOFREP |
| **🟡 SANCTIONS** | OFAC designations, arms embargos, weapons sales, IAEA inspections, UN resolutions | SIPRI, US Treasury, EU Sanctions Map, Arms Control Assoc., IAEA |
| **🟣 CYBER** | APT groups, infrastructure attacks, state-sponsored hacking, electronic warfare | The Record, Mandiant, CyberScoop, Dark Reading, Krebs on Security |
| **🟠 PROXY** | Hezbollah, Houthi, PMF, Hamas, ISIS, SDF operations and movements | Al Monitor, Middle East Eye, Iran International, Jamestown Foundation |

### 🗺️ Interactive Tactical Map
- **Leaflet.js** rendered via WebView2 with dark CartoDB tiles
- **Layer control**: Toggle events, flights, military bases, missile sites, air defense, eclipse paths, heatmap
- **Rich popups** with severity-colored markers and event details
- **JS ↔ C# message bridge** for real-time map updates
- **Heatmap overlay** showing conflict density

### 🚀 Missile & Air Defense Tracking
- **12 missile sites**: IRGC underground facilities, Houthi launch sites, Hezbollah arsenals, IRGCN coastal positions
- **12 air defense sites**: Iron Dome, Arrow-2, Arrow-3, David's Sling, THAAD, S-300, Bavar-373, Patriot, S-400, Khordad-15
- Range rings and threat assessment on the map

### 🌑 Eclipse Warfare Analysis
- 11 eclipse events tracked (2025-2028)
- Middle East visibility assessment
- Military significance scoring (GPS degradation, EMP vulnerability windows, SOF timing)
- Live countdown timer to next event

### ✈️ Military Flight Identification
- **160+ callsign prefix patterns** covering:
  - US (USAF, Navy, Marines, Army, Coast Guard, SOF)
  - UK RAF, French, German, Turkish, Israeli, Russian, Chinese
  - NATO AWACS, tankers, ISR, MPA
  - Drone/UAV callsigns (RQ-series, MQ-series, Global Hawk, Reaper, Predator)
  - Aggressor/adversary squadrons
- Automatic aircraft type identification from callsign patterns
- Severity classification (loitering munitions = CRITICAL)

---

## 🖥️ Screenshot

```
┌──────────────────────────────────────────────────────────────────────┐
│ [ N01D :: OVERWATCH ]     THREAT LEVEL: ELEVATED     ⚠ 3 ALERTS    │
│ ⟳ REFRESH   📥 JSON   📥 CSV                                       │
├──────────────────────────────────────────────────────────────────────┤
│ 🔍 Search...  ☑MIL ☑DIP ☑ECO ☑HUM ☑CYB ☑NUC ☑INT  ☑Auto-Refresh │
├──────────────────────────────────────────────────────────────────────┤
│ TIMELINE │ MAP │ FLIGHTS │ MARITIME │ ⚔ WAR OPS │ 🔔 │ 🌑 │ 🚀    │
│                                                                      │
│  ▪ [CRITICAL] Israeli airstrike reported in southern Lebanon         │
│    Source: Liveuamap ME • 2 min ago                                  │
│    Tags: SIGACT AIRSTRIKE ISRAEL HEZBOLLAH                           │
│                                                                      │
│  ▪ [HIGH] CENTCOM confirms Houthi drone intercept over Red Sea       │
│    Source: CENTCOM Press • 15 min ago                                 │
│    Tags: SIGACT DRONE-STRIKE HOUTHI                                  │
│                                                                      │
│  ▪ [MEDIUM] APT42 targets Gulf state energy infrastructure           │
│    Source: Mandiant Blog • 1h ago                                    │
│    Tags: CYBER IRAN                                                  │
│                                                                      │
├──────────────────────────────────────────────────────────────────────┤
│ STATUS: 247 events loaded | Last refresh: 14:32:10 UTC | v1.0       │
└──────────────────────────────────────────────────────────────────────┘
```

---

## 🚀 Quick Start

### Prerequisites
- **Windows 10/11** (64-bit)
- [**.NET 8.0 SDK**](https://dotnet.microsoft.com/download/dotnet/8.0)
- **WebView2 Runtime** (included with modern Windows / Edge)

### Build & Run
```powershell
git clone https://github.com/bad-antics/n01d-overwatch.git
cd n01d-overwatch
dotnet build
dotnet run
```

### Or download the release
```powershell
# Download the latest release from GitHub Releases
# Extract and run N01D-Overwatch.exe
```

---

## 📁 Project Structure

```
n01d-overwatch/
├── App.xaml                    # Application entry + theme loading
├── App.xaml.cs                 # Startup configuration
├── MainWindow.xaml             # 659-line WPF UI — tabs, map, panels
├── MainWindow.xaml.cs          # 1200+ line code-behind — all logic
├── Models.cs                   # Data models, enums, event types
├── N01D.Overwatch.csproj       # Project file — .NET 8, WebView2
├── overwatch.ico               # Custom radar/crosshair icon
├── Services/
│   ├── AlertService.cs         # Configurable alert engine
│   ├── EclipseService.cs       # Eclipse event tracking (2025-2028)
│   ├── FlightTrackingService.cs # OpenSky + 160 callsign patterns
│   ├── MissileDefenseService.cs # 24 missile/defense site database
│   ├── RssFeedService.cs       # 48+ RSS feed aggregator
│   ├── ShipTrackingService.cs  # Maritime vessel tracking
│   └── WarMonitoringService.cs # 34-feed war ops classifier
├── Themes/
│   └── XChatTheme.xaml         # XChat IRC-inspired dark theme
└── Shared/
    └── Themes/
        └── N01DTheme.xaml      # N01D hacker color palette
```

---

## 🔧 Architecture

```
                    ┌─────────────────────┐
                    │   N01D :: OVERWATCH  │
                    │    WPF Desktop App   │
                    └──────────┬──────────┘
                               │
          ┌────────────────────┼────────────────────┐
          │                    │                     │
    ┌─────▼─────┐      ┌──────▼──────┐      ┌──────▼──────┐
    │  RSS/OSINT │      │   OpenSky    │      │  WebView2   │
    │  82+ Feeds │      │  Network API │      │  Leaflet.js │
    └─────┬─────┘      └──────┬──────┘      └──────┬──────┘
          │                    │                     │
    ┌─────▼──────────────────▼─────────────────────▼─────┐
    │              Service Layer                          │
    │  ┌──────────┐ ┌──────────┐ ┌──────────┐           │
    │  │ RssFeed  │ │ Flight   │ │ WarOps   │           │
    │  │ Service  │ │ Tracking │ │ Monitor  │           │
    │  └──────────┘ └──────────┘ └──────────┘           │
    │  ┌──────────┐ ┌──────────┐ ┌──────────┐           │
    │  │ Missile  │ │ Eclipse  │ │  Alert   │           │
    │  │ Defense  │ │ Service  │ │  Engine  │           │
    │  └──────────┘ └──────────┘ └──────────┘           │
    │  ┌──────────┐                                     │
    │  │  Ship    │  → Keyword Classifier               │
    │  │ Tracking │  → Geo-Location (70+ sites)         │
    │  └──────────┘  → Severity Engine                  │
    └───────────────────────┬───────────────────────────┘
                            │
                    ┌───────▼────────┐
                    │   Unified UI    │
                    │  XChat Theme    │
                    │  Dark Tactical  │
                    └────────────────┘
```

---

## 🎨 XChat Theme

The UI is inspired by classic **XChat IRC client** aesthetics — a deep navy-black palette with colored accents:

| Element | Color | Hex |
|---------|-------|-----|
| Background | Deep Navy | `#080810` |
| Surface | Dark Blue | `#161625` |
| Blue | Channel Blue | `#3388FF` |
| Green | Online Green | `#33CC33` |
| Red | Alert Red | `#EE3333` |
| Purple | Op Purple | `#AA55FF` |
| Orange | Warning | `#FF8833` |
| Cyan | Info Cyan | `#33CCCC` |
| Yellow | Highlight | `#DDCC33` |

---

## 🛡️ Severity Classification

Events are automatically classified into 4 severity levels:

| Level | Color | Trigger Examples |
|-------|-------|-----------------|
| **CRITICAL** | 🔴 Red | Nuclear events, chemical attacks, invasion, assassination, WMD |
| **HIGH** | 🟠 Orange | Airstrikes, missile strikes, casualties, APT zero-day, sanctions |
| **MEDIUM** | 🟡 Yellow | Notable military movements, diplomatic developments |
| **LOW** | 🟢 Green | Routine monitoring, background intelligence |

---

## 🌐 Geo-Location Database

70+ named locations with precise coordinates for automatic event geo-tagging:

- **Gaza Strip**: Gaza, Khan Younis, Rafah
- **West Bank**: Jenin, Nablus, Hebron, Ramallah
- **Israel**: Tel Aviv, Haifa, Jerusalem, Golan Heights
- **Lebanon**: Beirut, South Lebanon, Bekaa Valley, Baalbek
- **Syria**: Damascus, Aleppo, Idlib, Deir ez-Zor, Al-Tanf, Latakia, Raqqa
- **Iraq**: Baghdad, Erbil, Mosul, Basra, Al Asad, Kirkuk
- **Yemen**: Sanaa, Aden, Hodeidah, Marib, Saada
- **Iran**: Tehran, Isfahan, Natanz, Fordow, Bushehr, Bandar Abbas, Kharg Island
- **Gulf States**: Riyadh, Abu Dhabi, Dubai, Doha, Manama, Kuwait City
- **Chokepoints**: Strait of Hormuz, Bab el-Mandeb, Suez Canal, Red Sea, Persian Gulf
- **Horn of Africa**: Mogadishu, Djibouti, Khartoum

---

## 📊 Data Export

Export intelligence data in multiple formats:
- **JSON** — Full structured event data with all metadata
- **CSV** — Spreadsheet-compatible flat export
- Events include: title, summary, source, severity, category, coordinates, tags, timestamp

---

## 🤝 Contributing

Contributions welcome! Areas of interest:
- Additional OSINT feed sources
- New military callsign patterns
- Enhanced geo-location coverage
- ADS-B integration improvements
- Satellite imagery overlays
- Additional conflict zone coverage

---

## ⚖️ Legal & Ethics

This tool aggregates **publicly available, open-source information** only. It does not:
- Access classified or restricted systems
- Intercept communications
- Track specific individuals
- Violate any terms of service

Intended for **research, journalism, academic study, and situational awareness** purposes.

---

## 📜 License

MIT License — see [LICENSE](LICENSE) for details.

---

## 🔗 Related Projects

- [**n01d-suite-native**](https://github.com/bad-antics/n01d-suite-native) — Full N01D desktop tool suite (13 apps)
- [**blackflag**](https://github.com/bad-antics/blackflag) — Parent workspace with Discord bots, Docker deployments, and more

---

<p align="center">
  <strong>Built with ⚡ by <a href="https://github.com/bad-antics">bad-antics</a></strong>
  <br/>
  <em>Intelligence is a right, not a privilege.</em>
</p>
