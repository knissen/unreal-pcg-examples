# unreal-pcg-examples

Teaching project to show some use cases for PCG (Procedural Content Generation) in Unreal Engine 5.7.

## YouTube Channel References

- [PCG 1. Getting Started](https://www.youtube.com/watch?v=ZWwjqyFM9ZY) — Series of videos covering the basics of PCG
- [Randomize Anything with PCG](https://www.youtube.com/watch?v=QE65wzDZxfY) — Describes using packed level actors and tags to randomize objects in game. Also covers randomizing the color for items by using a property on the mesh material
- [Procedural Minds YouTube Channel](https://www.youtube.com/@Procedural_Minds) - Great videos explaining PCG

## Levels

### PCGForestExample
**Path:** `PCGExamples/Content/Levels/PCGForestExample.umap`

Basic example of using PCG to generate a forest with various implementations. Covers using the GetLandscapeData node and interior of a spline loop to
sample the landscape.

### PCGForestExample
**Path:** `PCGExamples/Content/Levels/PCGPathsExample.umap`

Examples of using the PCG graph system to generate paths. Examples include the use of the Project node to align points to the landscape below.
Includes using the shape grammar system for generating a fence with a gate.

### PCGPackedLevelsExample
**Path:** `PCGExamples/Content/Levels/PCGPackedLevelsExample.umap`

Shows a Packed Level asset in the scene and then an PCG graph implementation of randomizing items in that level based on Actor tags on items. Based on the
[Randomize Anything with PCG](https://www.youtube.com/watch?v=QE65wzDZxfY) video.

---

## Epic Games Example Project

[Cassini Sample](https://www.fab.com/listings/3f7cd12c-30b3-47d6-90c2-8604ed068ab7)
[Cassini YouTube Video](https://www.youtube.com/watch?v=j3ke6MmcaeY)

This is some more advanced use cases but interesting to dive into if you're read.

Shows using packed level assets to create a space station hallway with a lot of detail. Also uses hierarchical generation to generate debris.
Shows an asteroid field with over a million asteroids using PCG point generation on the GPU (pretty technical).
