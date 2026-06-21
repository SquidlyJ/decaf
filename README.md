# DeCaf

DeCaf is a VS Code extension for reading messy support logs faster.

This GitHub repo is a release-only distribution for the DeCaf VSIX package. It does not contain private development logs, test samples, or customer files.

## Download

Download the latest VSIX from this repo:

- `decaf-1.0.vsix`

## Install In VS Code

1. Open VS Code.
2. Open the Extensions view.
3. Select the `...` menu.
4. Choose `Install from VSIX...`.
5. Select `decaf-1.0.vsix`.
6. Reload VS Code if prompted.

## What DeCaf Does

- Detects supported log formats locally.
- Opens a temporary DeCaf view while keeping the original log untouched.
- Adds timeline gap markers for quiet periods and session breaks.
- Applies DeCaf-only color themes for easier scanning.
- Highlights useful log keywords such as failures, successes, retries, and state changes.
- Supports focused time-range views with optional dates.
- Opens a theme preview so you can compare palettes quickly.

## Privacy

DeCaf is local by design:

- No network calls.
- No telemetry or analytics.
- No AI calls.
- No server or cloud processing.
- No bundled sample logs.
- No log content sent outside VS Code.
- No automatic changes to original log files.

See `PRIVACY.md` for more details.

## Verify The Download

Optional checksum verification:

```bash
shasum -a 256 decaf-1.0.vsix
```

Compare the output with `SHA256SUMS.txt`.

## Current Version

Version: `1.0`

This is an early GitHub-distributed release. Marketplace publishing may come later.
