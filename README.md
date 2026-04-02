# Meta Business Suite SSL Pinning Bypass for Android (2026) – Intercept & Capture HTTPS Traffic

[![Telegram](https://img.shields.io/badge/💬_Chat_on_Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&labelColor=121212&color=26A5E4&logoWidth=20)](https://t.me/MUH4MM4DSH4KIB)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![ARM64](https://img.shields.io/badge/ARM64--v8a-Patched_APK-blue?style=for-the-badge)
![x86_64](https://img.shields.io/badge/x86__64-Patched_Library-blue?style=for-the-badge)

> Bypass Meta Business Suite SSL certificate pinning on Android to intercept, inspect, and analyze HTTPS network traffic — works on both **rooted** and **non-rooted** devices.

---

## 📖 Overview

This project provides two bypass methods for Meta Business Suite's SSL/TLS certificate pinning on Android, enabling security researchers and developers to capture and analyze Meta Business Suite HTTPS traffic using standard MITM proxy tools. Inspect API endpoints, Facebook Page management calls, Instagram business account integrations, ad performance data, audience insights, and authentication flows.

---

## 🎥 Proof of Concept

<img width="720" height="1640" alt="Image" src="https://github.com/user-attachments/assets/85bc231c-23c1-4c41-b122-90ce8f506ac0" />

▶️ [**Watch the Full Video Demonstration**](https://github.com/user-attachments/assets/882a24bb-1867-4a6d-862a-c32545d19974)

---

## 📋 Supported Meta Business Suite Version

| App | Package | Version | Patched Library | Status |
|-----|---------|---------|-----------------|--------|
| Meta Business Suite | `com.facebook.pages.app` | **546.0.0.56.106** | `libstartup.so` | ✅ Bypassed |

> For the **latest bypassed APK or patched library**, [contact me on Telegram](https://t.me/MUH4MM4DSH4KIB).

---

## ⚙️ Supported Architectures & Methods

| Architecture | Method | Best For |
|---|---|---|
| `arm64-v8a` | ✅ Patched APK | Physical devices & ARM64 emulators |
| `x86_64` | ✅ Patched `libstartup.so` | x86_64 emulators (Nox, LDPlayer, BlueStacks) |

---

## 📱 Requirements

### Option A: Physical Android Device (ARM64)

- Android phone or tablet (**rooted or non-rooted**)
- A traffic interception proxy tool:
  - [Proxypin](https://proxypin.com) — free, lightweight
  - [Reqable](https://reqable.com) — feature-rich, modern UI

### Option B: Android Emulator (x86_64)

- Windows PC with one of the following emulators installed:
  - [Nox Player](https://www.bignox.com/) — root access enabled
  - [LDPlayer](https://www.ldplayer.net/) — root access enabled
  - [BlueStacks](https://www.bluestacks.com/) — root access enabled
- A desktop MITM proxy tool:
  - [Burp Suite](https://portswigger.net/burp) — industry standard
  - [Mitmproxy](https://mitmproxy.org/) — open source
  - [Reqable](https://reqable.com)
  - [Proxypin](https://proxypin.com)

> **Note:** Root access must be enabled in the emulator for the x86_64 library replacement method.

---

## 🚀 Bypass Procedure

### Method 1 — Patched APK (ARM64-v8a)

Best for **physical Android devices** and ARM64 emulators. No root required.

1. **Uninstall** the official Meta Business Suite app from your device (if installed).
2. **Download** the SSL pinning bypassed Meta Business Suite APK from this repository.
3. **Install** the patched APK on your Android device or emulator.
4. **Configure** your proxy tool of choice (Proxypin, Reqable, Burp Suite, or Mitmproxy) to intercept traffic.
5. **Launch Meta Business Suite** and start capturing HTTPS requests and responses.

> **Tip:** Install and trust the proxy's CA certificate on your device for full HTTPS decryption.

---

### Method 2 — Library Replacement (x86_64)

Best for **x86_64 emulators** (Nox, LDPlayer, BlueStacks). Requires root access in the emulator.

#### Step 1 — Push the Patched Library

Replace the original `libstartup.so` with the patched version using ADB:

```bash
adb push D:\patched\libstartup.so /data/data/com.facebook.pages.app/lib-compressed/libstartup.so
```

#### Step 2 — Set Correct Permissions (if needed)

```bash
adb shell chmod 755 /data/data/com.facebook.pages.app/lib-compressed/libstartup.so
```

#### Step 3 — Configure Your Proxy

Set up your preferred MITM proxy tool (Proxypin, Reqable, Burp Suite, or Mitmproxy) and install/trust its CA certificate on the emulator.

#### Step 4 — Launch & Capture

Open the Meta Business Suite app and start intercepting HTTPS requests and responses in your proxy tool.

> **Tip:** Force-stop Meta Business Suite before launching it after the library replacement to ensure the patched library is loaded.

---



## 📬 Contact & Latest Builds

For the **most up-to-date** SSL pinning bypassed Meta Business Suite APK or patched `libstartup.so`, reach out directly:

[![Telegram](https://img.shields.io/badge/💬_Chat_on_Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&labelColor=121212&color=26A5E4&logoWidth=20)](https://t.me/MUH4MM4DSH4KIB)

---


## 🏷️ Tags

`meta business suite ssl pinning bypass` · `meta business suite certificate pinning` · `meta business suite mitm` · `meta business suite traffic interception` · `meta business suite burp suite` · `facebook pages app proxy android` · `meta business suite https decrypt` · `meta business suite security` · `android ssl bypass no root` · `libstartup.so patch` · `meta business suite api reverse engineering` · `meta business suite ssl bypass 2026` · `com.facebook.pages.app` · `meta business suite apk patched` · `facebook page management api` · `meta business suite graphql api` · `meta ad insights api`
