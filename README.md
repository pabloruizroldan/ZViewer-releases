# ZViewer

A second viewport for ZBrush. ZViewer shows the model you are sculpting in
another window, updated as you work, without ever touching your ZBrush
camera: as a pure black silhouette or in clay, from up to four angles at once,
with a reference image over it to line the silhouette up against.

**[Download ZViewer 1.0.0](https://github.com/pabloruizroldan/ZViewer-releases/releases/latest)**
— free, for Windows and ZBrush 2025 or later.

## Install

1. Download `ZViewer-1.0.0.zip` from the
   [latest release](https://github.com/pabloruizroldan/ZViewer-releases/releases/latest).
2. Extract it anywhere and double-click **`install.bat`**. It asks for
   administrator rights (the plugin goes into ZBrush's folder under Program
   Files), finds your ZBrush and asks which one to install into.
3. Start ZBrush. The palette is at **ZPlugin > ZViewer**: press
   **Open Viewer**.

Nothing else to install: Node.js comes inside the zip. ZViewer is installed in
`%LOCALAPPDATA%\Programs\ZViewer`, so the extracted folder can be deleted
afterwards.

**Update:** download the new zip and run its `install.bat` the same way. It
replaces the version you have and keeps your settings.

**Uninstall:** Settings > Apps > ZViewer, or `uninstall.bat` in the install
folder. Close ZBrush first.

The full guide — the viewer, stroke sync, keys, troubleshooting — is the
`README.md` inside the zip.

## Report a problem

Open an [issue](https://github.com/pabloruizroldan/ZViewer-releases/issues) with your ZBrush version
and what happened. The logs in `%LOCALAPPDATA%\ZViewer\logs` help.

## License

MIT. See `LICENSE` and `THIRD-PARTY-NOTICES.txt` in the zip.
