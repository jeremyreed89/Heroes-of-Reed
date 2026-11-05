# Heroes of Reed

A small single-file HTML combat game in the style of classic hex-grid fantasy strategy battles.

Open `index.html` in any browser — no build step.

- 15×11 hex battlefield on a grassy field with random rocks and bushes
- One red stack vs one blue stack (squares), with mounted heroes at each side
- Turn order by speed, move/attack, retaliation once per round, Wait, Defend
- Hero spellbook (Magic Arrow, Cure, Stone Skin, Bloodlust), one cast per round
- Play vs computer (you are Red) or hot-seat for 2 players

Keys: `W` wait, `D` defend, `S` spellbook, `Esc` close spellbook.

---

# Memory Trainer (playing cards)

Open `memory/index.html` in any browser (phone or desktop). It's a single file with no build step. Your data stays on the device (browser localStorage).

- **Learn**: flash cards, in order or random. Tap a card to flip it and see its Person / Action / Object (or only one of them), then mark ✗ or ✓. Your score shows after 52 cards, and you can retry the ones you missed.
- **My PAO Deck**: enter a person, action, and object for each card. Export/import JSON, or paste a `card, person, action, object` list (works from spreadsheets).
- **Test**: memorize a shuffled deck against the clock, 1 or 3 cards at a time (switch any time, swipe or tap to advance, keep cycling). Press Done, then rebuild the order by tapping cards from the sorted deck. Drag to reorder, tap to send a card back. Submit to see your % and time.
- **Records**: best accuracy, and fastest time at 90% or higher.
