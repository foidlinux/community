# FOID Community Repository

## Rules
- POSIX shell `build` scripts only
- musl libc compatible (no glibc-specific stuff)
- No systemd dependencies
- One directory per package
- Directory name = package name

## Directory structure
pkgname/
├── build        # required, POSIX shell
├── version      # required, format: X.Y-Z
├── depends      # optional, one dep per line
├── sources      # optional, URLs to download
└── description  # optional, one line
## Submitting
1. Fork this repo
2. Add your package directory
3. Open Pull Request
4. Wait for review
