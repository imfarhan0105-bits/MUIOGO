# MUIOGO

Modelling User Interface for OG-Core and OSeMOSYS.

## Repository Positioning

This repository is a downstream project and is operationally separate from upstream
`OSeMOSYS/MUIO`.

- Upstream repository: `https://github.com/OSeMOSYS/MUIO`
- Downstream repository (this repo): `https://github.com/EAPD-DRB/MUIOGO`

Contributions to upstream are welcome, but delivery in this repository cannot depend
on upstream timelines, releases, or maintainer availability.

`MUIO-Mac` exists as a separate macOS port effort. A project objective for `MUIOGO`
is to become platform independent so that a separate platform-specific port is no
longer required.

## What this repository contains

- `API/`: Flask backend and run/data endpoints
- `WebAPP/`: frontend UI (served by Flask)
- `WebAPP/DataStorage/`: model inputs, cases, and run outputs
- `docs/`: Sphinx user/model documentation source

## Quick start (local)

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python API/app.py
```

Open: `http://127.0.0.1:5002`

## Canonical project docs

Contributor and governance docs are in-repo and versioned:

- `CONTRIBUTING.md`
- `docs/GSoC-2026.md`
- `docs/ARCHITECTURE.md`
- `docs/DOCS_POLICY.md`
- `.github/ISSUE_TEMPLATE/`
- `.github/pull_request_template.md`

## Wiki usage

The wiki is for high-level background/context only:

- [Project Background and Vision](https://github.com/EAPD-DRB/MUIOGO/wiki/Project-Background-and-Vision)

Process, setup, architecture, scope, and contribution rules must stay in this
repository.

## License

Apache License 2.0 (`LICENSE`).
