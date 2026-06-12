# 🎵 RootTone

**Persistent system sound customization for rooted Android devices.**

RootTone lets you replace any system sound (keyboard clicks, lock/unlock, notifications, charging) with your own audio files — and keeps them after every reboot, via a Magisk module.

---

## ✨ Features

- 🔊 Browse and preview all system sounds
- 📁 Import your own `.ogg` or `.mp3` files
- ✅ Changes survive reboot (powered by Magisk Magic Mount)
- 🧩 No Xposed required — works with plain Magisk
- 🎨 Clean Material You UI (Jetpack Compose)

---

## 📋 Requirements

- Android 10+
- Magisk 24.0+
- Root access granted to the app

---

## 🚀 Installation

1. Download the latest APK from [Releases](../../releases)
2. Install the APK on your device
3. Open RootTone — it will prompt you to install the companion Magisk module
4. Reboot once
5. Done — start customizing!

---

## 🗂️ Project Structure

```
RootTone/
├── app/                  # Android app (Kotlin + Compose)
├── magisk-module/        # Companion Magisk module
└── docs/                 # Sound map and contributing guide
```

---

## 🛣️ Roadmap

- [x] Project setup
- [ ] MVP: browse + replace system sounds
- [ ] Sound pack support (import/export sets)
- [ ] Scheduled profiles (e.g. silent at night)
- [ ] Per-app sound overrides

---

## 🤝 Contributing

Pull requests are welcome! See [docs/contributing.md](docs/contributing.md) for guidelines.

---

## 📄 License

MIT © RootTone Contributors
