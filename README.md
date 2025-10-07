<p align="center">
  <img src="https://raw.githubusercontent.com/hanzutweaks/utility/main/images/showcase.png" alt="Hanzu Tweaking Utility showcase">
</p>

<p align="center">
  <a href="https://github.com/hanzutweaks/utility/releases/latest/download/Hanzu%20Tweaking%20Utility%20v3.0%20%28Stable%29.cmd" target="_blank" rel="noopener">
    <img src="https://raw.githubusercontent.com/hanzutweaks/utility/main/images/download_button.png" alt="Download Hanzu Tweaking Utility v3.0 (Stable)">
  </a>
</p>

---

# Hanzu Tweaking Utility

**Hanzu Tweaking Utility** is a focused Windows tweak pack for gamers and creators — built to **boost FPS**, **reduce input latency**, and **remove bloat** using transparent, script-based changes.

> 🧠 **Principles:** transparent · reversible · minimal risk  
> 🔒 **Zero telemetry:** no pings, no installers, no background processes

---

## 🎯 What it does

- **Performance tuning** for low-latency gaming and a snappier desktop  
- **Debloat & service control** (diagnostics, telemetry, scheduled clutter)  
- **GPU presets** for NVIDIA / AMD (safe gaming-oriented defaults)  
- **Power tuning** (High/Ultimate performance, sensible device policies)  
- **Network cleanup & latency tweaks** (DNS/IP stack refresh, TCP presets)  
- **One-click cleanup** for temp, cache, and log buildup  

_All changes use standard Windows mechanisms (registry, services, tasks, `powercfg`, `netsh`/`ipconfig`). Each edit is commented in the script for review._

---

## 🧭 Module Map

### System Performance
1) **General Windows Optimizations** – scheduler bias, responsiveness, low-latency defaults  
2) **Disable Services** – turns off non-essential diagnostics/telemetry/services  
3) **System Cleanup & Repair** – temp/cache purge, DISM/SFC helpers  
4) **Debloat** – removes safe UWP bloat and scheduled clutter

### Power & Hardware
5) **Power Optimization** – High/Ultimate performance, `powercfg` tuning  
6) **CPU Optimization** – **Win32 Priority Separation**, MMCSS, timer/distribution tweaks  
7) **USB Tweaks** – selective suspend controls, **MSI mode** (when supported)  
8) **Hardware Tweaks** – HPET, OneDrive, QoL toggles

### Input & GPU Enhancement
9) **Keyboard Optimization** – repeat/lag tuning  
10) **Mouse Optimization** – acceleration off, precision settings  
11) **Controller Tweaks** – polling/latency presets  
12) **GPU Optimization** – NVIDIA/AMD safe defaults (VSync, shader cache, power)

### Storage & Memory
13) **Storage Optimizations** – NTFS, indexing, prefetch/superfetch policy  
14) **RAM Optimization** – standby list guidance, pagefile policy (documented)  
15) **Disk Repair** – CHKDSK/DISM helpers, quick SMART shortcuts  
16) **Disk Cleanup** – deep cleanup (logs, caches, temp, Delivery Optimization)

### Network & Connectivity
17) **Internet Refresher** – renew/flush/reset stack (`ipconfig`/`netsh`)  
18) **Network Optimization** – NDU throttles, TCP/latency presets, quick DNS set

### Advanced
19) **Performance Settings** – DirectX/MMCSS/priority/Fullscreen Optimizations toggle  
20) **Game Booster** – one-click apply of the safest, high-impact mix

> **Signature toggles:** Win32 Priority Separation · Task-kill timeout optimization · MMCSS · System Responsiveness · **Fullscreen Optimizations toggle** · **MSI on USB** · NTFS tuning · Disable Diagnostics · DirectX defaults · Distribute Timers · Disable Mouse Accel · Keyboard Optimizations

---

## 🚀 Quick Start

1. Open **[Releases → Latest](https://github.com/hanzutweaks/utility/releases/latest)**  
2. Download **`Hanzu Tweaking Utility v3.0 (Stable).cmd`** (or use the button above)  
3. **Right-click → Run as Administrator**  
4. Choose modules → **Apply** → Reboot

> 🛡️ **Safety first:** Create a **System Restore Point** and a **Registry Backup** before applying changes.  
> 🌐 **Internet:** Only required to **download the tool and any optional assets**; tweaks themselves run offline.

---

## ⚡ Quick Guide

1) **Extract** if you downloaded a `.zip`  
2) **Right-click → Run as administrator** on the `.cmd`  
3) Create a **System Restore Point** & a **Registry Backup**  
4) **Read all pop-ups** and the short description for each category before applying

> 💬 **Kind request:**
> After you’re done, please write a quick review and share feedback on our Discord — it really helps!  
> **Discord:** https://discord.gg/YTgc3d3UDg

---

## ✅ Does / ❌ Never

**Does**
- Use documented Windows settings (registry, services, tasks, `powercfg`, `netsh`)  
- Prioritize **stability and responsiveness** first; FPS gains second  
- Emits a clear “Applying …” status line for each tweak as it executes

**Never**
- Modify game files or inject overlays  
- Hack drivers or kernel components  
- Phone home or collect data

---

## 🧩 Compatibility & Requirements

| Item                | Support / Requirement                              |
|---------------------|-----------------------------------------------------|
| Operating System    | Windows **10 / 11** (x64)                           |
| Hardware            | Laptops & desktops (some options are hardware-dependent) |
| Privileges          | **Administrator** (elevated) required               |
| Internet            | **Only to download** the tool/optional assets; tweaks run offline |
| Storage             | Minimal (script + backups; recommend ≥100 MB free)  |
| Dependencies        | None (scripted; no installer, no runtime needed)    |

---

## ❓ FAQ

**Will this get me banned in games?**  
No. It only adjusts Windows settings.

**How do I revert?**  
Use **System Restore** or re-run and toggle items off. If you exported registry backups, restore those as needed.

**How much FPS will I gain?**  
Varies by system. Expect smoother input/consistency; FPS gains depend on hardware and bottlenecks.

**Does it collect data?**  
**No.** Zero telemetry.

---

## 🗒️ Changelog & Downloads

See **[Releases](https://github.com/hanzutweaks/utility/releases)** for version notes and assets.  
> GitHub Releases also show **download counts**.

---

## 📄 License

**All rights reserved © 2025 HanzuTweaks.**  
You may view and use this utility for **personal use only**.  
**Redistribution, modification, or repackaging is prohibited** without written permission.  
See `LICENSE.txt` for details.

---
