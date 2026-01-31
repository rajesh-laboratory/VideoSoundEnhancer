# VideoSoundEnhancer

Motion-synced sound effects tool for video.

## Demo

https://github.com/rajesh-laboratory/VideoSoundEnhancer/raw/main/demo/demo.mp4

## Overview

Analyzes motion in video and modulates sound effects volume to match movement intensity. Works well with periodic/rhythmic motion.

## Features

- Runs locally (no upload, no API keys)
- ~2x realtime processing on modern CPU
- Low memory usage

## Use Cases

- AI-generated videos (Wan2.2, Kling, Runway, etc.)
- Adding impact/wet sounds to existing videos
- Sound effects tracks for game animations

## Usage

```bash
VideoSoundEnhancer014-demo.exe input.mp4 sfx.wav -o output.mp4
```

### Options

| Option | Description | Default |
|--------|-------------|---------|
| `--start` | Start position (sec) | 0 |
| `--sensitivity` | Motion sensitivity | 1.0 |
| `--volume` | Sound effects volume | 0.8 |

## Demo Limitations

| | Demo | Full |
|---------|------|------|
| Duration | 60 sec | Unlimited |
| Input | MP4 | MP4, AVI, MKV, MOV |
| Output | MP4 | MP4, WAV |

## Download

[Releases](../../releases)

## Requirements

Windows. All DLLs included.

## Security

[VirusTotal](https://www.virustotal.com/gui/url/effbe8327cbf65f78b39a53f905a96f06c586dbca350ed28bea9b96d9c251552) - Clean

## License

Proprietary. Free for personal use.
