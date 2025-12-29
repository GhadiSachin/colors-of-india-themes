# Step-by-Step Installation Guide

## Prerequisites
- Visual Studio Code installed (version 1.60.0 or higher)
- Basic familiarity with VS Code extensions

## Installation Methods

### Method 1: Install from VSIX (Recommended)

1. **Download the VSIX file**
   - Locate the `colors-of-india-themes-1.0.0.vsix` file

2. **Open VS Code**
   - Launch Visual Studio Code

3. **Open Command Palette**
   - Windows/Linux: Press `Ctrl + Shift + P`
   - Mac: Press `Cmd + Shift + P`

4. **Install Extension**
   - Type: `Extensions: Install from VSIX`
   - Press Enter
   - Navigate to and select the downloaded `.vsix` file
   - Click "Install"

5. **Wait for Installation**
   - VS Code will install the extension automatically
   - You'll see a notification when complete

6. **Activate Theme**
   - Press `Ctrl + K` then `Ctrl + T` (or `Cmd + K` then `Cmd + T` on Mac)
   - Select your preferred "Colors of India" theme
   - Or go to: `File > Preferences > Color Theme`

### Method 2: Manual Installation

1. **Extract the ZIP file**
   - Extract `colors-of-india-themes.zip`

2. **Locate VS Code Extensions Folder**
   - **Windows**: `C:\Users\[YourUsername]\.vscode\extensions`
   - **Mac**: `~/.vscode/extensions`
   - **Linux**: `~/.vscode/extensions`

3. **Copy Theme Folder**
   - Copy the extracted `colors-of-india-themes` folder
   - Paste it into the extensions folder

4. **Restart VS Code**
   - Close and reopen VS Code completely

5. **Select Theme**
   - `File > Preferences > Color Theme`
   - Choose your desired theme from the list

### Method 3: Development Mode (For Developers)

1. **Clone or Extract**
   - Extract the theme folder to any location

2. **Open in VS Code**
   - Open the theme folder in VS Code
   - Press `F5` to open Extension Development Host

3. **Test Theme**
   - In the new window, select the theme
   - Make changes to theme files
   - Reload to see updates

## Activating Themes

### Quick Switch
1. Press `Ctrl + K` then `Ctrl + T` (Windows/Linux)
2. Or `Cmd + K` then `Cmd + T` (Mac)
3. Use arrow keys to preview themes
4. Press Enter to select

### Through Settings
1. Click gear icon (⚙️) in bottom left
2. Select "Color Theme"
3. Browse and select your theme

## Available Themes

You'll see these themes in your Color Theme list:
- ✅ Kerala - God's Own Country
- ✅ Rajasthan - Land of Kings
- ✅ Tamil Nadu - Temple Land
- ✅ Maharashtra - Land of Warriors
- ✅ Punjab - Land of Five Rivers
- ✅ West Bengal - Cultural Hub
- ✅ Gujarat - Vibrant Culture
- ✅ Karnataka - Sandalwood State
- ✅ Assam - Tea Gardens
- ✅ Goa - Beach Paradise

## Customizing Themes

### Override Specific Colors

Add to your `settings.json`:

```json
{
  "workbench.colorCustomizations": {
    "[Kerala - God's Own Country]": {
      "editor.background": "#1a1a1a",
      "activityBar.background": "#2D5016"
    }
  }
}
```

### Modify Token Colors

```json
{
  "editor.tokenColorCustomizations": {
    "[Rajasthan - Land of Kings]": {
      "comments": "#6A9955",
      "strings": "#FFD700"
    }
  }
}
```

## Troubleshooting

### Theme Not Appearing
- Ensure VS Code is version 1.60.0 or higher
- Restart VS Code after installation
- Check the extensions folder path is correct

### Colors Look Wrong
- Some color values may need monitor calibration
- Try adjusting VS Code settings
- Report issues on GitHub

### Installation Failed
- Check file permissions
- Run VS Code as administrator (Windows)
- Verify the folder structure is intact

## Uninstalling

### From VSIX Install
1. Go to Extensions view (`Ctrl + Shift + X`)
2. Find "Colors of India - State Themes"
3. Click the gear icon
4. Select "Uninstall"

### From Manual Install
1. Navigate to extensions folder
2. Delete the `colors-of-india-themes` folder
3. Restart VS Code

## Support

For issues or questions:
- Check the README.md file
- Review this installation guide
- Report bugs on GitHub

---
**Happy Theming! 🎨🇮🇳**
