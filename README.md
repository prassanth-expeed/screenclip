# ScreenClip

A fast, polished screenshot, screen-recording and voice-recording tool for Windows.

## Download

Get the latest build from the [Releases page](https://github.com/prassanth-expeed/screenclip/releases/latest).
No installation of Python or anything else is needed.

| File | What it is |
|---|---|
| `ScreenClip-<version>-win64-portable.exe` | Single file, runs from anywhere (unpacks on each launch, so it starts a little slower) |
| `ScreenClip-<version>-win64.zip` | Unzip and run `ScreenClip\ScreenClip.exe`; fastest start |

The executables are not code-signed, so Windows SmartScreen may show "Windows protected your PC" the first time.
Click **More info** → **Run anyway**. Requires Windows 10 (2004+) or Windows 11, 64-bit.

## Features

**Screenshots**
- Capture an **area** (drag), a **window** (hover to highlight, click to pick) or a whole **display**.
- Multi-monitor and mixed-DPI aware. Captures are pixel-exact.
- Built-in editor: pen, highlighter, line, arrow, rectangle, ellipse, text (any font, size, bold/italic and colour),
  numbered steps, pixelate. Undo/redo, zoom, copy to clipboard, save as PNG, JPG or WebP.
- Optional auto-save and copy-to-clipboard on capture.

**Screen recording**
- Record an area, a window (follows it when it moves) or a display to H.264 MP4, 15–60 fps, four quality presets.
- Countdown, pause/resume, a floating control bar and a red frame that stay out of the recording.
- Microphone and/or system audio (what you hear), mixed into one AAC track. Mute either source while recording.
- Camera bubble: your webcam as a circle or rounded rectangle on top of the screen, for tutorials and walkthroughs.
- Clip editor: open any recording, trim the ends, cut sections out of the middle, save as a new MP4 or an animated
  GIF, or grab a frame as a screenshot.

**Voice recording**
- Audio-only recordings: microphone, system audio, or both mixed together.
- Pause/resume, mute and a live input-level meter. Saved as M4A, MP3 or WAV.

**App**
- Runs in the system tray. Global shortcuts work from any app.
- Recent captures strip with thumbnails: open, annotate, reveal in Explorer, delete.

## Shortcuts

| Shortcut | Action |
|---|---|
| Ctrl+Shift+A | Capture an area |
| Ctrl+Shift+W | Capture a window |
| Ctrl+Shift+F | Capture a display |
| Ctrl+Shift+R | Record an area |
| Ctrl+Shift+M | Record voice (microphone) |
| Ctrl+Shift+P | Pause / resume recording |
| Ctrl+Shift+X | Stop recording |

Shortcuts can be switched off in Preferences → General.

## Feedback

Bug reports and ideas are welcome: open an [issue](https://github.com/prassanth-expeed/screenclip/issues) and
include your Windows version, monitor layout (count and scaling) and the steps that reproduce the problem.

---
[MIT licensed](LICENSE) · Windows 10 (2004+) and Windows 11.
