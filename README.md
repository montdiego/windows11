# Windows 11 Configuration Setup Guide

<details>
<summary>📌 Windhawk Mods Installation</summary>

### 1. Download Windhawk
[Download Windhawk](https://windhawk.net/download){:target="_blank"}

### 2. Install Required Plugins
Download configurations from [windows11 repository](https://github.com/montdiego/windows11){:target="_blank"}:

| Plugin Name | Configuration File |
|-------------|--------------------|
| Taskbar auto-hide when maximized | Default |
| Taskbar Clock Customization | [config.json](https://github.com/montdiego/windows11/blob/main/clock.json){:target="_blank"} |
| Taskbar height and icon size | [config.json](https://github.com/montdiego/windows11/blob/main/taskbar_size.json){:target="_blank"} |
| Taskbar tray system icon tweaks | [config.json](https://github.com/montdiego/windows11/blob/main/tray_icons.json){:target="_blank"} |
| Notification Center Styler | [config.json](https://github.com/montdiego/windows11/blob/main/notifications.json){:target="_blank"} |
| Start Menu Styler | [config.json](https://github.com/montdiego/windows11/blob/main/start_menu.json){:target="_blank"} |
| Taskbar Styler | [config.json](https://github.com/montdiego/windows11/blob/main/taskbar.json){:target="_blank"} |

</details>

<details>
<summary>🎨 Desktop Background Setup</summary>

1. Download wallpaper:  
   [custom-background.jpg](https://github.com/montdiego/windows11/blob/main/background.jpg){:target="_blank"}
2. Right-click image → "Set as desktop background"

</details>

<details>
<summary>⚡ Flow Launcher Setup</summary>

### 1. Install Application
[Download Flow Launcher](https://www.flowlauncher.com/#){:target="_blank"}

### 2. Apply Configuration
1. Hide when on Tray
2. Start on Windows startup

### 3. Install Theme
1. Download: [theme.json](https://github.com/montdiego/windows11/blob/main/flow_launcher.xaml){:target="_blank"}
2. Place in:  
   `%AppData%\FlowLauncher\Themes`

</details>

<details>
<summary>🔧 Windows Required & Suggested Settings</summary>

### Required Settings
1. Enable **Transparency Effects**:  
   **Settings → Personalization → Colors → Transparency Effects → ON**
2. Set **Accent Color** to `#7D2D02`:  
   **Settings → Personalization → Colors → Choose your color → Custom → Accent Color → #7D2D02**

### Suggested Settings
- Enable **Animations** for smoother UI:  
  **Settings → Accessibility → Visual Effects → Animation Effects → ON**

</details>

<details>
<summary>🛠️ Windows 11 Debloat & Privacy Optimization</summary>

### 1. Run Windows 11 Debloater
Run the following command in **PowerShell (Admin)**:
```powershell
irm 'https://christitus.com/win' | iex
```
Alternatively, you can download the `.bat` script from:
[Download Debloat Script](https://github.com/montdiego/windows11/blob/main/debloat.bat){:target="_blank"}

### 2. Apply Recommended Settings
- Download settings for the debloat tool:  
  [debloat-settings.json](https://github.com/montdiego/windows11/blob/main/debloat_settings.json){:target="_blank"}
- Download O&O ShutUp10++ settings:  
  [ooshutup10-settings.cfg](https://github.com/montdiego/windows11/blob/main/ooshutup10.cfg){:target="_blank"}
- **Note:** If using a desktop PC, disable **hibernation** after applying settings.

</details>

<details>
<summary>🧹 Windows Cleaning & Optimization</summary>

Use **CCleaner Portable** for cleaning, optimizing, and removing unnecessary files:
[Download CCleaner Portable](https://portableapps.com/apps/utilities/ccportable){:target="_blank"}

</details>
