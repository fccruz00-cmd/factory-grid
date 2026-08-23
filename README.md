# Factory Grid

Jogo incremental de automação em Canvas 2D, inspirado em fábricas encadeadas e exploração top-down.

## Jogar

**https://fccruz00-cmd.github.io/factory-grid/**

## Sistemas

- Extração de ferro e cobre
- Esteiras, divisores, combinadores e túneis subterrâneos
- Fornalhas e montadoras com receitas configuráveis
- Produção incremental e progresso offline
- Árvore tecnológica e prestígio
- Paredes, torretas, munição e waves inimigas
- Save automático no `localStorage`

## Controles

- `WASD` ou setas: mover
- `B`: modo de construção
- `1–9`: selecionar construção
- Botão direito no modo BUILD: remover
- `R`: girar
- `F`: inverter divisor/combinador
- `C`: receitas
- `U`: melhorar
- `T`: tecnologias
- `M`: menu

## Tecnologia

HTML, JavaScript puro e Canvas 2D, sem bibliotecas externas.

## Arte

As construções usam sprites cartoonescos de 40 × 40 px gerados com PixelLab. Os arquivos e o mapeamento ficam em `assets/sprites/`; o render vetorial anterior permanece como fallback durante o carregamento.
