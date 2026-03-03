# unreal-pcg-examples

Teaching project to show some use cases for PCG (Procedural Content Generation) in Unreal Engine 5.7.

## YouTube Channel References

- [PCG 1. Getting Started](https://www.youtube.com/watch?v=ZWwjqyFM9ZY) — Series of videos covering the basics of PCG
- [Randomize Anything with PCG](https://www.youtube.com/watch?v=QE65wzDZxfY) — Describes using packed level actors and tags to randomize objects in game
- [Procedural Minds YouTube Channel](https://www.youtube.com/@Procedural_Minds) - Great videos explaining PCG

## Levels

### PCGForestExample
**Path:** `PCGExamples/Content/Levels/PCGForestExample.umap`

Basic example of using PCG to generate a forest.

**PCG Graphs used:**
- `PCG_Forest` — Simple graph that samples the terrain and generates a forest from various tree static meshes
- `PCG_DetailedForest` — Improves on the simple forest and adds details around the base of the tree, with meshes scaled based on distance from tree
- 'PCG_SplineForest' - Uses the interior of a spline to set the bounds of the forest

---
