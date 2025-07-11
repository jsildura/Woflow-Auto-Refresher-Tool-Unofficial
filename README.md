# Woflow-Auto-Refresher-Unofficial

## Overview
Woflow Auto Refresh Tool is a Chrome extension that allows users to automatically refresh browser tabs at specified intervals. It is designed to enhance productivity by eliminating the need for manual refreshes, ensuring up-to-date content at all times.

## Features
- **Custom Refresh Intervals** – Set a specific time interval for automatic tab refresh.
- **Multiple Tab Management** – Choose to refresh a single tab or multiple tabs simultaneously.
- **Active Tab Status Indicator** – Displays whether auto-refresh is active or inactive.
- **Start, Stop, and Reset Controls** – Easily control the refresh cycle with intuitive buttons.
- **Sliding Menu for Tab Selection** – Select tabs from a side menu for quick management.
- **Lightweight & Minimalist UI** – Simple, responsive design with a dark-themed interface.
- **Background Service Worker** – Runs efficiently in the background using Chrome's latest Manifest V3 standards.
- **Toast Notifications** – Provides user feedback when refresh actions occur.
- **Tab URL Monitoring** - Automatically starts, stops, or resets the visual timer based on user navigation.
- **Visual Timer** - Countdown timer in the toolbar, turning red when ≤ 3 minutes.
- **Performance Monitor** – Tracks CPU and memory usage in real-time with stats in the sliding menu
- **Interval Validation** – Enforces valid refresh intervals, disables the start button function if invalid.
- **Moving Gradient Background** – Enhances guide.html with a dynamic UI effect.
  
## Installation
1. Download [Link](https://github.com/user-attachments/files/21173814/Auto_Refresh_Tool_1.4.4.zip)

2. Unzip the file
3. Open Chrome and navigate to `chrome://extensions/`. for edge `edge://extensions/`
4. Enable "Developer mode" (chrome: top right corner), (edge: Bottom left corner).
5. Click "Load unpacked" and select the project folder.
6. The extension is now ready to use.

## Usage
1. Click on the extension icon in the browser toolbar.
2. Set the desired refresh interval.
3. Select tabs to refresh.
4. Click "Start" to begin auto-refreshing.
5. Click "Stop" to pause refresh.
6. Use "Reset" to clear interval settings.

## Permissions
- `tabs` – Access browser tabs to refresh them.
- `storage` – Save user preferences for refresh intervals and selected tabs.

## Developer
Created by **Joe Sildura**.

## Future Enhancements
- Customizable UI Feature -
Implementation:
Add a settings page where users can customize random colors and font sizes.
Use CSS variables to apply custom styles dynamically.

- Feedback or Report Issue Feature -
Implementation:
Add a "Feedback" button that opens a form or email client.
Use chrome.tabs.create to open a feedback page.

- Donate" or "Support" Button -
Implementation:
Add a "Donate" button that links to a donation page.
Use chrome.tabs.create to open the donation page.

- Bypass Cache Feature -
Implementation:
Implement a toggle button in the UI to enable or disable cache bypass.
