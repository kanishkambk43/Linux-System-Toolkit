# Ubuntu Installation

## What is Ubuntu?

Ubuntu is a free, open-source Linux distribution based on Debian. It is widely used for software development, DevOps, cloud computing, and servers.

---

## Installation Methods

- **WSL (Windows Subsystem for Linux)** ⭐ Recommended for Windows users
- **Dual Boot** – Install Ubuntu alongside Windows
- **Virtual Machine** – Run Ubuntu inside software like VirtualBox or VMware
- **Dedicated Installation** – Use Ubuntu as the primary operating system

---

## Install Ubuntu using WSL

1. Open **PowerShell** as Administrator.
2. List available distributions:

```powershell
wsl --list --online
```

3. Install Ubuntu:

```powershell
wsl --install Ubuntu-24.04
```

4. Restart your computer if prompted.
5. Launch Ubuntu and create a username and password.

---

## Verify Installation

Check the Ubuntu version:

```bash
lsb_release -a
```

Check the kernel version:

```bash
uname -r
```

---

## Update Ubuntu

Update package information:

```bash
sudo apt update
```

Upgrade installed packages:

```bash
sudo apt upgrade -y
```

---



