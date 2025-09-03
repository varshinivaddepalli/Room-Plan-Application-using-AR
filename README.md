# 🏠 Room-Plan-Application-using-AR

[![Swift](https://img.shields.io/badge/Swift-5.7-orange.svg?style=flat\&logo=swift)](https://swift.org)
[![iOS](https://img.shields.io/badge/iOS-16%2B-black.svg?style=flat\&logo=apple)](https://developer.apple.com/ios/)
[![Xcode](https://img.shields.io/badge/Xcode-14%2B-blue.svg?style=flat\&logo=xcode)](https://developer.apple.com/xcode/)

RoomPlan App is a Swift-based iOS application showcasing **Apple's RoomPlan API**, built on **ARKit** and **LiDAR**. It enables real-time scanning of indoor environments, generating precise **3D floor plans** with furniture detection. Export scans in **USD/USDZ** formats and refine them in professional tools like **Cinema 4D, Shapr3D, and AutoCAD**.

---
## 📸 Demo

<div align="center">
  <img src="output.gif" alt="App Demo" width="300"/>
</div>

---
## ✨ Features

* 📏 **Accurate 3D Floor Plans** – Detects walls, doors, windows, and room layout.
* 🛋️ **Furniture Recognition** – Identifies and places furniture in scans.
* ⚡ **Real-time Scanning** – Instant visualization during the scan.
* 🎨 **Customizable Interface** – Easily adaptable to your app’s design.
* 📂 **Export Support** – Export scans as **USD / USDZ** files.
* 🏢 **Industry Applications** – Ideal for **real estate, interior design, architecture, CAD, and e-commerce**.

---

## 📂 Project Structure

```
RoomPlanExampleApp/
│
├── RoomPlanExampleApp.xcodeproj/       # Xcode project configuration
│   └── xcshareddata/
│       └── xcschemes/
│           └── RoomPlanExampleApp.xcscheme   # Build/Run scheme
│
├── Info.plist                          # App configuration & permissions
├── Sources/                            # Swift source files
└── Assets/                             # App icons, images, resources
```

---

## 🛠️ Requirements

* **iOS 16.0+**
* **Xcode 14.0+**
* **Swift 5.7+**
* Device with **LiDAR Scanner**:

  * iPhone 12 Pro, 13 Pro, 14 Pro
  * iPad Pro (2020 and newer)

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/RoomPlanExampleApp.git
cd RoomPlanExampleApp
```

### 2. Open in Xcode

```bash
open RoomPlanExampleApp.xcodeproj
```

### 3. Select a LiDAR-enabled device

* Connect an iPhone Pro or iPad Pro.
* Choose it as the **run destination** in Xcode.

### 4. Build & Run

Press `Cmd + R` in Xcode.

---

## 📤 Exporting Floor Plans

Exported files can be used in:

* **Cinema 4D**
* **Shapr3D**
* **AutoCAD**
* Any tool supporting **USD/USDZ** formats

---

## 🏗️ Roadmap

* ☁️ Cloud sync for floor plans
* 🤖 AI-driven room classification & labeling
* 🏠 Multi-room scanning & stitching
* 📐 Advanced editing tools inside the app
  
---

## 🙌 Acknowledgements

* [Apple RoomPlan API](https://developer.apple.com/augmented-reality/roomplan/)
* [ARKit](https://developer.apple.com/augmented-reality/)
* [USD/USDZ File Format](https://developer.apple.com/augmented-reality/tools/)

---
