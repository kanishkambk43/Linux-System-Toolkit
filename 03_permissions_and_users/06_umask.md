# umask

`umask` controls the **default permissions** given to newly created files and directories.

## Check Current umask

```bash
umask
```

Example:

```text
0022
```

## How It Works

Linux starts with default permissions:

```text
Files       → 666
Directories → 777
```

The `umask` value is subtracted from these defaults.

For `umask 022`:

```text
File:       666 - 022 → 644
Directory:  777 - 022 → 755
```

So newly created files usually get:

```text
-rw-r--r--
```

And directories:

```text
drwxr-xr-x
```

## Change umask

```bash
umask 027
```

This changes the default permissions for the current shell session.

## Example

```bash
umask 022

touch file.txt
mkdir folder

ls -l
```

## Quick Reference

| Command | Purpose |
|---|---|
| `umask` | Show current umask |
| `umask 022` | Set umask |
| `666` | Default file permissions |
| `777` | Default directory permissions 

