# CLAUDE.md

Public downloads for PURE DESKTOP's AI model marketplace: the card metadata in `models.json`, plus per model runner scripts and small assets under `models/`. Large model weights live on Hugging Face. `admin/` holds the CMS config.

- This repo is public. Never commit anything private.
- The desktop app reads `models.json` straight from main (`https://raw.githubusercontent.com/Pure-BPM/pure-desktop-models/main/models.json`), so a merge reaches every user right away. Keep `models.json` valid JSON with its existing structure, and say in the pull request exactly what users will see change. Merging is Tim's call.
- Plugin installers aren't here. They're in `Pure-BPM/pure-plugins-releases`.
