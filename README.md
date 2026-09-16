# Soundtrak AI Studio — team edition

This download contains two folders:

- **`code/`** — the Studio itself. Your organisation runs a pinned release of this and updates it
  by pulling; nobody edits it in place.
- **`data/`** — your campaigns, your brands, your libraries. This is your work, and it is yours.

## What to do with them

Follow the **organisation deployment guide** — it walks an administrator through creating the two
repositories on your own git host (Azure DevOps Repos or GitHub Enterprise both work) and putting
these folders into them. Do not clone this repository as your working copy; download it, then
follow the guide.

`data/config.yaml` already declares the team profile, and `data/.gitattributes` is set up to keep
heavy media in LFS from the first commit.

## Licence

Free for your own organisation's internal business use. Client or agency work, resale and hosting
need a separate commercial licence — see `code/LICENSE` and `code/COMMERCIAL-LICENSE.md`.
