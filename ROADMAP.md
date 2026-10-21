# Roadmap

Development priorities after TVA Timeline v1.0.3 Early Access. These items are plans, not shipped features or guaranteed release dates. Priorities may change as users report reproducible problems.

[Download and installation](README.md) · [Version history](CHANGELOG.md) · [Report an issue](https://github.com/ramadhian-e/tva-timeline/issues)

## Current baseline

- [x] Main and Night modes in one application.
- [x] A complete Main animation with a final message and return sequence.
- [x] Preserved Night design, walking animation, loading table, and schedule settings.
- [x] Dedicated layouts for supported round and rectangular displays.
- [x] A v1.0.3 package with 204 regional PRG builds covering 123 SDK model IDs.
- [x] Simulator validation, preview assets, and updated USB installation documentation.
- [x] A public GitHub download and a README with installation guidance.

## Priority 1: Test on physical watches

- [ ] Record the exact model, PartNumber, firmware, display settings, and application version for each test.
- [ ] Verify installation, selection, wake, sleep, and repeated wake cycles on the fenix 6X Pro ASIA Solar.
- [ ] Collect representative results from Forerunner 165 / 965 and supported fenix 8 models.
- [ ] Collect rectangular-display results from Venu Sq, Venu Sq 2, and Venu X1.
- [ ] Check clock and sensor-field visibility during every Main animation phase.
- [ ] Verify Main/Night selection and automatic transitions at 21:00 and 06:00.
- [ ] Measure battery use over a documented period with consistent settings and a comparison watch face.

The compatibility list records supported SDK builds; it does not mean every listed physical watch has been tested.

## Priority 2: Improve animation using measured results

- [ ] Measure frame pacing, dropped frames, and visible pauses during the full Main sequence on physical devices.
- [ ] Investigate frame-loading delays, especially on older MIP watches, while keeping memory use within each device's limits.
- [ ] Tune rendering and data refresh only where measurements show a benefit.
- [ ] Recheck repeated wakes and Main/Night switches for memory errors or crashes.
- [ ] Preserve readable time and activity fields while improving motion.

The current targets are **20 fps for Main** and **10 fps for Night** during the wake animation. Performance changes must be evaluated per model. Continuous animation and a guaranteed frame rate on every Garmin device are not release commitments.

## Priority 3: Make downloads and reporting easier

- [ ] Collect installation feedback for Windows storage names such as Primary and Internal Storage, and update the guide when confirmed differences appear.
- [ ] Evaluate a simpler download-selection guide while preserving exact model and PartNumber matching.
- [ ] Add representative Main/Night images and the confirmed YouTube preview URL to the repository.
- [ ] Add a structured bug-report template requesting model, firmware, app version, reproduction steps, and expected versus actual behavior.
- [ ] Keep download links, device lists, release notes, and tutorials aligned with each published package.

## Design constraints

- Keep the approved Night appearance and animation behavior intact when making Main improvements.
- Preserve wake-limited animation and static low-power / always-on behavior.
- Keep the time, date, activity, altitude, and temperature fields unobstructed on supported screen shapes.
- Retain the existing public application identity for updates to the same Garmin Store application.
- Add devices only after checking SDK support, build output, layout, and resource limits.

## Before the next application release

- [ ] Reproduce the problems addressed by the update and verify the fixes.
- [ ] Build every intended device target and check each affected native display profile.
- [ ] Check Night preservation, mode transitions, wake behavior, and always-on rendering for regressions.
- [ ] Record available physical-device results and clearly identify remaining test gaps.
- [ ] Verify PRG selection, archive integrity, and the contents of the distribution package.
- [ ] Update the application version, release tag, changelog, README, previews, and device list where applicable.

A future application version will be scoped around verified fixes and test results. No date has been assigned. Documentation-only improvements can be published separately from an application update.
