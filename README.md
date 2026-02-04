# VideoSoundEnhancer

Motion-synced sound effects tool for video.

## Demo

https://github.com/rajesh-laboratory/VideoSoundEnhancer/raw/main/demo/demo.mp4

## Overview

Analyzes motion in video and modulates sound effects volume to match movement intensity. Works well with periodic/rhythmic motion.

## Features

- Runs locally (no upload, no API keys)
- No duration limit — handles any length video
- Pure Rust optical flow engine (no OpenCV / Python dependency)

### Performance

| Metric | Value |
|--------|-------|
| Processing speed | ~2x realtime on modern CPU |
| Memory usage | Constant (~200 MB) regardless of video length |
| Parallelism | Multi-core (scales with CPU cores) |

## Use Cases

- AI-generated videos (Wan2.2, Kling, Runway, etc.)
- Adding impact/wet sounds to existing videos
- Sound effects tracks for game animations

## Usage

```bash
VideoSoundEnhancer016-demo.exe input.mp4 sfx.wav -o output.mp4
```

### Options

| Option | Description | Default |
|--------|-------------|---------|
| `--sensitivity` | Motion sensitivity | 1.0 |
| `--sfx-volume` | SFX volume in final mix | 0.8 |
| `--original-volume` | Original audio volume in final mix | 1.0 |

## Demo Limitations

| | Demo | Full |
|---------|------|------|
| Duration | Unlimited | Unlimited |
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
