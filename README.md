# MUIOGO

Modelling User Interface for OG-Core and OSeMOSYS.

Full project background and vision moved to the wiki:
- [Project Background and Vision](https://github.com/EAPD-DRB/MUIOGO/wiki/Project-Background-and-Vision)

## What this repo contains

- `API/`: Flask backend and run/data endpoints
- `WebAPP/`: frontend UI (served by Flask)
- `WebAPP/DataStorage/`: model inputs, cases, and run outputs
- `docs/`: Sphinx documentation source

## Quick start (local)

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python API/app.py
```

Open: `http://127.0.0.1:5002`

## Notes

- The frontend currently calls the local API at `http://127.0.0.1:5002/` from `WebAPP/Classes/Base.Class.js`.
- Model execution uses GLPK and CBC via backend subprocess calls.
- If your environment cannot read UTF-16 requirement files, convert with `iconv` first.

## Documentation

- Project docs source: `docs/source/`
- ReadTheDocs config: `.readthedocs.yml`

## License

Apache License 2.0 (`LICENSE`).
