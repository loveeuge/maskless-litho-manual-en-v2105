# Translation QA Notes

The English manual was written as an operator guide rather than a literal word-for-word translation.

## Review Passes

1. Terminology pass
   - Preserved exact UI labels such as `LED ON`, `Keystone Preview / Expose`, `GDS Import Settings`, `Enable UV Keystone`, and `Disable UV Keystone`.
   - Kept file names and command names unchanged.

2. Naturalness pass
   - Replaced literal Korean phrasing with concise operator English.
   - Used imperative steps for procedures and short explanatory paragraphs for concepts.
   - Avoided unclear phrases such as "apply the screen" and used "apply the DLP display" instead.

3. Technical consistency pass
   - Explained that `LED ON` is raw output and does not apply UV Keystone correction.
   - Explained that `Keystone Preview / Expose` prepares the corrected image first and stops before LED ON on correction failure.
   - Matched the v2.0.10.5 GDS crop workflow: yellow DLP frame, white GDS bounds, crop center, zoom, Fit View, and Frame check.

4. Screenshot pass
   - Every referenced screenshot exists in `assets/img`.
   - Screenshots are the v2.0.10.5 captures, not the older v2.0.9 images.

5. English-only pass
   - Site content and supporting Markdown were checked for Hangul characters.
