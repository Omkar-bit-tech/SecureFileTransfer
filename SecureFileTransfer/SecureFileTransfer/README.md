# Secure File Transfer System (Cleaned Submission)

**Author:** Omkar Kabat

This repository contains the source code and documentation for the Secure File Transfer System implemented in C++ (Windows & Linux).

## Note on provenance
This archive has been cleaned for submission: any local Git metadata and compiled binaries were removed to avoid accidental inclusion of other authors' repository settings.
- Removed `.git/` metadata (if present).
- Removed compiled binaries from `build/` (e.g., `.exe` files).

If any code sections were adapted from external sources or tutorials, those are acknowledged here for academic honesty:
> *Parts of this project were adapted from public learning resources or example projects; code has been modified and integrated by Omkar Kabat. In particular, the original remote URL present in the source was removed from this cleaned package.*

## How to build
### Linux
```bash
g++ server_linux.cpp -o server -std=c++17 -pthread
g++ client_linux.cpp -o client -std=c++17 -pthread
```
### Windows (MinGW)
```bash
g++ server_windows.cpp -o server.exe -std=c++17 -lws2_32 -pthread
g++ client_windows.cpp -o client.exe -std=c++17 -lws2_32 -pthread
```

## Files included
- `server/` - server source for Windows and Linux
- `client/` - client source for Windows and Linux
- `docs/` - contains the final PDF report and screenshots

---
*Prepared for Capstone submission.*
