Rebuilt character: Meshy v7 output re-fitted onto a clean template body (MakeHuman CC0 base mesh, 13,380 verts / 13,378 quads, 9 UV islands).

Files
  original_meshy_output.glb        the generated mesh as it came out of Meshy (41k tris, 4,118 UV islands)
  rebuilt_white_outfit.glb         Body + Head (template topology, baked 2048 texture), Eyes (2 patches), Hair (shell cut from the original)
  rebuilt_black_outfit.glb         same, with the outfit recoloured in UV space (mask in texture_black_outfit.png)
  rebuilt_head_split_exploded.glb  head as its own mesh with its own texture, lifted 16 cm to show the split
  rebuilt_body_quads.obj           quad mesh with UVs; groups: Head, Body, EyeSockets_hidden
  texture_*.png                    baked base colour (2048), outfit variant, head-only, body-only
  metrics.json                     fit distances and counts
  board*.jpg                       comparison renders

Known rough spots: lip seam is slightly jagged, lid edges have small artifacts, fine cloth detail (hems) is smoothed (no normal map baked yet), scalp under the hair carries hair colour.
