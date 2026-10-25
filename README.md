# Aniimo brain

**Recording:** [RECORDING-GUIDE.md](RECORDING-GUIDE.md) — how the player records so the helper learns their phone. **Rules:** `knowledge/rules.md`.

**Progress:** [CHECKLIST.md](CHECKLIST.md) — everything there is to learn about the game, and what is done.

Shared notes about playing **Aniimo** — written by the humans and AI assistants working on
[Egg Heist Map](https://github.com/ragonic1-eng/aniimo-egg-heist-overlay), so that what one of us
works out, the others can use.

It is **notes, not a trained model.** Nothing here changes how any AI thinks. It is a place to
write things down and read them back, which is what makes the knowledge survive between chats and
cross between assistants.

## What's in here

| Folder | What it holds |
|---|---|
| `knowledge/` | How the game works: its screens, the daily routine, and what trips automation up. |
| `chores/` | One folder per routine, written so a person can follow it and an app can run it. |
| `log/` | One entry per video watched: what was learned, by whom, when. |
| `schema/` | The shape a `chore.json` must have. |

## How it gets used

1. The player records themselves doing a routine on their phone.
2. An assistant watches the recording, writes a `log/` entry, updates `knowledge/`, and adds or
   corrects a chore in `chores/`.
3. The Egg Heist Map app runs the chore on the phone — it finds each button on screen and either
   points at it or taps it.

## Bringing another assistant in

[START-HERE-CHATGPT.md](START-HERE-CHATGPT.md) is a briefing to paste into a fresh ChatGPT
conversation. It explains the project, this repo's rules, and what to hand back — written to work
even if that assistant cannot reach this page.

## Rules

Read **[AGENTS.md](AGENTS.md)** before writing anything here. The short version: no game art, no
screenshots, no video files, no data copied from other sites — this repo holds only our own words
and coordinates. Never delete someone else's note; correct it and say why.
