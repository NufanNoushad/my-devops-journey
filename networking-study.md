# 📡 Networking Study Notes — Adrian Cantrill Playlist

## 🎓 Section 1: Introduction & OSI Model Overview

This section introduces the **OSI Model** (Open Systems Interconnection) — a conceptual framework used to understand and standardize the functions of a networking system.

The model is divided into **seven layers**, which are grouped into:
- 🔽 **Media Layers** (Layers 1–3): Physical, Data Link, Network
- 🔼 **Host/Upper Layers** (Layers 4–7): Transport, Session, Presentation, Application

---

## 🧱 OSI Layer 1: The Physical Layer

### 📖 Definition:
Layer 1 deals with the **physical transmission of raw binary data** (1s and 0s) over a medium such as copper, fiber optics, or air (wireless).  
It’s the **foundation** of all networking.

---

### 🔌 What Does Layer 1 Handle?

#### 🧵 Transmission Medium:
- **Copper cables** (e.g., Ethernet)
- **Fiber optic cables** (light-based communication)
- **Wireless** (radio waves)

#### ⚡ Electrical/Optical Signaling:
- Converts binary bits into signals:
  - `1` = voltage/light present  
  - `0` = no voltage/light  
- This is **purely about signal transfer**, not meaning or structure

#### 🔧 Connectors & Hardware:
- Ethernet cables (**RJ45**)
- **Network Interface Cards (NICs)**
- Basic hardware devices: **hubs**, **repeaters**

#### 📶 Bit Rate & Signaling:
- Defines **how fast data is transmitted** (e.g., 100 Mbps, 1 Gbps)
- Involves:
  - Timing
  - Modulation (voltage or light variation)

---

### 🧠 Summary:
Layer 1 doesn’t interpret data — it simply **transmits signals** across physical hardware.  
It is a **“dumb” layer**, unaware of what the data means.

---

