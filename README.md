# 🦊 Firefox for Ubuntu RISC-V (DC-ROMA, etc.)

This repository provides a **precompiled Firefox `.deb` package for RISC-V architecture**, designed for use on Ubuntu RISC-V systems like the **DC-ROMA RISC-V Laptop**.

Due to GitHub's file size limitations, the `.deb` file is hosted on **Google Drive**, and the APT metadata is hosted here.

---

## 📦 What’s Included

- Firefox `.deb` package for `riscv64`
- APT metadata (`Packages.gz`) to allow installation via `apt`
- Manual download and install instructions
- Google Drive-hosted `.deb` (3.3 GB)

---

## 🔧 Requirements

- Ubuntu 22.04+ (RISC-V)
- Internet connection
- `apt`, `dpkg`, `wget`, and optionally `gzip`

---

## 🛰️ Installation (via APT repository)

You can install the package directly using `apt` by adding this repo:

```bash
echo "deb [trusted=yes] https://faahmed123.github.io/firefox-nightly-riscv64 binary/" | sudo tee /etc/apt/sources.list.d/firefox-riscv64.list
sudo apt update
sudo apt install firefox-riscv64
