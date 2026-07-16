# Circuit Typist

A falling-words typing speed arcade game. Words drop down a circuit-board playfield — type each one before it hits the floor. Speed and word difficulty ramp up over time, and WPM/accuracy are tracked live.

## Play

**[Play it here](https://bluelabelcommerce-cell.github.io/typing-speed-game/)** — or open [`index.html`](./index.html) locally in a browser.

## How it works

Single self-contained HTML file — no build step, no dependencies. Vanilla HTML/CSS/JS, driven by `requestAnimationFrame`.

- Words spawn at the top and fall at increasing speed as you level up.
- Type letters to match the word closest to the floor that starts with them; matched letters light up.
- Miss a word (it reaches the floor) and you lose one of 5 lives; run out and it's game over.
- Live stats: WPM, accuracy, score, combo, and level, with a results screen at the end of each run.
