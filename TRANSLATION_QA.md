# Translation QA Notes

The English v2.1 manual was written as an operator guide rather than a literal translation.

## Review Passes

1. Terminology pass
   - Preserved exact UI labels such as `LED ON`, `GDS Import Settings`, `Enable UV Keystone`, `Disable UV Keystone`, `Start Calibration`, and `TEST Mode`.
   - Kept file names, commands, status text, and extension names unchanged.

2. Naturalness pass
   - Replaced literal Korean phrasing with concise operator English.
   - Used imperative steps for procedures and short explanatory paragraphs for concepts.
   - Avoided ambiguous phrases such as "apply the screen"; used "apply the DLP display" or "select the DLP monitor" instead.

3. Technical consistency pass
   - Removed the obsolete explanation that treated `Keystone Preview / Expose` as a current UI button.
   - Explained the v2.1 behavior: `LED ON` applies UV Keystone only when the active profile is `APPLIED (ON)`, otherwise it uses raw output.
   - Documented manual LED status updates: `Manual LED starting...` and `Manual exposing... 0.000s`.
   - Matched the v2.1 UV Keystone Calibration guard for DLP and main/camera monitor native resolution.
   - Matched the GDS crop workflow: yellow DLP frame, white GDS bounds, crop center, zoom, Fit View, Center Frame on GDS, and Frame check.

4. Screenshot pass
   - Every referenced screenshot exists in `assets/img`.
   - Screenshots are v2.1 captures from the current PySide UI.
   - Pattern Settings correctly shows `LED ON` only; no nonexistent `Keystone Preview / Expose` button is shown.

5. English-only pass
   - Site content and supporting Markdown were checked for Hangul characters.
