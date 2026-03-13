# Meta Business Suite SSL Pinning Bypass (2026) – Intercept & Capture HTTPS Traffic

[![Telegram](https://img.shields.io/badge/💬_Chat_on_Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&labelColor=121212&color=26A5E4&logoWidth=20)](https://t.me/MUH4MM4DSH4KIB)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![ARM64](https://img.shields.io/badge/ARM64--v8a-Supported-blue?style=for-the-badge)
![x86_64](https://img.shields.io/badge/x86__64-Supported-blue?style=for-the-badge)

> Bypass Meta Business Suite SSL certificate pinning on Android by patching `libstartup.so` — intercept, inspect, and analyze HTTPS network traffic on both **rooted** and **non-rooted** devices.

---

## 📖 Overview

This project provides a **patched `libstartup.so`** library for the Meta Business Suite Android app with SSL/TLS certificate pinning disabled, enabling security researchers and developers to capture and analyze Meta Business Suite HTTPS traffic using standard MITM proxy tools.

---

## 🎥 Proof of Concept

<img width="720" height="1640" alt="Image" src="https://github.com/user-attachments/assets/6502a832-46d3-426b-87c5-ead655e029e0" />




▶️ [**Watch the Full Video Demonstration**](https://github.com/user-attachments/assets/96f59599-036e-4fc8-abf5-4210fee78c9b)

---

## 📋 Supported Meta Business Suite Version

| App | Version | Patched Library | Status |
|-----|---------|-----------------|--------|
| Meta Business Suite | **543.0.0.46.107** | `libstartup.so` | ✅ Bypassed |

> For the **latest patched `libstartup.so`**, [contact me on Telegram](https://t.me/MUH4MM4DSH4KIB).

---

## ⚙️ Supported Architectures

| Architecture | Support |
|---|---|
| `arm64-v8a` | ✅ |
| `x86_64` | ✅ |

---

## 📱 Requirements

### Option A: Physical Android Device

- Android phone or tablet (**rooted or non-rooted**)
- A traffic interception proxy tool:
  - [Proxypin](https://proxypin.com) — free, lightweight
  - [Reqable](https://reqable.com) — feature-rich, modern UI

### Option B: Android Emulator (PC)

- Windows PC with one of the following emulators installed:
  - [Nox Player](https://www.bignox.com/) — root access enabled
  - [LDPlayer](https://www.ldplayer.net/) — root access enabled
- A desktop MITM proxy tool:
  - [Burp Suite](https://portswigger.net/burp) — industry standard
  - [Mitmproxy](https://mitmproxy.org/) — open source
  - [Reqable](https://reqable.com)
  - [Proxypin](https://proxypin.com)

> **Note:** Root access must be enabled in the emulator to replace the native library.

---

## 🚀 Bypass Procedure

### Step 1 — Push the Patched Library

Replace the original `libstartup.so` with the patched version using ADB:

```bash
adb push D:\patched\libstartup.so /data/data/com.facebook.pages.app/lib-compressed/libstartup.so
```

### Step 2 — Set Correct Permissions (if needed)

```bash
adb shell chmod 755 /data/data/com.facebook.pages.app/lib-compressed/libstartup.so
```

### Step 3 — Configure Your Proxy

Set up your preferred MITM proxy tool (Proxypin, Reqable, Burp Suite, or Mitmproxy) and install/trust its CA certificate on the device or emulator.

### Step 4 — Launch & Capture

Open the Meta Business Suite app and start intercepting HTTPS requests and responses in your proxy tool.

> **Tip:** Force-stop Meta Business Suite before launching it after the library replacement to ensure the patched library is loaded.

---

**Package name:** `com.facebook.pages.app`

**Target path:**
```
/data/data/com.facebook.pages.app/lib-compressed/libstartup.so
```

---


**Q: The patched version doesn't match the latest Meta Business Suite release — what do I do?**
A: [Contact me on Telegram](https://t.me/MUH4MM4DSH4KIB) for the latest patched `libstartup.so`.

---

## 📬 Contact & Latest Builds

For the **most up-to-date** patched `libstartup.so` for Meta Business Suite, reach out directly:

[![Telegram](https://img.shields.io/badge/💬_Chat_on_Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&labelColor=121212&color=26A5E4&logoWidth=20)](https://t.me/MUH4MM4DSH4KIB)

---

## 🏷️ Tags

`meta business suite ssl pinning bypass` · `meta business suite certificate pinning` · `meta business suite mitm` · `meta business suite traffic interception` · `meta business suite burp suite` · `facebook pages app proxy android` · `meta business suite https decrypt` · `meta business suite security` · `android ssl bypass no root` · `libstartup.so patch` · `meta business suite api reverse engineering` · `meta business suite ssl bypass 2025` · `com.facebook.pages.app`

---
