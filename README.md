# python-garak

Arch Linux packaging for [Garak](https://github.com/NVIDIA/garak), the LLM vulnerability scanner.

**Current Version:** 0.14.0

### Packaging Architecture
To maintain system stability and bypass a massive web of missing AUR dependencies, this package ships as a self-contained Python virtual environment. 

The software is isolated within `/opt/python-garak/`, and a symlink is provided at `/usr/bin/garak` so the tool can be run globally from your terminal just like a native application.
