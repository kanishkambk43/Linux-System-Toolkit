# sudo

`sudo` allows a normal user to run commands with **administrator (root) privileges**.

## Basic Usage

```bash
sudo command
```

Example:

```bash
sudo apt update
```

Here:

```text
sudo → Run with administrator privileges
apt  → Package manager
update → Update package information
```

## Check sudo Access

```bash
sudo -l
```

This shows which commands the current user is allowed to run with `sudo`.

## Open a Root Shell

```bash
sudo -i
```

Exit the root shell:

```bash
exit
```

## Why Use sudo?

Some operations require administrator privileges, such as:

```bash
sudo apt install nginx
sudo systemctl restart nginx
sudo chown user file.txt
```

> ⚠️ Be careful when using `sudo`. Commands run with administrator privileges can modify or delete important system files.

## Quick Reference

| Command | Purpose |
|---|---|
| `sudo command` | Run command as administrator |
| `sudo -l` | Show sudo permissions |
| `sudo -i` | Open root shell |
| `exit` | Exit root shell |
