# N01D :: OVERWATCH

```
 ███╗   ██╗ ██████╗  ██╗██████╗        ██████╗ ██╗   ██╗███████╗██████╗ ██╗    ██╗ █████╗ ████████╗ ██████╗██╗  ██╗
 ████╗  ██║██╔═══██╗███║██╔══██╗      ██╔═══██╗██║   ██║██╔════╝██╔══██╗██║    ██║██╔══██╗╚══██╔══╝██╔════╝██║  ██║
 ██╔██╗ ██║██║   ██║╚██║██║  ██║█████╗██║   ██║██║   ██║█████╗  ██████╔╝██║ █╗ ██║███████║   ██║   ██║     ███████║
 ██║╚██╗██║██║   ██║ ██║██║  ██║╚════╝██║   ██║╚██╗ ██╔╝██╔══╝  ██╔══██╗██║███╗██║██╔══██║   ██║   ██║     ██╔══██║
 ██║ ╚████║╚██████╔╝ ██║██████╔╝      ╚██████╔╝ ╚████╔╝ ███████╗██║  ██║╚███╔███╔╝██║  ██║   ██║   ╚██████╗██║  ██║
 ╚═╝  ╚═══╝ ╚═════╝  ╚═╝╚═════╝       ╚═════╝   ╚═══╝  ╚══════╝╚═╝  ╚═╝ ╚══╝╚══╝ ╚═╝  ╚═╝   ╚═╝    ╚═════╝╚═╝  ╚═╝
                              [ CONFLICT INTELLIGENCE DASHBOARD | bad-antics ]
```

Real-time Middle East and Global Conflict Intelligence Dashboard.
OSINT aggregation, flight tracking, maritime awareness, war ops monitoring, missile defense mapping, equipment order of battle, warzone radio streams, eclipse warfare analysis, satellite thermal detection, and war economy market impact tracking.

**No API keys required.** Uses publicly available OSINT feeds, the OpenSky Network, and NASA FIRMS satellite data.

---

## What is N01D Overwatch?

A Windows desktop intelligence dashboard that aggregates open-source intelligence (OSINT) from dozens of real-time sources into a single unified command interface. Built for researchers, analysts, journalists, and anyone tracking geopolitical events in conflict zones.

Think of it as a personal situation awareness terminal — pulling live data from RSS feeds, flight trackers, ship transponders, missile site databases, equipment deployments, warzone press radio streams, war operations monitoring, NASA satellite thermal hotspots, and conflict-driven market intelligence — all rendered on an interactive dark-themed map with XChat IRC aesthetics.

---

## Core Capabilities

### Multi-Source Intelligence Aggregation

- **RSS/OSINT Feeds** — 82+ sources including Reuters, AP, BBC, Al Jazeera, CENTCOM, Bellingcat, Janes, Liveuamap, The War Zone, ACLED, Airwars
- **Flight Tracking** — 160+ military callsign prefixes identified via OpenSky Network (drones, tankers, AWACS, fighters, SOF, aggressors)
- **War Ops Monitoring** — 34+ dedicated feeds across SIGACT, Sanctions, Cyber Operations, and Proxy/Militia activity
- **Missile/Defense Sites** — 24 tracked installations (IRGC ballistic missiles, Iron Dome, Arrow-2/3, THAAD, S-300/400, Patriot)
- **Equipment OOB** — Order of Battle for 8 regional forces with ~60 weapon systems, deployment locations, active counts
- **Warzone Radio** — Live press radio streams from conflict zones and CENTCOM briefings
- **Eclipse Warfare** — 11 events (2025-2028) with military significance analysis
- **Maritime Awareness** — AIS ship tracking in Strait of Hormuz, Red Sea, Persian Gulf
- **Ground Tracking** — NASA FIRMS VIIRS satellite thermal hotspots auto-refreshed every 10 minutes across the Middle East conflict zone
- **War Economy / Market Impacts** — 9 market sectors tracked: Energy, Defense, Commodities, Currencies, Shipping, Cybersecurity, Reconstruction, Insurance, Crypto. Commodity prices, defense stock watchlist, sanctions tracker, and trade feed aggregator
- **Equipment Intel Scanner** — 12 defense RSS feeds (Defense News, Janes, The War Zone, Breaking Defense, Naval News, etc.) scanned for procurement, delivery, and deployment keywords
- **Live Tracking** — 30-second auto-polling with real-time LIVE status indicator
- **Auto-Refresh Pipeline** — RSS/OSINT (configurable), Ships/Flights/WarOps (5 min), NASA FIRMS thermal (10 min), Equipment Intel RSS (every refresh cycle)

### War Ops — 4-Category Threat Monitor

- **SIGACT** — Drone strikes, airstrikes, artillery, ground ops, naval engagements, airspace closures. Feeds: CENTCOM, Liveuamap, Bellingcat, The War Zone, ACLED, Airwars, SOFREP
- **SANCTIONS** — OFAC designations, arms embargos, weapons sales, IAEA inspections, UN resolutions. Feeds: SIPRI, US Treasury, EU Sanctions Map, Arms Control Assoc., IAEA
- **CYBER** — APT groups, infrastructure attacks, state-sponsored hacking, electronic warfare. Feeds: The Record, Mandiant, CyberScoop, Dark Reading, Krebs on Security
- **PROXY** — Hezbollah, Houthi, PMF, Hamas, ISIS, SDF operations and movements. Feeds: Al Monitor, Middle East Eye, Iran International, Jamestown Foundation

### Interactive Tactical Map

- Leaflet.js rendered via WebView2 with dark CartoDB tiles
- Layer control — toggle events, flights, military bases, missile sites, air defense, equipment deployments, eclipse paths, ground flock tracking, market impact zones, heatmap
- Rich popups with severity-colored markers and event details
- JS-to-C# message bridge for real-time updates
- Heatmap overlay showing conflict density

### Equipment Order of Battle + Intel Feed

8 regional forces tracked with full equipment databases, plus a live intel feed scanning 12 defense industry RSS sources for new procurement, delivery, and deployment news:

- **Iran** — F-14A, Su-35S, Shahed-136, Fateh sub, Karrar MBT, and more
- **Israel** — F-35I Adir, F-15I Ra'am, Hermes 900, Harop, Merkava IV, Iron Dome
- **US CENTCOM** — CVN carrier, DDG-51 destroyers, F-22A, B-1B, THAAD, Patriot PAC-3
- **Saudi Arabia** — F-15SA, Typhoon, M1A2S Abrams
- **Turkey** — F-16V, KAAN prototype, TB2/Akinci drones, S-400
- **Houthis** — Toufan BM, anti-ship missiles, Samad/Qasef drones
- **Hezbollah** — 100K rockets, 1500 PGMs, 4000 ATGMs
- **UAE** — F-16E Desert Falcon, Leclerc MBT

### Warzone Radio Streams

Live press and field radio accessible from the dashboard:

- Al Jazeera English Live, BBC World Service, Voice of America Middle East
- France 24 English, Rudaw Kurdish, Iran International, i24NEWS, TRT World
- CENTCOM press briefing feeds
- Scanner and field streams when available

### Missile and Air Defense Tracking

- 12 missile sites — IRGC underground facilities, Houthi launch sites, Hezbollah arsenals, IRGCN coastal positions
- 12 air defense sites — Iron Dome, Arrow-2, Arrow-3, David's Sling, THAAD, S-300, Bavar-373, Patriot, S-400, Khordad-15
- Range rings and threat assessment on the map

### War Economy and Market Impact Tracking

Conflict-driven investment intelligence across 9 market sectors:

- **Impacts** — 15+ tracked market impacts with severity, direction, and affected assets
- **Commodities** — Brent crude, WTI, natural gas, gold, wheat, uranium, shipping rates, and more with conflict-adjusted pricing
- **Defense Stocks** — Watchlist of defense contractors (Lockheed Martin, RTX, Northrop Grumman, BAE, General Dynamics, L3Harris, etc.) with conflict catalysts
- **Alerts** — Market-moving conflict events with trade implications
- **Sanctions** — Active sanctions tracking with economic impact assessment
- **Trade Feeds** — 12 financial/defense trade news sources
- **Map Integration** — Market impact zones rendered on the tactical map with severity-colored circles

### Ground Tracking — NASA FIRMS Satellite Thermal

- VIIRS SNPP satellite data auto-refreshed every 10 minutes
- Thermal hotspot detection across the Middle East conflict zone (25-55E, 30-40N)
- Ground flock tracking with scan timestamps
- Merged into tactical map as a toggleable layer

### Eclipse Warfare Analysis

- 11 eclipse events tracked (2025-2028)
- Middle East visibility assessment
- Military significance scoring (GPS degradation, EMP vulnerability windows, SOF timing)
- Live countdown timer to next event

### Military Flight Identification

160+ callsign prefix patterns covering:

- US — USAF, Navy, Marines, Army, Coast Guard, SOF
- UK RAF, French, German, Turkish, Israeli, Russian, Chinese
- NATO AWACS, tankers, ISR, MPA
- Drone/UAV callsigns — RQ-series, MQ-series, Global Hawk, Reaper, Predator
- Aggressor/adversary squadrons
- Automatic aircraft type identification and severity classification

---

## Quick Start

### Prerequisites

- Windows 10/11 (64-bit)
- .NET 8.0 SDK — https://dotnet.microsoft.com/download/dotnet/8.0
- WebView2 Runtime (included with modern Windows / Edge)

### Build and Run

```powershell
git clone https://github.com/bad-antics/n01d-overwatch.git
cd n01d-overwatch
dotnet build
dotnet run
```

---

## Project Structure

```
n01d-overwatch/
  App.xaml / App.xaml.cs         — Application entry + theme loading
  MainWindow.xaml                — WPF UI with tabs, map, panels
  MainWindow.xaml.cs             — All application logic
  Models.cs                      — Data models, enums, event types
  N01D.Overwatch.csproj          — .NET 8, WebView2
  overwatch.ico                  — Custom radar icon
  Services/
    AlertService.cs              — Configurable alert engine
    EclipseService.cs            — Eclipse event tracking (2025-2028)
    EquipmentDatabaseService.cs  — Military OOB for 8 forces + 12 RSS intel feeds
    FlightTrackingService.cs     — OpenSky + 160 callsign patterns
    GroundTrackingService.cs     — NASA FIRMS satellite thermal hotspots
    MarketImpactService.cs       — War economy / 9-sector market tracking
    MissileDefenseService.cs     — 24 missile/defense site database
    RssFeedService.cs            — 48+ RSS feed aggregator
    ShipTrackingService.cs       — Maritime vessel tracking
    WarMonitoringService.cs      — 34+ feed war ops classifier
  Themes/
    XChatTheme.xaml              — XChat IRC-inspired dark theme
  Shared/Themes/
    N01DTheme.xaml               — N01D hacker color palette
```

---

## Architecture

```
                        N01D :: OVERWATCH
                         WPF Desktop App
                              |
         ____________________/|\____________________
        |                     |                     |
   RSS/OSINT              OpenSky                WebView2
   82+ Feeds            Network API             Leaflet.js
        |                     |                     |
        |_____________________|_____________________|
                              |
                       Service Layer
                              |
   RssFeed --- FlightTracking --- WarOps Monitor
   MissileDefense --- Eclipse --- Alert Engine
   ShipTracking --- Equipment OOB --- Radio Streams
   GroundTracking --- MarketImpact --- Equipment Intel
                              |
             Keyword Classifier + Geo-Location (70+) + Severity Engine
                              |
                         Unified UI
                       XChat IRC Theme
```

---

## XChat Theme

The UI is inspired by classic XChat IRC client aesthetics — a deep navy-black palette with colored accents:

- **Background** — Deep Navy `#080810`
- **Surface** — Dark Blue `#161625`
- **Blue** — Channel Blue `#3388FF`
- **Green** — Online Green `#33CC33`
- **Red** — Alert Red `#EE3333`
- **Purple** — Op Purple `#AA55FF`
- **Orange** — Warning `#FF8833`
- **Cyan** — Info Cyan `#33CCCC`
- **Yellow** — Highlight `#DDCC33`

---

## Severity Classification

Events are automatically classified into 4 severity levels:

- **CRITICAL** (Red) — Nuclear events, chemical attacks, invasion, assassination, WMD
- **HIGH** (Orange) — Airstrikes, missile strikes, casualties, APT zero-day, sanctions
- **MEDIUM** (Yellow) — Notable military movements, diplomatic developments
- **LOW** (Green) — Routine monitoring, background intelligence

---

## Geo-Location Database

70+ named locations with precise coordinates for automatic event geo-tagging:

- **Gaza Strip** — Gaza, Khan Younis, Rafah
- **West Bank** — Jenin, Nablus, Hebron, Ramallah
- **Israel** — Tel Aviv, Haifa, Jerusalem, Golan Heights
- **Lebanon** — Beirut, South Lebanon, Bekaa Valley, Baalbek
- **Syria** — Damascus, Aleppo, Idlib, Deir ez-Zor, Al-Tanf, Latakia, Raqqa
- **Iraq** — Baghdad, Erbil, Mosul, Basra, Al Asad, Kirkuk
- **Yemen** — Sanaa, Aden, Hodeidah, Marib, Saada
- **Iran** — Tehran, Isfahan, Natanz, Fordow, Bushehr, Bandar Abbas, Kharg Island
- **Gulf States** — Riyadh, Abu Dhabi, Dubai, Doha, Manama, Kuwait City
- **Chokepoints** — Strait of Hormuz, Bab el-Mandeb, Suez Canal, Red Sea, Persian Gulf
- **Horn of Africa** — Mogadishu, Djibouti, Khartoum

---

## Data Export

- **JSON** — Full structured event data with all metadata
- **CSV** — Spreadsheet-compatible flat export

---

## Legal and Ethics

This tool aggregates publicly available, open-source information only. It does not access classified systems, intercept communications, track individuals, or violate any terms of service. Intended for research, journalism, academic study, and situational awareness.

---

## License

MIT License — see LICENSE for details.

---

## Related Projects

- **n01d-suite-native** — https://github.com/bad-antics/n01d-suite-native — Full N01D desktop tool suite (13 apps)
- **blackflag** — https://github.com/bad-antics/blackflag — Parent workspace

---

Built by bad-antics — https://github.com/bad-antics
Intelligence is a right, not a privilege.
