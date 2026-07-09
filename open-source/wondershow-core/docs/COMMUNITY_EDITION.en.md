# WonderShow Community Edition

WonderShow Community Edition is the free, practical build for creators, teachers, and developers. The 2.0 Community Edition provides a stable, offline, reproducible recording and light post-production workflow: record a presentation window, presenter camera, and microphone on macOS; save a `.wondershow` project; then finish basic camera editing, clip selection, and export after recording.

## Feature Scope

Community Edition includes:

- Camera input: built-in Mac cameras, common UVC cameras, and external capture devices.
- Screen and window recording: presentation windows, full display capture, and manually selected windows.
- Source switching during recording: `⌘1` to `⌘6` source slots.
- Presenter PiP and core layouts: screen main, presenter PiP, presenter main, side-by-side, top/bottom, screen-only, and speaker-only.
- Canvas ratios: landscape, portrait, and square, with recording-time layout/canvas changes replayed in preview and export.
- Audio recording: current macOS microphone input written as a separate raw audio track.
- Project workflow: `.wondershow` projects with raw tracks, program track, timeline, layout, and export metadata.
- Program preview and export: preview after recording, export MP4/MOV/GIF, and manually export up to 4K.
- Basic camera editing: rectangular/circular screen focus regions, automatic keyframes, standard masks, basic borders, undo/redo, single-clip export, and small merged clip exports.
- Basic presenter adjustments: mirror, brightness, contrast, and lightweight smoothing.
- Multilingual UI: Simplified Chinese, Traditional Chinese, and English.

## Shortcuts

| Shortcut | Action |
|----------|--------|
| `⌥⌘R` | Start / stop recording |
| `⌘1` - `⌘6` | Switch source slots during recording |
| `⌘Z` / `⇧⌘Z` | Undo / redo camera or clip edits |
| `⌘←` / `⌘→` | Previous / next frame |
| `⌘N` | Create a camera keyframe |
| `Delete` | Delete the selected keyframe or clip |
| `Return` | Play / pause camera preview |
| `ESC` | Cancel the current camera selection and roll back newly created automatic keyframes |

## How To Use

1. Open `灵演社区版.app`.
2. Allow Camera, Microphone, and Screen Recording permissions in macOS System Settings. Camera permission appears only after the app requests it.
3. Choose the input device and audio input from the right-side panel.
4. Choose the recording source: presentation window, full display, or manually selected windows.
5. Choose the recording mode and layout, such as “Camera + Screen” and “Screen Main + Speaker PiP”.
6. Click “Start Recording”, then wait for program composition after stopping.
7. Use “Preview Program” to check the result. For refinement, enter camera editing, adjust keyframes or clip ranges, then export the video.

## Open-Source Documentation And Code

The open-source repository includes:

- WonderShow Core Swift Package.
- Public `.wondershow` project schemas for manifests, timelines, layouts, and export settings.
- MediaPipe sidecar local protocol and security constraints.
- Plugin APIs, examples, and tests.
- `README`, `LICENSE`, `NOTICE`, `CONTRIBUTING`, `SECURITY`, `ROADMAP`, and `PACKAGE_BOUNDARY`.
- Trilingual Community Edition documentation: Simplified Chinese, Traditional Chinese, and English.

## Support The Author

If WonderShow Community helps you, the About panel includes small QR codes for supporting me with a cola or a small boost. Thank you for trying it and sending feedback.
