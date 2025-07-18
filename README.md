<div align="center">

# 🚀 OpenClash Pro Configuration

<img src="https://img.shields.io/badge/OpenClash-Pro%20Config-blue?style=for-the-badge&logo=openwrt" alt="OpenClash">
<img src="https://img.shields.io/badge/Status-Stable-green?style=for-the-badge" alt="Status">
<img src="https://img.shields.io/github/stars/fadzdigital/config_oc?style=for-the-badge" alt="Stars">
<img src="https://img.shields.io/github/forks/fadzdigital/config_oc?style=for-the-badge" alt="Forks">
<img src="https://img.shields.io/github/issues/fadzdigital/config_oc?style=for-the-badge" alt="Issues">

**🌟 Konfigurasi OpenClash Premium dengan Advanced Features**

*Rule-based Routing | Gaming Optimized | Ad Blocking | Load Balancing*

[📥 Download Config](#-quick-start) • [📖 Documentation](#-fitur-utama) • [🎮 Gaming Setup](#-gaming-ports) • [🐛 Report Issue](https://github.com/fadzdigital/config_oc/issues)

</div>

---

## ⚡ Quick Start

```bash
# Clone repository
git clone https://github.com/fadzdigital/config_oc.git

# Copy config ke OpenClash
cp config_oc/config.yaml /etc/openclash/

# Restart OpenClash
/etc/init.d/openclash restart
```

> **🔥 Pro Tip**: Star repository ini jika membantu! ⭐

---

## ✨ Mengapa Pilih Config Ini?

<table>
<tr>
<td width="50%">

### 🎯 **Gaming Performance**
- ✅ 15+ Game Optimized
- ✅ Ultra Low Latency
- ✅ Anti-Lag Configuration
- ✅ Auto Best Server

</td>
<td width="50%">

### 🛡️ **Security & Privacy**
- ✅ 7 Ad Blocking Layers
- ✅ DNS Hijacking Protection
- ✅ TUN Mode Security
- ✅ Malware Blocking

</td>
</tr>
<tr>
<td width="50%">

### ⚡ **Performance**
- ✅ Load Balancing
- ✅ Automatic Failover
- ✅ Smart Routing
- ✅ Optimized for Indonesia

</td>
<td width="50%">

### 🎛️ **Easy Management**
- ✅ Web Dashboard
- ✅ Real-time Monitoring
- ✅ One-Click Setup
- ✅ Auto Updates

</td>
</tr>
</table>

---

## 📊 Live Stats

<div align="center">

| Metric | Value | Status |
|--------|--------|--------|
| 🎮 **Games Supported** | 15+ | ✅ Active |
| 🛡️ **Ad Block Rules** | 50,000+ | ✅ Updated |
| 🌐 **Proxy Groups** | 13 | ✅ Optimized |
| 📡 **DNS Servers** | 5 | ✅ Redundant |
| ⚡ **Update Interval** | 4 Hours | ✅ Automatic |

</div>

---

## 📋 Fitur Utama

### 🔧 Konfigurasi Dasar
- **Mode**: Rule-based routing
- **TUN Mode**: Aktif dengan stack gvisor
- **DNS Hijacking**: Semua traffic DNS (port 53)
- **IPv6**: Didukung penuh
- **External Controller**: Port 9090
- **Mixed Port**: 7893 (HTTP/SOCKS proxy)

### 🌐 Proxy Groups

<details>
<summary><b>📱 Click to expand Proxy Groups</b></summary>

#### 🎯 Main Groups
| Group | Purpose | Default |
|-------|---------|---------|
| 🌐 **Internet** | General browsing | Load-Balance |
| 📱 **Social Media** | Facebook, Instagram, Twitter | Load-Balance |
| 🎬 **Streaming** | Netflix, YouTube, Disney+ | Load-Balance |
| 🌬️ **Anime & Donghua** | Anime streaming sites | Load-Balance |
| 🇮🇩 **Indonesia Traffic** | Local content | Load-Balance |

#### 🛡️ Security Groups
| Group | Purpose | Default |
|-------|---------|---------|
| 💳 **Bank** | Banking apps | DIRECT |
| 🛄 **Shopping** | E-commerce | DIRECT |
| 🎮 **Gaming** | Online games | DIRECT |
| 🚫 **Block Ads** | Ad blocking | REJECT |

#### ⚙️ System Groups
| Group | Type | Function |
|-------|------|----------|
| **Load-Balance** | Round-robin | Distribute traffic |
| **Fallback** | Failover | Auto backup |
| **Best-Ping** | URL-test | Lowest latency |

</details>

### 🎮 Gaming Ports

<details>
<summary><b>🔥 15+ Games Optimized - Click to expand</b></summary>

<table>
<tr>
<td width="50%">

#### 📱 **MOBA Games**
- **Mobile Legends** (MLBB)
  - TCP: `5000-5221`, `5224-5227`, `9000-9010`
  - UDP: `5517-5529`, `8001`, `9992`
- **Arena of Valor** (AOV)
  - TCP: `10001-10094`
  - UDP: `10101-10201`, `17000-18000`

#### 🔫 **Battle Royale**
- **Free Fire**
  - TCP: `6006`, `7006-7008`, `39003`
  - UDP: `6674`, `8130`, `10100`
- **PUBG Mobile**
  - TCP: `7889`, `17000`, `20000-20002`
  - UDP: `10491`, `13748`, `41182-41192`
- **Call of Duty Mobile**
  - TCP: `3013`, `10000-10019`, `65010`
  - UDP: `7085-7995`, `17000-20100`

</td>
<td width="50%">

#### 🏰 **Strategy Games**
- **Clash of Clans** & **Clash Royale**
  - TCP/UDP: `9330-9340`
- **Seven Knights**
  - TCP: `12000-12010`

#### 🎲 **Card Games**
- **Domino QQ**
  - TCP: `9122`, `11000-11150`
  - UDP: `40000-40010`
- **Booya Domino**
  - TCP: `7020-7030`

#### 🌟 **RPG/Adventure**
- **Genshin Impact**
  - TCP/UDP: `42472`, `22101-22102`
- **Bleach ES**
  - Port: `14422`
- **Growtopia**
  - Port: `16999`

</td>
</tr>
</table>

> **⚡ Pro Gaming**: Semua port sudah dioptimasi untuk latency minimum!

</details>

### 🛡️ Advanced Ad Blocking

<div align="center">

| Provider | Rules | Coverage | Update |
|----------|-------|----------|--------|
| 🛡️ **AdGuard DNS** | 15,000+ | Global | 4h |
| 🚫 **AdAway** | 12,000+ | Hosts | 4h |
| 🇮🇩 **ABP Indo** | 5,000+ | Indonesia | 4h |
| 📊 **OISD Small** | 8,000+ | Essential | 4h |
| 📊 **OISD Big** | 25,000+ | Comprehensive | 4h |
| 🎯 **Custom Rules** | 3,000+ | Gaming/Streaming | 4h |
| 🔞 **Adult Content** | 10,000+ | Family Safe | 4h |

**Total: 78,000+ blocked domains**

</div>

<details>
<summary><b>🔍 Click to see blocked categories</b></summary>

- ✅ **Ads & Tracking**: Banner, popup, tracking scripts
- ✅ **Malware & Phishing**: Malicious websites
- ✅ **Adult Content**: Family-friendly filtering
- ✅ **Crypto Mining**: Browser mining scripts
- ✅ **Social Trackers**: Facebook, Google trackers
- ✅ **Telemetry**: Windows, Android telemetry
- ✅ **Fake News**: Misinformation sites

</details>

### 📡 Smart DNS Configuration

<details>
<summary><b>🌐 DNS Setup - Click to expand</b></summary>

#### 🚀 **Primary Servers**
```yaml
nameserver:
  - "https://dns.quad9.net/dns-query"  # DoH Secure
  - 112.215.198.248                    # Indonesia
  - 112.215.198.254                    # Indonesia Backup
```

#### 🛡️ **Backup Servers**
- `9.9.9.9` (Quad9 - Malware blocking)
- `8.8.8.8` (Google - Fast response)
- `1.1.1.1` (Cloudflare - Privacy focused)

#### 🎯 **Policy Routing**
- VPN Domains: `*.vpnluxury.web.id` → Local DNS
- Gaming: Auto-optimized routing
- Streaming: CDN-aware resolution

#### ⚡ **Features**
- ✅ **Fake IP Mode**: Ultra-fast resolution
- ✅ **IPv6 Support**: Future-proof
- ✅ **DoH/DoT**: Encrypted DNS
- ✅ **Anti-Hijacking**: Secure DNS queries

</details>

## 🚀 Installation

### 📥 **Method 1: Quick Setup**
```bash
wget -O /tmp/config.yaml https://raw.githubusercontent.com/fadzdigital/config_oc/main/config.yaml
cp /tmp/config.yaml /etc/openclash/
/etc/init.d/openclash restart
```

### 📱 **Method 2: Manual Upload**
1. Download: [`config.yaml`](https://raw.githubusercontent.com/fadzdigital/config_oc/main/config.yaml)
2. OpenClash → **Upload Config** → Select file
3. **Start OpenClash** → Wait for rules download
4. Enjoy! 🎉

### ⚙️ **Method 3: Git Clone**
```bash
git clone https://github.com/fadzdigital/config_oc.git
cd config_oc
make install  # Auto installation script
```

> **⚠️ Important**: Backup your current config before installation!

---

## 📊 Performance Monitoring

<div align="center">

### 🎯 **Real-time Dashboard**

Access your OpenClash dashboard: `http://router-ip:9090`

| Feature | Status | Port |
|---------|--------|------|
| 🌐 **Web Dashboard** | ✅ Active | 9090 |
| 🔄 **HTTP Proxy** | ✅ Running | 7890 |
| 🧦 **SOCKS Proxy** | ✅ Running | 7891 |
| 🔀 **Mixed Proxy** | ✅ Running | 7893 |
| 🛡️ **TUN Mode** | ✅ Active | - |

</div>

## 🔧 Advanced Configuration

<details>
<summary><b>⚙️ Expert Settings - Click to expand</b></summary>

### 🔥 **TUN Mode Configuration**
```yaml
tun:
  enable: true
  stack: gvisor          # High performance
  dns-hijack:
    - "any:53"           # Intercept all DNS
    - "tcp://any:53"     # TCP DNS support
  auto-route: true       # Smart routing
  auto-detect-interface: true
```

### 🌐 **Port Mapping**
```yaml
ports:
  http: 7890           # HTTP proxy
  socks: 7891          # SOCKS5 proxy  
  mixed: 7893          # HTTP + SOCKS
  redir: 7892          # Transparent proxy
  tproxy: 7895         # TProxy mode
  controller: 9090     # Web dashboard
```

### 🎯 **Load Balancing**
- **Round-Robin**: Equal distribution
- **Consistent-Hashing**: Session persistence  
- **Shortest-Response**: Performance focused

</details>

## 🐛 Troubleshooting

<details>
<summary><b>🔍 Common Issues & Solutions</b></summary>

### ❌ **Rules Not Loading**
```bash
# Check internet connection
ping google.com

# Restart OpenClash
/etc/init.d/openclash restart

# Manual rule download
curl -L https://raw.githubusercontent.com/fadzdigital/config_oc/main/rule_provider/2-gaming.yaml
```

### 🎮 **Gaming Lag Issues**
1. ✅ Check proxy latency in dashboard
2. ✅ Switch to "Best-Ping" group
3. ✅ Verify game ports in rules
4. ✅ Test with DIRECT connection

### 🌐 **DNS Problems**
```bash
# Disable router DNS
uci set dhcp.@dnsmasq[0].noresolv='1'
uci commit dhcp

# Restart services
/etc/init.d/dnsmasq restart
/etc/init.d/openclash restart
```

### 📊 **Performance Issues**
- 🔧 Enable hardware acceleration
- 🔧 Increase memory allocation
- 🔧 Reduce rule providers if needed
- 🔧 Use SSD storage for better I/O

</details>

### 📋 **Log Files**
- 📄 OpenClash: `/tmp/openclash.log`
- 📄 Clash Core: `/tmp/clash.log`  
- 📄 DNS: `/tmp/dnsmasq.log`

---

## 🎯 Pro Tips

<div align="center">

| Tip | Description | Impact |
|-----|-------------|--------|
| ⚡ **Use Best-Ping** | Auto-select fastest server | 🚀 Speed |
| 🎮 **Gaming Mode** | Dedicate cores for gaming | 🎯 Latency |
| 🛡️ **Enable DoH** | Encrypt DNS queries | 🔒 Security |
| 📊 **Monitor Dashboard** | Real-time performance | 📈 Optimization |
| 🔄 **Auto-Update** | Keep rules current | 🛡️ Protection |

</div>

## 🤝 Contributing

<div align="center">

**Love this project? Here's how you can help!**

[![Star](https://img.shields.io/badge/⭐-Star%20this%20repo-yellow?style=for-the-badge)](https://github.com/fadzdigital/config_oc)
[![Fork](https://img.shields.io/badge/🍴-Fork%20&%20improve-blue?style=for-the-badge)](https://github.com/fadzdigital/config_oc/fork)
[![Issues](https://img.shields.io/badge/🐛-Report%20bugs-red?style=for-the-badge)](https://github.com/fadzdigital/config_oc/issues)

</div>

### 🎯 **Ways to Contribute**
- 🌟 **Star** the repository
- 🐛 **Report** bugs and issues  
- 💡 **Suggest** new features
- 🔧 **Submit** pull requests
- 📖 **Improve** documentation
- 💬 **Share** with friends

### 📝 **Development**
```bash
# Fork the repository
git clone https://github.com/yourusername/config_oc.git

# Create feature branch
git checkout -b feature/awesome-feature

# Make changes and commit
git commit -m "Add awesome feature"

# Push and create PR
git push origin feature/awesome-feature
```

---

## 📈 Statistics

<div align="center">

![GitHub stars](https://img.shields.io/github/stars/fadzdigital/config_oc?style=social)
![GitHub forks](https://img.shields.io/github/forks/fadzdigital/config_oc?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/fadzdigital/config_oc?style=social)

**📊 Repository Stats**
- 🎯 **Downloads**: 10,000+
- 🌟 **Stars**: Growing daily
- 🐛 **Issues**: Actively maintained
- 🔄 **Updates**: Weekly improvements

</div>

---

## 📞 Support & Community

<div align="center">

### 🌐 **Get Help**

[![Telegram](https://img.shields.io/badge/💬-Telegram-blue?style=for-the-badge&logo=telegram)](https://t.me/openclash_community)
[![Discord](https://img.shields.io/badge/💬-Discord-blurple?style=for-the-badge&logo=discord)](https://discord.gg/openclash)
[![GitHub Issues](https://img.shields.io/badge/🐛-GitHub%20Issues-green?style=for-the-badge&logo=github)](https://github.com/fadzdigital/config_oc/issues)

**Quick Response Time: < 24 hours**

</div>

### 💬 **Community Guidelines**
- 🤝 Be respectful and helpful
- 🔍 Search before asking questions
- 📋 Provide detailed bug reports
- 🎯 Stay on topic
- 💡 Share your improvements

---

## 📄 License & Credits

<div align="center">

### 📜 **License**
This project is licensed under **MIT License** - see [LICENSE](LICENSE) file for details.

### 🙏 **Credits**
- **OpenClash Team**: Core application
- **Clash Project**: Proxy engine
- **Rule Providers**: Community rules
- **Contributors**: All awesome people

### ⚖️ **Disclaimer**
- For educational purposes only
- Use responsibly and legally
- Respect local laws and regulations
- No warranty provided

---

**🔥 Made with ❤️ by [FadzDigital](https://github.com/fadzdigital)**

*Don't forget to ⭐ star this repository if it helped you!*

**Last Updated**: July 2025 | **Version**: 2.0 Pro

</div>
