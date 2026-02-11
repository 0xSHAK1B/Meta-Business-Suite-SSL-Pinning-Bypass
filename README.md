# 🔐 SSL Pinning Bypass Meta Business Suite

Meta Business Suite SSL Pinning Bypass for Android – intercept Meta Business Suite traffic.



---

## 🎥 Evidence 

<img width="720" height="1640" alt="Image" src="https://github.com/user-attachments/assets/583f8714-7a4d-4eb1-946f-1d5c33ae91ee" />

▶️ [Watch the Demonstration](https://github.com/user-attachments/assets/d285e3d9-a9bf-46f4-9c55-d1daa746c2be)

---

## ⚙️ Supported Architectures
- **arm64-v8a**
- **x86_64**
---
## Meta Business Suite App Version 
- **539.0.0.47.107**
---

## 📱 Mobile Device Requirements
- Android device (**Rooted** or **Non-Rooted**)
- One of the following traffic interception tools:
  - [Proxypin](https://proxypin.com)
  - [Reqable](https://reqable.com)

---

## 💻 Emulator Setup
- Windows PC with:
  - **Reqable**, **Burp Suite**, or **Mitmproxy** installed
  - **Nox** or **LDPlayer** Android emulator
  - **Root access** enabled in the emulator

---

## 🚀 Bypass Procedure

1. Replace patched `libstartup.so with /data/data/com.facebook.pages.app/lib-compressed/libstartup.so`
2. Replace the patched library file:
   ```bash
   adb push D:\patched\libstartup.so /data/data/com.facebook.pages.app/lib-compressed/libstartup.so

3. Use Proxypin / Reqable / Burp Suite / Mitmproxy for capturing traffics.

## For latest patched libstartup.so contract with me.
<a href="https://t.me/MUH4MM4DSH4KIB" target="_blank">
  <img src="https://img.shields.io/badge/💬_Chat_on_Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&labelColor=121212&color=26A5E4&logoWidth=20" alt="Telegram" style="border-radius: 8px;"/>
</a>
