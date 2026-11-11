# Geniza Fragments Status

Interactive status report for the Cairo Geniza fragments recorded by the Friedberg Genizah Project (FGP) and the National Library of Israel (NLI).

**Web interface:** https://kashi-noam.github.io/geniza-fragments-status/

The page covers 238,492 fragments (one per NLI catalogue record) and shows, for the whole corpus and for any filtered subset:

- images and automatic transcription (Kraken HTR) coverage
- digital transcriptions (FGP and Princeton Geniza Project), published transcriptions and translations
- research status from bibliography (mentions, discussions, editions, translations)
- catalogue completeness, content, dates, script, material and physical condition
- joins

The **Explore the data** section lets you combine filters, break results down by any field, cross two fields, list matching fragments and download them as CSV. Every chart has a `?` explaining what it shows.

## Sources

- NLI Geniza MARC catalogue (export up to May 2024)
- FGP image index, bibliography export and FIST database (Jan 2026), using only records shown on the public FGP site
- Princeton Geniza Project open data ([pgp-metadata](https://github.com/princetongenizalab/pgp-metadata), [pgp-text](https://github.com/princetongenizalab/pgp-text)), pulled Nov 2026
- Automatic transcriptions produced by the EPHE / Paris team

The page contains metadata, counts and statuses only; no transcription text is included. It is a single self-contained HTML file (data embedded) and works offline.
