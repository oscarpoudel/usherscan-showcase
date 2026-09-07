# UsherScan (UScan)

![Logo](assets/logo.png)

**Advanced AI Crack Segmentation Scanner** — real-time concrete/structural crack detection built with Flutter + YOLO on-device inference.

## Features

- **Real-time camera scanning** — live YOLO instance segmentation of cracks from your camera feed, with FPS counter and switchable front/rear camera
- **On-device AI** — TensorFlow Lite model runs fully offline; no cloud, no internet required
- **Batch image processing** — select multiple photos from your gallery and process them all at once with live progress tracking
- **Adjustable segmentation controls** — mask opacity, mask thickness, confidence threshold, 4 mask color options, and background blur toggle — tweak live while scanning
- **Voice feedback** — text-to-speech announces detections hands-free
- **Scan session library** — every session auto-saved with original images, processed results, and metadata; browse chronologically in the gallery with full-screen zoom
- **Dark cyberpunk UI** — sleek dark theme with blue neon accents

## Screenshots

<table>
  <tr>
    <td align="center"><img src="screenshots/screenshot_1_home.jfif" width="220" alt="Home"><br><sub>Home</sub></td>
    <td align="center"><img src="screenshots/screenshot_crack_det.jpeg" width="220" alt="Crack Detection"><br><sub>Crack Detection</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="screenshots/screenshot_2_gallary.jpeg" width="220" alt="Gallery"><br><sub>Gallery</sub></td>
    <td align="center"><img src="screenshots/screenshot3_batch_processor_page.jpeg" width="220" alt="Batch Processor"><br><sub>Batch Processor</sub></td>
  </tr>
</table>

## Technology

| Component | Tech |
|-----------|------|
| Framework | Flutter / Dart |
| AI Model | YOLO instance segmentation (Ultralytics) |
| Inference | TensorFlow Lite (on-device) |
| Platforms | Android, iOS, macOS, Linux, Windows, Web |

## About

Built for structural inspection and concrete damage assessment — catch hairline cracks and surface damage early with a smartphone.

---

This repository is a showcase only. Source code is not public.
