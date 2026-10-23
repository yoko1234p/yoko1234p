<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img src="assets/header-light.svg" alt="Pak Wing HO — independent macOS and browser tools" width="100%">
</picture>

[**English**](README.md) · [繁體中文](README.zh-Hant.md) · [简体中文](README.zh-Hans.md)

I build independent macOS and browser tools that make everyday work easier to find, finish and review.

## Featured tools

<p align="center">
<a href="https://github.com/yoko1234p/BarPilot"><img src="assets/card-BarPilot.svg" alt="BarPilot" width="31%"></a>
<a href="https://github.com/yoko1234p/EdgeNotes"><img src="assets/card-EdgeNotes.svg" alt="EdgeNotes" width="31%"></a>
<a href="https://github.com/yoko1234p/NotchHub"><img src="assets/card-NotchHub.svg" alt="NotchHub" width="31%"></a>
</p>

## Technical profile

I work with native macOS frameworks, browser extensions, web interfaces and test tooling. Each area below links to public code you can inspect.

| Area | Used in these projects | Source evidence |
|:--|:--|:--|
| Languages & UI | Swift · SwiftUI · AppKit · JavaScript · TypeScript · HTML/CSS · Python | [BarPilot](https://github.com/yoko1234p/BarPilot/blob/main/BarPilot/Sources/BarPilot/BarPilotApp.swift) · [TGLocal](https://github.com/yoko1234p/TGLocal/blob/main/src/popup.html) · [TypeScript](https://github.com/yoko1234p/impatrickho/blob/main/App.tsx) · [Python code](https://github.com/yoko1234p/BarPilot/blob/main/scripts/localization/check-catalogs.py) |
| macOS APIs | Vision · ScreenCaptureKit · Accessibility · EventKit · UserNotifications | [CaptureText](https://github.com/yoko1234p/CaptureText/blob/main/DeskTools/Sources/CaptureCore/Recognition.swift) · [BarPilot](https://github.com/yoko1234p/BarPilot/blob/main/BarPilot/Sources/BarPilot/MenuBarInventory.swift) · [NotchHub](https://github.com/yoko1234p/NotchHub/blob/main/NotchHub/Sources/NotchHub/Features/CalendarWidget/CalendarManager.swift) |
| Browser platform | Chrome Extension Manifest V3 · content scripts · Web APIs | [Extension manifest](https://github.com/yoko1234p/TGLocal/blob/main/manifest.json) · [Media controls](https://github.com/yoko1234p/TGLocal/blob/main/src/inline.js) |
| Web interface | React · Vite · React Three Fiber · Framer Motion · Tailwind CSS | [Portfolio app](https://github.com/yoko1234p/impatrickho/blob/main/App.tsx) · [3D scene](https://github.com/yoko1234p/impatrickho/blob/main/components/Scene3D.tsx) · [Dependencies](https://github.com/yoko1234p/impatrickho/blob/main/package.json) |
| Build & verification | Swift Package Manager · XcodeGen · Node.js/npm · Playwright | [SwiftPM](https://github.com/yoko1234p/BarPilot/blob/main/BarPilot/Package.swift) · [XcodeGen](https://github.com/yoko1234p/NotchHub/blob/main/NotchHub/project.yml) · [Browser tests](https://github.com/yoko1234p/TGLocal/blob/main/tests/extension.spec.mjs) |

### Selected engineering work

- **CaptureText:** on-device OCR and table recognition, with screen capture and export workflows. [Recognition source](https://github.com/yoko1234p/CaptureText/blob/main/DeskTools/Sources/CaptureCore/Recognition.swift) · [Table source](https://github.com/yoko1234p/CaptureText/blob/main/DeskTools/Sources/CaptureCore/TableRecognition.swift)
- **BarPilot:** menu-bar inventory, positioning and display-specific layouts. [Inventory source](https://github.com/yoko1234p/BarPilot/blob/main/BarPilot/Sources/BarPilot/MenuBarInventory.swift) · [Positioning source](https://github.com/yoko1234p/BarPilot/blob/main/BarPilot/Sources/BarPilot/MenuBarPositionService.swift)
- **TG Local:** Telegram Web media controls and guarded resumable downloads, checked with browser tests. [Download source](https://github.com/yoko1234p/TGLocal/blob/main/src/downloads.js) · [Browser tests](https://github.com/yoko1234p/TGLocal/blob/main/tests/extension.spec.mjs)
- **Web portfolio:** interactive React/TypeScript interface with a 3D scene and motion design. [App source](https://github.com/yoko1234p/impatrickho/blob/main/App.tsx) · [Scene source](https://github.com/yoko1234p/impatrickho/blob/main/components/Scene3D.tsx)

## Explore the apps

| Series | Project | What it does |
|:--|:--|:--|
| **System utilities** | | |
| | [BarPilot](https://github.com/yoko1234p/BarPilot) | Arrange menu-bar icons and display layouts. · [↓ Preview](https://github.com/yoko1234p/BarPilot/releases/tag/v0.5.1-preview.1) |
| | [QuickSwitch](https://github.com/yoko1234p/QuickSwitch) | System switches, keep-awake timers and profiles. · [↓ Preview](https://github.com/yoko1234p/QuickSwitch/releases/tag/v0.4.0-preview.1) |
| | [SuperPilot](https://github.com/yoko1234p/SuperPilot) | Finder actions, batch rename and shortcuts. · [↓ Preview](https://github.com/yoko1234p/SuperPilot/releases/tag/v0.4.4-preview.1) |
| **Text and notes** | | |
| | [CaptureText](https://github.com/yoko1234p/CaptureText) | Screen OCR, speech and table export. · [↓ Preview](https://github.com/yoko1234p/CaptureText/releases/tag/v0.9.0-preview.1) |
| | [EdgeNotes](https://github.com/yoko1234p/EdgeNotes) | Screen-edge notes, inline images and calculations. · [↓ Preview](https://github.com/yoko1234p/EdgeNotes/releases/tag/v0.8.0-preview.1) |
| | [SelectionBar](https://github.com/yoko1234p/SelectionBar) | Actions and extensions for selected text. · [↓ Preview](https://github.com/yoko1234p/SelectionBar/releases/tag/v0.5.2-preview.1) |
| **Developer tools** | | |
| | [DevWorkbench](https://github.com/yoko1234p/DevWorkbench) | Offline formatting, conversion and redaction. · [↓ Preview](https://github.com/yoko1234p/DevWorkbench/releases/tag/v0.6.0-preview.1) |
| **Focus and learning** | | |
| | [NotchHub](https://github.com/yoko1234p/NotchHub) | Notch workspace, focus, calendar and vocabulary. · [↓ Preview](https://github.com/yoko1234p/NotchHub/releases/tag/v0.3.0-preview.1) |
| **Web and media** | | |
| | [TGLocal](https://github.com/yoko1234p/TGLocal) | Telegram Web media controls and readable downloads. · [↓ Preview](https://github.com/yoko1234p/TGLocal/releases/tag/v0.5.0-preview.1) |

## Start here

Each project has its own source, build steps and preview download. The macOS previews are ad-hoc signed and not notarized; follow the installation notes in each repository. TG Local is a Chrome extension loaded through Developer mode.

## Contributing

Open an issue in the relevant project with your macOS or Chrome version, steps to reproduce and what you observed. Original maintained app code is GPL-3.0-only; third-party material keeps its own notices.
