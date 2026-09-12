# head and tail

These commands are used to view the beginning or end of a file.

## `head`

Shows the first 10 lines by default.

```bash
head file.txt
```

Show a specific number of lines:

```bash
head -n 5 file.txt
```

---

## `tail`

Shows the last 10 lines by default.

```bash
tail file.txt
```

Show a specific number of lines:

```bash
tail -n 5 file.txt
```

Follow a file as it changes:

```bash
tail -f app.log
```

This is commonly used for **monitoring log files**.

Press `Ctrl + C` to stop.

---

## Quick Reference

| Command | Purpose |
|---|---|
| `head file` | First 10 lines |
| `head -n 5 file` | First 5 lines |
| `tail file` | Last 10 lines |
| `tail -n 5 file` | Last 5 lines |
| `tail -f file` | Follow new content |


```