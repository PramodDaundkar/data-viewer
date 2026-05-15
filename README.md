# Data Viewer

A unified, browser-based viewer for **Parquet** and **CSV** files. Drop any file — the app auto-detects the format and uses the right engine.

## Supported formats
- `.parquet` / `.parq`
- `.csv` / `.tsv` / `.txt`

## Features
- **Auto-detects file type** from extension
- **DuckDB WASM engine** for large files (lazy reads, no full file in RAM)
  - Parquet: switches at > 100K rows
  - CSV: switches at > 5 MB
- Virtual scrolling — handles millions of rows smoothly
- Per-column filtering, global search, sort, drag-to-resize columns
- Toggle column visibility
- SQL query editor with autocomplete (Ctrl+Enter to run)
- CSV options: delimiter override, header row toggle
- All processing is local — no data leaves your browser

## Live URL
👉 https://pramoddaundkar.github.io/data-viewer/

## Previous standalone viewers
- [parquet-viewer](https://github.com/PramodDaundkar/parquet-viewer) — superseded by this repo
- [csv-viewer](https://github.com/PramodDaundkar/csv-viewer) — superseded by this repo
