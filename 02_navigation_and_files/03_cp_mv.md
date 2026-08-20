# cp and mv

These commands are used to copy, move, and rename files and directories.

## `cp`

Copies a file.

```bash
cp file.txt backup.txt
```

Copy a file into a directory:

```bash
cp file.txt Documents/
```

Copy a directory and its contents:

```bash
cp -r project backup/
```

---

## `mv`

Moves a file:

```bash
mv file.txt Documents/
```

Rename a file:

```bash
mv old.txt new.txt
```

Rename a directory:

```bash
mv old_folder new_folder
```

Move and rename at the same time:

```bash
mv file.txt Documents/new.txt
```

---

## Example

```bash
touch notes.txt

cp notes.txt backup.txt

mv backup.txt Documents/

mv notes.txt linux_notes.txt
```

## Quick Reference

| Command | Purpose |
|---|---|
| `cp` | Copy files |
| `cp -r` | Copy directories |
| `mv` | Move files/directories |
| `mv` | Rename files/directories |

