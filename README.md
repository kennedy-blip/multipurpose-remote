# ⚡ Universal Virtual Remote

> A fully responsive, multi-purpose virtual remote control web application that works on **phones**, **tablets**, and **desktops** — right from the browser. No app installs needed.

![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Mobile%20%7C%20Desktop-blue)
![Tech](https://img.shields.io/badge/Tech-Vanilla%20HTML%20%2F%20CSS%20%2F%20JS-orange)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📸 Overview

**Universal Virtual Remote** is a single-page web application that simulates remote controls for **7 different device categories**. Built with vanilla HTML, CSS, and JavaScript — zero frameworks, zero dependencies. Deploy once, use everywhere.

---

## 🚀 Quick Start

### Deploy to Render (or any static host)

1. **Fork or clone** this repository
2. **Push** to your GitHub/GitLab
3. **Create a new Web Service** on [Render](https://render.com)
4. Set the **Build Command**: *(leave blank)*
5. Set the **Start Command**: *(leave blank — it's static)*
6. Set the **Publish Directory**: `.` (or the folder containing `index.html`)
7. Click **Create Web Service** → Done! 🎉

### Run Locally

```bash
# Just open index.html in your browser
open index.html

# Or serve with any static server
npx serve .
python3 -m http.server 8000
```

---

## 🎮 Supported Devices & Controls

### 📺 1. TV Remote

| Section | Controls |
|---------|----------|
| **Power** | On/Off toggle |
| **Channels** | Full numeric keypad (0–9) + backspace |
| **Volume** | Volume Up / Volume Down rocker buttons |
| **Channels** | Channel Up / Channel Down rocker buttons |
| **Navigation** | D-Pad (Up / Down / Left / Right / OK) |
| **Actions** | Menu, Back, Home, Info |
| **Quick Keys** | Red, Green, Yellow, Blue color buttons |
| **Playback** | Rewind, Play/Pause, Play, Stop, Fast Forward |
| **Bottom** | Mute, Input Source, Sleep Timer, Record |

---

### 🔊 2. Audio / Sound System Remote

| Section | Controls |
|---------|----------|
| **Power** | On/Off toggle |
| **Volume** | Continuous slider (0–100) with live value display |
| **Playback** | Shuffle, Previous, Play, Next, Repeat |
| **Sound Modes** | Music, Movie, News, Game, Night, Bass Boost |
| **Equalizer** | Bass slider, Mid slider, Treble slider (0–100 each) |
| **Sources** | Mute, Bluetooth, AUX, USB |

---

### ❄️ 3. AC (Air Conditioner) Remote

| Section | Controls |
|---------|----------|
| **Power** | On/Off toggle |
| **Temperature** | Digital display (16°C–30°C) with ± buttons + Turbo mode |
| **Modes** | Cool, Heat, Auto, Dry, Fan Only, Eco |
| **Fan Speed** | Auto, 1, 2, 3, 4 |
| **Controls** | Swing, Timer, Sleep, Self Clean, Display, Quiet Mode |

---

### 📽️ 4. Projector Remote

| Section | Controls |
|---------|----------|
| **Power** | On/Off toggle |
| **Source** | HDMI 1, HDMI 2, USB, VGA, WiFi, Cast |
| **Navigation** | D-Pad (Up / Down / Left / Right / OK) |
| **Keystone** | Vertical keystone slider (-30 to +30) |
| **Zoom** | Zoom slider (0–100) |
| **Brightness** | Brightness slider (0–100) |
| **Actions** | Menu, Back, Freeze, Blank Screen |

---

### 🎬 5. Streaming Device Remote

| Section | Controls |
|---------|----------|
| **Power** | On/Off toggle |
| **Actions** | Home, Search, Back |
| **Navigation** | D-Pad (Up / Down / Left / Right / OK) |
| **Playback** | Rewind, Previous, Play/Pause, Next, Fast Forward |
| **Quick Launch** | Netflix, YouTube, Prime Video, Disney+, Spotify, Hulu |
| **Controls** | Mute, Closed Captions (CC), Cast, Picture Mode |
| **Volume** | Continuous slider (0–100) |

---

### 💡 6. Smart Lights Remote

| Section | Controls |
|---------|----------|
| **Power** | On/Off toggle |
| **Brightness** | Continuous slider (0–100%) |
| **Color Temperature** | Warm-to-cool slider (2700K–6500K) |
| **Scenes** | Reading, Relax, Work, Sunset, Party, Night |
| **Color Picker** | Red, Orange, Yellow, Green, Blue, Purple, White, Rainbow |
| **Effects** | Timer, Fade, Strobe, Smooth Transition |

---

### 🌀 7. Fan Remote

| Section | Controls |
|---------|----------|
| **Power** | On/Off toggle |
| **Speed** | 1 (Low), 2 (Medium), 3 (High) |
| **Modes** | Normal, Natural (simulates breeze), Sleep (gradual slowdown) |
| **Oscillation** | Oscillate toggle, Rotate toggle |
| **Timer** | 1 Hour, 2 Hours, 4 Hours, 8 Hours presets |

---

## ✨ Features

### 📱 Mobile-First Design
- Large, touch-friendly buttons designed for thumbs
- Horizontally scrollable device tabs with swipe support
- No pinch-zoom interference (disabled for app feel)
- Responsive layout adapts to any screen size

### 💻 Desktop Support
- Full **keyboard control** mapped to all remotes
- Click-friendly with ripple animations
- Responsive layout works in any browser window

### 📳 Haptic Feedback
- Vibration pulses on every button press (on supported devices)
- Different vibration patterns for power toggles vs. regular presses
- Subtle slider vibration during adjustments

### 🔊 Sound Effects
- Optional click sounds via Web Audio API
- No external audio files needed — generated programmatically
- Toggle on/off from Settings

### 🌊 Ripple Animations
- Material Design-style ripple effect on button press
- Originates from the exact touch/click point
- Toggle on/off from Settings

### ⏱️ Long Press Repeat
- Hold **Volume Up/Down** or **Channel Up/Down** for continuous adjustment
- Hold **Temperature ±** on AC remote for rapid changes
- Auto-repeats every 150ms after 500ms hold

### ⚙️ Settings Panel
| Setting | Default | Description |
|---------|---------|-------------|
| Haptic Feedback | ✅ ON | Vibration on button presses |
| Sound Effects | ❌ OFF | Audio click feedback |
| Button Animations | ✅ ON | Ripple effect on press |
| Show Toast Messages | ✅ ON | Command confirmation toasts |
| Keyboard Controls | ✅ ON | Desktop keyboard shortcuts |

### 🌙 Dark Theme
- Sleek dark UI mimicking a real physical remote
- Purple accent color scheme (`#6c5ce7`)
- Comfortable for use in dark rooms (e.g., home theater)

---

## ⌨️ Keyboard Shortcuts (Desktop)

| Key | Action |
|-----|--------|
| `↑` `↓` `←` `→` | Navigate (D-Pad) |
| `Enter` | OK / Select |
| `Escape` / `Backspace` | Back |
| `Space` | Play / Pause |
| `M` | Mute Toggle |
| `H` | Home |
| `P` | Power Toggle |
| `+` / `=` | Volume Up (or Temp + on AC) |
| `-` / `_` | Volume Down (or Temp - on AC) |
| `0`–`9` | Channel / Number input |
| `Ctrl+1`–`Ctrl+7` | Switch between devices |

---

## 🏗️ Architecture

### File Structure

```
/
├── index.html    ← Everything in one file (HTML + CSS + JS)
└── README.md     ← This file
```

### How It Works

The app is built as a **single HTML file** with three inline sections:

1. **`<style>`** — All CSS (variables, responsive layout, animations, dark theme)
2. **HTML Body** — Semantic structure with `device-remote` sections for each device
3. **`<script>`** — JavaScript state management, event handling, audio, haptics

### State Management

```javascript
state = {
  activeDevice: 'tv',         // Currently selected device
  devices: {                   // Per-device power state
    tv: { power: false },
    audio: { power: false },
    ac: { power: false, temp: 24 },
    projector: { power: false },
    stream: { power: false },
    light: { power: false },
    fan: { power: false },
  },
  settings: {                  // User preferences
    haptic: true,
    sound: false,
    anim: true,
    toast: true,
    keyboard: true,
  }
}
```

### Command Flow

```
User taps button → sendCmd(device, command)
                   ├── vibrate() → navigator.vibrate()
                   ├── playClick() → Web Audio API
                   ├── showToast() → Visual confirmation
                   └── console.log() → For integration/debugging
```

---

## 🔌 Integration Guide (Making It Real)

This remote is a **frontend UI** ready for backend integration. To connect it to real devices:

### Option A: WebSocket / REST API

Replace the `console.log` in `sendCmd()` with actual API calls:

```javascript
function sendCmd(device, cmd) {
  fetch('https://your-api.com/remote', {
    method: 'POST',
    headers: { 'Content-Type': 'application/json' },
    body: JSON.stringify({ device, command: cmd })
  });
}
```

### Option B: MQTT / IoT Bridge

Connect to an MQTT broker via WebSocket to send commands to ESP32, Raspberry Pi, or other IoT devices:

```javascript
const client = mqtt.connect('wss://your-broker.com');
function sendCmd(device, cmd) {
  client.publish(`remote/${device}`, cmd);
}
```

### Option C: Home Assistant Integration

Send commands to Home Assistant's REST API:

```javascript
function sendCmd(device, cmd) {
  fetch('http://homeassistant.local:8123/api/services/remote/send_command', {
    method: 'POST',
    headers: {
      'Authorization': 'Bearer YOUR_TOKEN',
      'Content-Type': 'application/json',
    },
    body: JSON.stringify({ entity_id: `remote.${device}`, command: cmd })
  });
}
```

### Option D: Infrared Blaster

Pair with an IR blaster like Broadlink RM4 or Tuya IoT:

```javascript
function sendCmd(device, cmd) {
  // Map commands to IR codes
  const irCodes = { tv: { power: 'CODE_1234', vol_up: 'CODE_5678' } };
  fetch('https://your-ir-blaster/api/send', {
    method: 'POST',
    body: JSON.stringify({ code: irCodes[device][cmd] })
  });
}
```

---

## 📱 PWA (Progressive Web App) Support

To make this installable on phones like a native app, add these files:

### `manifest.json`
```json
{
  "name": "Universal Virtual Remote",
  "short_name": "Remote",
  "start_url": "/",
  "display": "standalone",
  "background_color": "#0a0a0f",
  "theme_color": "#6c5ce7",
  "icons": [
    { "src": "icon-192.png", "sizes": "192x192", "type": "image/png" },
    { "src": "icon-512.png", "sizes": "512x512", "type": "image/png" }
  ]
}
```

### Add to `index.html` `<head>`:
```html
<link rel="manifest" href="manifest.json">
<meta name="theme-color" content="#6c5ce7">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
```

Users can then **"Add to Home Screen"** for a fullscreen, app-like experience.

---

## 🌐 Browser Compatibility

| Feature | Chrome | Firefox | Safari | Edge |
|---------|--------|---------|--------|------|
| Core UI | ✅ | ✅ | ✅ | ✅ |
| Haptic (Vibration API) | ✅ Android | ✅ Android | ❌ | ✅ |
| Web Audio (Click Sound) | ✅ | ✅ | ✅ | ✅ |
| Keyboard Shortcuts | ✅ | ✅ | ✅ | ✅ |
| Touch Events | ✅ | ✅ | ✅ | ✅ |
| Add to Home Screen | ✅ | ✅ | ✅ | ✅ |

---

## 🛠️ Customization

### Change Accent Color

Edit the CSS variable in `<style>`:

```css
:root {
  --accent: #6c5ce7;       /* Change to any color */
  --accent-glow: rgba(108, 92, 231, 0.3);
}
```

### Add a New Device Remote

1. Add a new tab button in the `device-tabs` section
2. Create a new `device-remote` div with `id="remote-yourdevice"`
3. Add the device to the `state.devices` object in JavaScript
4. Add device name to `deviceNames` in `sendCmd()`
5. Optionally add keyboard shortcut mapping

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

---

<p align="center">
  Built with ❤️ using Vanilla HTML, CSS & JavaScript<br>
  <strong>No frameworks. No dependencies. Just the web.</strong>
</p>
