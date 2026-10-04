# PS4 Bridge v4.4 — NOVA Next

An unofficial Qt/Python desktop manager for your own GoldHEN-enabled PS4, built for Linux (including Gentoo).

## Features
- PS4 game library using names and sizes read from a **read-only copy** of `app.db`
- Real game icons (`icon0.png`), cinematic artwork (`pic1.png`), Favorites, and game-details view
- FTP file explorer and file transfers
- Optional local-network PS4 discovery, drag-and-drop uploads, connection monitoring, and notification center
- Theme Studio, activity dashboard, plugin marketplace, and PKG tools for legitimate homebrew

## Source availability

This repository currently contains documentation and dependencies only. The `ps4_bridge.py` application source is missing, and no GitHub release has been published here yet. Cloning this repository is not sufficient to run PS4 Bridge.

## Running a complete source bundle (Gentoo/Linux)

The following commands apply only to a source folder that includes `ps4_bridge.py` and its supporting modules and assets:

```bash
python3 -m venv .venv
.venv/bin/python -m pip install -r requirements.txt
.venv/bin/python ps4_bridge.py
```

Enable GoldHEN FTP on your PS4 and enter its IP address and FTP port (commonly `2121`). This app is unofficial and is not affiliated with Sony.

## Notes

Temperature and exact free storage require additional compatible PS4-side services. The GUI and transfers should be verified on your own setup. Don't publicly upload your console's `app.db`, downloaded artwork, logs, or local configuration.
