# Users and Groups

Linux supports multiple users and groups to control access to files and system resources.

## Current User

```bash
whoami
```

## List Users

```bash
cat /etc/passwd
```

## List Groups

```bash
cat /etc/group
```

## Create a User

```bash
sudo adduser username
```

## Delete a User

```bash
sudo deluser username
```

## Create a Group

```bash
sudo groupadd developers
```

## Add User to a Group

```bash
sudo usermod -aG developers username
```

## Check User's Groups

```bash
groups username
```

## Switch User

```bash
su - username
```

## Quick Reference

| Command | Purpose |
|---|---|
| `whoami` | Show current user |
| `adduser` | Create user |
| `deluser` | Delete user |
| `groupadd` | Create group |
| `usermod -aG` | Add user to group |
| `groups` | Show user's groups |
| `su -` | Switch user |

## Next

➡️ Continue to **05_sudo.md**