
### How to fix shading issue in Unreal Engine if model (fbx) was created in Blender.
1. In Blender mark sharp edges explicitly (Edit Mode -> Select -> Select Sharp Edges, Set Required Angle, Mark Sharp Edges).
2. Shade model by auto-smooth with the same angle.
3. Export model as fbx with option: Geometry -> Smoothing = Edges.
