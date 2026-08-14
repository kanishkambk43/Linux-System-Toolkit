# First Linux Commands

These are some of the basic commands used frequently in Linux.

## File and Directory Commands

```bash
ls              # List files
pwd             # Show current directory
cd Documents    # Change directory
mkdir test      # Create directory
touch file.txt  # Create file
cp file.txt backup.txt   # Copy file
mv file.txt new.txt      # Move/rename file
rm new.txt      # Remove file
rmdir test      # Remove empty directory
```

## Viewing Files

```bash
cat file.txt    # Display file contents
less file.txt   # View file page by page
head file.txt   # Show first lines
tail file.txt   # Show last lines
```

## System Information

```bash
whoami          # Current user
hostname        # System hostname
uname -r        # Kernel version
date            # Current date and time
uptime          # System running time
```

## Getting Help

```bash
man ls          # Manual for a command
ls --help       # Quick help
```

## Example

```bash
mkdir linux
cd linux
touch notes.txt
echo "Linux Basics" > notes.txt
cat notes.txt
```

