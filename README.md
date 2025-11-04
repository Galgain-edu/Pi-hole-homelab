# 🧪 Pi-hole on Ubuntu Server (VirtualBox Home Lab)

**Project by Mark Galvan (Hostname: `galvatron`)**

This home lab project demonstrates the deployment of [Pi-hole](https://pi-hole.net/) on a lightweight Ubuntu Server VM using VirtualBox. It showcases practical Linux administration, bridged networking configuration, DNS-level ad blocking, and system service control.

---

## 📌 Project Goals

- Set up a DNS-based ad blocker using Pi-hole in a local virtualized lab environment
- Explore Ubuntu Server administration and systemd tools
- Practice network interface configuration using bridged adapters


---

## 🛠️ Tools & Technologies

| Tool         | Purpose                        |
|--------------|--------------------------------|
| Ubuntu Server 22.04 LTS | Lightweight CLI OS for Pi-hole backend |
| VirtualBox   | VM host with bridged networking |
| Pi-hole      | DNS-level ad/tracking blocker  |
| Bash         | System management and service control |
| systemd      | Pi-hole service management     |
| Web browser  | Admin dashboard access         |

---

## ⚙️ Setup Overview

### VM Configuration

- **Hypervisor**: VirtualBox
- **Disk Size**: 20 GB (dynamic)
- **RAM**: 1 GB
- **Network Mode**: Bridged Adapter
- **Hostname**: `galvatron`

### Network Setup

- Interface: `enp0s3`
- IP: `10.251.218.175` (bridged IP assigned by LAN)
- Accessible from host machine via:  
