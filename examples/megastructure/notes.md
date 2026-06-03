# Megastructure Example

Prompt version: v0.1 main prompt  
Model: GPT Image 2  
Reference type: AI-generated reference image  
Result type: 2:1 equirectangular panorama  

## Description

This example tests whether Ref2VR Panorama Prompt can expand a futuristic megastructure reference image into a 360-degree equirectangular panorama. The intended viewer position is human eye height on a central elevated bridge or skyway inside a massive sci-fi city.

## Viewing note

The output from GPT Image 2 is a 2:1 equirectangular panorama image. After downloading, it may look like a very wide flat image in a normal image viewer.

To view it as a 360° environment, open it in a supported web viewer, app, or VR viewer and use the viewer's 360 mode, such as "Enter 360 world" or an equivalent option.

`viewer-screenshot.png` shows the generated panorama opened in a supported viewer with an "Enter 360 world" option.

This project generates VR-viewable panorama images. It does not generate a standalone interactive 3D world, so you need a compatible viewer to experience the image as a 360° scene.

## What worked

- Strong sense of architectural scale
- Clear futuristic megastructure atmosphere
- Bridge-based viewpoint gives the scene a stronger sense of physical presence
- Good foreground, midground, and background depth
- Suitable for testing VR-style panorama viewing

## What needs checking

- Left-right seam quality in a panorama viewer
- Whether the viewer position truly feels like standing on the bridge
- Whether the horizon remains stable
- Whether top and bottom areas distort in VR viewing
- Whether any architecture appears duplicated, warped, or physically inconsistent

## Notes

Both the reference image and the generated panorama are AI-generated demo assets created for testing this prompt workflow.

This example should not be treated as proof of perfect 360-degree reconstruction. It demonstrates a prompt-based workflow for generating panorama-style outputs from a reference image.
