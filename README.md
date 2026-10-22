# Ping Pong vs Bot

A table tennis game you play in the browser against a computer opponent. It is one file, `index.html`, with no build step or dependencies.

**Play it:** https://nickypeakin.github.io/ping-pong/

To run it locally, download or clone this repo and open `index.html` in any modern browser.

## Bot levels

| Level  | How it plays |
| ------ | ------------ |
| Easy   | Reacts late and chases the ball instead of predicting where it will go. |
| Medium | Predicts bounces off the side of the table, but only half-reads your sidespin. |
| Hard   | Reacts almost instantly, reads spin fully, and aims its returns away from your bat. |

Every bot gets less accurate as the rally speeds up, so even Hard can be beaten in a long rally.

## Controls

| Action | Mouse / keyboard | Touch |
| ------ | ---------------- | ----- |
| Move your bat | Mouse, or `↑` `↓` / `W` `S` | Drag on the table |
| Serve | Click or `Space` | Tap |
| Pause | `P` or `Esc` | Pause button |

Move your bat while you hit the ball to put sidespin on it, which makes the ball curve.

## Rules

- First to 11 points, and you must win by 2.
- Serve changes every 2 points, and every point once the score reaches 10–10 (deuce).
- Your win/loss record for each level is saved in your browser.

On a tall screen such as a phone held upright, the table turns so your end is at the bottom.
