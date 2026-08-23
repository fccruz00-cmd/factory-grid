# Factory Grid — PixelLab sprites

Conjunto de 18 sprites em pixel art cartoonesca, gerado com PixelLab para a grade nativa de 40 × 40 px do jogo.

- Câmera: top-down alta em 3/4.
- Paleta: verde-carvão, aço dessaturado, latão quente, ciano e menta.
- Orientação-base dos elementos direcionais: norte. O Canvas gira os sprites conforme `building.dir` ou `aimAngle`.
- Fundo: transparente quando o objeto não ocupa o tile inteiro. `belt.png` e `underground_out.png` são tiles de máquina opacos por design.
- Fallback: se uma imagem ainda não carregou, o render vetorial anterior continua sendo usado.

## Mapeamento

| Tipo do jogo | Arquivo |
| --- | --- |
| Hub | `hub.png` |
| `belt` | `belt.png` |
| `splitter` | `splitter.png` |
| `merger` | `merger.png` |
| `underground` entrada | `underground_in.png` |
| `underground` saída | `underground_out.png` |
| `miner` | `miner.png` |
| `furnace` | `furnace.png` |
| `assembler` | `assembler.png` |
| `terminal` | `terminal.png` |
| `wall` | `wall.png` |
| `turret` | `turret.png` |
| `cannon` | `cannon.png` |
| `railgun` | `railgun.png` |
| `beacon` | `beacon.png` |
| `deepDrill` | `deep_drill.png` |
| `repairStation` | `repair_station.png` |
| `tesla` | `tesla.png` |
