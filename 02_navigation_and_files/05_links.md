# Links

Linux supports two types of links:

- **Hard Link**
- **Symbolic (Soft) Link**

## Symbolic Link

A symbolic link is a shortcut/reference to another file or directory.

Create one:

```bash
ln -s original.txt shortcut.txt
```

Check the link:

```bash
ls -l
```

Example:

```text
shortcut.txt -> original.txt
```

## Hard Link

A hard link points directly to the same file data.

Create one:

```bash
ln original.txt hardlink.txt
```

## Difference

| Hard Link | Symbolic Link |
|---|---|
| Points to the file's data | Points to the file path |
| Usually cannot link directories | Can link directories |
| Still works if original name is removed | Breaks if target is removed |

## Example

```bash
touch original.txt

ln -s original.txt softlink.txt
ln original.txt hardlink.txt

ls -li
```

`ls -li` shows the inode number, which helps understand how hard links work.

## Next

➡️ Continue to **06_wildcards.md**
```