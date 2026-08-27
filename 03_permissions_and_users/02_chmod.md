# chmod

`chmod` is used to change file and directory permissions.

## Syntax

```bash
chmod permissions file
```

## Numeric Permissions

```text
r = 4
w = 2
x = 1
```

Example:

```bash
chmod 755 script.sh
```

This gives:

```text
Owner  → rwx
Group  → r-x
Others → r-x
```

## Symbolic Permissions

Add execute permission:

```bash
chmod +x script.sh
```

Remove write permission:

```bash
chmod -w file.txt
```

Give the owner execute permission:

```bash
chmod u+x script.sh
```

Give the group write permission:

```bash
chmod g+w file.txt
```

Remove permission from others:

```bash
chmod o-r file.txt
```

## Check Permissions

```bash
ls -l
```

## Example

```bash
touch script.sh

chmod +x script.sh

ls -l script.sh
```

## Quick Reference

| Command | Purpose |
|---|---|
| `chmod 755 file` | Set numeric permissions |
| `chmod +x file` | Add execute permission |
| `chmod u+x file` | Add execute for owner |
| `chmod g+w file` | Add write for group |
| `chmod o-r file` | Remove read from others |

## Next

➡️ Continue to **03_chown_chgrp.md**