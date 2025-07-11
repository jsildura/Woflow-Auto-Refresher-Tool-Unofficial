# Woflow-Auto-Refresher-Unofficial

## Overview
Woflow Auto Refresh Tool is a Chrome extension that allows users to automatically refresh browser tabs at specified intervals. It is designed to enhance productivity by eliminating the need for manual refreshes, ensuring up-to-date content at all times.

## Features ✨
- ⏱️ **Auto-refresh** pages from 1 second to 48 hours
- 🌐 **Multi-URL support** with individual intervals
- 📊 **Performance monitoring** (CPU & memory)
- 🎨 **Fluent Design UI** with light/dark themes
- 🔢 **Visual countdown** timer in toolbar
- 📈 **Refresh statistics** tracking
- ⌨️ **Keyboard shortcuts** for quick control
- 🔄 **Session persistence** across browser restarts
- 🔁 **New Version Checker** check for new version

## Installation

## Chrome/Edge/Brave
1. Download [Link](https://github.com/user-attachments/files/21173814/Auto_Refresh_Tool_1.4.4.zip)
2. Unzip the file
3. Open Chrome and navigate to `chrome://extensions/`. for edge `edge://extensions/`
4. Enable "Developer mode" (chrome: top right corner), (edge: Bottom left corner).
5. Click "Load unpacked" and select the project folder.
6. The extension is now ready to use.

## Usage 🚀

1. Click on the extension icon in the browser toolbar.
2. Set the desired refresh interval.
3. Select tabs to refresh.
4. Click "Start" to begin auto-refreshing.
5. Click "Stop" to pause refresh.
6. Use "Reset" to clear interval settings.

## Keyboard Shortcuts
| Shortcut           | Action                 |
| ------------------ | ---------------------- |
| `Enter`            | Start refresh          |
| `ESC`              | Stop refresh           |
| `Delete`           | Reset all              |
| `Alt + M`          | Toggle sliding menu    |
| `Ctrl + Shift + E` | Start refresh (global) |
| `Ctrl + Shift + D` | Stop refresh (global)  |

## Sliding Menu Features

🔗 Active URLs Tab
- View all monitored pages
- See refresh counts and intervals
- Remove individual URLs


📊Performance Tab
- Real-time CPU usage (%)
- Memory consumption (MB)
- System resource monitoring

## Technical Details 🛠️
- Architecture
<img width="2181" alt="deepseek_mermaid_20250711_121610" src="https://github.com/user-attachments/assets/e20f92a1-2297-46aa-80f1-a924ea01c802" />

## Technologies
- Chrome Extensions API
- Fluent Design System
- CSS Animations
- System Performance APIs
  
## Permissions
| **Permission**  | **Why We Need It**                                                    | **What You'll See**                                             |
| --------------- | --------------------------------------------------------------------- | --------------------------------------------------------------- |
| `tabs`          | To access and reload your browser tabs for auto-refresh functionality | Enables the core feature of refreshing your pages automatically |
| `storage`       | To save your preferences (intervals, settings) between sessions       | Remembers your settings when you close/reopen the browser       |
| `commands`      | To enable keyboard shortcuts for quick control                        | Lets you use `Ctrl+Shift+` shortcuts for common actions         |
| `system.cpu`    | To monitor and display CPU usage in the dashboard                     | Shows system impact in the **Performance** tab (optional)       |
| `system.memory` | To monitor and display memory usage in the dashboard                  | Shows system impact in the **Performance** tab (optional)       |
| `activeTab`     | To interact with your currently active tab                            | Required to start/stop refresh on your current page             |
| `webNavigation` | To detect when you navigate between pages                             | Maintains proper refresh state during browsing                  |
| `notifications` | To alert you about important events                                   | Shows update notifications and status messages                  |

## Troubleshooting 🔧
Refresh not working?
- Verify tab is active (background tabs may throttle)
- Check URL hasn't changed (redirects may break tracking)
- Confirm interval is 1-172800 seconds

High CPU usage?
- Increase refresh intervals
- Reduce number of active refreshes
- Check for extension conflicts

## Future Enhancements
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


## Developer - Joe Sildura
- 📧 Contact: sildura.joelito.t@gmail.com
- 🐛 Report issues: GitHub Issues
