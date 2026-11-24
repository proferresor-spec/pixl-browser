# PIXEL

**A Chromium browser for Windows with a glass interface, built in Rust.**

## Download

👉 **[Download the latest PIXEL-Setup.exe](https://github.com/proferresor-spec/pixel-browser/releases/latest)**

Run the file and click **Install**.
- No admin rights needed.
- It installs to `%LOCALAPPDATA%\Programs\PIXEL`.
- Windows may show *"Windows protected your PC"* because the installer isn't code-signed yet. Click **More info → Run anyway**.

You need Windows 10 or 11 with the Microsoft Edge WebView2 runtime. Windows 11 already includes it.

## Features

- **Tab Islands**: related tabs group automatically and can be collapsed or recoloured.
- **Split screen**: 2–4 pages side by side, each pane resizable.
- **Sidebar apps**: WhatsApp, Telegram, Discord, Instagram, X and others, plus a music player.
- **PIXEL Shield**: ads and trackers are blocked, YouTube ads included, using EasyList and the uBlock Origin lists.
- **PIXEL AI**: an assistant built into the browser (powered by Groq). It can summarize pages, compare tabs, look at screenshots, and drive the browser, but only with your permission. No API key needed.
- **Chrome extensions**: install them straight from the Chrome Web Store.
- **Import** from Chrome, Edge, Brave, Vivaldi, Opera and Firefox: bookmarks, history and extensions.
- **Memory saver**: background tabs go to sleep. PIXEL aims to stay under 1 GB of RAM.

## Updates

PIXEL updates itself from this page. When a new release appears it downloads in the background, gets checked with SHA-256, and installs when you click **Restart to update**. Your data is kept.

## Privacy

- Your browsing data stays on your PC, in `%LOCALAPPDATA%\PIXEL`.
- PIXEL AI requests go through a small proxy, so the AI service key never ships inside the app. That proxy only sees a random install ID, which is used for fair-use limits.
- Settings → Setup & import → **Delete everything** removes all data.
