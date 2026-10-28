# Usage

## Requirements

- Python 3.12
- Windows 10 or 11 (or the platform listed in the README)

## Install

1. Install Python 3.12 and FFmpeg.
2. Install Relay with pipx install relay-dl.
3. Paste a URL or drop a list into the queue.
4. Pick a preset and a destination folder.
5. Start the queue and let it run.

## Configuration

```text
%APPDATA%\Relay\
├── config.ini
├── profiles\
└── logs\
```

- FFmpeg is required and checked at startup.
- Queue state lives in SQLite and resumes.
- Presets cover 4K, 1080p, MP3, and FLAC.

## Commands

```text
# install
pipx install relay-dl

# download
relay get https://youtu.be/... --preset 4k
relay get urls.txt --audio flac --jobs 4

# library
relay library --verify
```

## Uninstall

Delete the application folder and `%APPDATA%\Relay`. No services, no
drivers, no scheduled tasks are installed.