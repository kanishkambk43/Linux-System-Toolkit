# grep

`grep` is used to **search for matching text** inside files.

## 1. Basic Usage

Search for a word in a file:

```bash
grep "error" file.txt #So the output is simply those matching lines
```

## 2. Case-Insensitive Search

Ignores uppercase and lowercase differences:

```bash
grep -i "error" file.txt
```

## 3. Show Line Numbers

Displays the line number of matching text:

```bash
grep -n "error" file.txt
```

## 4. Search Recursively

Search inside all files in a directory:

```bash
grep -r "error" .
```

## 5. Invert Match

Shows lines that **do not contain** the given text:

```bash
grep -v "error" file.txt
```

## 6. Count Matches

Counts the number of matching lines:

```bash
grep -c "error" file.txt
```

## 7. Use grep with Pipes

Search for a process:

```bash
ps aux | grep nginx
```

## Quick Reference

| Command | Purpose |
|---|---|
| `grep "text" file` | Search for text |
| `grep -i` | Ignore case |
| `grep -n` | Show line numbers |
| `grep -r` | Search recursively |
| `grep -v` | Show non-matching lines |
| `grep -c` | Count matching lines |

## Example

```bash
grep -n "python" notes.txt
```

This displays lines containing `python` along with their line numbers.

