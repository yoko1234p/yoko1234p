<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img src="assets/header-light.svg" alt="Pak Wing HO — independent macOS and browser tools" width="100%">
</picture>

[English](README.md) · [**繁體中文**](README.zh-Hant.md) · [简体中文](README.zh-Hans.md)

我開發獨立的 macOS 與瀏覽器工具，讓日常工作更易找到、完成和整理。

## 精選工具

<p align="center">
<a href="https://github.com/yoko1234p/BarPilot"><img src="assets/card-BarPilot.svg" alt="BarPilot" width="31%"></a>
<a href="https://github.com/yoko1234p/EdgeNotes"><img src="assets/card-EdgeNotes.svg" alt="EdgeNotes" width="31%"></a>
<a href="https://github.com/yoko1234p/NotchHub"><img src="assets/card-NotchHub.svg" alt="NotchHub" width="31%"></a>
</p>

## 技術履歷

我使用 macOS 原生框架、瀏覽器擴充、網頁介面和測試工具。下表每項技術都連到可查閱的公開程式碼。

| 範疇 | 實際使用 | 原始碼證據 |
|:--|:--|:--|
| 語言與介面 | Swift · SwiftUI · AppKit · JavaScript · TypeScript · HTML/CSS · Python | [BarPilot](https://github.com/yoko1234p/BarPilot/blob/main/BarPilot/Sources/BarPilot/BarPilotApp.swift) · [TGLocal](https://github.com/yoko1234p/TGLocal/blob/main/src/popup.html) · [TypeScript](https://github.com/yoko1234p/impatrickho/blob/main/App.tsx) · [Python 程式碼](https://github.com/yoko1234p/BarPilot/blob/main/scripts/localization/check-catalogs.py) |
| macOS 系統介面 | Vision · ScreenCaptureKit · Accessibility · EventKit · UserNotifications | [CaptureText](https://github.com/yoko1234p/CaptureText/blob/main/DeskTools/Sources/CaptureCore/Recognition.swift) · [BarPilot](https://github.com/yoko1234p/BarPilot/blob/main/BarPilot/Sources/BarPilot/MenuBarInventory.swift) · [NotchHub](https://github.com/yoko1234p/NotchHub/blob/main/NotchHub/Sources/NotchHub/Features/CalendarWidget/CalendarManager.swift) |
| 瀏覽器平台 | Chrome Extension Manifest V3 · content scripts · Web APIs | [擴充設定](https://github.com/yoko1234p/TGLocal/blob/main/manifest.json) · [媒體控制](https://github.com/yoko1234p/TGLocal/blob/main/src/inline.js) |
| 網頁介面 | React · Vite · React Three Fiber · Framer Motion · Tailwind CSS | [作品集 App](https://github.com/yoko1234p/impatrickho/blob/main/App.tsx) · [3D 場景](https://github.com/yoko1234p/impatrickho/blob/main/components/Scene3D.tsx) · [依賴套件](https://github.com/yoko1234p/impatrickho/blob/main/package.json) |
| 建置與驗證 | Swift Package Manager · XcodeGen · Node.js/npm · Playwright | [SwiftPM](https://github.com/yoko1234p/BarPilot/blob/main/BarPilot/Package.swift) · [XcodeGen](https://github.com/yoko1234p/NotchHub/blob/main/NotchHub/project.yml) · [瀏覽器測試](https://github.com/yoko1234p/TGLocal/blob/main/tests/extension.spec.mjs) |

### 代表性實作

- **CaptureText：**本機 OCR 與表格辨識，串接畫面擷取及匯出流程。[OCR 原始碼](https://github.com/yoko1234p/CaptureText/blob/main/DeskTools/Sources/CaptureCore/Recognition.swift) · [表格原始碼](https://github.com/yoko1234p/CaptureText/blob/main/DeskTools/Sources/CaptureCore/TableRecognition.swift)
- **BarPilot：**選單列圖示盤點、定位及按螢幕配置布局。[盤點原始碼](https://github.com/yoko1234p/BarPilot/blob/main/BarPilot/Sources/BarPilot/MenuBarInventory.swift) · [定位原始碼](https://github.com/yoko1234p/BarPilot/blob/main/BarPilot/Sources/BarPilot/MenuBarPositionService.swift)
- **TG Local：**Telegram Web 媒體控制與有條件的中斷續傳，並以瀏覽器測試驗證。[下載原始碼](https://github.com/yoko1234p/TGLocal/blob/main/src/downloads.js) · [瀏覽器測試](https://github.com/yoko1234p/TGLocal/blob/main/tests/extension.spec.mjs)
- **網頁作品集：**React／TypeScript 互動介面，包含 3D 場景和動畫設計。[App 原始碼](https://github.com/yoko1234p/impatrickho/blob/main/App.tsx) · [場景原始碼](https://github.com/yoko1234p/impatrickho/blob/main/components/Scene3D.tsx)

## 探索 App

| 系列 | 項目 | 用途 |
|:--|:--|:--|
| **系統效率** | | |
| | [BarPilot](https://github.com/yoko1234p/BarPilot) | 整理選單列圖示與多螢幕布局。 · [↓ 預覽版](https://github.com/yoko1234p/BarPilot/releases/tag/v0.5.1-preview.1) |
| | [QuickSwitch](https://github.com/yoko1234p/QuickSwitch) | 系統開關、保持喚醒計時與配方。 · [↓ 預覽版](https://github.com/yoko1234p/QuickSwitch/releases/tag/v0.4.0-preview.1) |
| | [SuperPilot](https://github.com/yoko1234p/SuperPilot) | Finder 操作、批量改名與快捷鍵。 · [↓ 預覽版](https://github.com/yoko1234p/SuperPilot/releases/tag/v0.4.4-preview.1) |
| **文字與筆記** | | |
| | [CaptureText](https://github.com/yoko1234p/CaptureText) | 畫面 OCR、朗讀與表格匯出。 · [↓ 預覽版](https://github.com/yoko1234p/CaptureText/releases/tag/v0.9.0-preview.1) |
| | [EdgeNotes](https://github.com/yoko1234p/EdgeNotes) | 側邊筆記、行內圖片與文字計算。 · [↓ 預覽版](https://github.com/yoko1234p/EdgeNotes/releases/tag/v0.8.0-preview.1) |
| | [SelectionBar](https://github.com/yoko1234p/SelectionBar) | 選字操作與擴充。 · [↓ 預覽版](https://github.com/yoko1234p/SelectionBar/releases/tag/v0.5.2-preview.1) |
| **開發工具** | | |
| | [DevWorkbench](https://github.com/yoko1234p/DevWorkbench) | 離線格式整理、轉換與資料遮蔽。 · [↓ 預覽版](https://github.com/yoko1234p/DevWorkbench/releases/tag/v0.6.0-preview.1) |
| **專注與學習** | | |
| | [NotchHub](https://github.com/yoko1234p/NotchHub) | 劉海工作台、專注計時、日曆與生詞。 · [↓ 預覽版](https://github.com/yoko1234p/NotchHub/releases/tag/v0.3.0-preview.1) |
| **網頁與媒體** | | |
| | [TGLocal](https://github.com/yoko1234p/TGLocal) | Telegram Web 媒體操作及可辨認下載。 · [↓ 預覽版](https://github.com/yoko1234p/TGLocal/releases/tag/v0.5.0-preview.1) |

## 從這裏開始

每個項目均有獨立原始碼、建置步驟和預覽版下載。macOS 預覽版使用臨時簽署，未經 Apple 公證；請依照各 repo 的安裝說明操作。TG Local 是透過開發人員模式載入的 Chrome 擴充。

## 參與開發

請到相關項目開 Issue，註明 macOS 或 Chrome 版本、重現步驟及實際情況。原創 App 程式碼採 GPL-3.0-only；第三方素材保留各自授權聲明。
