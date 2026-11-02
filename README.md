# Brightbud

A learning game for kids on iPad. Children answer questions in four subjects, earn stars, and spend them to dress up and grow their own bud character.

**Play it:** https://nish83.github.io/brightbud/

## Put it on an iPad

1. Open the link above in **Safari** on the iPad.
2. Tap the **Share** button, then **Add to Home Screen**, then **Add**.
3. Open Brightbud from the home screen. It runs full screen and works offline after the first visit.

Each child's progress is saved on that iPad.

## What's in it

- **Maths, Words, Numbers and Geography**, each with 10 levels. A child moves up after 4 right answers in a row and back down after 2 wrong in a row.
- **Step-by-step explanations** after every answer, right or wrong, with an option to read them aloud.
- **Stars and the Bud Shop:** colours, hats, glasses, capes, wings, pets and worlds to buy. The bud grows from a seed to a Mighty Bloom as stars are earned.
- **Colouring:** 12 pictures (nature, animals, princesses and magic). Tap a shape to fill it, including rainbow and glitter. Pictures save automatically.
- **Dress-up:** six original characters (Princess Juniper, Princess Rosa, Marina the Mermaid, and Hana, Yuna and Dara of the Starlight Hunters, a K-pop idol trio who battle gloom monsters). Change hair, tops, bottoms, dresses, shoes, accessories, props, places and skin tone, each in many colours. Special items unlock with stars. Includes makeup and a **Fashion show** mode: a theme is revealed, you dress up against a 2-minute timer (optional), walk the runway, and three judges score the look and say what they loved. Finish 1st, 2nd or 3rd on the podium to win stars.
- **Grown-ups area** (hold the button): levels and accuracy per subject, manual level changes, reading voice, sound, and player management.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole game: layout, questions and logic |
| `manifest.webmanifest` | App name, colours and icons for the home screen |
| `sw.js` | Offline cache. Change `VERSION` when you update the game |
| `icons/` | App icon (`icon.svg` is the source) |

## Updating

Edit `index.html`, bump `VERSION` in `sw.js`, then commit and push to `main`. GitHub Pages republishes in about a minute, and installed iPads pick up the change the next time the app is opened with an internet connection.
