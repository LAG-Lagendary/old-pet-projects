# 🔮 Astrological Ping Tracker & Space Signal Monitor

> *"Fortune-telling via network packets, predicting fate through fiber-optic latency, and absolute pseudo-scientific precision."*

Welcome to the repository where harsh network engineering meets pure astrology. This project is designed for anyone tired of boring speed tests who wants to determine their geographical location (or check remote employees) solely by how fast data packets run to servers around the world.

Inside the repository lie two key instruments for conducting digital magic sessions.

---

## 🛠️ Repository Structure

```text
astrological-ping-tracker/
├── README.md               # Documentation & digital prophecy guide
├── geo_ping_analyzer.py    # Tool #1: Geographical estimation via global ping
├── ping_monitor.py         # Tool #2: Continuous latency & stability monitor
└── start_monitoring.sh     # Helper script for parallel background monitoring
```

---

## 🌐 1. Geo Ping Analyzer (`geo_ping_analyzer.py`)

> *"Show me your ping to Cloudflare, and I'll tell you what digital dot of the world you're in."*

This script measures latency (`RTT`) to dozens of global DNS servers (from North America to Oceania) and delivers a rough regional diagnosis to your ISP using the "high-precision" method of minimum pinging.

### 🚀 Quick Start
```bash
python3 geo_ping_analyzer.py
```

### 📊 Sample Output
```text
🌍 Running the PING geo-analyzer...
Checking 10 global targets. Sending 3 packets to each target.
[✅ OK] Cloudflare_EU: 45.75 ms | Loss: 0.0% (0/3) | Location: Frankfurt/London, Germany/United Kingdom (Europe)

⭐ GEOGRAPHICAL LOCATION ESTIMATION BY PING
================================================================================================
Based on network latency analysis, the CLOSEST point to you is:
-> TARGET: Cloudflare_EU (1.1.1.1)
-> LOCATION: Frankfurt/London Germany/UK (Europe)
-> AVERAGE PING: 45.75 ms
-> LOSS: 0.0%

✅ CONCLUSION:
Your network connection is likely in the same region (or continent) as Frankfurt/London, Germany/UK (Europe). This is confirmed by the very low latency (RTT).
======================================================================================
```

---

## 📡 2. Signal to Space — Fortune-Telling Monitor (`ping_monitor.py`)

> *"Continuous observation of network pain and cosmic interference."*

A tool for long-term monitoring of ping stability. Ideal for checking remote employees or servers for sudden bouts of "jittery" routing.

### 🧭 Physics of the Process
While classical `ping` does not provide GPS coordinates, it calculates the approximate distance to an object using the speed of light in fiber optics (averaging $200,000 \text{ km/s}$):

$$\text{Approximate distance (km)} \approx \frac{\text{RTT (seconds)}}{2} \times 200,000 \text{ km/s}$$

* **20 ms ping to New York?** Either magic, or someone placed a server right next door.
* **120 ms ping?** Standard intercontinental reality (or your ISP routed traffic around half the planet).

### 🚀 Launching Monitoring
To run all targets in parallel in the background, use the provided helper script:
```bash
bash start_monitoring.sh
```

To stop the background processes:
```bash
ps aux | grep ping_monitor.py
# Find the process PID and terminate: kill <PID>
```

---

## ⚙️ Configuration

You can easily customize the list of targets (`TARGETS`), the number of packets sent (`PING_COUNT`), and timeouts right at the beginning of each Python file.

## 📜 License

Distributed under the **"Everything is permitted"** principle. If your internet goes down again, don't complain to the stars—fix it yourself.
