# 📱 Mobile Development Setup with Expo Go

##  Overview
Mobile development demands more computational power than web development due to device emulation and native builds.  
To simplify this, we’ll use the **Expo Framework for React Native**, which lets you create, test, and run mobile apps seamlessly on physical devices — no Android Studio or Xcode required.

This setup ensures a smooth, efficient, and cost-effective mobile development workflow.

---

## Prerequisites

Before starting, ensure the following tools are installed:

| Tool | Description | Installation Link |
|------|--------------|-------------------|
| **Node.js LTS** | JavaScript runtime required for Expo CLI | [https://nodejs.org](https://nodejs.org) |
| **VS Code** | Recommended IDE for React Native | [https://code.visualstudio.com](https://code.visualstudio.com) |
| **Operating System** | macOS, Linux, or Windows | — |
| **Physical Device** | Android or iOS smartphone | — |
| **Expo Go App** | Used to preview your app | [https://expo.dev/go](https://expo.dev/go) |

---

##  Why Use Expo Go?

Expo Go removes the need for heavy emulators by running your React Native projects **directly on your device**.  
It offers:
-  **Fast refresh** — instant updates after saving code changes  
-  **QR-based previewing** — scan and launch apps instantly  
-  **Cross-platform support** — works on Android and iOS  
-  **No native dependencies** — no need to install Xcode or Android SDKs  

---

##  Installation Steps

### 1️ Verify Node.js and npm
Check if Node.js and npm are installed:

```bash
node -v
npm -v
```