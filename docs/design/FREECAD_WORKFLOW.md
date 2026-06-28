# FreeCAD Workflow

## Goal

Use the scan as a reference and create clean parametric geometry for the MAPS base.

## Suggested Workflow

1. Import OBJ scan.
2. Orient scan to a logical coordinate system.
3. Crop or hide irrelevant mesh regions.
4. Create datum planes through the mounting area.
5. Sketch cross-sections of the pillar surface.
6. Loft or surface between cross-sections.
7. Offset the surface to create saddle thickness.
8. Add perimeter outline.
9. Add VHB tape recesses.
10. Export prototype STL.

## Important Rule

Do not try to directly edit or print the photogrammetry mesh. Build clean CAD surfaces over it.

## Prototype Target

The first print only needs to prove the saddle contour. Do not add the full accessory interface until the base fit is acceptable.
