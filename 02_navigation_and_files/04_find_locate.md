# find and locate

These commands are used to search for files and directories.

## `find`

Search for a file in a specific directory.

```bash
find . -name "file.txt"
```

Search for a directory:

```bash
find . -type d -name "project"
```

Search for files with a specific extension:

```bash
find . -name "*.txt"
```

Search from the root directory:

```bash
find / -name "file.txt"
```

> ⚠️ Searching `/` may require `sudo` and can take time.

---

## `locate`

Searches for files using a pre-built database.

```bash
locate file.txt
```

Update the database:

```bash
sudo updatedb
```

---

## Difference

| Command | Description |
|---|---|
| `find` | Searches the file system directly |
| `locate` | Searches a file database |
| `find` | More flexible |
| `locate` | Usually faster |

## Example

```bash
mkdir project
touch project/notes.txt

find . -name "notes.txt"
```

## Next

➡️ Continue to **05_links.md**