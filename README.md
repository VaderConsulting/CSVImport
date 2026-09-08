# CSVImport

VB6 utility that queries site CSV files through the Microsoft Text ODBC driver and ADO. On load it opens a DSN pointed at a local CSV folder (default `C:\temp`), runs a SQL SELECT against `siteinfo#csv` filtered by subnet, and prints subnet / siteloc / siteserver rows. Commented code shows the intended sync from a netlogon sites share before querying.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Project1` (`CSVImport.vbp`) | VB6 | WinForms exe | ADO Text-driver query over site CSV |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `CSVImport.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Microsoft ActiveX Data Objects 2.0 Library
- Microsoft Text Driver (*.txt; *.csv) ODBC

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Old/CSVImport`.
Company names in project files: CSC.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
