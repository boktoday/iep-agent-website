# IEP Ally website

The promotional site for **IEP Ally**, a free, local-first IEP planning agent for parents.

- Live: https://boktoday.github.io/iep-ally-website/
- The agent: https://github.com/boktoday/iep-ally-hermes-agent

## Pages

- `index.html` — hero, what it does, how it works, the team, privacy, download
- `hire.html` — the paid human side (setup sessions, workshops, advocacy prep)
- `legal.html` — terms, disclaimer, privacy

## Palette

Pinks, purples and a soft green, carried from the IEP Companion Generator app it grows out of:
purple `#9333ea` / `#581c87`, pink `#f472b6` / `#fdf2f8`, green `#4ade80` / `#f0fdf4`.

## Notes

- `assets/og-card.png` is rendered from `og-card.html` (Playwright, 1200x630).
- Site pages carry the OneDollarStats cookieless counter, matching the rest of the estate.
- Square corners, Newsreader + Inter, a working hamburger on mobile. Render gate: no horizontal overflow at 390 and 1440.
