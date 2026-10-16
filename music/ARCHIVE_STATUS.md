# Archive Status

## Completed

- GitHub music archive created and organized.
- Major album/song families have dedicated canonical folders.
- Historical ChatGPT Library filenames have been inventoried by family.
- Readable composition/arrangement notes for key projects have been copied into GitHub.
- A catalog and forward-working convention are in place.
- `The Waters` now has a dedicated canonical song folder and exact Library reference for `the waters v3.mp3` plus its related Water MIDI/packages.

## Legacy binary migration limitation

The historical `.mid`, `.zip`, `.mp3`, and `.wav` artifacts still exist in the ChatGPT Music Creation Library, but the current Library interface exposes their metadata without an authorized raw-byte export path. A direct raw-byte materialization attempt was made again on 2026-10-16 and was rejected by the Library authorization layer.

That means the GitHub connection cannot copy those historical binary bytes directly from the Library in this session. The exact historical filenames are retained in the family READMEs and catalog so the originals remain locatable in ChatGPT Library.

## Going forward

New music files should be committed to this repository at creation time whenever GitHub write access is available, rather than relying on later Library recovery.

Preferred structure:

- `albums/<album>/` — album tracks, album-wide MIDI, packages and notes
- `songs/<song>/` — standalone song versions and notes
- `series/<family>/` — related exploratory song families
- `sketches/` — riffs, motif auditions and experiments
- `incoming/` — unclassified new material

Do not silently overwrite meaningfully different arrangements; preserve version lineage.
