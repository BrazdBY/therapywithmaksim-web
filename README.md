# Public Assets Directory

This directory contains static assets (images, fonts, etc.) that are served directly.

## Required Images

The following images are referenced in the application and should be placed in this folder:

### Portrait Photos
- `maksim-dark.jpg` - Main hero portrait (dark sweater, professional)
- `maksim-desk.jpg` - About teaser image (grey suit at desk, landscape)
- `maksim-blue.jpg` - About page portrait (light blue shirt, friendly)

### Certificates
- `certificate-academy.jpg` - Academy of Hypno-Experts certificate
- `certificate-institute.jpg` - Institute certificate

### Content Images
- `hypnotherapy-vs-therapy.jpg` - Image for "Why Hypnotherapy vs Regular Therapy" section (800x600px recommended, landscape orientation)
  - **Description:** Illustration showing iceberg metaphor - regular therapy above water (conscious level), hypnotherapy below water (subconscious level)
  - **Status:** ⏳ Image needs to be added to this directory
  - **After adding:** Run `npm run optimize-images` to create optimized and WebP versions

## Image Guidelines

- **Format**: JPG or PNG
- **Quality**: High resolution (1920px width recommended for portraits)
- **Optimization**: Compress images before adding (use tools like TinyPNG)
- **File size**: Keep under 500KB per image when possible

## Temporary Placeholder

If you don't have images yet, you can use placeholder services:
- https://via.placeholder.com/800x1000
- https://picsum.photos/800/1000

Or create simple colored rectangles as placeholders.
