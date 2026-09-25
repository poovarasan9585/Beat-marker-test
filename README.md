# Beat Marker — Premiere Pro 23.2

CEP panel for audio beat detection and sequence markers.

## Features
- Audio-file beat detection using Web Audio API
- BPM estimate
- Sensitivity control
- Minimum beat spacing
- All / strong / every-2nd-beat modes
- Sequence offset
- Create and clear Premiere sequence markers

## Install
Copy the extension folder to:

`%APPDATA%\Adobe\CEP\extensions\com.mrblack.beatmarker`

Enable CEP debug/unsigned-extension mode if required by your Premiere/CEP environment, restart Premiere Pro, then open:

**Window > Extensions > Beat Marker**

## Important
The panel analyzes an audio file selected in the panel. It does not directly extract raw timeline audio. If the audio starts later in the sequence, use Sequence offset.
