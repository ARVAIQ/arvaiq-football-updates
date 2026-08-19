# ARVAIQ Football Updates

Public release-only repository for the ARVAIQ Football desktop updater.

Private source code remains in `ARVAIQ/arvaiq-platform`.

## Rules

This repository must never contain:
- source code
- secrets or `.env` files
- databases
- models / learning datasets
- logs
- customer data

Application binaries are distributed through GitHub Releases, not committed to the repository.

## Release assets

Each release should use a semantic tag such as `v2.0.7` and contain:

- `ARVAIQ.Football.-.Setup.exe`
- `ARVAIQFootballSetup.sha256`

Optional compatibility assets:
- `ARVAIQFootball.exe`
- `ARVAIQFootball.sha256`
