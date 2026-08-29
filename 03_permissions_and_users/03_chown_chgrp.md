# chown and chgrp

These commands are used to change the **owner** and **group** of files and directories.

## `chown`

Changes the owner of a file.

```bash
sudo chown user file.txt
```

Change both owner and group:

```bash
sudo chown user:group file.txt
```

Change ownership of a directory and its contents:

```bash
sudo chown -R user:group myfolder
```

---

## `chgrp`

Changes the group of a file.

```bash
sudo chgrp group file.txt
```

For a directory:

```bash
sudo chgrp -R group myfolder
```

---

## Check Owner and Group

```bash
ls -l
```

Example:

```text
-rw-r--r--  user  developers  file.txt
```

Here:

```text
user        → Owner
developers  → Group
file.txt    → File
```

## Quick Reference

| Command | Purpose |
|---|---|
| `chown` | Change owner |
| `chgrp` | Change group |
| `chown user:group` | Change owner and group |
| `-R` | Apply recursively |

