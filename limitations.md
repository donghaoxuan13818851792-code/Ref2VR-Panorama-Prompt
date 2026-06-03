# Limitations

This project is a prompt workflow, not a new image-generation model, 3D reconstruction tool, or guaranteed panorama engine.

## Realistic Limits

- The result may look equirectangular but may not be mathematically perfect.
- Left-right seams may still fail, especially when detailed objects cross the seam.
- Top and bottom areas may distort because equirectangular images stretch heavily near the poles.
- People, text, signs, hands, faces, and complex objects may deform.
- Reflections, shadows, and lighting may not remain physically consistent across the full panorama.
- Fine architectural geometry may bend, repeat, or fail to connect cleanly.
- Generated details may drift away from the reference image if the model fills too much unknown space.

## Spatial Continuity

A generated panorama can create the feeling of a surrounding world, but it does not create a real 3D scene. Multi-point panorama roaming may not preserve true spatial continuity between locations.

If you need accurate geometry, measured spaces, depth maps, collision, parallax, or navigable 3D structure, use dedicated 3D capture, photogrammetry, scene reconstruction, or modeling tools.

## Best Use

Use this workflow for concept exploration, visual ideation, mood development, prototype environments, and early VR-style tests. Always review the generated image in a panorama or VR viewer before presenting or publishing it.
