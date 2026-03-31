# home-lab-setup
Today I adjusted several settings on my TP‑Link router to improve the security, privacy, and performance of my home network.

# Home Network Configuration – TP-Link HX510

This document records all network configuration changes I made to improve speed, privacy, and security on the TP-Link HS510 router and connected devices.

---

##  DNS Configuration

### **Router DNS (Cloudflare)**
- Primary DNS: **1.1.1.1**
- Secondary DNS: **1.0.0.1**

### **Browser DNS (Opera GX)**
- Secure DNS (DNS-over-HTTPS): **Enabled**
- Provider: **Cloudflare**

### **DNS Consolidation**
Both router and browser now use Cloudflare for:
- Faster resolution
- Better privacy
- Higher reliability

##  Wireless Security Settings

### **WPA3**
- **Enabled**
- Strongest Wi-Fi encryption available

### **WPS**
- **Disabled**
- Prevents brute-force PIN attacks

---

##  Guest Network Segmentation

### **Guest Network**
- **Enabled**

### **Guest Access Controls**
- Allow Guests to Access Local Network: **OFF**
- Allow Guests to Access Each Other: **OFF**

This isolates guest devices and IoT devices from the main network and from each other.

---

##  Advanced Wireless Settings

| Setting | Status | Notes |
|--------|--------|-------|
| WMM | **ON** | Required for stable Wi-Fi performance |
| Short GI | **ON** | Small speed boost |
| Fast Roaming (802.11r) | **OFF** | Only useful with multiple access points |


