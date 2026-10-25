# Briefing for ChatGPT

Paste the text below into a new ChatGPT conversation. It is self-contained: it works even if
ChatGPT cannot reach the repo. Everything in it is also readable at
`https://raw.githubusercontent.com/ragonic1-eng/aniimo-brain/main/<path>`.

---

I'm building a helper that does my daily chores in a mobile game called **Aniimo**, and I want
you working on it alongside Claude Code, which runs on my PC. Please read this whole brief before
answering.

## The project

I play Aniimo on a Samsung phone. There's an Android app — **Egg Heist Map** — that already:

- draws the dungeon map over the game and points an arrow at the next egg nest;
- has a feature called **Help me Daily**, where I teach it a routine by doing it once, and it
  then repeats it for me — it finds each button on screen by its picture and either shows me
  where to tap, or taps it itself through an accessibility service.

What I want next is for it to learn routines from **screen recordings** instead of me teaching
each one by hand on the phone.

## How you fit in

I record myself doing a routine. The recording gets turned into:

1. **Knowledge** — what the game's screens are, what my daily routine is, what breaks automation.
2. **Chores** — the steps themselves, in a form the app can run.

That knowledge lives in a public GitHub repo so that you and Claude both work from the same
notes, and so nothing is lost when a conversation ends:

**https://github.com/ragonic1-eng/aniimo-brain**

Read these first:

- `AGENTS.md` — the rules for writing anything into the repo. **These apply to you.**
- `README.md` — what each folder is for.
- `schema/chore.schema.json` — the exact shape a chore must have.
- `knowledge/` and `chores/` — what is known so far (currently almost empty; that's the point).

## What you can and can't do here

- You **can** read that repo (it's public), read frames and screenshots I upload, and write text.
- You **cannot** run anything on my PC, or commit to the repo. So give me your work as text I can
  paste, in the exact file format, saying which path it belongs at — for example
  "`knowledge/screens.md`, add this section:".
- Claude handles the PC side: reading the video file, cutting it into frames, measuring where I
  tapped, and writing the app's own chore files.

## The rules, in short (full version in `AGENTS.md`)

- **Nothing copyrighted or personal goes in the repo.** No game art, no screenshots, no data
  copied from fan sites, no video files, no account IDs. Describe a button in words — "green
  CLAIM button, lower middle" — never paste the picture. The repo is public.
- **Say where every fact came from**, and sign it: `— ChatGPT, 2026-10-25`. If you're guessing,
  say you're guessing.
- **Never overwrite someone else's note.** If Claude wrote something you think is wrong, add a
  `**Correction (date, ChatGPT):**` underneath with what's wrong and how you know.
- **Steps are written as "look for this → do this → expect that"**, never a bare coordinate.
  Coordinates break on a different phone and after a game update. A coordinate may be a hint for
  where to look first, nothing more.
- **Say when you're unsure.** An honest "I can't tell from this frame" is worth more than a
  confident wrong answer — a wrong step makes the app tap the wrong thing on my live account.

## What I'll send you

Frames from my gameplay recordings, in order, with rough timestamps. For each batch I want:

1. **What's on each frame** — which screen, what the buttons say, what changed since the frame
   before.
2. **Where one routine ends and the next begins.**
3. **A draft chore** for each routine, as both `chore.md` (for people) and `chore.json` (matching
   the schema), ready for me to paste into the repo.
4. **Anything that looks like it would break automation** — a popup that only appears sometimes,
   a button that greys out once used, an animation that has to finish first.

## Things already learned, so you don't rediscover them

- A greyed-out button is the **same shape** as its live version. Comparing shapes alone made the
  app treat a used "CLAIMED" button as a live "CLAIM" one. Colour has to be compared too.
- In the Lost Sanctum dungeon, eggs are **re-rolled every run** — a nest that was empty last run
  may hold one now, so nothing about egg locations carries between runs.
- The app can replay taps, holds and swipes. It **cannot yet walk the character** around, so
  routines that need movement are out of scope for now; menu routines are in scope.

## Start by

Reading the repo, then telling me:

1. In your own words, what this project is trying to do, so I can check we agree.
2. What you'd want to see in a recording to describe a routine well — how long, what to include,
   anything I should do slowly or twice.
3. Anything in `AGENTS.md` you think is wrong or missing.

Don't write any chores yet — you haven't seen the game.
