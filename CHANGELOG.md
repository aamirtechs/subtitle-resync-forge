# Changelog

## 1.0.0 - 2026-10-23

- SRT, VTT, ASS and SBV input with SRT and VTT output
- Constant shift in milliseconds for simple out-of-sync fixes
- Frame-rate rescale presets plus a custom ratio for drift that grows over time
- Two-point anchor sync that pins the first and last cue to known times
- Validation for overlaps, negative times and reading speed over 21 CPS, plus a clean transcript export
