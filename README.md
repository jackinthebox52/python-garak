# python-garak
Arch Linux packaging for [Garak](https://github.com/NVIDIA/garak), the LLM vulnerability scanner.

**Current Version:** 0.15.1

### Packaging Architecture
This package ships as a self-contained Python virtual environment to cleanly isolate Garak's extensive dependency tree from your system Python environment.

The software lives in `/opt/python-garak/`, with a symlink at `/usr/bin/garak` so the tool is available globally from your terminal like any native application.
