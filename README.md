# Bharat 3D — Android APK

**Bharat 3D** — India ka 3D map + walk mode, poora app ke andar (offline).

**Direct APK download:** https://github.com/rewpal5-dotcom/Bharat-3D/releases/latest/download/app-debug.apk

## App mein kya hai

- **3D map** — asli relief wala India, drag se rotate, pinch se zoom, States mode (rajya ke naam ke saath)
- **🚶 Walk mode** — mandir, gaon, khet, nadi-ghat, jungle wali 3D duniya; character, joystick, RUN/JUMP, camera ghumana, paas jaakar jagah ki jankari
- **Full-screen** — koi status bar / navigation bar nahi, poori screen par map
- **Offline** — sab kuch APK ke andar, koi internet nahi chahiye, koi ad nahi

## Controls

- Map: drag = rotate, pinch/scroll = zoom, 🗺 = States mode, 🚶 = walk mode
- Walk: left joystick = chalna, screen drag = camera, RUN/JUMP buttons, paas jaane par "देखें"

## Build

```bash
./gradlew assembleDebug
```

GitHub Actions har push par APK bana kar release mein daal deta hai.

## Tech

Java + WebView · bundled HTML5 canvas 3D renderer (koi library nahi) · minSdk 24 · targetSdk 35 · compileSdk 36

## License

MIT
