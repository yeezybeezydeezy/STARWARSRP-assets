# STARWARSRP assets

Model data for the PAC 3 Suite Texture Painter (https://yeezybeezydeezy.github.io/STARWARSRP/painter/): the server's clone,
fleet and general player models.

- `models.json`: every model, by family
- `m/<model>.json`: bodygroups, mesh parts, materials (.vmt settings and textures) and clothing pieces; `m/<model>_<slot>.png` piece maps
- `g/<hash>.bin.gz`: mesh parts, shared between models (float32 position, normal, UV; then uint32 indices)
- `vtf/<id>.vtf`: the game's textures, unchanged

## Player models for PAC3

- `playermodels/<model>/`: the model as a GMod addon (model, hands, materials, Lua)
- `pac/<model>.zip`: the model and its materials, uncompressed, for PAC3's URL model loader
- `pac/<model>.txt`: a PAC3 outfit that makes you that model. Put it in `garrysmod/data/pac3/` and wear it (or `pac_wear_parts <model>`).
  It links the zip at a fixed commit, because PAC keeps a downloaded URL forever: a changed zip needs a new link.

| Model | Outfit |
|---|---|
| TheNoobOfficial_R (RoPorter) | `pac/thenoobofficial_r.txt` |
