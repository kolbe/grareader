# grareader
Convert Galera's GRA\_* files to human readable output

# Install

Get the file and put it into the executable path:

```bash
git clone https://github.com/ashraf-s9s/grareader
cp grareader/grareader /usr/bin
```

# Usage:

For MySQL/PXC 5.6 & MariaDB 10.x:

```bash
grareader GRA_5_1992992.log
```

For MySQL/PXC/MariaDB 5.5:

```bash
grareader GRA_5_1992992.log 5.5
```
