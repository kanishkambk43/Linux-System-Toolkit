# WSL Setup

## What is WSL?

**Windows Subsystem for Linux (WSL)** allows you to run a Linux environment directly on Windows without using a virtual machine or dual boot.

---

## Check WSL Version

```powershell
wsl --status
```

---

## List Installed Distributions

```powershell
wsl --list --verbose
```

or

```powershell
wsl -l -v
```
OUTPUT:

  NAME            STATE           VERSION
* Ubuntu-24.04    Running         2
  Debian          Stopped         2
  Kali-Linux      Stopped         2
---

## Start Ubuntu

```powershell
wsl
```

or

```powershell
ubuntu
```

---

## Shutdown WSL

```powershell
wsl --shutdown
```

---

## Update WSL

```powershell
wsl --update
```

---

## Set Default Distribution

```powershell
wsl --set-default Ubuntu-24.04 ->>> SETS UBUNTU AS A DEFAULT LINUX DISTRIBUTION
```

---

## Check Linux Version

```bash
uname -a
```

---

## Exit Ubuntu

```bash
exit
```

---



