# awk

`awk` is a Linux command used to **extract, filter, and process text column by column**.

## 1. Print a Specific Column

`$1` represents the first column, `$2` the second column, and so on.

```bash
awk '{print $1}' file.txt
```

Prints the first column of each line.

## 2. Print Multiple Columns

```bash
awk '{print $1, $2}' file.txt
```

Prints the first and second columns.

## 3. Example

Suppose `students.txt` contains:

```text
Kanishka 85
Rahul 90
Arun 78
```

Command:

```bash
awk '{print $1}' students.txt
```

Output:

```text
Kanishka
Rahul
Arun
```

## 4. Use a Custom Delimiter

For comma-separated data:

```text
Kanishka,85
Rahul,90
Arun,78
```

Command:

```bash
awk -F ',' '{print $1}' students.csv
```

Output:

```text
Kanishka
Rahul
Arun
```

`-F ','` tells `awk` to use a comma as the column separator.

## 5. Filter Using a Condition

Print students whose marks are greater than 80:

```bash
awk '$2 > 80 {print $1, $2}' students.txt
```

Output:

```text
Kanishka 85
Rahul 90
```

## 6. Print Line Numbers

```bash
awk '{print NR, $0}' file.txt
```

- `NR` — current line number.
- `$0` — the entire line.

## Quick Reference

| Command | Purpose |
|---|---|
| `awk '{print $1}' file` | Print first column |
| `awk '{print $1, $2}' file` | Print first two columns |
| `awk -F ','` | Use comma as delimiter |
| `awk '$2 > 80' file` | Filter using a condition |
| `awk '{print NR, $0}' file` | Print line numbers and lines |

## Next

➡️ Continue to **`05_package_management/01_apt.md`**