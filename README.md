# Documentation
Parts list and specifications for my desktop PC
# 🖥️ Desktop PC Parts

This repository contains the hardware specifications and components for my desktop PC build.

---

## 🔧 System Overview


- **Build Type:** Desktop

- **Primary Use:** ( Workstation / General Use)

- **Operating System:** (Windows 10)

---

## 🧠 Core Components


| Components

|---------|-------|

| CPU |ryzen 5 5600x |

| Motherboard |MSI Motherboard B450M BAZOOKA LGA1151  |

| RAM |16G |

| GPU |NVIDIA GeForce RTX3050 |

| Storage (SSD/HDD) | WD SSD 500G|

| Power Supply | Corsair 80plus bronze |


---

## 🖥️ ports


Motherboard | 3 usb 3.0 slots 1 HDMI 2.1 and 1 ethernet port



GPU  | 1 HDMI 2.1 slot and 2 Native Displayport 1.4a



CASE| 2 USB 3.0 and AUX 3.5M
---

## 🌡️ Performance Notes


- Idle Temps:50c

- Load Temps:70c

- Cpu Temp 58c

- Motherboard Temp 42c

---

---

## 📸 Photos


---
| Port / Connector | Location | Purpose | Common Issues |
| --- | --- | --- | --- |
| USB-3.1 |	FRONT |	Data, Power, Video |Wrong cable (non-Thunderbolt) |
| HDMI | BACK OF CASE |	External display | Physical damage |
|DisplayPort | Rear | External Display | "No signal" message by incorrect input |
| Ethernet (RJ-45) |	BACK OF CASE |	Wired networking	| Bent pins / driver issues/ NOT PUSHED IN COMPLETELY|
|RAM Slot |	Internal | Memory expansion	| Improper seating / WRONG SLOT |
| AUX 3.1 |	FRONT | AUDIO INTERNAL AND EXTERNAL SPEAKERS	| NOT PLUGGED IN COMPLETELY |

## HOW TO USE POWERSHELL TO GET THIS INFO

-OS NAME,Version,32/64 bit
```
Get-ComputerInfo
```

-OS CPU INFO
```
GET-CIMINSTANCE WIN32_PROCESSOR
```

--RAM INFO
```
Get-ciminstance WIN32_Physicalmemory
```

--STORAGE
```
GET-PHYSICALDISK
```

--GPU INFO
```
GET-Ciminstance win32_videocontroller
```
