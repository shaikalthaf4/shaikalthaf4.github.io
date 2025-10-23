# Quick Setup Guide - PRISM Lab Website

## Required: Add Lab Logo

1. Copy `prism_logo_v2.png` to the `/images/` folder
2. The logo will automatically appear in the website header and sidebar

## Optional: Add Publication Images

Add representative images for your papers to `/images/publications/`:

- `edge-ai-sensor.png` - Edge AI integration paper
- `smartvision-bridge.png` - SmartVision system paper  
- `drone-bridge-inspection.png` - Drone damage prediction paper
- `miter-gates.png` - Miter gates vision paper
- `crack-detection.png` - Crack detection paper
- `wireless-accelerometer.png` - Wireless accelerometer paper
- `cnn-anomaly.png` - CNN anomaly detection paper

Images will display automatically once added (400x300px recommended).

## Optional: Add Smart Bridge Media

1. Upload video/GIF of UIUC Smart Bridge to `/images/` or `/files/`
2. Edit `_pages/highlights.md` to reference the file

## View Your Site

### Locally:
```bash
bundle install
bundle exec jekyll serve
```
Visit: http://localhost:4000

### On GitHub Pages:
Just push your changes - the site will rebuild automatically.

## Questions?

See `IMPLEMENTATION_SUMMARY.md` for detailed information about all changes made.
