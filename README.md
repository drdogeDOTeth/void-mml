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
script, so they stay up without a server.

The rideable version, a dock where every player gets their own bike that follows them (built for 100+ players),
is a scripted document run from the MML Editor. It is not hosted here, but it loads its models from here.

| Model | Use |
|---|---|
| `HoverBike_MML_Body.glb` | the bike, full detail (27,210 triangles), no plumes |
| `HoverBike_MML.glb` | the bike with its five plasma plumes, for the attachment |
| `HoverBike_MML_Lite.glb` | the crowd bike: 7,586 triangles with the side and lift plumes baked in, no rear plume |
| `PlasmaJet_MML.glb`, `PlasmaJet_MML_Lite.glb` | one plume (1,920 / 400 triangles), 1 m along +X from the nozzle |

Metres, +Y up, the bike faces +X, origin on the ground under its middle. The seat is aqua blue. Light and
material emission never exceed 1.
