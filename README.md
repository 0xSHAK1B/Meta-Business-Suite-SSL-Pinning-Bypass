# 🔐 SSL Pinning Bypass Meta Business Suite

Meta Business Suite SSL Pinning Bypass and intercept Meta Business Suite Traffic.



---

## 🎥 Evidence 

<img width="720" height="1640" alt="Image" src="https://github.com/user-attachments/assets/312e89bd-3dff-4a9b-9238-e6c37b2eaf7c" />

▶️ [Watch the Demonstration](https://github.com/user-attachments/assets/e1cca0af-0594-4dbc-a069-1ccd8e3b38cc)

---

## ⚙️ Supported Architectures
- **arm64-v8a**
- **x86_64**
---
## Meta Business Suite App Version 
- **536.1.0.41.435**
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
