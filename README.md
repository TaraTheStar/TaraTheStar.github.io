# tarathestar.github.io

The landing page at <https://tarathestar.github.io/> — a single static
`index.html`, no build step. GitHub Pages serves it from `main` at the repo
root; the project sites (`/enso/`, `/familiar/`) are separate repos published
under the same origin and are unaffected by anything here.

## Palette

The suite shares a spine and varies one axis. Paper (`hue 41, L 95%`) and gold
(`#6f5520` light / `#c9a55c` dark) are constant everywhere. Each project owns a
hue: its dark background is that hue at `L≈9%`, its accent the same hue at
`L≈75%` dark / `L≈29%` light. Type is Lora + JetBrains Mono throughout.

| project | hue |
|---|---|
| ensō | 306° (Kaimurasaki) |
| familiar | 269° |
| this page | 245° (indigo) |
| azoth | — uses the shared gold, being the substance the others hold in common |

Both themes are defined here: dark on `:root`, light under
`prefers-color-scheme: light`.
