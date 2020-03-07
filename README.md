# Pack
Pack is yet another package manager for LFS-like Linux distro. Unlike many other package managers, 
Pack is not responsible for checking dependencies, or solving conflicts; the user is in charge.
Pack is only designed to keep a clean list of installed packages, and their version. Enjoy!

# Usage
Usage is stright forward. Package means the downloaded source (.tar file)
```sh 
Pack
add              - adds package to the list
sync             - adds all packages at selected directory.
remove           - removes package from the list
download         - downloads the source from URL given, unzip.
list             - print list of installed packages
count            - print package count
```
