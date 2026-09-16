# cut and paste

These commands are used to extract and combine text from files.

## `cut`

Extracts specific columns or characters from a file.

Extract the first 5 characters:

```bash
cut -c 1-5 file.txt
```

Extract the first column separated by commas:

```bash
cut -d ',' -f 1 data.csv
```

- `-d` → Delimiter
- `-f` → Field (column)
- `-c` → Characters

---

## `paste`

Combines lines from multiple files side by side.

```bash
paste file1.txt file2.txt
```

Use a delimiter:

```bash
paste -d ',' file1.txt file2.txt
```

---

## Quick Reference

| Command | Purpose |
|---|---|
| `cut -c` | Extract characters |
| `cut -d` | Set delimiter |
| `cut -f` | Extract fields |
| `paste` | Combine files side by side |
| `paste -d` | Set delimiter |

## Next

➡️ Continue to **05_grep.md**