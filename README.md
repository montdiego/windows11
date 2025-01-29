# Windows 11 Configuration Setup Guide

## Windhawk Mods Installation

### 1. Download Windhawk
- Download the latest version of Windhawk:  
  [Windhawk Official Download](https://windhawk.net/download)

### 2. Install Required Plugins
After installing Windhawk, import the following configurations from this repository:

| Plugin Name | Description | Configuration File |
|-------------|-------------|--------------------|
| **Taskbar auto-hide when maximized** | Auto-hides taskbar only when a window is maximized | [Download Config](repo/windhawk/taskbar-auto-hide-config.json) |
| **Taskbar Clock Customization** | Custom date/time formats, fonts, and colors | [Download Config](repo/windhawk/taskbar-clock-config.json) |
| **Taskbar height and icon size** | Adjust taskbar height/icon size (Win11) | [Download Config](repo/windhawk/taskbar-height-config.json) |
| **Taskbar tray system icon tweaks** | Hide system icons or "Show desktop" button | [Download Config](repo/windhawk/taskbar-tray-config.json) |
| **Windows 11 Notification Center Styler** | Custom Notification Center themes | [Download Config](repo/windhawk/notification-center-config.json) |
| **Windows 11 Start Menu Styler** | Custom Start Menu themes | [Download Config](repo/windhawk/start-menu-config.json) |
| **Windows 11 Taskbar Styler** | Custom Taskbar themes | [Download Config](repo/windhawk/taskbar-styler-config.json) |

**Steps to Import Configs**:
1. Open Windhawk
2. Click `Install Mod` > `Import from File`
3. Select the downloaded JSON configuration files

---

## Desktop Background Setup

### 1. Download Wallpaper
- Download the wallpaper from the repository:  
  [Wallpaper Download](repo/wallpapers/custom-background.jpg)

### 2. Set as Desktop Background
1. Right-click the downloaded image
2. Select "Set as desktop background"

---

## Flow Launcher Setup

### 1. Install Flow Launcher
- Download the latest version:  
  [Flow Launcher GitHub Release](https://github.com/Flow-Launcher/Flow.Launcher/releases)

### 2. Apply Configuration
1. Download the config file:  
   [Flow Config Download](repo/flow-launcher/config.json)
2. Navigate to Flow Launcher settings folder:
   - Press `Win + R` and paste:  
     `%AppData%\FlowLauncher\Settings`
3. Replace `Settings.json` with the downloaded config file

---

## ShareX Setup

### 1. Install ShareX
- Download the latest version:  
  [ShareX Official Download](https://getsharex.com/)

### 2. Apply Custom Configuration
1. Download the config file:  
   [ShareX Config Download](repo/sharex/sharex-config.sxcr)
2. Open ShareX
3. Go to `Tools > Import/Export > Import settings...`
4. Select the downloaded `.sxcr` file

---

**Replace `repo/` with your repository's actual path**  
Example: `https://github.com/yourusername/your-repo/blob/main/windhawk/...`
