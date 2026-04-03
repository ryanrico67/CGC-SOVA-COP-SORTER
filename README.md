# ONTEL COP Sorter v6

Browser-based tool for sorting and packaging telecom site documentation into COP ZIP files.

## Supported Project Types
- **CGC / Embedded** — Verizon embedded closeout packages
- **CGC / NSB** — Verizon new build closeout packages
- **SOVA** — SOVA closeout and 48HR packages
- **Photo Only** — Timestamp, resize, and compress photos without sorting

## Features
- Auto-sorts files into correct COP folder structure by filename pattern matching
- Photo timestamping, resizing, and JPEG compression
- Prefix toggle (add prefix or keep original names)
- 48HR COP flat folder generation with optional RFE Mitigation N/A docs
- Invoice PDF merging
- JSA photo-to-PDF compilation
- Duplicate photo detection
- Smart prefix stripping for pre-named files

## Usage
1. Visit the live site or open `index.html` in any browser
2. Select your project type
3. Enter Site Name and FuzeID
4. Upload your files
5. Review sorted results
6. Download your COP ZIP

## Runs 100% in-browser — no server, no uploads, no data leaves your machine.
