# pwd, ls, and cd

These commands are used to navigate through the Linux file system.

## `pwd`

Shows the current working directory.

```bash
pwd
```

Example:

```text
/home/kanishka
```

---

## `ls`

Lists files and directories.

```bash
ls
```

Useful options:

```bash
ls -l      # Detailed information
ls -a      # Show hidden files
ls -lh     # Human-readable sizes
ls -la     # Detailed list including hidden files
```

---

## `cd`

Changes the current directory.

```bash
cd Documents
```

Go to the parent directory:

```bash
cd ..
```

Go to the home directory:

```bash
cd ~
```

Go to the root directory:

```bash
cd /
```

---

## Example

```bash
pwd
ls
cd Documents
pwd
cd ..
pwd
```

## Quick Reference

| Command | Purpose |
|---|---|
| `pwd` | Show current directory |
| `ls` | List files |
| `cd` | Change directory |
| `cd ..` | Go to parent directory |
| `cd ~` | Go to home directory |
| `cd /` | Go to root directory |

