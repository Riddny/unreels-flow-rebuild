# Growth Audit — Unreels

**Live:** https://riddny.github.io/unreels-flow-rebuild/

Five ranked ideas for the Unreels iOS onboarding and paywall, plus a clickable prototype that rebuilds them in Unreels' own design: the black canvas, the glowing lime button, the photo tiles, the gradient loader bars and the plan cards. Only what the screens say back to the user changes, plus one new screen when the paywall closes.

| # | Idea | Potential outcome |
| :-- | :-- | :-- |
| 01 | Offer the monthly plan (₪69.90, no trial) when the paywall closes | ARPU +10–15% |
| 02 | Make the paywall headline the goal they picked | CR +15–20% |
| 03 | Put 4.7 and 1M users next to the price | CR +10–15% |
| 04 | Let the loader name their niche, first pick and role | CR +10–15% |
| 05 | Show the criteria behind "660 templates" | CR +10–20% |

The prototype has English and Russian, light and dark, a 30-second walkthrough, and jump chips so you can open any screen with answers already filled in. On a phone it runs full-screen: https://riddny.github.io/unreels-flow-rebuild/?open=proto

## Grounding

Every price, rating, quote and claim comes from Unreels' own published material: the App Store listing (US and Israel storefronts, including the in-app purchase list) and the in-app screens. Prices are in shekels, as they appear on the paywall. The testimonials are quoted verbatim in Russian.

*Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps — not measured lift for Unreels.*

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.
