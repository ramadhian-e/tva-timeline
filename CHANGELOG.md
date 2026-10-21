# Changelog

Changes to TVA Timeline are recorded here, with the newest version first.

## [1.0.3](https://github.com/ramadhian-e/tva-timeline/releases/tag/v1.0.3) — Early Access

### Main animation

- Expanded Miss Minutes from 25 poses to a 200-frame Main sequence, targeting 20 fps during the wake animation.
- Added more complete landing, pointing, blinking, and return movements.
- Added the ending message: **“Hey y'all! DON'T RUIN THE SACRED TIMELINE!”** around Miss Minutes before she returns.
- Kept the clock, date, activity, altitude, and temperature fields clear during the sequence.
- Loaded animation frames in small banks to limit memory use on older watches.

### Preserved behavior

- Preserved the approved v1.0.2 Night design, walking animation, decorative loading bar, process table, and schedule settings.
- Retained the Night animation target of 10 fps and the default Night schedule of 21:00–06:00.
- Retained the existing Garmin compatibility and dedicated round and rectangular layouts.

### Distribution and documentation

- Provided a manual installation package with 204 PRG files covering 123 Garmin SDK model IDs and supported regional variants.
- Provided Main and Night GIF previews for all 13 native display profiles.
- Revised Windows USB instructions to include the **Primary → GARMIN → APPS** path shown on the fenix 6X Pro ASIA Solar.
- Added a dedicated fenix 6X Windows tutorial and instructions for MTP devices without an Eject option.
- Verified that the three regional PRG files in the **fenix6xpro folder of this v1.0.3 package** are identical, and clarified that users only need one copy.
- Published a GitHub pre-release and added download, compatibility, installation, and feedback information to the repository README.

The tutorial and packaging revisions did not change the v1.0.3 application binary.

### Validation

- Completed all 204 regional SDK builds.
- Checked the Main animation against data-field masks across all 13 native display profiles.
- Completed functional simulator checks on 17 representative model IDs.
- Preserved the previous Night resources and rendering behavior in the release validation.

Frame rates are targets, not guarantees for every watch. Physical-device frame-rate and battery measurements remain incomplete; performance depends on the watch and firmware.

## 1.0.2 — Expanded Garmin support

- Expanded compatibility, including Forerunner 165 / 165 Music, Forerunner 965, and supported fenix 8 variants.
- Added dedicated rectangular layouts for Venu Sq / Sq Music, Venu Sq 2 / Sq 2 Music, and Venu X1.
- Enlarged the clock and timeline monitor on rectangular displays and rearranged the data fields.
- Adapted the Miss Minutes popup and Night walking animation to rectangular screens.
- Added resources at native display sizes and a dim AMOLED always-on time/date display with minute-by-minute position changes.

## 1.0.1 — First public early access build

- Introduced Main and Night themes for the fenix 6X target, with automatic scheduling and manual selection.
- Added a curved timeline monitor, nine animated branches, orange safety boundaries, and a larger moving white pulse.
- Added the Miss Minutes popup and decorative Night loading animation.
- Moved activity fields inward and standardized labels to English.
- Optimized memory use for the fenix 6X.

## Looking ahead

See [ROADMAP.md](ROADMAP.md) for development priorities and [README.md](README.md) for downloads and installation instructions.
