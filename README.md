# Black Circuit Theme Studio

Free, open-source offline **Windows x64** theme editor for **Ableton Live 10, 11 and 12**, created by Black Circuit.

## Download

Open [Releases](../../releases/latest) and download **Black-Circuit-Theme-Studio-3.0.6-Setup.exe**.
A portable Windows build and the complete source archive are available in the same release.

## Features

- Create, edit and generate color palettes for Live 10, 11 and 12.
- Export version-specific **.ask** themes for Ableton.
- Undo/redo, A/B comparison and editable theme parameters.
- Save editor workspaces as separate .json backups.
- Local operation, with no account, subscription or usage quota.

The editor runs on Windows; no macOS or Linux application build is provided.
Preview colors are approximate: check exported themes in the intended Live version.
This independent project is not an Ableton product or endorsed by Ableton.

## Source and build

Download and extract **Black-Circuit-Theme-Studio-3.0.6-Source.zip** from Releases.
The archive includes the application source, build scripts, lockfile, tests and reference assets.
Run `npm ci` then `npm start` with a suitable Node.js installation.
For the Windows installer, install Inno Setup 6.7+, set `ISCC_PATH` to `ISCC.exe`, then run `npm run build`.
See the source archive's README.md and SIGNING.md for further details.

## License

Original Black Circuit code: **MIT License**, including the original code in the 3.0.6 binaries.
Third-party assets and dependencies retain their own rights; see THIRD-PARTY-NOTICES.md and SOURCES.md.
