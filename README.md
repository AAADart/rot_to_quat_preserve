# 🌀 Rot to Quat (Preserve Motion)

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Blender](https://img.shields.io/badge/Blender-4.0%2B-orange.svg)](https://www.blender.org/)
[![Release](https://img.shields.io/github/v/release/AAADart/rot_to_quat_preserve?color=brightgreen)](https://github.com/AAADart/rot_to_quat_preserve/releases/latest)

Blender add-on that converts **Euler / Axis-Angle animation** to **Quaternion rotation**  
while preserving motion, continuity, and interpolation.

---




https://github.com/user-attachments/assets/b951513f-846d-4861-ba53-dd5b45617ba3








## ✨ Features

- 🧩 **Two modes:**  
  - *Keyframes Only* — converts at existing keyframes (optionally add between-keys sampling)  
  - *All Frames* — full-frame bake across scene range
- 🌀 **Quaternion continuity** — prevents 180° flips  
- ⚙️ **Interpolation control:** Default / Linear / Auto-Clamped  
- 🧭 **Delete or mute source curves** (works for both Action & NLA)
- 🎯 Works with Active / Selected objects  
- 💡 Tested on Blender **4.5.2**

---

## 🧩 Installation

1. Download the latest version from the [Releases page](https://github.com/AAADart/rot_to_quat_preserve/releases/latest)  
   → **rot_to_quat_preserve-1.5.1.zip**
2. In Blender:
   - Go to **Edit → Preferences → Add-ons → Install…**
   - Select the downloaded `.zip`
   - Enable **Rot to Quat (Preserve Motion)**
3. Open **3D Viewport → N → Animation → Rot -> Quat (Preserve)**

---

## 🚀 Usage

1. Select your object(s) with Euler / Axis-Angle animation.  
2. Choose **Sample Mode**:
   - *Keyframes Only* or *All Frames*  
3. (Optional) Enable **Delete Source Curves** to clean up Euler f-curves.  
4. Click **Convert Now** 🎬  
5. Enjoy quaternion animation with preserved motion!

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

© 2025 [AAADart](https://github.com/AAADart)

---

> 💬 *"When you realize your animation needs quaternions — this add-on has your back."*
