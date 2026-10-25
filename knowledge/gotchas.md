# Things that trip automation up

Anything that makes a routine stop working, and what to do about it. Write these down the moment
one is seen — they are the difference between a chore that works once and one that works daily.

## Already known, from building the app

- **A greyed-out button is the same shape as the live one.** A claimed "CLAIMED" button matched
  the green "CLAIM" button when compared by shape alone. The app now also compares colour.
  *Source:* app testing, 2026-10-24 · — Claude, 2026-10-25
- **Eggs are re-rolled every run** in the Lost Sanctum, so a nest that was empty last run may hold
  one now. Never carry last run's ticks over. *Source:* app testing · — Claude, 2026-10-25

## Seen in recent videos (environment run, 2026-10-25)

Evidence for all of these: `log/2026-10-25-environment-videos.md` · — Claude, 2026-10-25

- **A "Rate Me" popup can appear in the middle of play** — a review request with *Maybe Later* and
  *Confirm*. **What to do:** every chore should check for it before each step and tap Maybe Later.
- **Paid buttons sit right next to free ones.** Companion Handbook has **Buy Level** and "Level Up
  to Collector's Edition" beside the reward track; Inventory has **Sell**; Mail has **Delete Read**
  next to **Claim All**; the main menu's right rail ends in a power (log-out) button. **What to
  do:** a chore must name exactly the button it wants, and the app should refuse any step whose
  landmark reads Buy, Sell, Delete, Level Up or a price.
- **Tapping a creature locks onto it.** "Tap Model to Lock On Target" is **on** by default
  (Settings → Game). A tap out in the world that misses a button can lock on to an Aniimo and
  swing the camera. **What to do:** chores that tap in the world must expect a lock-on, or the
  player can switch that setting off.
- **The top-right icon row grows as the account levels.** Three icons at level 15, seven at 51, so
  every icon's position shifts. **What to do:** find icons by picture, never by position.
- **The skill buttons are renamed by whatever Aniimo is in the party** (Damage, Control, Dash, Heal,
  REGEN …). **What to do:** never write a chore step as "tap Dash" — the button may not exist.
- **The game refuses taps that come too fast** — a toast "Actions too frequent" appeared in combat,
  and "Insufficient EP to use this skill" when energy ran out. **What to do:** leave a pause
  between taps and treat either toast as "wait, then retry".
- **Events come and go every update, and their order in the Events list changes.** **What to do:**
  find an event by its title, never by its row.
- **Recovery exists:** Settings → Game → **Unstuck** [Confirm] frees a stuck character. A walking
  chore that stops making progress can use it.

## Seen while watching players do their dailies (2026-10-25)

- **Claimed Daily Activity cards jump to the end of the row.** Every claim shifts the rest left,
  so a chore can never reuse the last claim's position. **What to do:** a repeating step that
  searches the whole row each time.
- **Daily Activity chests are claimed separately from the cards.** Claiming every card leaves the
  reward chests on the points bar waiting, each with a red gift badge. **What to do:** a second
  loop for the chests, with its own close for the "Item Obtained" box.
- **The Shop's bottom row mixes free and paid tabs** — Corner Shop sits right beside Top-Up, Pack
  and Monthly Pass. **What to do:** never tap those three; find Corner Shop by its words.
- **The app runs consecutive repeating steps as one loop.** Two separate loops need an ordinary
  step between them. **What to do:** as in `chores/daily-activity-claim/`, step 6.
- **The app has no optional steps yet.** The schema's `optional` (for popups that show only
  sometimes) is not understood by the app — a missing popup would stop a chore. **What to do:** the
  importer must skip an optional step that is not on screen, before any drafted chore can run.

*Source:* `log/2026-10-25-streamer-dailies.md` — Claude, 2026-10-25

## Template

- **What happens:** the symptom, as the player would describe it.
- **Why:** what is actually going on.
- **What to do:** how a chore should handle it.
- *Source:* · *signed:*
