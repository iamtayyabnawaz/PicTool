# Pic-Tool — Photo Resizer & White Background Tool

A fast, 100% client-side **AI Photo Resizer & White Background Tool** built by **Tayyab Nawaz**.

## Features

- **Automatic AI White Background:** Uses Google MediaPipe `ImageSegmenter` directly in your browser to cleanly separate portraits from messy backgrounds and place them on a crisp `#FFFFFF` backdrop (with optional smooth edge feathering and passport blue/gray swatches).
- **Portal-Ready Presets & Custom Dimensions:** Defaults automatically to **600 × 800 px** and **≤ 25 KB** (ideal for PECTAA / IBS & official registration portals), plus built-in presets for **Passport (2×2 in)**, **ID / CNIC (35×45 mm)**, **High-Res Print**, and **Custom Dimensions**.
- **Smart Binary-Search Compression:** Maximizes visual clarity while strictly staying at or below your target KB size limit.
- **Multi-Format Export:** Instant download as **JPG**, **PNG**, or **PDF**, with batch photo queue support.
- **100% On-Device Privacy:** Photos are processed locally in your browser and are never uploaded to any external server.
