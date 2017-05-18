### Find files recursively with a specific extension
```bash
find ./ -type f -name "*.txt"
```

### Find Duplicate Files on Linux
```bash
sudo apt-get install fdupes
```

```bash
fdupes /path/to/folder
```

### Open all files containing a string with gedit
```bash
grep -lir 'string_value' ./ |xargs gedit
```