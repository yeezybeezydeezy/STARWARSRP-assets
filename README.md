# STARWARSRP assets

Model data for the PAC 3 Suite Texture Painter (https://yeezybeezydeezy.github.io/STARWARSRP/painter/): the server's clone,
fleet and general player models.

- `models.json`: every model, by family
- `m/<model>.json`: bodygroups, mesh parts, materials (.vmt settings and textures) and clothing pieces; `m/<model>_<slot>.png` piece maps
- `g/<hash>.bin.gz`: mesh parts, shared between models (float32 position, normal, UV; then uint32 indices)
- `vtf/<id>.vtf`: the game's textures, unchanged
