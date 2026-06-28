# T3dkky

A browser-based score keeper for **Mölkky**, the Finnish wooden pin-tossing game.

No installs, no accounts — just open it and play. Designed to sit on a table and be tapped between throws.

## Play

**[Open T3dkky →](https://t3dboy.github.io/T3dkky/)**

Works great on a phone. Add it to your home screen for a full-screen experience.

## Features

- Up to 10 players, all visible at once with no scrolling
- The current thrower is called out clearly at the top
- Tap a number (1–12) to add that score, or **Miss** for zero
- Full undo — step back through every throw to the very first
- Game state is saved automatically, so a refresh won't lose your scores
- **Rematch** keeps the same line-up for another round

## Rules

- Knock down **one pin** → score the number on that pin (1–12)
- Knock down **two or more pins** → score the number of pins knocked over
- First to **exactly 50** wins
- Go **over 50** and you drop back to **25**
- Miss every pin **three turns in a row** and you're eliminated

### Optional house rules

- **Fun Mode** — no penalty for going over 50; first to reach 50+ wins
- **Strike-outs off** — never get eliminated for missing

## Running locally

It's a single static file. Open `index.html` in any browser, or serve the folder:

```sh
python3 -m http.server 8000
```

then visit `http://localhost:8000`.
