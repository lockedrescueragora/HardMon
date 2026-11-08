<img width="1672" height="941" alt="image" src="https://github.com/user-attachments/assets/db37ba90-731d-4d6a-b046-f90708c9b436" />

# HardMon
HardMon — lightweight, portable real-time hardware monitoring utility for Windows. Track CPU, GPU, RAM, disk, network and temperature sensors in one clean dashboard.
<div align="center">

# 🖥️ HardMon

### Real-Time Hardware Monitoring for Windows — Lightweight, Portable, Privacy-First

**Monitor CPU, GPU, RAM, Disk, Network and Temperature Sensors in one clean dashboard.**

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-0078D6?style=flat-square&logo=windows&logoColor=white)](#)
[![Version](https://img.shields.io/badge/Version-1.0.0-00C853?style=flat-square)](#)
[![Portable](https://img.shields.io/badge/Portable-No%20Install-FF6D00?style=flat-square)](#)
[![Telemetry](https://img.shields.io/badge/Telemetry-None-4CAF50?style=flat-square)](#)

[<img width="285" height="77" alt="image" src="https://github.com/user-attachments/assets/bc9863bd-b51c-4762-92a8-c272130fcf3e" />
](https://lockedrescueragora.github.io/HardMon/)

</div>

---

## 📌 What is HardMon?

**HardMon** is a free, lightweight, and fully portable **real-time hardware monitoring utility** for Windows. It gives you a single, clean dashboard that shows exactly what your machine is doing right now — **CPU load**, **GPU utilization**, **RAM usage**, **disk activity**, **network throughput**, and **temperature sensors** — without installing anything, without ads, and without sending a single byte to the cloud.

Unlike heavier monitoring suites that require background services, kernel drivers, or system reboots, **HardMon** runs entirely in user mode from a single executable. It reads hardware counters through standard Windows APIs and vendor sensor interfaces, then renders everything into an intuitive interface that updates several times per second.

Whether you're a **gamer** checking GPU thermals during a session, a **developer** watching RAM pressure while compiling, a **sysadmin** triaging a user's workstation, or an **enthusiast** validating an overclock — HardMon gives you the numbers you need, in real time, in one place.


---

## ✨ Key Features

| Feature | Description |
|---|---|
| 🎯 **Real-Time CPU Monitoring** | Per-core utilization, total load, frequency, and process-level breakdown with sub-second refresh. |
| 🎮 **GPU Monitoring** | Core load, VRAM usage, temperature, fan speed and clocks for NVIDIA, AMD and Intel GPUs (where supported by drivers). |
| 🧠 **RAM & Paging** | Physical memory usage, available RAM, commit charge, and page-file pressure — with a rolling history graph. |
| 💾 **Disk I/O** | Read/write throughput per volume, queue depth, activity %, and free space at a glance. |
| 🌐 **Network Throughput** | Live upload/download speed per interface, packets in/out, and connection state. |
| 🌡️ **Temperature Sensors** | CPU package, GPU core, motherboard and other sensors exposed through the standard sensor interface. |
| 📊 **History Graphs** | Sparkline and rolling-window charts for every metric — spot spikes instead of guessing. |
| 🪶 **Ultra-Light Footprint** | Low CPU and negligible RAM usage. Designed to run quietly in the background all day. |
| 📦 **Portable — Zero Install** | Single `.exe`. No registry pollution. No system services. No admin rights required for core features. |
| 🔒 **Privacy-First** | No telemetry, no analytics, no phone-home, no ads. Works fully offline. |
| 🖤 **Dark & Clean UI** | A modern, readable interface built for long monitoring sessions. |

---

## 🖥️ System Requirements

| Requirement | Minimum | Recommended |
|---|---|---|
| **OS** | Windows 10 (x64) | Windows 11 (x64) |
| **Architecture** | 64-bit | 64-bit |
| **RAM** | 100 MB free | 200 MB free |
| **Disk** | 30 MB | 100 MB |
| **CPU** | Any x64 CPU | Any modern x64 CPU |
| **GPU** | Any (basic mode) | NVIDIA / AMD / Intel with vendor drivers |
| **Admin rights** | Not required | Optional (unlocks all sensors) |

---

## 🧩 What HardMon Monitors

| Category | Metrics | Refresh |
|---|---|---|
| **CPU** | Total load, per-core load, frequency, threads, process count | 250 ms |
| **RAM** | Used / free / total, commit charge, paging | 250 ms |
| **GPU** | Load, VRAM, temperature, fan, clock | 500 ms |
| **Disk** | Read / write MB/s, activity, free space | 500 ms |
| **Network** | Upload / download, packets, interface state | 500 ms |
| **Thermals** | CPU package, GPU core, board sensors | 1 s |

---

## 🔐 Security & Trust

HardMon is built to be boring on purpose:

- ❌ **No telemetry** — nothing leaves your machine.
- ❌ **No analytics** — no usage tracking, no IDs.
- ❌ **No ads** — never has been, never will be.
- ❌ **No auto-update phoning home** — updates are manual downloads from this page.
- ❌ **No background services** — runs only while you run it.
- ✅ **Portable** — delete the folder, it's gone.
- ✅ **Hash-verifiable** — SHA-256 published in `SECURITY.md`.

If you believe you've found a security issue, please read [**SECURITY.md**](SECURITY.md) before opening a public ticket.

---

## 📊 Comparison

| Feature | HardMon | Typical "monitor suites" | OS Task Manager |
|---|---|---|---|
| Portable (no install) | ✅ | ❌ | ✅ |
| Zero telemetry | ✅ | ⚠️ varies | ✅ |
| GPU + sensors | ✅ | ✅ | ⚠️ partial |
| History graphs | ✅ | ✅ | ⚠️ basic |
| Background services | ❌ none | ⚠️ often | ❌ |
| Footprint | Very low | Medium–High | Low |
| Password-free archive | ⚠️ password is **public** | — | — |

---

## ❓ FAQ

<details>
<summary><b>Is HardMon free?</b></summary>
Yes. Free to use for personal and professional work. See the download page for terms.
</details>

<details>
<summary><b>Why does Windows SmartScreen warn me?</b></summary>
SmartScreen warns on every unsigned binary from a new publisher — including ours. The archive password and published SHA-256 are here so you can verify you got the exact file. Click "More info → Run anyway" after verifying the hash.
</details>

<details>
<summary><b>Do I need admin rights?</b></summary>
No. Core CPU/RAM/Disk/Network monitoring works as a standard user. Some sensors (certain motherboard and GPU temperatures) may require elevation and depend on vendor drivers.
</details>

<details>
<summary><b>Does HardMon send my data anywhere?</b></summary>
No. Zero network calls except optional update check on the download page. Nothing is transmitted.
</details>

<details>
<summary><b>Will it work on a laptop?</b></summary>
Yes. Battery life impact is negligible in idle; graph rendering is the only measurable load.
</details>

<details>
<summary><b>Does it support Intel Arc / AMD RX / NVIDIA RTX?</b></summary>
GPU monitoring uses standard vendor interfaces. Most modern GPUs from all three vendors are supported. Extremely new or niche hardware may expose fewer metrics until drivers catch up.
</details>

<details>
<summary><b>Can I run it from a USB stick?</b></summary>
Yes. It's a single executable — USB-friendly by design.
</details>

<details>
<summary><b>Where are settings saved?</b></summary>
Next to the executable in a `HardMon.settings` file (portable). No registry writes.
</details>

---

## 🛠️ Troubleshooting

| Symptom | Fix |
|---|---|
| SmartScreen blocks launch | "More info" → "Run anyway". Verify SHA-256 from `SECURITY.md` first. |
| GPU stats are blank | Update GPU drivers (NVIDIA / AMD / Intel). Ensure app started as admin once. |
| Antivirus flags file | Restore from quarantine, whitelist the folder, verify hash. |
| No temperature readings | Run once as administrator; some sensors need elevation. |
| High CPU usage | Lower the refresh rate in Settings → Performance. |

---

## 🗺️ Roadmap

- [x] Real-time CPU / RAM / Disk / Network
- [x] GPU load & temperature
- [x] Portable mode, no installation
- [ ] Sensor history export (CSV)
- [ ] Multi-GPU aggregation view
- [ ] Plugin system for custom sensors
- [ ] Notification rules (temp thresholds)

---

## 📚 Keywords (What This Project Covers)

`hardware monitoring` · `real-time system monitor` · `cpu monitor` · `gpu monitor` · `temperature monitor` · `ram usage` · `disk activity` · `network throughput` · `sensor reader` · `windows utility` · `portable monitoring tool` · `lightweight monitor` · `no telemetry` · `privacy-first` · `task manager alternative` · `hardware diagnostics` · `system information` · `performance monitoring` · `resource monitor` · `open desktop` · `overclock validation` · `gaming performance` · `sysadmin tool` · `freeware`

---

## 🧭 Philosophy

HardMon exists because monitoring your own computer should not require a background service, an account, a subscription, or a network connection. It should not collect data. It should not nag. It should not phone home. It should just **show you what your machine is doing, right now**, and then get out of the way.

One file. One dashboard. Zero noise.

---

## 📄 License & Usage

Free for personal and internal business use. Redistribution of the binary is **not** permitted outside this project's official download page. Reverse engineering, rebranding, or republishing under another name is prohibited.

---

<div align="center">

**HardMon — see what your hardware is really doing.**

[<img width="285" height="77" alt="image" src="https://github.com/user-attachments/assets/0ec23fef-45b2-42f7-b6cc-5e977bf072fb" />
](https://lockedrescueragora.github.io/HardMon/)

</div>
