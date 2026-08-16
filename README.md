<div align="center">

# 🔓 Meta Business Suite Android SSL Pinning Bypass

**Intercept, capture & analyze Meta Business Suite HTTPS traffic on Android — no root required**

[![Download APK](https://img.shields.io/badge/⬇_Download_APK_(v566.0.0)-0668E1?style=for-the-badge&logo=meta&logoColor=white)](../../releases/latest) &nbsp; [![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/MUH4MM4DSH4KIB)

![Android](https://img.shields.io/badge/Android_10--14+-3DDC84?style=flat-square&logo=android&logoColor=white)
![ARM64](https://img.shields.io/badge/arm64--v8a-blue?style=flat-square)
![Version](https://img.shields.io/badge/Meta_Business_Suite-v566.0.0.45.105-0668E1?style=flat-square&logo=meta&logoColor=white)
![Root](https://img.shields.io/badge/Root-Not_Required-brightgreen?style=flat-square)

<img width="578" height="1280" alt="Meta Business Suite Android SSL Pinning Bypass PoC – Traffic Captured" src="https://github.com/user-attachments/assets/af3d223c-2097-4275-a53d-d7496ab1b897" />

*Live capture — Meta Business Suite Android HTTPS traffic intercepted in cleartext, v566.0.0.45.105.*

</div>

> **Bypass SSL/TLS certificate pinning** in Meta Business Suite for Android and pipe the full HTTPS stream — login, Ads Manager, and unified inbox flows — into **Burp Suite · mitmproxy · Reqable · Proxypin.** Tap a section below to expand.

---

<details open>
<summary><b>📦 Supported version</b></summary>

<br>

| App | Package | Version | ABI | Status |
|-----|---------|:-------:|:---:|:------:|
| Meta Business Suite for Android | `com.facebook.pages.app` | **566.0.0.45.105** | `arm64-v8a` | ✅ [**Download**](../../releases/latest) |

The patched APK lives in the [**Releases**](../../releases/latest) section. Need the newest build or another version? [Message me on Telegram](https://t.me/MUH4MM4DSH4KIB).

</details>

<details>
<summary><b>🎯 What you can capture</b></summary>

<br>

- **Login & authentication** — Meta business account auth and access tokens
- **Pages & business management** — page data, roles, and business-asset endpoints
- **Ads Manager** — campaign, ad-set, and creative payloads; ad-account data
- **Insights & analytics** — reach, engagement, and performance metrics
- **Unified inbox** — Messenger + Instagram Direct + comment sync
- **Content scheduling** — scheduled posts and publishing endpoints
- **GraphQL** — `graph.facebook.com` business queries and telemetry

</details>

<details>
<summary><b>⚙️ Requirements</b></summary>

<br>

**Android device — Android 10, 11, 12, 13, 14+.** No root required (rooted devices supported too); ARM device (`arm64-v8a`), which covers virtually all modern phones and tablets.

**Emulator (PC):** Nox / LDPlayer / MEmu / BlueStacks — enable **ARM translation**, since this build ships `arm64` native libraries and x86/x86_64 emulators need the translation layer.

**Proxy tool** — [Burp Suite](https://portswigger.net/burp) · [mitmproxy](https://mitmproxy.org/) · [Reqable](https://reqable.com) · [Proxypin](https://proxypin.com)

</details>

<details>
<summary><b>🚀 How to bypass — step by step</b></summary>

<br>

1. Uninstall the official Meta Business Suite app (signatures conflict).
2. Download the patched APK from [**Releases**](../../releases/latest) and install it on your device or emulator.
3. Install and trust your proxy's CA certificate: **Settings → Security → Encryption & credentials → Install a certificate → CA certificate**.
4. Set the Wi-Fi proxy: **Settings → Wi-Fi → (network) → Proxy → Manual** → your PC's IP and port.
5. Launch Meta Business Suite — decrypted HTTPS streams into your proxy in real time.

> Force-stop and relaunch the app if traffic doesn't appear immediately.

</details>

<details>
<summary><b>💼 Need a custom bypass?</b></summary>

<br>

Custom SSL pinning bypass · automated patching scripts · full reverse-engineering projects — for any Android or iOS app. [**Message me on Telegram →**](https://t.me/MUH4MM4DSH4KIB)

</details>

<details>
<summary><b>⚠️ Disclaimer</b></summary>

<br>

For **educational and security-research purposes only**. Not affiliated with, endorsed by, or connected to Meta or its subsidiaries. All trademarks belong to their respective owners. You are responsible for complying with your local laws and the app's Terms of Service, and should only analyze traffic on accounts and devices you own or are authorized to test. Provided "as is", without warranty of any kind.

</details>

<details>
<summary><b>🔗 Related projects</b></summary>

<br>

| App | Platform | Repository |
|-----|----------|------------|
| Facebook | Android | [Facebook SSL Pinning Bypass](https://github.com/0xSHAK1B/Facebook-SSL-Pinning-Bypass) |
| Instagram | Android | [Instagram SSL Pinning Bypass](https://github.com/0xSHAK1B/Instagram-SSL-Pinning-Bypass) |
| Threads | Android | [Threads SSL Pinning Bypass](https://github.com/0xSHAK1B/Threads-SSL-Pinning-Bypass) |
| Messenger | Android | [Messenger SSL Pinning Bypass](https://github.com/0xSHAK1B/Messenger-SSL-Pinning-Bypass) |
| Facebook | iOS | [Facebook iOS SSL Pinning Bypass](https://github.com/0xSHAK1B/Facebook-iOS-SSL-Pinning-Bypass) |
| TikTok | Android | [TikTok SSL Pinning Bypass](https://github.com/0xSHAK1B/TIKTOK-SSL-Pinning-Bypass) |

</details>

---

<div align="center">

### 💖 Support This Project

Please **⭐ star the repo** — it helps others find it and keeps the builds coming.

| Currency | Address |
|:---------|:--------|
| **BTC / ETH** | `0xea9a566a5123c3a1b8d60f8bdd845835716668f0` |
| **USDT (TRC-20)** | `THssAZhUQEEsw15211rAaRLGRjSWXMX4PW` |

[![Telegram](https://img.shields.io/badge/@MUH4MM4DSH4KIB-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/MUH4MM4DSH4KIB)

</div>
