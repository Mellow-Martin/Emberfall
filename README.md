# Emberfall Chronicles

A turn-based fantasy RPG for phones, built as a single HTML page with hand-cleaned pixel art.

**Play:** open `index.html` in any browser (or the GitHub Pages link once Pages is on). Progress saves in the browser.

## What's in it
- Three classes, each with its own weapon line: Warrior (swords), Mage (staves), Rogue (paired daggers)
- Five armor/weapon tiers that change how your hero looks
- Three regions plus their boss lairs: Mosswood, Ashen Crypt, Cinder Peaks
- Melee/magic and fire/frost/poison weaknesses on every enemy; armor resists elements
- Hunts, boss challenges after 4 wins, and the Final Stand (endless waves, no retreat)
- The Lantern Inn: rest, buy and sell gear with a try-on preview, potions (10 max each)

## Layout
- `index.html` — the whole game; all art is embedded
- `art/final/` — the cleaned sprites, backgrounds, UI kit and effects the game uses
- `art/scripts/` — Python used to key, pixelize and slice the generated art

Art generated with Higgsfield (Nano Banana 2.1) and cleaned for the game.
