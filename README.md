<p align="center">
  <img src="https://clickfitapp.com/images/app-icon-light.png" alt="ClickFit" width="128" height="128" />
</p>

<h1 align="center">ClickFit</h1>

<p align="center">
  <strong>Every window, exactly where you want it.</strong><br />
  Effortless window management for macOS — drag, snap, tile, and resize with a single gesture.
</p>

<p align="center">
  <a href="https://github.com/mertogzhn/ClickFitMac/releases/latest"><img src="https://img.shields.io/github/v/release/mertogzhn/ClickFitMac?style=for-the-badge&label=Download&color=8b9fcc" alt="Latest Release" /></a>
  <a href="https://clickfitapp.com"><img src="https://img.shields.io/badge/Website-clickfitapp.com-8b9fcc?style=for-the-badge" alt="Website" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/macOS-15%20Sequoia%2B-black?logo=apple" alt="macOS 15+" />
  <img src="https://img.shields.io/badge/Apple%20Silicon%20%26%20Intel-Universal-green" alt="Universal Binary" />
  <img src="https://img.shields.io/badge/Built%20with-Swift-F05138?logo=swift&logoColor=white" alt="Swift" />
</p>

---

<p align="center">
  <img src="https://clickfitapp.com/images/screenshots/dark.jpg" alt="ClickFit in action" width="100%" />
</p>

## About

ClickFit is a native macOS menu-bar app that turns your mouse and trackpad into a complete window-management toolkit. Hold a modifier, click anywhere on a window, and move, resize, tile, or arrange it — without hunting for tiny edges or title bars. It stays invisible until you need it.

## Installation

1. Download the latest **`ClickFit.dmg`** from the [Releases](https://github.com/mertogzhn/ClickFitMac/releases/latest) page.
2. Open the DMG and drag **ClickFit.app** to your `/Applications` folder.
3. Launch ClickFit. On first run, grant access in **System Settings → Privacy & Security → Accessibility**.
4. The ClickFit icon appears in your menu bar — you're ready to go.

ClickFit also updates itself automatically. New releases are delivered via Sparkle and signed with a Developer ID certificate.

## Requirements

- macOS 15 Sequoia or later
- Apple Silicon or Intel Mac (Universal binary)
- Accessibility permission (required at runtime — never collected or sent anywhere)

## Features

### Mouse Gestures
Hold your chosen modifier and **left-drag** to move any window from anywhere on its surface. **Right-drag** to resize from any point — no more chasing 4-pixel edges. **Double-click** to center, **double-right-click** to maximize.

### Smart Snapping
Windows snap to screen edges, neighboring window borders, and grid positions. Visual previews show exactly where a window will land before you release.

### Coupled Resize
Grab the shared edge between two adjacent windows and resize them together in perfect sync. ClickFit's coupling engine works with both its own gestures and macOS native corner-drag resize, even on Chrome and Electron apps.

### Tile Zones
Throw a window toward any edge or corner to tile it into halves, quarters, thirds, fourths, sixths, or full-screen. Adaptive tiling adjusts boundaries based on already-anchored neighbors so layouts stay tight.

### Layouts
20+ built-in multi-window layouts — columns, rows, grids, focus arrangements, and split ratios — plus a full-screen drawing editor for your own custom layouts. Apply any layout instantly via hotkey or the radial picker.

### Radial Layout Picker
Hold a modifier and right-click (or double-tap with four fingers on the trackpad) to open a circular picker. Hover any layout for a live preview, then click to apply.

### Throw-to-Zone
A directional gesture that maps the angle and distance of your throw to a tile zone — short throws hit halves, longer throws land in a 3×3 grid, and the longest throws move windows to neighboring displays.

### Tab Groups
Stack multiple windows into a single frame with a tabbed bar — like browser tabs, but for any app. Drag windows into the same spot to auto-tab, or build groups manually.

### Workspaces
Capture a snapshot of every open window — apps, frames, displays, and tab groups — and restore it on demand. Workspaces survive reboots, cable swaps, and resolution changes thanks to topology-aware adaptation.

### Keyboard Shortcuts
Every action is bindable to a global hotkey: tiling, centering, maximizing, raising, layout switching, workspace recall, cross-display moves, and more.

### Multi-Display & Spaces
Move windows across monitors and macOS Spaces with a single shortcut. ClickFit understands mixed-resolution and mixed-DPI setups.

### Restore Position
Made a mistake? Tap the restore hotkey to flip a window back to its previous frame. Free for everyone — no Pro license required.

## Pricing

ClickFit ships with a **7-day free trial** of every feature. After the trial, a subscription unlocks Pro features like layouts, workspaces, tab groups, and the radial picker. Core gestures, snapping, and restore-position remain free.

License management lives in **Settings → License** inside the app.

## Support

- **Bugs and feature requests:** [Issues](https://github.com/mertogzhn/ClickFitMac/issues)
- **Release notes:** [clickfitapp.com/release-notes](https://clickfitapp.com/release-notes)
- **Email:** mert.oguzhanasilturk@gmail.com

## Privacy

ClickFit runs entirely on your Mac. It does not collect telemetry, track usage, or upload window data anywhere. Accessibility permission is used only to read and write window frames locally. Optional crash reporting via Sentry is opt-in.

---

<p align="center">
  &copy; 2026 ClickFit. All rights reserved.
</p>
