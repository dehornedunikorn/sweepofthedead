# Asset sheet — SWEEP OF THE DEAD

## Visual specification
- **Style:** gritty, readable 2D pixel-art; muted olive, concrete grey, rust red, dirty cream.
- **Camera:** strict top-down / slight 3-quarter for characters and props.
- **Target cell:** 64×64 px; transparent background for sprites.
- **Atlas layout:** 8 columns × 4 rows; 512×256 px total, 64 px gutters/cells.

## Atlas map
| Row | Cols 1–8 |
|---|---|
| 1 | Survivor idle, survivor hurt, walker, runner, crawler, armored walker, loot crate, exit gate |
| 2 | Grass tile, cracked asphalt, concrete, blood-stained ground, rubble, road marking, barricade, fence |
| 3 | Pistol, ammo box, canned food, bandage, backpack, flashlight, radio, map |
| 4 | Fog tile, revealed tile, danger marker, flag marker, health icon, ammo icon, food icon, medkit icon |

## Production rules
- Keep silhouettes distinct at 64 px.
- Use a 1 px dark outline and restrained highlights.
- No copyrighted characters, logos, or traced television-series artwork.
- Keep all gameplay-critical symbols legible at phone size.

The playable prototype currently uses native CSS/HTML glyph placeholders; this specification is the target atlas contract for replacing them without changing gameplay logic.
