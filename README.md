# void-mml

Static MML documents and models for Otherside, served by GitHub Pages at
`https://drdogedoteth.github.io/void-mml/`.

## Hover bike

| Document | What it is |
|---|---|
| [`hoverbike/parked.html`](https://drdogedoteth.github.io/void-mml/hoverbike/parked.html) | Hovering in place: bobbing, idling jets, cyan underglow. Place it on the ground. |
| [`hoverbike/flyby.html`](https://drdogedoteth.github.io/void-mml/hoverbike/flyby.html) | Flying a banked 20 m loop around its placement point, about 6 m up, one lap every 13 s. |
| [`hoverbike/attachment.html`](https://drdogedoteth.github.io/void-mml/hoverbike/attachment.html) | A single socketed `<m-model>`: the bike under a player, for worlds that add MML attachments. |

To use one in Otherside, add its URL and a name at https://www.otherside.xyz/mmls, then choose it from the
in-world MML menu (MML Director role).

They use only tags Otherside's Unreal clients support (`m-group`, `m-model`, `m-light`, `m-attr-anim`) and no
script, so they stay up without a server. Models: `HoverBike_MML_Body.glb` (27,210 triangles),
`HoverBike_MML.glb` (the bike with its five plasma jets, for the attachment) and `PlasmaJet_MML.glb` (one plume,
1 m along +X). Metres, +Y up, the bike faces +X.
