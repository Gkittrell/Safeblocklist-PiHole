# Safeblocklist-PiHole



 
---

# ✅ Overview

This repository contains a **Pi‑hole Safe Mode Blocklist** designed for users who want:
Add the blocklist URL  
In Pi‑hole:
Paste the **Raw GitHub URL** to the `.txt` blocklist file.
Once list is add, head to your terminal and run this command line:
sudo pihole -g


- ✅ Less tracking  
- ✅ Fewer ads  
- ✅ Better privacy  
- ✅ Zero breakage  
- ✅ A simple, maintainable list  

This list is tailored for:
- PC  
- Mobile devices  
- PS4 / game consoles  
- Smart TVs  
- Streaming apps (Hulu, YouTube, Netflix, etc.)

---

# ✅ Blocklist Modes

This repo supports multiple modes:

### 🟢 **Safe Mode (Default)**
- Blocks ads, trackers, telemetry  
- Does NOT break Hulu or YouTube  
- Best for everyday use  

### 🟡 **Aggressive Mode (Coming Soon)**
- Blocks more telemetry  
- May break some app features  

### 🔴 **Nuclear Mode (Coming Soon)**
- Maximum blocking  
- Will break streaming services  
- For advanced users only  

---

# ✅ Installation (Pi‑hole)

### 1. Add the blocklist URL  
In Pi‑hole:

Paste the **Raw GitHub URL** to the `.txt` blocklist file.

### 2. Update Gravity  in CLI pihole -g
Go to:


Pi‑hole will download and apply the list.

---

# ✅ What This Blocklist Does

### ✔ Blocks:
- Major ad networks  
- Cross‑site trackers  
- Mobile app tracking SDKs  
- Behavioral analytics  
- Smart TV tracking  
- General telemetry (Windows, Android, iOS)  
- CNAME‑cloaked trackers  

### ✔ Does *not* block:
- Hulu ad servers  
- YouTube ad endpoints  
- PSN authentication  
- Microsoft/Apple login domains  
- MarkMonitor domain‑management infrastructure  

This ensures **maximum compatibility** with everyday apps and services.


#License

MIT License  
Feel free to fork, modify, and use this list in your own setup.

# ✅ Author

**Blunder**  
Maintainer of the Pi‑hole Safe Mode Blocklist  
Privacy‑focused, stability‑first network configuration

---


