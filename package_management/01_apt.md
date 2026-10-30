# APT (Advanced Package Tool)

`apt` is a package management tool used in Ubuntu and other Debian-based Linux distributions.

It helps you install, update, upgrade, and remove software packages.

## 1. Update Package Lists

Fetches the latest package information from configured repositories.

```bash
sudo apt update
```

## 2. Upgrade Installed Packages

Upgrades installed packages to their latest available versions.

```bash
sudo apt upgrade
```

Automatically confirms the upgrade:

```bash
sudo apt upgrade -y
```

## 3. Install a Package

Installs software on your system.

```bash
sudo apt install git
```

Install multiple packages:

```bash
sudo apt install git curl wget
```

## 4. Remove a Package

Removes installed software but keeps its configuration files.

```bash
sudo apt remove git
```

Remove software along with its configuration files:

```bash
sudo apt purge git
```

## 5. Search for Packages

Searches available packages by name or description.

```bash
apt search python3
```

## 6. Show Package Information

Displays details about a package.

```bash
apt show git
```

## 7. Remove Unused Dependencies

Removes packages that were automatically installed but are no longer required.

```bash
sudo apt autoremove
```

## Quick Reference

| Command | Purpose |
|---|---|
| `sudo apt update` | Update package lists |
| `sudo apt upgrade` | Upgrade installed packages |
| `sudo apt install package` | Install software |
| `sudo apt remove package` | Remove software |
| `sudo apt purge package` | Remove software and configuration |
| `apt search package` | Search for packages |
| `apt show package` | Display package information |
| `sudo apt autoremove` | Remove unused dependencies |

## Important

- `apt update` does not upgrade installed software.
- `apt upgrade` upgrades installed software.
- `sudo` provides administrative privileges for system-level operations.

