# MASKLESS LITHO v2.1.5 English Manual

Operator guide for the PLANCK INC standard edition.

- Site: https://loveeuge.github.io/maskless-litho-manual-en-v2105/
- Official release: https://github.com/PLANCK-INC/MASKLESSLITHO/releases/tag/v2.1.5
- Executables: `maskless_v2_1_5.exe`, `maskless_v2_1_5_fast.exe`
- Source baseline: commit `4077c33`, README, current UI and controller sources

Includes first-projection confirmation, the 30-second confirmation deadline,
Display Apply validation and recovery, DLP 1920x1080/100% requirements,
Fast Portable, removal of Focus from the standard edition, GDS raster checks,
Keystone compatibility, shutdown and CAD save handling.

The site is static: `index.html` and `assets/img` are sufficient for hosting.
The 19 images show current UI widgets with example data. LED confirmation and
UV progress states are illustrated without hardware commands, not physical
optical-validation evidence.

See `IMAGE_REFERENCE.md` and `TRANSLATION_QA.md` for image placement and QA scope.
Both languages are maintained in the local source file
`manual_site_v2105/manual_content.py`; directory names are retained for compatibility.
Rebuild from the MASKLESSLITHO workspace:

```powershell
.\venv64\Scripts\python.exe manual_site_v2105_en\build_manual_site_en.py
```
