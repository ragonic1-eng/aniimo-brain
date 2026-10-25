# Rules for anything writing to this repo

Applies to every assistant (Claude, ChatGPT, Codex, …) and to people.

## 1. What must never go in

- **No game art, map images, icons, or screenshots.** Describe a button in words
  ("green CLAIM button, lower middle"), never paste the picture.
- **No data copied from fan sites** (aniimotools.dev and the like). Their layout data and map art
  stay in the app's own private repo. Our own measurements and observations are fine.
- **No video files**, and nothing large. If a file would be over ~1 MB, it does not belong here.
- **No account details**, UIDs, or anything personal from a recording.

This repo may be public. Everything in it must be safe to be public.

## 2. How to write

- **Plain words.** Someone who has never played should be able to follow a chore.
- **Say where a fact came from**: `seen in log/2026-10-25-dailies.md`, `measured in the app`,
  `told by the player`. A guess must say it is a guess.
- **Never delete or rewrite someone else's note.** If it is wrong, add a `**Correction (date,
  who):**` line underneath saying what is wrong and how you know.
- **Sign what you add** at the end of the section or log entry: `— Claude, 2026-10-25`.
- Keep it short. A fact that earns its place is worth two sentences, not two paragraphs.

## 3. Watching a video

One `log/` entry per video, named `YYYY-MM-DD-what-it-shows.md`. In it:

- how long it was, what the player set out to do;
- the screens that appeared, in order, with the time they appeared;
- every tap: what was tapped and what happened;
- anything surprising — a popup, a wait, a thing that only happens the first time.

Then update `knowledge/` with what is new, and `chores/` with the routine itself. The log is the
evidence; `knowledge/` and `chores/` are the conclusions.

## 4. Chores

Each chore is a folder under `chores/`, named in lowercase with dashes:

- `chore.md` — the goal, when it counts as done, the steps in words, and what to watch out for.
- `chore.json` — the same steps, in the shape `schema/chore.schema.json` describes, so the app
  can run them.

A chore step says **what to look for** and **what to do**, never a bare coordinate: screens move
between phones and between game updates. Coordinates are a hint for where to look first.

## 5. Disagreeing

Two assistants will sometimes read the same video differently. Do not argue in the files. Write
both readings with the evidence for each, mark the one you believe and why, and let the player
settle it. A note that says "unsure" is worth more than a confident wrong one.
