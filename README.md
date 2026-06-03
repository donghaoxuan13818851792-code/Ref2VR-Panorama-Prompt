# Ref2VR Panorama Prompt

Version: v0.1 documentation MVP

A lightweight GPT Image 2 prompt workflow for turning reference images into 360-degree equirectangular VR-style panoramas.

## What It Does

Ref2VR Panorama Prompt provides a reusable prompt and review workflow for expanding a provided reference image into a full surrounding environment. It is designed to help generate 2:1 equirectangular panoramic images that can be checked in panorama or VR-style viewers.

This project is not a new image-generation model, a new AI technology, or a breakthrough 360-degree system. It is a practical prompt template and documentation workflow for improving reference-image-based panorama generation.

## Who It Is For

This project is for creators, designers, educators, researchers, and beginners who want a low-barrier, no-code way to experiment with VR-style panoramic image generation from a reference image.

It may be useful if you want to:

- Turn a concept image, photo, illustration, or mood reference into a surrounding scene
- Generate a 2:1 image for testing in panorama viewers
- Create immersive visual drafts without building a 3D environment
- Use a repeatable checklist to evaluate results

## Basic Usage

1. Upload a reference image.
2. Paste the prompt from [prompt.md](prompt.md).
3. Generate a 2:1 equirectangular panorama.
4. Check the result in a panorama or VR viewer.

## Key Features

- Reference-image-based scene expansion
- 2:1 equirectangular format
- Human eye-level viewpoint
- Full surrounding environment
- Stable horizon
- Seamless left-right wrapping
- Seam safety guidance
- Avoids fisheye, ordinary wide-angle, and poster-like outputs

## Project Files

- [prompt.md](prompt.md): Main reusable prompt
- [checklist.md](checklist.md): Practical review checklist for generated panoramas
- [limitations.md](limitations.md): Realistic limits and failure cases
- [examples/](examples/): Placeholder for example runs and notes

## Important Note

AI-generated panoramas may look equirectangular and immersive, but they may not be mathematically perfect. Always inspect the output in a panorama or VR viewer before using it in a real project.

Final output quality depends on the model, reference image quality, aspect ratio support, generation settings, and the panorama viewer used for testing.
