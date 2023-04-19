This repo covers the issues with PyInstaller in termux.
 . . . . . . . . . . 

##   pyinstaller-in-termux

**Error When Installing Pyinstaller in Termux:**
                 
               --Error Log--
   ```
1.   ERROR: Command errored out with exit status 1:
2.   command: /data/data/com.termux/files/usr/bin/python3 /data/data/com.termux/files/usr/lib/python3.10/site-packages/pip/_vendor/pep517/in_process/_in_process.py build_wheel /data/data/com.termux/files/usr/tmp/tmp3w5vqddw
3.       cwd: /data/data/com.termux/files/usr/tmp/pip-install-9ehmgwym/pyinstaller_396dd277de2f49098f7e5863a15c8bdf
4.  Complete output (29 lines):
5.  running bdist_wheel
6.  running build
7.  running build_bootloader
8.  No precompiled bootloader found. Trying to compile it for you ...
9.  Setting top to                           : /data/data/com.termux/files/usr/tmp/pip-install-9ehmgwym/pyinstaller_396dd277de2f49098f7e5863a15c8bdf/bootloader
10. Setting out to                           : /data/data/com.termux/files/usr/tmp/pip-install-9ehmgwym/pyinstaller_396dd277de2f49098f7e5863a15c8bdf/bootloader/build
11. Python Version                           : 3.10.1 (main, Dec  9 2021, 15:28:13) [Clang 12.0.8 (https://android.googlesource.com/toolchain/llvm-project c935d99d7
12. Checking for 'gcc' (C compiler)          : not found
13. Checking for 'clang' (C compiler)        : /data/data/com.termux/files/usr/bin/clang
14. Checking size of pointer                 : 8
15. Platform                                 : Linux-64bit-arm detected based on compiler
16. Checking for compiler flags -m64         : yes
17. Checking for linker flags -m64           : yes
18. Checking for library dl                  : yes
19. Checking for library pthread             : yes
20. Checking for library m                   : yes
21. Checking for library z                   : yes
22. Checking for library cmocka              : not found
33. Checking for function unsetenv           : yes
34. Checking for function mkdtemp            : yes
35. Checking for function dirname            : yes
36. Checking for function basename           : yes
37. Checking for function strndup            : yes
38. Checking for function strnlen            : yes
39. Checking for compiler flags -Wl,--as-needed : yes
40. Checking for program 'strip'                : not found
41. Could not find the program ['strip']
42. (complete log in /data/data/com.termux/files/usr/tmp/pip-install-9ehmgwym/pyinstaller_396dd277de2f49098f7e5863a15c8bdf/bootloader/build/config.log)
43. ERROR: Failed compiling the bootloader. Please compile manually and rerun setup.py
44. ----------------------------------------
45. ERROR: Failed building wheel for pyinstaller
46. Failed to build pyinstaller
47. ERROR: Could not build wheels for pyinstaller, which is required to install pyproject.toml-based projects
```
#### Requirements:
- -- gcc
- -- clang
- -- python
> ***(Installed)***

### Fixing-Instalation -->







