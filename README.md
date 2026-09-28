# SONOS Panel v2.0 (Concept)

> A whole-home audio controller built on one idea: the house should be understood at a glance.

**▶ Live demo:** [ovidemetrian.github.io/SONOS-panel](https://ovidemetrian.github.io/SONOS-panel/)
**▶ Saturday demo (Amp Multi house):** [ovidemetrian.github.io/SONOS-panel/?demo](https://ovidemetrian.github.io/SONOS-panel/?demo)
Open it on any phone or tablet. No install, no account, no sign-in.

---

## The Philosophy: The Final Ten Feet

After 30 years of designing and installing custom AV and smart-home systems, one truth remains: **the final ten feet is everything.**

You can engineer flawless audio hardware and a bulletproof network, but the final ten feet is defined entirely by the people on the sofa. The speakers, the lights, the TV and everything in the rack have to disappear so the experience can take over. If someone hesitates at the glass to figure out how to group the kitchen and the patio, the moment is gone.

True enjoyment happens when friction drops to zero. People don't want to manage their system. They want to live in it. The SONOS Panel is designed around that reality.

---

## What's New in v2.0

Version 2.0 keeps the same design and adds what a professional installation needs.

### 🏠 Amp Multi Zones
A five-room sample house runs on one Amp Multi. When the installer wires Kitchen and Dining as one zone, the panel says **Kitchen + Dining** and offers one volume. It never shows a control the wiring can't deliver.

### 🔀 Speakers That Move
Carry the Sonos Play from the Patio into the Theater and it becomes a rear surround, using Sonos Positioning Technology, part of Sonos Fabric. The panel moves it on screen, so a quieter Patio is never a mystery.

### 🎧 Listeners, Not Just Rooms
Headphones are a person, not a room. With headphone linking (Early Access, Sonos Ace Ultra only), Maya can pull the dinner music to her ears, and Priority One leaves her headphones alone.

### 🤝 Honest Priority One
Other controllers act too: the Sonos app, Sonos 27web, Sonos 27voice, assistants connected through Sonos 27mcp, Josh.ai, and soon Sonos Custom Agents. When P1 brings the house back, it restores only what it can verify and names any room someone else changed in the meantime. Example: *"Patio was changed by Josh.ai after the silence, so it was left as is."*

### 📡 Offline Mode
When the internet drops, the panel says what still works: TV, Bluetooth, Line-In, the local music library, P1, volume and grouping. Streaming tiles dim and explain why, instead of failing silently.

### 🔧 Installer View
A read-only map of the Amp Multi's eight outputs, the Sonos zones they form, and the home areas the family sees. Wiring and tuning stay in the Sonos app.

### ▶️ Saturday Demo
Ten steps from 5:45 pm to 10:42 pm walk through all of it: dinner, guests, movie night, headphones, Priority One, another controller acting, an honest resume, the internet dropping, and Bluetooth saving the evening.

---

## Core Mechanics

### 🎨 Colour as Immediate Context
Every room has its own colour, and the panel takes on the colour of the room you're controlling. A calm row of colour bubbles shows every room; the current one is larger with a white ring. Recognising a colour is faster than reading a label, so people know where they are before they read a single word.

### 🎛️ Zero-Scroll Grouping
Grouping rooms happens on a single screen with no scrolling. The whole house fits in one glance. "This room only" or "all rooms together" is one decision, not a trip through menus.

### ↩️ Mistakes Are Cheap
People explore more freely when they aren't afraid of messing up the house. The interface makes mistakes cost nothing:
- **Priority One (P1):** silences the entire house instantly, then brings back everything it can verify.
- **Back to Square One:** resets every room to a clean state, with an immediate **Undo**.

### 🗣️ Natural Multimodal Control
- **Voice:** speak a command and the panel answers out loud. When the microphone isn't available, you can type or tap a suggestion. Voice is never the only way in.
- **Intercom:** hold to talk or send a quick announcement. Music in the chosen rooms lowers while you speak, then comes back on its own.
- **Speaker Chimes:** can't tell which speaker is which? Play a chime and find it by ear.
- **Ambient Logic:** sleep timers fade music out gradually, and a morning alarm wakes the house.

### 🧭 Built for Trust
- **Command Log:** a visible record of every action, including who acted: the panel, another controller, or the system
- **TV Flag:** marks rooms with a soundbar
- **Guided Setup:** a flow for adding new speakers, clearly marked as sample devices
- **Sample Houses:** 4-room, 6-room and Amp Multi homes for demonstration

---

## Why It Works

| Common pain point | The SONOS Panel's answer |
|---|---|
| "Which room am I controlling?" | The whole screen is that room's colour. |
| Grouping buried in menus | The whole house, one screen, one decision |
| Fear of messing things up | P1 restore and Undo on every big action |
| Two rooms wired as one zone | One linked area, one volume, clearly labelled |
| A speaker moved and the sound changed | The panel shows where it went and its new role |
| Several apps and voices controlling the house | P1 respects their changes and says who made them |
| The internet goes down | A clear list of what still works, nothing failing silently |
| Voice that fails silently | Spoken replies, plus typed and tap fallbacks |
| Announcements clashing with music | Automatic lowering and restore |
| Everyday features hidden or removed | Alarms, sleep timer, voice and intercom live in the core |

---

## Local First

Many of the homes this concept serves are exactly where the internet is least reliable: mountain and rural properties, second homes, boats, and owners who keep devices off the internet for privacy. The house has to keep playing when the outside connection fails.

The proposed path is a small hub inside the house that talks to the speakers over the local network, with the cloud as the online path for remote and account features. The offline mode in this prototype shows what that experience should feel like. A real local path still has to be proven in the field.

---

## Technical Execution

- A single self-contained file written in HTML, CSS and vanilla JavaScript, with no frameworks or libraries and no build step (typography loads from Google Fonts)
- Phone-native, responsive layout that runs in any modern mobile or desktop browser
- Voice features depend on the browser's speech support, which varies by browser and device
- Add `?demo` to the address to open straight into the Saturday demo
- **All music, lighting, shade, speaker, headphone and network behaviour is simulated.** This is an interface concept and does not connect to real speakers or smart-home devices.

---

## Version History

- **v2.0:** Amp Multi zones, moving speakers, listeners, honest Priority One, offline mode, installer view, Saturday demo
- **v1.9:** calm colour-bubble room bar, zero-scroll grouping, room count instead of a fixed four

---

## Author

**Ovidiu Mircea Demetrian (Ovi)**
Founder, Smart Homes by Ovi & Media Content Delivery, LLC · Phoenix, Arizona
In professional audio since 1994

🌐 [mediacontentdelivery.com](https://www.mediacontentdelivery.com) · [10lawsofai.com](https://10lawsofai.com) · [Portfolio](https://ovidemetrian.github.io/my-future-past/)
✉️ ovidemetrian@gmail.com

*Lumină, nu vrăjală — light, not trickery.*

---

## Disclaimer

This is an independent, unofficial UI/UX concept. It is not affiliated with, endorsed by, or sponsored by Sonos, Inc., Lutron Electronics, Josh.ai or Home Assistant. All product names, logos and brands are the property of their respective owners and are used here only for identification.

## Copyright

© 2026 Ovi Demetrian / Media Content Delivery, LLC. **All rights reserved.**
No license is granted to copy, modify, distribute or create derivative works from this code or design without written permission.
