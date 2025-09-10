# Linux Commands

- [Linux Commands](#linux-commands)
  - [whoami](#whoami)
  - [hostname](#hostname)
  - [pwd](#pwd)
  - [ls (list)](#ls-list)
  - [cd](#cd)
  - [cat](#cat)
  - [wget](#wget)
  - [head](#head)
  - [tail](#tail)
  - [grep](#grep)
  - [file](#file)
  - [sort](#sort)
  - [uniq](#uniq)
  - [strings](#strings)
  - [mkdir](#mkdir)
  - [mv](#mv)
  - [cp](#cp)
  - [touch](#touch)
  - [zip](#zip)
  - [unzip](#unzip)
  - [gzip](#gzip)
  - [gunzip](#gunzip)
  - [bzip2](#bzip2)
  - [tar](#tar)
  - [base64](#base64)
  - [tr](#tr)
  - [xxd](#xxd)
  - [chmod](#chmod)
  - [diff](#diff)
  - [Networking Commands](#networking-commands)
    - [nmap](#nmap)
    - [nc](#nc)
    - [ncat](#ncat)

### whoami

```
whoami
```

This command is used for checking the current user you are working as.

### hostname

```
hostname
```

This command is used for checking the hostname of the System.

### pwd

```
pwd
```

This command is used for checking the current directory you are working in.

### ls (list)

```
ls
```

This command is used for listing all the directories and files in the current directory.

```
ls -a
```

This command is used for listing all the hidden directories and files in the current directory.

```
ls -al
```

This command is used for listing all the hidden directories and files in the current directory. And it gives us the Extra Information like Permissions, User, Group, Size

### cd

```
cd
```

This command is used to jump directories.

```
cd ~
```

This command is used to jump to the root directory.

### cat

```
cat
```

This command is used for viewing the contents of a file.

### wget

```
wget
```

This command is used for downloading the file from the URL or some external source.

### head

```
head
```

This command is used for viewing only the top ten lines of any File.

### tail

```
tail
```

This command is used for viewing only the bottom ten lines of any File.

### grep

```
grep
```

This command is used for getting a line that contains the particular text.

```
grep -A
```

This command is used for getting the trailing lines that contains the particular text.

```
grep -E
```

This command is used for getting the lines that contains the given Regex Expressions.

### file

```
file
```

This command is used for gives the description of the file. Like what type of file it is etc.

### sort

```
sort
```

This command is used for sorting the data in a given file/any text.

### uniq

```
uniq
```

This command is used for getting all the unique text/files.

### strings

```
strings
```

This command is used for converting the contents of the file to string, if the file is in the format other than ASCII text.

### mkdir

```
mkdir
```

This command is used for adding an empty directory.

### mv

```
mv
```

This command is used for moving a file or contents of the file to other folder or file respectively.

### cp

```
cp
```

This command is used for copying a file or contents of the file to other folder or file respectively.

### touch

```
touch
```

This command is used for creating a file.

### zip

```
zip
```

This command is used for compressing the file in 'zip' format.

### unzip

```
unzip
```

This command is used for decompressing the file in 'zip' format.

### gzip

```
gzip
```

This command is used for compressing the file in 'gz' format.

### gunzip

```
gunzip
```

This command is used for decompressing the file in 'gz' format.

### bzip2

```
bzip2
```

This command is used for compressing the file in 'bz2' format.

```
bzip2 -d
```

This command is used for decompressing the file in 'bz2' format.

### tar

```
tar
```

This command is used for compressing the file in 'tar' format.

```
tar -x
```

This command is used for extracting the file in 'tar' format.

### base64

```
base64
```

This command is used for converting the text/file to the base64 encoded format.

```
base64 -d
```

This command is used for decoding the base64 encoded text/file.

### tr

```
tr
```

This command is used to custom encode and decode the text/file. Like ROT13 algorithm.

### xxd

```
xxd
```

This command is used to encode and decode the hex encoded data.

### chmod

```
chmod
```

This command is used to give/remove the permissions to a file/directory.

### diff

```
diff
```

This command is used to see the difference of data between two files.

## Networking Commands

### nmap

```
nmap
```

These commands are the industry standard port scanning tool. It is used to scan the URLs to understand and get more details about the system we are dealing with.

### nc

```
nc
```

This command is used for basic networking scan build by Unix. It creates simple TCP/UDP connections, port scanner, server or client and file transfer.

### ncat

```
ncat
```

This command has some advance networking scan developed by Nmap project. It is more feature rich than `nc`. It supports SSL/TLS encryption, Proxy, Connection brokering, IPv6, Scripting via Ncat options, Active maintenance as part of the Nmap suite.
