# 🤸 Pose AI — Local Setup Guide

This guide explains how to run **Pose AI** locally on your computer using **Visual Studio Code** and the **Live Server** extension.

---

## 📋 Prerequisites

- [Visual Studio Code](https://code.visualstudio.com/) installed on your computer
- Project files downloaded locally

---

## 🚀 Step 1 — Install the Live Server Extension

1. Open **VS Code**
2. Click the **Extensions** icon in the left sidebar (or press `Ctrl+Shift+X`)
3. In the search bar, type:
   ```
   Live Server
   ```
4. Find the **"Live Server"** extension by **Ritwick Dey**
5. Click **Install**

> ✅ The extension only needs to be installed once and will be ready to use going forward.

---

## 📂 Step 2 — Open the Project in VS Code

1. Open **VS Code**
2. Go to **File → Open Folder…**
3. Navigate to the folder containing the Pose AI files and click **Select Folder**

The project structure you will see:

```
📁 pose-ai/
├── home.html       ← Landing page
├── index.html      ← Mode selection menu
├── live.html       ← Live Tracking
├── score.html      ← 15s Posture Test
├── about.html      ← About page
└── style.css       ← Styling
```

---

## ▶️ Step 3 — Start the Live Server

**Option A — From the file:**
1. Open the `home.html` file in the editor
2. **Right-click** anywhere in the code
3. Select **"Open with Live Server"**

**Option B — From the status bar:**
1. At the bottom of VS Code, click the **"Go Live"** button
2. Your browser will open automatically

> 🌐 The browser will automatically open at: **`http://127.0.0.1:5500/home.html`**

---

## 📸 Step 4 — Using the App

| Page | URL | Description |
|---|---|---|
| Home | `http://127.0.0.1:5500/index.html` | Landing page |
| Menu | `http://127.0.0.1:5500/menu.html` | Mode selection |
| Live Tracking | `http://127.0.0.1:5500/live.html` | Continuous posture monitoring |
| 15s Test | `http://127.0.0.1:5500/score.html` | 15-second posture evaluation |
| About | `http://127.0.0.1:5500/about.html` | Project information |

> ⚠️ **Important:** The app uses your computer's **camera**. The browser will request permission — click **"Allow"** to enable Live Tracking and the 15s Test.

---

## 🛑 Stopping the Live Server

To stop the server:
- Click **"Port: 5500"** in the VS Code status bar, or
- Press `Ctrl+Shift+P` and type `Live Server: Stop Server`

---

## ❓ Common Issues

**The browser doesn't open automatically:**
> Open your browser manually and navigate to `http://127.0.0.1:5500/home.html`

**I don't see the "Go Live" button:**
> Make sure the Live Server extension is installed and that you have an HTML file open in the editor.

**The camera doesn't work:**
> Live Server uses `http://` locally. Make sure you have granted camera permissions to your browser for the address `127.0.0.1`.

---

*Pose AI — Real-time Posture Detection*  
*Dissertation Project — University of East London (UEL), May 2026*  
*Author: Nikolaos Kapsalas | Supervisor: Antonis Archontis*
