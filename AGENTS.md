# AGENTS.md

## Cursor Cloud specific instructions

This repository is a personal **storywriting / notes** repository, not a software
project. It contains prose and diagram documents only:

- `README.md` — one-line description of the repo's purpose.
- `Leon flies a valkyrie.txt` — a prose story (plain UTF-8 text).
- `Macross Celebre Transdimensional Fleet Comp.excalidraw` — an
  [Excalidraw](https://excalidraw.com) diagram stored as JSON (`"type": "excalidraw"`).

### What this means for setup / dev workflow

- There is **no source code, package manifest, dependency lockfile, build system,
  test suite, linter, or git hook**. There is nothing to install, lint, test, build,
  or run. The startup update script is intentionally a no-op.
- To "run" the content, open the documents in their intended viewers:
  - `.txt` / `.md` — any text editor / Markdown viewer.
  - `.excalidraw` — open or import the file at https://excalidraw.com (or the
    Excalidraw VS Code / Obsidian extension). It is plain JSON, so it can also be
    validated with `python3 -c "import json; json.load(open('<file>'))"`.
- File names contain spaces — always quote paths in shell commands.
- Tasks here are editorial (writing/editing prose, updating the diagram), not code
  changes. There is no application to demonstrate beyond viewing/validating the
  documents.
