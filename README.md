# App Studio — Ultra (fresh Canvas)
This is the single-file HTML IDE + Agent + Terminal UI you edited in canvas.

## How to use
1) Open `index.html` in a modern browser.
2) Click **New File/New Folder** to add files in the in-memory VFS.
3) Use **Run** to render `/index.html` into the Preview.
4) **Download .zip** exports your current VFS to a zip.
5) **Settings** stores preview keys locally (do not use real production secrets).

## Notes
- CodeMirror is used (no web workers) to avoid Monaco worker import issues in sandboxed contexts.
- Terminal is a stub in this build; for a Node sandbox use WebContainer with COOP/COEP or your own remote PTY.
