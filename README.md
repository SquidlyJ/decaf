# DeCaf

Read messy support logs faster in VS Code.

This is the release-only GitHub repo for DeCaf. It contains the public VSIX package and documentation only. It does not contain private development logs, test samples, or customer files.

## Download

Download:

- `decaf-1.0.vsix`

## Install

1. Open VS Code.
2. Open the Extensions view.
3. Select the `...` menu.
4. Choose `Install from VSIX...`.
5. Select `decaf-1.0.vsix`.
6. Reload VS Code if prompted.

## What You Get

- Local log detection.
- A cleaner generated DeCaf view while the original log stays untouched.
- Timeline gap markers for quiet periods and session breaks.
- DeCaf-only color themes.
- Keyword highlighting for failures, successes, retries, and state changes.
- Optional focused time-range views.
- Theme preview.

## Privacy

DeCaf is local by design:

- No network calls.
- No telemetry or analytics.
- No AI calls.
- No server or cloud processing.
- No bundled sample logs.
- No log content sent outside VS Code.
- No automatic changes to original log files.

See `PRIVACY.md` and `SECURITY.md` before sharing log examples publicly.

## Verify The Download

Optional checksum verification:

```bash
shasum -a 256 decaf-1.0.vsix
```

Compare the output with `SHA256SUMS.txt`.

## Documentation

- [Wiki](https://github.com/SquidlyJ/decaf/wiki)
- [Privacy](PRIVACY.md)
- [Security](SECURITY.md)
- [Release notes](RELEASE_NOTES.md)

## Current Version

Version: `1.0`

This is an early GitHub-distributed release. Marketplace publishing may come later.
