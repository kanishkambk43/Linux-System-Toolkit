# wc, sort, and uniq

These commands are useful for **counting, sorting, and removing duplicate lines**.

## `wc`

Counts lines, words, and characters.

```bash
wc file.txt
```

Count only lines:

```bash
wc -l file.txt
```

Count only words:

```bash
wc -w file.txt
```

Count only characters:

```bash
wc -m file.txt
```

---

## `sort`

Sorts lines alphabetically.

```bash
sort file.txt
```

Sort in reverse order:

```bash
sort -r file.txt
```

Sort numbers correctly:

```bash
sort -n numbers.txt
```

---

## `uniq`

Removes **consecutive duplicate lines**.

```bash
uniq file.txt
```

To remove all duplicates, sort first:

```bash
sort file.txt | uniq
```

Count occurrences:

```bash
sort file.txt | uniq -c
```

---

## Quick Reference

| Command | Purpose |
|---|---|
| `wc -l` | Count lines |
| `wc -w` | Count words |
| `wc -m` | Count characters |
| `sort` | Sort lines |
| `sort -r` | Reverse sort |
| `sort -n` | Numeric sort |
| `uniq` | Remove consecutive duplicates |
| `uniq -c` | Count duplicates |

## Next

➡️ Continue to **04_cut_paste.md**