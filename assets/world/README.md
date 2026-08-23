# Factory Grid world sprites

Cartoon pixel-art props generated with PixelLab and integrated at the game's native 40 × 40 tile size. Terrain is rendered procedurally so water, grass, roads, and shorelines remain continuous across the grid.

## Included assets

- `tree.png`, `rock.png`: environmental props with transparent backgrounds
- `deposit_*.png`: distinct iron, copper, coal, and tungsten deposits
- `player_*.png`: four directional views of the Factory Grid engineer
- `enemy.png`: base scrap-raider sprite; enemy classes are color/size variants in the renderer
- `coast_tileset.png`: 25-piece PixelLab Wang terrain set used only at grass/water transitions
- `road_tile_*.png`: 18-piece PixelLab path set covering ends, straights, corners, T-junctions, and crossings

## Art direction

High top-down cartoon pixel art with compact silhouettes, selective outlines, crisp color clusters, soft down-right shadows, and consistent top-left lighting. Prompts requested readable single-cell assets with no text or ground baked into transparent props. Grass, animated water, shore banks, and roads are code-rendered to avoid visible seams and repeated texture stamps.

Generated through the PixelLab MCP on 2026-08-23. The renderer retains vector fallbacks if an image cannot be loaded.
