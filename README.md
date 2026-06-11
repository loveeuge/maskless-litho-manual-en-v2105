# MASKLESS LITHO v2.1 English Manual Site

This repository contains the English GitHub Pages operator manual for MASKLESS LITHO v2.1.

- Source of truth: current `README.md`, `ui/main_window.py`, `ui/pattern_settings_section_builder.py`, `ui/setting_window.py`, `ui/gds_layer_dialog.py`, and `ui/uv_keystone_window.py`
- Release executable: `maskless_v2_1.exe`
- Main topics: Quick Start, Safety, Pattern Settings, Manual LED ON, Interactive GDS Import, UV Keystone Calibration, Draw CAD, Expose Setup, Settings, Troubleshooting
- Assets: v2.1 UI screenshots captured from the current PySide UI

Important v2.1 behavior:

- The v2.1 UI does not include a separate `Keystone Preview / Expose` button.
- `LED ON` applies the active UV Keystone profile when the profile is `APPLIED (ON)`, and uses raw output when UV Keystone is disabled or unavailable.
- Manual LED status changes to `Manual LED starting...`, then `Manual exposing... 0.000s` after LED ON succeeds.
- UV Keystone Calibration validates the selected DLP monitor and the main/camera monitor native resolution before starting.

The site is static and runs from `index.html` plus `assets/img`.
