# File Permissions

Linux controls who can read, write, or execute a file.

## Permission Types

| Permission | Symbol | Meaning |
|---|---|---|
| Read | `r` | Read the file |
| Write | `w` | Modify the file |
| Execute | `x` | Run the file |

## Permission Groups

Permissions are assigned to three groups:

```text
u → User (owner)
g → Group
o → Others
```

Check permissions:

```bash
ls -l
```

Example:

```text
-rwxr-xr--
```

Breakdown:

```text
- rwx r-x r--
  │   │   │
  │   │   └── Others
  │   └────── Group
  └────────── Owner
```

So:

```text
Owner  → rwx
Group  → r-x
Others → r--
```

## Numeric Permissions

Each permission has a value:

```text
r = 4
w = 2
x = 1
```

For example:

```text
rwx = 4 + 2 + 1 = 7
r-x = 4 + 0 + 1 = 5
r-- = 4 + 0 + 0 = 4
```

Therefore:

```text
754
```

means:

```text
Owner  → rwx
Group  → r-x
Others → r--
```

