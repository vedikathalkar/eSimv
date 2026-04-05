# eSim 2.5 Installation Bug Report on Ubuntu 25.04

## Author: Vedika Thalkar
## Date: April 2026
## Email: vedikathalkar@gmail.com

## Summary
eSim 2.5 does not officially support Ubuntu 25.04.
This report documents 13 bugs found and fixed 
during installation.

## Bugs Fixed
1. Unsupported Ubuntu 25.04 in main installer
2. KiCad 6.0 PPA returns 404
3. libgit2-1.8 unavailable
4. KiCad symbols directory missing
5. Unsupported Ubuntu 25.04 in NGHDL installer
6. install-nghdl-25.04.sh doesn't exist
7. libcanberra-gtk-module removed
8. Unhandled LLVM version 20.1.2
9. pyhdlparser GitHub URL 504 timeout
10. nghdl.zip overwrites edited scripts
11. KiCad library path hardcoded to 6.0
12. Missing install keyword in apt-get xz-utils
13. PyQt5 installed twice

## Result
eSim 2.5 successfully installed and launched 
on Ubuntu 25.04 after applying all fixes!
