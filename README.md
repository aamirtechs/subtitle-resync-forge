# Subtitle Resync Forge
Live page: https://aamirtechs.github.io/subtitle-resync-forge/

Fix out-of-sync subtitles properly with a constant shift and frame-rate drift correction, convert between SRT and VTT, and strip overlaps in one local tool. Built for creators, course makers and video editors working with captions timed for a different frame rate.

## Features
- SRT, VTT, ASS and SBV input with SRT and VTT output
- Constant shift in milliseconds for simple out-of-sync fixes
- Frame-rate rescale presets plus a custom ratio for drift that grows over time
- Two-point anchor sync that pins the first and last cue to known times
- Validation for overlaps, negative times and reading speed over 21 CPS, plus a clean transcript export

## How it works
Drop in an SRT, VTT, ASS or SBV file, apply a shift, a frame-rate rescale or a two-point anchor sync, review overlap and reading-speed warnings, then download clean SRT or VTT or a plain transcript. It runs entirely in the browser.

## Privacy
Runs 100% in your browser. Your files never leave this device, nothing is uploaded, and there is no tracking.

## Development
Core logic lives in `src/logic.js` and is shared by the page and the tests. Run the tests with `npm test`.

## License
MIT, Copyright 2026 Amir Hussain.
