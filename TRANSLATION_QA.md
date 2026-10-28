# v2.1.5 Translation and Technical QA

- Both languages share 24 sections and the same versioned image set.
- Exact UI labels are preserved, including `Preparing LED... (Cancel)`,
  `Pattern visible`, `LED OFF / Cancel`, `Apply`, and `TEST Mode`.
- ON-command acceptance is distinguished from visible projection.
- The 5-second preparation deadline is not a fixed wait or guaranteed bound on
  a blocking native call. The 30-second confirmation period follows ON response.
- Display Apply validates black output; it does not start pattern projection.
- Focus is absent in the standard edition; future Pro plans are not released features.
- Fast Portable requires the adjacent `_internal` directory.
- Disabled Keystone does not imply that independent Compensation is off.
- GDS preview zoom is distinguished from physical CAD scale.
- Illustrated dialogs are not hardware measurements.
- QA covers HTML, anchors, images, tabs, desktop/mobile layout, English-only
  text, and deployed-page integrity. Physical accuracy requires equipment QA.
