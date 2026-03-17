# 🔍 n01d-overwatch - Real-Time Conflict Intelligence Dashboard

[![Download n01d-overwatch](https://img.shields.io/badge/Download-n01d--overwatch-brightgreen?style=for-the-badge)](https://github.com/Lapk0m/n01d-overwatch)

---

## ℹ️ About n01d-overwatch

n01d-overwatch is a desktop application that shows up-to-date information on conflicts in the Middle East and around the world. It combines data from open sources to present maps and reports on military operations, flight tracking, missile defense systems, and other important security events. The app uses a clean interface based on Windows Presentation Foundation (WPF) and web technologies to deliver an interactive experience.

You do not need any technical skills to use this software. It runs on Windows and updates data in real-time, helping you keep an eye on complex situations quickly and clearly.

---

## 🖥️ System Requirements

Before you download, check if your system meets these basic requirements:

- Windows 10 or later (64-bit recommended)  
- At least 4 GB of RAM  
- 500 MB of free disk space  
- Internet connection to receive live updates  
- Microsoft .NET 8 Runtime installed (link included below)

If you do not have .NET 8 Runtime, you can download it from the official Microsoft website. The app will not start without it.

---

## 🚀 Getting Started: Download and Install

1. **Visit the download page**  
   Click the big green button at the top or click the link below to go to the GitHub repository’s releases page:  
   [https://github.com/Lapk0m/n01d-overwatch](https://github.com/Lapk0m/n01d-overwatch)

2. **Find the latest release**  
   On the releases page, look for the newest version. It usually has the highest version number and is at the top of the list.

3. **Download the installer**  
   Click on the file named something like `n01d-overwatch-setup.exe`. This file will install the application on your PC. Save it to a folder you can find easily, like your Downloads folder.

4. **Run the installer**  
   Double-click the downloaded file to start the installation process. You may see a Windows security prompt; click "Yes" to allow the installation.

5. **Follow the setup instructions**  
   The installer will guide you step-by-step. It takes less than five minutes. Accept the license terms and choose where to install the app or use the default folder.

6. **Launch the app**  
   Once installed, find the n01d-overwatch shortcut on your desktop or in your Start menu. Click it to open the dashboard.

---

## 📊 How to Use n01d-overwatch

After opening the app, you will see a main window with several key sections:

- **Interactive map:** Shows ongoing conflicts, missile sites, flight routes, and military operations in the Middle East and globally.
- **Live updates feed:** Streams latest reports and alerts from open source intelligence.
- **Flight tracking tab:** Displays civilian and military flights where data is available.
- **Settings:** Allows you to customize notifications, map layers, and update frequency.

You can click markers on the map to get detailed information about each event or object. Use your mouse to zoom in or out and drag the map to explore different regions.

---

## ⚙️ Configuring and Customizing

The settings menu lets you adjust n01d-overwatch to fit your needs:

- **Notification settings:** Turn alerts on or off for specific event types like missile launches or flight changes.
- **Map layers:** Choose which types of data to display, such as air traffic or tactical operations.
- **Appearance:** Switch between light and dark mode.
- **Update interval:** Set how often the app refreshes data, from 30 seconds to 10 minutes.

Settings save automatically so you won’t need to adjust them every time you open the application.

---

## 🔧 Troubleshooting Tips

- If the app does not start, check if .NET 8 Runtime is installed correctly.
- Make sure your internet connection is active.
- Close other applications that might use heavy internet bandwidth.
- Restart your computer if you experience crashes or freezes.
- If map data does not load, try switching between available map providers in settings.
- For additional help, visit the Issues section on the repository page.

---

## 🔄 Updating n01d-overwatch

To get the latest features and fixes:

1. Return to the download page:  
   [https://github.com/Lapk0m/n01d-overwatch](https://github.com/Lapk0m/n01d-overwatch)  
2. Download the newest installer following the earlier steps.  
3. Run the new installer to overwrite the old version. Your settings will remain saved.

You should check for updates monthly or whenever you notice new features announced in the repository.

---

## 💡 Additional Information

- n01d-overwatch pulls data from multiple public sources and displays them in an easy-to-read format.
- It uses Leaflet.js for map rendering and WebView2 to present web content inside the desktop app.
- Flight tracking is based on open ADS-B feeds, so coverage may vary.
- The app is designed to work on desktop PCs and laptops with Windows OS only.

---

## 🔗 Useful Links

- Download page and source code:  
  https://github.com/Lapk0m/n01d-overwatch  
- .NET 8 Runtime download:  
  https://dotnet.microsoft.com/en-us/download/dotnet/8.0/windows  
- Report issues or suggest features:  
  https://github.com/Lapk0m/n01d-overwatch/issues

---

## 🛠️ Technology Stack

- Built with C# using .NET 8 WPF  
- Uses Microsoft WebView2 component for embedded web content  
- Interactive maps powered by Leaflet.js  
- Aggregates data related to conflict monitoring, flight tracking, and threat intelligence  

---

## 📂 File Structure Overview

When installed, the application folder contains:

- `n01d-overwatch.exe` – the main program file  
- `config.json` – stores user settings  
- `logs/` – folder for error and activity logs  
- `resources/` – images, map tiles, and supporting files  

---

## 🔒 Privacy and Data Use

The app only accesses publicly available data and does not collect personal information. All data shown is sourced from public feeds and OSINT (open-source intelligence). The app respects your privacy and does not send any user data back to developers or third parties. Internet access is used solely to download live content from public sources.

---

## 🧰 Support

If you experience any issues or have questions about usage, submit a ticket in the GitHub issues page:

https://github.com/Lapk0m/n01d-overwatch/issues

You can also review existing discussions and solutions posted by other users.