# Cashies Pawn Audit — Release Downloads

> **This is a custom, private-use application built specifically for use with Zenith.**
> Its data capture reads information directly from Zenith's screens and **will not work with any other application or system.**
> It is not a general-purpose tool, and it is of no use outside the environment it was designed for.

## What this repository is

This repository is used **only to distribute updates** for Cashies Pawn Audit to the store PCs that already run it.
It contains release files only — the application's source code is not published here.

## Who it's for

Cashies Pawn Audit is an internal tool used by specific stores to support their own audit processes. It is:

- **Designed exclusively for Zenith** — it depends on Zenith's screen layouts and will not capture data from any other software.
- **Not a commercial product** — it isn't offered for sale, licensing or general download.
- **Not supported for outside use** — no help, installation assistance or customisation is available to anyone outside the stores it was built for.

If you found this repository by chance, there's nothing here you can use.

## How updates work

Installed copies of the app check this repository's **latest release** for new versions. Every release contains two files:

| File | Purpose |
|---|---|
| `PawnAudit-X.Y.Z.zip` | The application files |
| `PawnAudit-X.Y.Z.update.json` | A digitally signed description of the zip |

The app installs an update **only** if its signature is valid for the application's release key and the zip matches the signed fingerprint exactly. Files that are altered, or published by anyone else, are rejected — there is no way to override this. Staff are always asked before an update is installed, and if a new version fails to start, the previous version is restored automatically.

## Questions

For questions about this repository, contact the repository owner through GitHub.
