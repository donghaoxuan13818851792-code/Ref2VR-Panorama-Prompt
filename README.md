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

1. Attach the reference image as an image.
2. Open [prompt.md](prompt.md), copy the full prompt text, and paste it directly into the image generation message.
3. Generate a 2:1 equirectangular panorama.
4. Check the result in a panorama or VR viewer.

Important: Do not upload `prompt.md` as the prompt file and expect it to run automatically. For best results, open `prompt.md`, copy the full prompt text, paste it directly into the image generation message, and attach the reference image in the same request.

The model may not treat an uploaded `.md` file as active generation instructions. This is a usage requirement of the workflow, not a change to the prompt itself.

## Important Note About Viewing

The output from GPT Image 2 is a 2:1 equirectangular panorama image. After downloading, it may look like a very wide flat image in a normal image viewer.

To view it as a 360° environment, open it in a supported web viewer, app, or VR viewer and use the viewer's 360 mode, such as "Enter 360 world" or an equivalent option.

This project generates VR-viewable panorama images. It does not generate a standalone interactive 3D world, so you need a compatible viewer to experience the image as a 360° scene.

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
- [examples/](examples/): Examples and notes
- Megastructure example: [examples/megastructure/](examples/megastructure/)

## Demo

The megastructure example includes `reference.png`, `result-panorama.png`, `viewer-screenshot.png`, and `notes.md`.

## Important Note

AI-generated panoramas may look equirectangular and immersive, but they may not be mathematically perfect. Always inspect the output in a panorama or VR viewer before using it in a real project.

Final output quality depends on the model, reference image quality, aspect ratio support, generation settings, and the panorama viewer used for testing.
