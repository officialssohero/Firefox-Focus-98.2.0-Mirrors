# Firefox Focus 98.2.0 – Media Playback Workaround (Android)

## 📌 Overview

This repository mirrors **Firefox Focus 98.2.0 (March 2022)** APKs for Android.

This specific version appears to **avoid Android browser audio muting / video interruption during active calls** (WhatsApp / VoIP / phone calls), a behavior that affects most modern browsers.

> ⚠️ This is **not a hack**, root method, or ADB trick.  
> It appears to be a behavioral difference in this historical version that was later fixed.

---

## 🧩 The Problem

On Android, most browsers:
- Mute website audio during calls
- Pause or stop video playback
- Lose media focus entirely

This affects:
- Chrome
- Firefox (regular)
- Brave / Edge / Opera
- Newer Firefox Focus versions

ADB / AppOps tweaks **do not work** for call audio.

---

## ✅ What Works

**Firefox Focus 98.2.0**
- Keeps **video + audio playing during calls**
- Does **not** lose media focus like newer versions
- Newer versions (99+) do **not** behave the same

---

## 📥 Downloads

All APK variants are available under **Releases**:

- arm64-v8a  
- armeabi-v7a  
- x86  
- x86_64  

➡️ **Most users should download `arm64-v8a`**

---

## 📱 Which APK should I install?

- **arm64-v8a** → Almost all modern Android phones (recommended)
- armeabi-v7a → Very old 32-bit ARM devices
- x86 / x86_64 → Emulators or Chromebooks

If installation fails, try another ABI.

---

## ⚙️ Installation Steps

1. Download the correct APK for your device
2. Enable **Install unknown apps**
3. Install the APK
4. Disable **auto-update** for Firefox Focus in Play Store
5. Do **NOT** set it as your default browser

---

## 🛠️ Troubleshooting

**App won’t install**
- Wrong ABI → try `arm64-v8a` first
- Android version too new → still works for most users

**Audio still mutes**
- Confirm the version is **98.2.0**
- Fully close other browsers
- Test with a normal (non-DRM) website video

---

## ⚠️ IMPORTANT SAFETY NOTICE

This is an **old browser**.

### ✅ SAFE USE
- Video playback
- Streaming
- Media / educational content
- Non-login websites

### ❌ DO NOT USE FOR
- Banking
- Payments / UPI
- Email or Google login
- Passwords
- Personal accounts

👉 **Use a modern browser for all normal and sensitive browsing.**

---

## 🧠 Why this exists

This repository exists to:
- Preserve a working media behavior
- Help users affected by Android call audio restrictions
- Share knowledge **freely and transparently**

No monetization. No modifications. No guarantees.

---

## 📄 Disclaimer

APKs are provided **as-is** for testing and media use only.  
Use at your own discretion.

---

## ⭐ Support

If this repository helped you, consider giving it a **star ⭐** so others can find it more easily.

---

## ❤️ Thanks

If this helps you, feel free to share the knowledge responsibly.  
**Solutions should be free and knowledge should be open.**
