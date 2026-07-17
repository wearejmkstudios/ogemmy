# OG Emmy — EPK Microsite

Official electronic press kit / landing page for **OG Emmy**, a London-based Nigerian Afrobeats artist.

A single-page static site — no build step, no framework. Open `index.html` directly, or serve the folder with any static host.

## Structure

```
index.html            Full site (Hero, Bio, Releases, Watch, Listen, Gallery, Events, Merch, Follow, Booking, Footer)
styles.css            Root stylesheet — imports Google Fonts + design tokens
tokens/               Design tokens: colors, typography, spacing, effects
assets/
  logo.png            Spotlight-ring wordmark (JMK Studios)
  icons/              Official social platform marks (Instagram, X, YouTube, Spotify, Apple Music)
  photography/        Artist photography (JMK Studios), web-optimized
```

## Design system

Colors, type, spacing and effects are driven entirely by CSS custom properties in `tokens/`.
Near-black backgrounds, a single warm-gold accent, condensed display caps (Anton), a cursive script
(Give You Glory) for song titles, Manrope for body, and IBM Plex Mono for metadata.

Fonts are Google Fonts substitutes for the look in the source press kits; swap in real brand fonts if available.

## Credits

Design & build by [JMK Studios](https://wearejmkstudios.io).
