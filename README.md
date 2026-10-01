# NIE Graduate Research Conference 2026 — Ebooklet

## Conference Ebooklet

- Landing page: https://brewsss.github.io/grc2026-ebooklet/
- PDF: `GRC2026_Ebooklet.pdf`
- QR (PNG, 1620×1620): `assets/GRC2026_Ebooklet_QR.png`
- QR (SVG, vector): `assets/GRC2026_Ebooklet_QR.svg`

The QR code encodes the landing page URL above (error correction H), not the PDF.

**Updating the ebooklet:** replace `GRC2026_Ebooklet.pdf` with the new version, keep the
same file name, then commit and push. The QR code does not need to be regenerated.

**Takedown (planned ~2026-10-08):** this site is meant to be public for one week only.
Delete the repository to remove the page and the PDF (including git history):

```
gh auth refresh -s delete_repo
gh repo delete BrewSSS/grc2026-ebooklet --yes
```
