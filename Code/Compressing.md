# Bash Commands for File Compression

## Compressing Files

### Using `gzip`

Compress a single file:
```bash
gzip filename.txt
```

Compress multiple files:
```bash
gzip file1.txt file2.txt file3.txt
```

### Using `bzip2`

Compress a single file:
```bash
bzip2 filename.txt
```

Compress multiple files:
```bash
bzip2 file1.txt file2.txt file3.txt
```

### Using `zip`

Compress a single file:
```bash
zip archive.zip filename.txt
```

Compress multiple files:
```bash
zip archive.zip file1.txt file2.txt file3.txt
```

Compress a directory:
```bash
zip -r archive.zip directory_name
```

## Decompressing Files

### Using `gunzip`

Decompress a single file:
```bash
gunzip filename.txt.gz
```

### Using `bunzip2`

Decompress a single file:
```bash
bunzip2 filename.txt.bz2
```

### Using `unzip`

Decompress a single file or archive:
```bash
unzip archive.zip
```

## Creating and Extracting Tarballs

### Creating a tarball

Create a compressed tarball using `gzip`:
```bash
tar -czvf archive.tar.gz directory_name
```

Create a compressed tarball using `bzip2`:
```bash
tar -cjvf archive.tar.bz2 directory_name
```

### Extracting a tarball

Extract a `gzip` compressed tarball:
```bash
tar -xzvf archive.tar.gz
```

Extract a `bzip2` compressed tarball:
```bash
tar -xjvf archive.tar.bz2
```
