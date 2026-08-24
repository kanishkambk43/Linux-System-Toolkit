# Wildcards

Wildcards are special characters used to match multiple files or directories.

## `*`

Matches zero or more characters.

```bash
ls *.txt
```

Lists all `.txt` files.

Example:

```text
notes.txt
commands.txt
linux.txt
```

---

## `?`

Matches exactly one character.

```bash
ls file?.txt
```

Matches:

```text
file1.txt
file2.txt
```

But not:

```text
file10.txt
```

---

## `[]`

Matches one character from the specified set.

```bash
ls file[123].txt
```

Matches:

```text
file1.txt
file2.txt
file3.txt
```

---

## Examples

Copy all `.txt` files:

```bash
cp *.txt backup/
```

Remove all `.log` files:

```bash
rm *.log
```

List files starting with `test`:

```bash
ls test*
```

## Quick Reference

| Wildcard | Meaning |
|---|---|
| `*` | Any number of characters |
| `?` | Exactly one character |
| `[]` | One character from a set |

## Next

➡️ Continue to **03_permissions_and_users/01_file_permissions.md**