# Chores

One folder per routine. Name it in lowercase with dashes: `daily-check-in`, `mysterious-shop`.

Each holds:

- **`chore.md`** — for people. The goal, when it is done, the steps in words, what to watch for.
- **`chore.json`** — for the app. The same steps, in the shape `../schema/chore.schema.json`
  describes.

## What a good step looks like

> Tap the green **CLAIM** button in the lower middle of the daily screen. It turns into a grey
> **CLAIMED** button and a "Reward claimed!" box appears over the screen.

It says what to look for, what to do, and how you know it worked. That last part is what lets the
app tell "it worked" from "nothing happened".

## What a bad step looks like

> Tap at 50%, 76%.

A coordinate alone breaks on a different phone, and silently taps the wrong thing after a game
update.
