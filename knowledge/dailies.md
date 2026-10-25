# The daily routine

What the player does every day, in the order they do it, and why each one is worth doing.

## What the player wants done

From the conversation of 2026-10-24:

- Collect the coins at the RV / Homeland.
- Buy everything in the mysterious shop.
- Daily check-ins and the goodies they give.
- Some simple daily quests.

— Claude, 2026-10-25

## From written guides — read, not yet seen in game

Gathered from fan guides on 2026-10-25, in my own words. **None of this is confirmed against the
player's own account**, and fan guides lag game updates, so treat every number as "probably" until
a recording shows it. Each becomes a candidate chore.

### Daily Activity — five tasks, a points bar

Five tasks each day: log in · spend 60 Primegy · catch 5 Aniimos · take one photo · collect 50
Season Stamps. All five give 700 activity points, and only **500** are needed to claim all five
reward packs — so two of the five can be skipped. Worth knowing: an automated routine does not
have to do everything.

*Unknown:* which tasks are cheapest to automate, and what the activity bar looks like on screen.

**Correction (2026-10-25, Claude):** the five tasks are **not fixed**. The Daily Activity screen
in a 18 Sept 2026 guide showed: Primegy (spend 60, +200) · Combat (defeat 5 Aniimo of any type,
+100) · Homeland (place an Aniimo in your Home, +100, with a **Go** button) · Log In (+100) ·
Stamps (earn 50 Season Stamps). Catching and the photo were not there. So at least the middle
tasks rotate, and a Daily Activity chore must read the cards each day rather than assume a list.
The screen also shows daily caps ("Obtained Today": EXP 0/3000 and tickets 0/1200) and the
reward chests at 100/200/300/400/500. *Source:* `log/2026-10-25-environment-videos.md`


### Shops that restock daily

Named in the guides: **Mysterious Vendor**, Curio Corner Shop, Outpost Vendor, Glimmer Exchange,
FunTown Shop. The player's "mysterious shop" is almost certainly the Mysterious Vendor.

*Unknown:* where each one is, how you travel to it, whether buying is one tap or a confirm.

### Primegy — the energy

Caps at 300 (600 with a monthly pass) and refills one point every six minutes. One of the five
daily tasks is spending 60 of it. Because it caps, letting it sit full wastes it.

### Free Nurture

One free Nurture a day, stacking up to three. At three, the next one is lost — so this is worth
doing daily even when nothing else is.

### Daily Supply Packs

Bought from the Item Exchange, refresh daily, 50 Primegy each. Buying one also covers the "spend
60 Primegy" task, near enough.

### Homeland / RV — daily jobs

Send Aniimos on six-hour trips, run the robot's jobs (about five a day), refill the incubators.
This is where the player's "RV coins" sits.

### Reset

Daily tasks reset at **04:00**. Anything claimed after that counts for the new day.

*Sources:* games.gg daily checklist · allthings.how daily activity guide · selphie1999gaming
dailies guide · mein-mmo (Homeland) — all read 2026-10-25 — Claude, 2026-10-25

## Seen on screen — where each daily lives

From recent videos; see `knowledge/screens.md` for what each screen looks like.

- **Daily Activity** — Institute Guide (card icon top-right, or main menu → Institute Guide).
  Cards that are done but not claimed, and the reward chests on the points bar, are the taps.
- **Stamp Rush** — same screen, third tab. Weekly, capped at 1000.
- **Event check-ins** — Events (calendar icon). Each check-in event has day cards; today's shows a
  live **Claim**.
- **Mysterious Vendor** — has its own page in Events with **Go Now**, which takes you to it.
- **Mail** — main menu → envelope → **Claim All**. Not daily as such, but rewards and
  compensation arrive here and letters expire.
- **Harvest Moon Festival** — until **28 Oct 2026 05:00 UTC**, with its own **Harvest Dailies**
  tab. Time-limited: worth a chore only if it is quick to make.

— Claude, 2026-10-25

## The routine as regular players run it

Three dedicated creators, filmed 1–19 Oct 2026, do the same things in nearly the same order.
Marked **menu** where it can be done from menus alone (a chore can do it today), **walk** where the
character has to move, **play** where it needs judgement.

1. **Shop → Corner Shop → Open All** — reveals the day's cosmetic stock. *menu*
2. **Shop → Corner Shop → Exchange → Mysterious Vendor** — buy the day's rotating stock; each item
   has a daily limit and a max button. Kairos does this first, every login. *menu* — this is the
   player's "buy everything in the mysterious shop", and it needs **no walking**.
3. **Spend Primegy** before it caps at 300: Institute Guide → Aniimo Challenge (fights, *play*), or
   Shop → Exchange → Outpost Vendor → **Daily Supply Pack** (*menu*, weaker value).
4. **Homeland:** Aniimo on a Trip, home orders, seeds, food, bud tickets, processors, egg hatchers,
   selling surplus. *menu + walk*
5. **Nurture** — one free a day, stacks to three; reached from the Map. *menu*, unconfirmed
6. **Institute Guide → Daily Activity → claim** everything, then the chests. *menu* — chore drafted:
   `chores/daily-activity-claim/`
7. **Mail → Claim All.** *menu* — chore drafted: `chores/claim-mail/`
8. **Egg Heist** — at least one run a day (the first gives double rank points). *play*
9. **Events** — whatever is running; check-ins have a Claim on today's card. *menu*

**Weekly** (Kairos, zenitizer): Companion Handbook quests and its stamp Exchange, the season shop,
discounted pods at Outpost Vendor and Super Claw, a weekly ticket at Coilstrike Club, the hardest
Holo-Battle Sim, Holo-Battle Interlink, Omega challenges (three each), emptying the Homeland
warehouse.

**Daily Activity tasks seen so far** (they rotate): Log In · Primegy 60 · Stamps 50 · Catch 5 ·
Combat (defeat 5) · Homeland (place an Aniimo) · Shop (buy any item). Buying at the Mysterious
Vendor covers "Shop"; buying a Daily Supply Pack covers most of "Primegy".

*Source:* `log/2026-10-25-streamer-dailies.md` — Claude, 2026-10-25

## More detail on the routine (2026-10-25)

- **Primegy is spent by claiming Alphas:** after a win, "Catch and Claim Rewards" costs 30.
  It refills one point every six minutes — 30 hours from empty to the 300 cap; the full-recovery
  timer agreed (37 missing showed 3 h 36 m). "Replenish Primegy" adds 60 for Glimmer.
- **Nurture:** teleport to a Bloom from the map, open Nurture, pick a region and an offering,
  tap Nurture. "Daily Nurture Chances x/25" is shown; each costs one Nurture crystal.
- **Homeland is mostly menus:** Home Overview → Service Hub → Daily Orders (Deliver, free
  refreshes) and Home Shop (seeds, selling). Trips give rewards with Confirm and Send Again. The
  plots and the chair buff need walking.
- **Aniilog Level → Submit Report** pays out research rewards — a new menu-only claim.
- **Weekly shops seen:** Super Claw (weekly limit 20 on discounted pods), the season shop's Weekly
  tab, the Egg Heist shop (daily limits, Chaos Tickets). Holo-Battle Sim resets weekly.

*Source:* `log/2026-10-25-gap-fill.md` — Claude, 2026-10-25

## The player's own routine (2026-10-25)

Seen in full in `log/2026-10-25-player-recording-1.md`. In order: login calendar → Events
(check-ins, Keep the Spark) → Corner Shop Open All → Daily Activity claim → teleport to Horizon
Square and **Check In** at the Sparkelf statue → **Mysterious Vendor by teleport and a short walk
to Weston** (buys to the daily limits: Primegy Battery ×2, Common Held Item Core ×5) → Breezy
Plains Outpost: **Research Console** (Aniilog report) and **Joff** (Daily Supply Pack ×3) →
claim Daily Activity and event tasks → Omega Sherro (weekly, 3 tries): teleport, jump to night,
twine, fight, chest (50 Primegy) → RV Park trips → Homeland: Home Shop, Daily Orders (free then
paid refreshes), Co-op Store sell, Harvest Dailies → a friend's Home: mine and till soil → Leave.

**Correction (2026-10-25, Claude):** the Mysterious Vendor is reached two ways — Shop → Corner
Shop → Exchange (Kairos, menu only) *or* Map → Mysterious Vendor → Teleport → walk to Weston (the
player). The menu route is the one to automate. *Source:* `log/2026-10-25-player-recording-1.md` — Claude, 2026-10-25

## Template

### <routine name>

- **Worth it because:** what you get.
- **Resets:** when it becomes available again.
- **Needs:** anything you must have first (a key, enough coins, a certain level).
- **Steps:** in words. Link the chore folder that automates it.
- *Source:* log entry · *signed:* who, when
