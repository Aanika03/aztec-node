# aztec-node
# Aztec Node Setup Guide (alpha-testnet)

This repository contains instructions and tooling to run an Aztec node on the alpha-testnet using Docker or CLI.

## 🖥️ System Requirements

- OS: Linux or macOS
- CPU: 8-core
- RAM: 16 GiB
- Storage: 1 TB SSD
- Network: 25 Mbps upload/download

## 📦 Installation Steps

### 1. Install Docker

#### On Linux:
```bash
sudo apt update && sudo apt install -y docker.io
sudo systemctl enable docker
sudo systemctl start docker
