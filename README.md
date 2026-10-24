# Twin Player

An offline video player for one or two local videos.

## Run

1. Download this repository using **Code → Download ZIP**.
2. Extract the ZIP.
3. Double-click `index.html` to open it in your browser.
4. Choose your videos and press **Play**.

No installation, internet connection, or server is required.
Your videos stay on your computer.

## Features

- Synchronized playback and seeking for two videos.
- Single-video mode with a full-width panel.
- Playback speeds from 0.5× through 3×.
- Fullscreen playback with controls that hide automatically.
- Audio selection and adjustable panel sizes.

Hover over the timeline to see time from the start.
The remaining-time display uses the shorter recording in two-video mode.
Playback stops when either recording finishes.
Choose your files again after reopening the page.

## Keyboard shortcuts

| Shortcut | Action |
| --- | --- |
| Click a video or press Space | Play or pause |
| Option + Shift | Toggle fullscreen |
| Left or Right Arrow | Seek backward or forward ten seconds |
| Option + Left or Right Arrow | Decrease or increase playback speed |
| Shift + Left Arrow | Expand the left panel to 75% |
| Shift + Right Arrow | Expand the right panel to 75% |

Standard arrow shortcuts preserve native behavior when a form control has focus.
Command + Left or Right Arrow blocks browser navigation inside the player.

## Compatibility

Use a modern browser with support for your video's encoding.
H.264 MP4 files with AAC audio are a suitable starting point.
Synchronization is intended for lecture viewing, not frame-accurate editing.

## Implementation

Plain HTML, CSS, and JavaScript in one file.
No package dependencies or external services.
The icon is embedded for offline use.
