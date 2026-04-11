# 🎧 YouTube Audio Only — Chrome Extension

**Listen to YouTube without the video.** Save bandwidth, reduce distractions, and extend battery life by streaming only the audio from YouTube.

[![Chrome Web Store](https://img.shields.io/badge/Chrome%20Web%20Store-Install-blue?logo=googlechrome&logoColor=white)](https://chromewebstore.google.com/detail/youtube-audio-only/bbpioegbpcgdmhjeekoojjpgdgbiefjn)

---

## ✨ Features

- **Audio-Only Mode** — Hides the YouTube video player so only audio streams, saving data and system resources.
- **Hide Thumbnails** — Optionally hide video thumbnails across YouTube for a cleaner, distraction-free experience.
- **One-Click Toggle** — Easily switch between normal and audio-only mode with a single click on the extension icon.
- **Lightweight & Fast** — Runs entirely in your browser with zero external network calls.
- **Privacy-First** — No data collection, no tracking, no analytics. Your preferences are stored locally.

---

## 🚀 Installation

1. Visit the [Chrome Web Store listing](https://chromewebstore.google.com/detail/youtube-audio-only/bbpioegbpcgdmhjeekoojjpgdgbiefjn).
2. Click **"Add to Chrome"**.
3. Navigate to any YouTube video and click the extension icon to toggle audio-only mode.

---

## 🛠️ How It Works

The extension uses Chrome APIs to modify YouTube's front-end behavior on pages you visit:

| Setting | Description | Storage Key |
|---------|-------------|-------------|
| **Hide Video Player** | Hides the video element, leaving only audio playback | `toggle` |
| **Hide Thumbnails** | Removes video thumbnails across YouTube pages | `thumbblock` |

All preferences are saved locally using `chrome.storage.sync` and persist across browser sessions.

---

## 🔒 Permissions

| Permission | Purpose |
|------------|---------|
| `activeTab` | Modify YouTube pages you are actively viewing |
| `storage` | Save your toggle settings locally in the browser |

> **No remote servers or external domains are ever contacted by this extension.**

---

## 🔐 Privacy Policy

This extension is built with privacy as a core principle:

- ❌ No personal data collected
- ❌ No browsing history accessed
- ❌ No third-party services, trackers, or analytics
- ✅ All code runs locally in your browser
- ✅ Settings stored only on your device

👉 [Read the full Privacy Policy](https://balakrishnanbsk.github.io/youtubeaudioonly-privacy/privacy.html)

---

## 💡 Use Cases

- 🎵 **Music & Podcasts** — Listen to audio content without wasting bandwidth on video.
- 📱 **Limited Data Plans** — Significantly reduce data usage on metered connections.
- 🔋 **Battery Saver** — Less rendering means longer battery life on laptops and tablets.
- 🧑‍💻 **Focus Mode** — Eliminate visual distractions while working or studying.
- ♿ **Accessibility** — Ideal for users who prefer or rely on audio-only content.

---

## ⚠️ Limitations

- May not support **YouTube Live streams**.
- Only works on **YouTube** (`youtube.com`) pages.

---

## 👨‍💻 Developer

**Balakrishnan BSK**

- GitHub: [@balakrishnanbsk](https://github.com/balakrishnanbsk)

---

## 📄 License

This project is open source. See the repository for license details.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to open an [issue](https://github.com/balakrishnanbsk/youtubeaudioonly-privacy/issues) or submit a pull request.

---

<p align="center">
  Made with ❤️ for distraction-free YouTube listening
</p>
