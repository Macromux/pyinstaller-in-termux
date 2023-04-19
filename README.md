# pyinstaller-in-termux

This repo talks and covers the issues with PyInstaller in termux.
 . . . . . . . . . . 

**Error When Installing Pyinstaller in Termux:**

   ```ERROR: Command errored out with exit status 1:
   command: /data/data/com.termux/files/usr/bin/python3 /data/data/com.termux/files/usr/lib/python3.10/site-packages/pip/_vendor/pep517/in_process/_in_process.py build_wheel /data/data/com.termux/files/usr/tmp/tmp3w5vqddw
       cwd: /data/data/com.termux/files/usr/tmp/pip-install-9ehmgwym/pyinstaller_396dd277de2f49098f7e5863a15c8bdf
  Complete output (29 lines):
  running bdist_wheel
  running build
  running build_bootloader
  No precompiled bootloader found. Trying to compile it for you ...
  Setting top to                           : /data/data/com.termux/files/usr/tmp/pip-install-9ehmgwym/pyinstaller_396dd277de2f49098f7e5863a15c8bdf/bootloader
  Setting out to                           : /data/data/com.termux/files/usr/tmp/pip-install-9ehmgwym/pyinstaller_396dd277de2f49098f7e5863a15c8bdf/bootloader/build
  Python Version                           : 3.10.1 (main, Dec  9 2021, 15:28:13) [Clang 12.0.8 (https://android.googlesource.com/toolchain/llvm-project c935d99d7
  Checking for 'gcc' (C compiler)          : not found
  Checking for 'clang' (C compiler)        : /data/data/com.termux/files/usr/bin/clang
  Checking size of pointer                 : 8
  Platform                                 : Linux-64bit-arm detected based on compiler
  Checking for compiler flags -m64         : yes
  Checking for linker flags -m64           : yes
  Checking for library dl                  : yes
  Checking for library pthread             : yes
  Checking for library m                   : yes
  Checking for library z                   : yes
  Checking for library cmocka              : not found
  Checking for function unsetenv           : yes
  Checking for function mkdtemp            : yes
  Checking for function dirname            : yes
  Checking for function basename           : yes
  Checking for function strndup            : yes
  Checking for function strnlen            : yes
  Checking for compiler flags -Wl,--as-needed : yes
  Checking for program 'strip'                : not found
  Could not find the program ['strip']
  (complete log in /data/data/com.termux/files/usr/tmp/pip-install-9ehmgwym/pyinstaller_396dd277de2f49098f7e5863a15c8bdf/bootloader/build/config.log)
  ERROR: Failed compiling the bootloader. Please compile manually and rerun setup.py
  ----------------------------------------
  ERROR: Failed building wheel for pyinstaller
Failed to build pyinstaller
ERROR: Could not build wheels for pyinstaller, which is required to install pyproject.toml-based projects
```
#### Hello
