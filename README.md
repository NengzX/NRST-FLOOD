# 🚀 NRST-FLOOD - High-Performance DDoS Testing Tool

![NRST-FLOOD](https://img.shields.io/badge/Node.js-≥16.0-green?style=flat-square)
![Version](https://img.shields.io/badge/Version-1.0-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-red?style=flat-square)

NRST-FLOOD is a **high-speed** and **efficient** DDoS testing tool designed for **educational and security research purposes only**. This tool can help you analyze the resilience of your servers against stress testing.

⚠️ **Disclaimer:** This tool is for **educational purposes only**. Misuse may violate laws and result in serious consequences.

---

## ✨ Features
- 🔥 **High-speed stress testing** with configurable parameters
- 🌐 **Proxy support** for better anonymity
- 📡 **Multi-threaded attack execution**
- ⚡ **User-friendly and lightweight**

---

## 🛠️ Installation

Make sure you have **Node.js (≥16.0)** installed.

#### 💻 **For Termux (Android)**
```sh
pkg update && pkg upgrade -y
pkg install nodejs -y
node -v   # Verify installation
```

### 1️⃣ Clone the repository
```sh
git clone https://github.com/yourusername/NRST-FLOOD.git
cd NRST-FLOOD
npm install net http2 tls cluster url path crypto user-agents fs axios https

```

## BASIC EXAMPLE USE 
```sh
node NRST-FLOOD.js <target_url> <duration> <rate> <threads> <proxy_file>
```
## EXAMPLE
```sh
node NRST-FLOOD.js https://example.com 120 32 8 proxy.txt
```
📜 License
This project is licensed under the MIT License.

⚠️ Disclaimer
The developer is NOT responsible for any misuse of this tool. This script is intended for educational purposes and server security testing only. DO NOT use it on systems without permission.
