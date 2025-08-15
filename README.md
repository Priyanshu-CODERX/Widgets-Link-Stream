<div align="center">
  <img src="assets/icons/icon.png" alt="Widgets Link Icon" width="128" height="128">
  <h1>Widgets Link</h1>
  <p>Share your MacBook screen to Widgets mixed reality app on Meta Quest headsets</p>
</div>

**Widgets Link** is a specialized macOS application that enables seamless screen sharing from your MacBook to the **Widgets mixed reality application** on Meta Quest headsets. Transform your MacBook into a powerful mixed reality workspace by streaming your screen directly to your VR headset.

## Features

- **Meta Quest Integration**: Seamlessly connect to Widgets mixed reality app
- **Real-time Screen Sharing**: Stream your MacBook display to VR in real-time
- **Optimized Performance**: Built specifically for Apple Silicon (M-series) MacBooks
- **Low Latency**: Minimal delay for responsive mixed reality experience
- **Privacy Focused**: Local processing with no cloud data transmission
- **Secure Pairing**: Pair via a one-time security code shown in the PC Connect widget, then click Start Capture

## System Requirements

- **MacBook**: Must have Apple Silicon (M1, M1 Pro, M1 Max, M2, M2 Pro, M2 Max, M3, M3 Pro, M3 Max)
- **macOS**: 12.0 (Monterey) or later
- **Meta Quest**: Quest 2, Quest Pro, or Quest 3 with Widgets app installed
- **Network**: Both devices must be on the same Wi-Fi network
- **RAM**: 8GB minimum, 16GB recommended
- **Storage**: 100MB available space

## Download

📥 **Download the latest version**: (https://github.com/yourusername/Widgets-Link-Stream/releases/)

## Installation

### Step 1: Download
1. Click the download link above
2. Download the `.dmg` file for your M-series MacBook

### Step 2: Install
1. **Open the downloaded `.dmg` file** (double-click in Downloads folder)
2. **Drag `Widgets Link.app` into your Applications folder**
3. **Eject the installer** by clicking the eject button next to "Widgets Link" in Finder

### Step 3: First Launch
Since this is an unsigned app, you'll need to bypass macOS security warnings:

1. **Right-click** on `Widgets Link.app` in your Applications folder
2. Select **"Open"** from the context menu
3. Click **"Open"** in the security dialog that appears
4. The app will now launch normally

**Note**: You only need to do this once. Future launches can be done normally.

## Required Permissions

### Screen Recording Permission
Widgets Link needs Screen Recording permission to capture and stream your MacBook's display:

1. **Launch Widgets Link** (following the steps above)
2. When prompted, click **"Allow"** for Screen Recording permission
3. **Quit the app completely** (⌘+Q)
4. **Reopen the app** - it should now work properly

### Manual Permission Setup (if needed)
If the app doesn't prompt for permissions:

1. Open **System Settings** (or System Preferences on older macOS)
2. Go to **Privacy & Security** → **Screen Recording**
3. Find **Widgets Link** in the list and check the box
4. **Quit and reopen** the app

## Usage

### Getting Started
1. On your Meta Quest headset, open the **Widgets** app, then open the **PC Connect** widget. A one-time **security code** will be displayed.
2. On your MacBook, launch **Widgets Link** from Applications or Spotlight (⌘+Space, then type "Widgets Link").
3. Enter the **security code** shown in the PC Connect widget into Widgets Link on your MacBook.
4. Click **Start Capture**.
5. If prompted, grant **Screen Recording** permission.
6. Your MacBook screen will now stream to the **PC Connect** widget in the Widgets mixed reality app.

### Connection Process
- Both devices must be on the **same Wi‑Fi network**
- Open the **PC Connect** widget on the headset to get the security code
- Enter the code in **Widgets Link** on your MacBook
- Click **Start Capture** to begin streaming
- Your MacBook display appears inside the **Widgets** mixed reality environment

### Disconnecting
- Click **Disconnect** in Widgets Link
- Or close Widgets Link to end the session

## Troubleshooting

### App Won't Open
- **Follow the First Launch steps** above (right-click → Open)
- Check if the app is blocked in **System Settings** → **Privacy & Security** → **Security**
- Try **restarting your MacBook** and launching again

### Permissions Not Working
- **Quit the app completely** (⌘+Q)
- **Recheck permissions** in System Settings
- **Restart your MacBook** and try again

### Can't Connect to Quest
- Ensure both devices are on the **same Wi‑Fi network**
- Confirm the **Widgets app** is running and the **PC Connect** widget is open
- Verify you entered the **exact security code** shown in the headset
- Try **restarting both devices** and reconnecting
- Ensure the **Quest headset is awake** (not in sleep mode)

### Security Code Issues
- If the code shows as **invalid**, double‑check each digit and try again
- If the code **expired**, reopen the **PC Connect** widget to get a new code
- Make sure there are **no leading/trailing spaces** when entering the code

### Screen Not Sharing
- Ensure **Screen Recording permission** is granted to Widgets Link
- Confirm you clicked **Start Capture** after entering the code
- Keep the **PC Connect** widget open on the headset while streaming
- Try **Disconnect**, then reconnect with a fresh code

### Performance Issues
- **Close unnecessary applications** on your MacBook
- Ensure a **stable Wi‑Fi connection** between devices
- **Restart both devices** if you experience lag or stuttering

## Screenshots

### Main Application Interface
![Widgets Link Application](/assets/screenshots/widgets-link-app.png)
*The main Widgets Link application interface for connecting to Meta Quest headsets*

### Permission Setup Process
![Permission Request](/assets/screenshots/permission-ask.png)
*Screen recording permission request dialog - click "Allow" to proceed*

![System Settings - Screen Recording](/assets/screenshots/screen-system-recording.png)
*Add Widgets Link to the Screen Recording whitelist in System Settings*

---

*These screenshots show the complete setup process from app launch to permission configuration*

## Support

- **Issues**: Report bugs or problems on the [GitHub Issues page](https://github.com/yourusername/Widgets-Link-Stream/issues)
- **Questions**: Check existing issues or create a new one for help
- **Feature Requests**: We welcome suggestions for improving the Meta Quest integration

## License

This project is licensed under the MIT License - see the [LICENSE.txt](LICENSE.txt) file for details.

---

**Widgets Link** - Bridge your MacBook to the mixed reality world of Widgets on Meta Quest.

*Built specifically for Apple Silicon MacBooks to deliver the best mixed reality experience* 