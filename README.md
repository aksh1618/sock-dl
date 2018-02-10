# sock-dl

## Features

- Downloads file from a link using socket connection.
- Takes url as required argument in command line and destination path an optional argument.
- Shows success message on completion, including download size, time and speed.
- Records logs in `download.log` created in the script directory.

## Usage

```
./sock-dl.py https://link-to-file.ext [path/to/download/destination]
```

## Example

```
user@machine:~$ ./sock-dl.py https://www.cca.edu/sites/default/files/pdf/08/word-to-pdf.pdf ~/Downloads
Finished Downloading word-to-pdf.pdf: Downloaded 125.76 kB in 1.33 s at 94.51 kB/s
```

This project was created as a part of [Project Omega](https://github.com/aksh1618/project-omega).