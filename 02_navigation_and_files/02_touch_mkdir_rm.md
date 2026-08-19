# touch, mkdir, and rm

These commands are used to create and remove files and directories.

## `touch`

Creates an empty file.

```bash
touch file.txt
```

Create multiple files:

```bash
touch file1.txt file2.txt
```

---

## `mkdir`

Creates a directory.

```bash
mkdir myfolder
```

Create nested directories:

```bash
mkdir -p project/src/components
```

---

## `rm`

Removes files.

```bash
rm file.txt
```

Remove multiple files:

```bash
rm file1.txt file2.txt
```

Remove an empty directory:

```bash
rmdir myfolder
```

Remove a directory and its contents:

```bash
rm -r myfolder
```

> ⚠️ `rm` permanently removes files. Use it carefully.

---

## Example

```bash
mkdir linux
cd linux

touch notes.txt
touch commands.txt

ls

rm commands.txt
ls

cd ..
rm -r linux
```

## Quick Reference

| Command | Purpose |
|---|---|
| `touch` | Create a file |
| `mkdir` | Create a directory |
| `rm` | Remove a file |
| `rmdir` | Remove an empty directory |
| `rm -r` | Remove directory and contents |



