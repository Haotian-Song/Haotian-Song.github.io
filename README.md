# Haotian Song's personal website

MkDocs Material source is in `docs/`; the generated local website is in `site/`.

## Build and preview

```powershell
python -m pip install -r requirements.txt
python -m mkdocs build --strict
python -m mkdocs serve
```

Open the address printed by MkDocs (normally http://127.0.0.1:8000).

## Content update — October 1, 2026

Updated the profile, NUS education and contact details; added doctoral research, publications and conference presentations; refreshed computational imaging; added an academic CV download; and retained earlier project pages and their URLs. The configuration now has one combined Markdown extensions list and light/dark themes.

Content was grounded in the workspace's academic research CV, NUS FEST CV, thesis-supported additions and September 22, 2026 publication summary. Expected graduation and manuscript-in-preparation status remain explicitly labeled. The academic CV is copied from the existing workspace PDF. Earlier Manchester experience is retained without claiming an unverified degree.

GitHub Pages publishes the generated website from the root of the `gh-pages` branch. Editable sources are maintained on `main`.
