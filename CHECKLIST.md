# What there is to learn about Aniimo — the checklist

The whole game broken into its mechanics, and every thing an assistant must understand before the
helper can play it. Claude, ChatGPT and the player work through it together.

**How to tick.** Three columns, because "I watched someone do it" is not "it works on the player's
phone":

| Column | ✅ means |
|---|---|
| **Learned** | Understood from video or screenshots, written into `knowledge/` with a source |
| **Your phone** | Seen on the player's own phone (their screenshots or recording) |
| **Automated** | A chore or the app does it, and it has run on the player's phone |

🟡 = partly: read in a guide but not seen, or seen but not understood. ⬜ = not yet. **—** = not
something to automate. Only tick with evidence, and sign the change in the commit.

The **Kind** column says what an automated version would need: **menu** (taps in menus — the app
can do this today), **walk** (moving the character — possible, not built), **play** (judgement:
fighting, aiming — the hardest).

---

## 1. Controls and the screen (phone)

| # | Item | Kind | Learned | Your phone | Automated | What unblocks it |
|---|---|---|---|---|---|---|
| 1.1 | Joystick — where it is, that it starts where the thumb lands | walk | ✅ | 🟡 rest icon only | ⬜ | Walking steps in the app |
| 1.2 | Turning the camera | walk | ⬜ | ⬜ | ⬜ | A recording of the player walking |
| 1.3 | Main action button | play | 🟡 where, not what | ✅ | ⬜ | A combat recording |
| 1.4 | Skill buttons — they rename with the party | play | ✅ | ✅ | ⬜ | — |
| 1.5 | Dash, jump, dodge | walk/play | 🟡 Dash and Dodge seen; jump not | ✅ | ⬜ | A recording |
| 1.6 | Twine / Untwine (taking control of the Aniimo) | play | ✅ the ring becomes the Aniimo's moves | ✅ | ⬜ | A recording |
| 1.7 | Recall, switch target, lock-on | play | ✅ where | 🟡 | ⬜ | — |
| 1.8 | Pod throw and catch mode | play | ✅ reticle, chance, pod picker, Alpha catch screen | ⬜ | ⬜ | A recording of a catch |
| 1.9 | Top-right shortcut icons, and that the row grows with level | menu | ✅ | ⬜ | — | A screenshot from the player's HUD |
| 1.10 | Opening the main menu (pod-in-a-ring icon) | menu | ✅ PC labels it Esc | ⬜ | ⬜ | One tap seen on the player's phone |
| 1.11 | Reading the minimap | — | ✅ | ✅ | ✅ app finds the player 4 of 5 | — |
| 1.12 | Quest tracker under the minimap | — | ✅ | ⬜ | — | — |

## 2. Getting around the world

| # | Item | Kind | Learned | Your phone | Automated | What unblocks it |
|---|---|---|---|---|---|---|
| 2.1 | The world map and its panels | menu | ✅ | ✅ | — | — |
| 2.2 | Teleporting from the map | menu | ✅ tap a Bloom → Teleport | ⬜ | ⬜ | A recording |
| 2.3 | Walking to a place | walk | ⬜ | ⬜ | ⬜ | Walking steps + 2.2 |
| 2.4 | Regions, branches, Breezy Plains etc. | — | ✅ 14 Idyll regions, listed in Nurture | 🟡 | — | — |
| 2.5 | Unstuck (Settings → Game) | menu | ✅ | ⬜ | ⬜ | — |
| 2.6 | Weather schedule on the map | menu | 🟡 Help covers weather; a time-of-day dial | ⬜ | — | — |

## 3. The menus — knowing every screen

| # | Screen | Learned | Your phone | Notes |
|---|---|---|---|---|
| 3.1 | Main menu grid and its right rail | ✅ | ⬜ | |
| 3.2 | Events (check-in cards, Go Now, Rules) | ✅ | ⬜ | Changes every update |
| 3.3 | Institute Guide: Daily Activity, Aniimo Challenge, Holo-Battle Sim, Stamp Rush | ✅ | ⬜ | Four card states known |
| 3.4 | Log — the quest menu (Lore / Quests / Journey) | ✅ | ⬜ | |
| 3.5 | Elite Training (five paths) | ✅ | ⬜ | |
| 3.6 | Settings (six tabs) | ✅ | ⬜ | |
| 3.7 | Character → Profile | ✅ | ⬜ | |
| 3.8 | Inventory (out in the world) | ✅ | ⬜ | The player's inventory shots are the Egg Heist one, a different screen |
| 3.9 | Mail | ✅ | ⬜ | |
| 3.10 | Shop: Corner Shop, Exchange, vendor pages | ✅ | ⬜ | Top-Up / Pack / Monthly Pass are paid |
| 3.11 | Season Achievement | ✅ | ⬜ | |
| 3.12 | Companion Handbook (season pass) and Monthly Pass | ✅ | ⬜ | Buy Level is paid |
| 3.13 | Aniimo Management | ✅ | ⬜ | Release is never in a chore |
| 3.14 | Party | ✅ | ⬜ | A battle party of four, on the Aniimo screen |
| 3.15 | Aniilog (the Aniimo index) | ✅ | ⬜ | Aniilog Level → Submit Report |
| 3.16 | Friends | ⬜ | ⬜ | Needed for "message friends" |
| 3.17 | Appearance | 🟡 seen once | ⬜ | Low priority |
| 3.18 | Courses | ⬜ | ⬜ | |
| 3.19 | Homeland menus: Manage, Build, Warehouse, orders, processors | ✅ Home Overview, Daily Orders, Trips, Home Shop | ⬜ | Build and Warehouse not yet seen |
| 3.20 | Hatching screen (Hatch, Twine an Aniipod) | ✅ | ⬜ |  |
| 3.21 | Start-up: login, announcements, server select | 🟡 server select only | ⬜ | Every chore day starts here |
| 3.22 | Character → Info · Badges · Talents | ✅ | ⬜ | Title, level, Aniimo level cap, Paths |
| 3.23 | Nurture and Nurturing Offering | ✅ | ⬜ | |
| 3.24 | Help (in-game encyclopedia) | ✅ | ⬜ | Good for checking a mechanic |
| 3.25 | Egg Heist shop | ✅ | ⬜ | Chaos Tickets, daily limits |

## 4. The daily routine

| # | Item | Kind | Learned | Your phone | Automated | What unblocks it |
|---|---|---|---|---|---|---|
| 4.1 | Claim Daily Activity tasks and chests | menu | ✅ | ⬜ | 🟡 drafted | Chore import + optional steps in the app |
| 4.2 | Mail → Claim All | menu | ✅ | ⬜ | 🟡 drafted | Same |
| 4.3 | **Mysterious Vendor — buy the day's stock** | menu | ✅ | ⬜ | ⬜ | Draft the chore |
| 4.4 | Corner Shop → Open All | menu | ✅ | ⬜ | ⬜ | Draft the chore |
| 4.5 | Daily Supply Pack (spend Primegy) | menu | ✅ | ⬜ | ⬜ | Draft the chore |
| 4.6 | Primegy: cap 300, +1 per 6 min, where to spend it | menu/play | ✅ 30 per Alpha claim; Glimmer refill | ⬜ | ⬜ |  |
| 4.7 | Free Nurture (one a day, stacks to 3) | menu | ✅ Map → Bloom → Nurture | ⬜ | ⬜ | A recording |
| 4.8 | Event check-ins | menu | ✅ | ⬜ | ⬜ | One chore per event; they change |
| 4.9 | Homeland / RV: trips, orders, seeds, food, bud tickets, processors, hatchers | menu + walk | ✅ orders, trips, shop; plots need walking | ⬜ | ⬜ | A recording of the player's Homeland round |
| 4.10 | Egg Heist — one run a day (first gives double rank points) | play | ✅ | ✅ | 🟡 map helper, not the run | — |
| 4.11 | Message friends | menu | ⬜ | ⬜ | ⬜ | 3.16 |
| 4.12 | Daily reset time | — | 🟡 guides say 04:00 | ⬜ | — | Which time zone |
| 4.13 | Which Daily Activity tasks rotate — seen so far: Log In, Primegy 60, Stamps 50, Catch 5, Combat 5, Homeland, Shop | — | 🟡 seven seen | ⬜ | — | Keep noting them |
| 4.14 | Aniilog Level → Submit Report | menu | ✅ | ⬜ | ⬜ | Draft the chore |
| 4.15 | Replenish Primegy with Glimmer (once a day, optional) | menu | ✅ | ⬜ | ⬜ | Must ask first — it spends |
| 4.16 | Daily Orders: deliver, use the free refreshes | menu | ✅ | ⬜ | ⬜ | Draft the chore |

## 5. The weekly routine

| # | Item | Kind | Learned | Your phone | Automated |
|---|---|---|---|---|---|
| 5.1 | Companion Handbook quests and its stamp Exchange | menu | 🟡 | ⬜ | ⬜ |
| 5.2 | Season shop | menu | ✅ | ⬜ | ⬜ |
| 5.3 | Discounted pods at Outpost Vendor and Super Claw | menu | ✅ Super Claw seen | ⬜ | ⬜ |
| 5.4 | Weekly ticket at Coilstrike Club | walk | 🟡 an NPC hands it out in Astra | ⬜ | ⬜ |
| 5.5 | Holo-Battle Sim (hardest level once) | play | ✅ the screen; the fights 🟡 | ⬜ | ⬜ |
| 5.6 | Holo-Battle Interlink (team mode, on a schedule) | play | 🟡 | ⬜ | — |
| 5.7 | Omega challenges, three each | play | 🟡 | ⬜ | ⬜ |
| 5.8 | Empty the Homeland warehouse | menu | 🟡 | ⬜ | ⬜ |
| 5.9 | Stamp Rush (weekly cap 1000) | menu/play | ✅ screen | ⬜ | ⬜ |
| 5.10 | Weekly reset day and time | — | 🟡 countdowns seen, not the exact moment | ⬜ | — |

## 6. How the game works underneath

| # | System | Learned | Notes |
|---|---|---|---|
| 6.1 | **Egg Heist / Lost Sanctum** — layouts, nests, locked rooms, doors, gold chests, keys, escape condition, evacuation, weight and loot | ✅ | Deepest area; the app is built on it. Eggs re-roll every run |
| 6.2 | Catching — pod types, catch rates | ✅ | Bonuses stack (pod type, Backstab); Alphas have their own catch screen |
| 6.3 | Combat — EP, skills, Alphas, Omegas | 🟡 | |
| 6.4 | Building a party | 🟡 | Four Aniimo; roles (DPS, Heal …) and elements; how to choose is not learned |
| 6.5 | Player level and its caps (Elite Training promotions unlock the next cap) | ✅ | Seen: "Level cap reached. Complete Elite Training – Title Promotion" |
| 6.6 | Aniimo growth — EXP items, Capability Awakening, Prismana, Sparkling, Umbral | 🟡 | Level Up, Training, Star Up / Ascend, Skills, Held Items seen; Awakening not |
| 6.7 | Eggs and hatching | ✅ |  |
| 6.8 | Currencies — Credits, Primegy, Season Stamps, Voxel Coins, Bud Tickets, Eggshell Coins | 🟡 names | Which buys what |
| 6.9 | Homeland economy | 🟡 | |
| 6.10 | Seasons and update timeline — mobile launch ~22 Sept 2026, big update 17 Oct, Whisperwake Isles next | ✅ | Re-check after every update |

## 7. What breaks automation

| # | Item | Learned | Handled in the app |
|---|---|---|---|
| 7.1 | Grey "Claimed" looks like live "Claim" | ✅ | ✅ colour check |
| 7.2 | "Rate Me" popup mid-play | ✅ | ⬜ needs optional steps |
| 7.3 | Paid buttons beside free ones (Buy Level, Top-Up, Sell, Delete Read) | ✅ | ⬜ refuse-list not built |
| 7.4 | Tapping a creature locks onto it | ✅ | ⬜ |
| 7.5 | Icon row grows with level | ✅ | ✅ finds by picture |
| 7.6 | Daily Activity cards reorder after each claim | ✅ | ✅ repeat searches whole screen |
| 7.7 | "Actions too frequent" when tapping fast | ✅ | ⬜ pause between taps not tuned |
| 7.8 | Events and their order change every update | ✅ | ✅ find by title |
| 7.9 | Start-up popups, disconnects, maintenance | ⬜ | ⬜ |
| 7.10 | Menus misread as the map (the app's own past bug) | ✅ | ✅ fixed in v0.13 |
| 7.11 | Releasing Aniimo cannot be undone | ✅ | ⬜ refuse-list not built |
| 7.12 | Dialogs that spend quietly (Replenish Primegy, Alpha claim, paid refreshes) | ✅ | ⬜ needs confirmFirst |
| 7.13 | The Alpha catch screen is on a timer | ✅ | ⬜ |

## 8. The helper itself (the app side)

| # | Item | Built | Ran on your phone |
|---|---|---|---|
| 8.1 | Egg Heist map overlay and arrow | ✅ v0.14 | 🟡 earlier versions only |
| 8.2 | Help me Daily — teach by doing, then run | ✅ v0.15 | ⬜ |
| 8.3 | Recording → chores converter | ✅ | ⬜ needs a real recording to tune |
| 8.4 | Import chores from this repo | ⬜ | ⬜ |
| 8.5 | Optional steps (popups that come and go) | ⬜ | ⬜ |
| 8.6 | Refuse paid / destructive buttons | ⬜ | ⬜ |
| 8.7 | Walking steps (press-and-drag on the joystick) | ⬜ | ⬜ |
| 8.8 | Fallback to a model when a picture is not found | ⬜ | ⬜ |

---

## Where it stands

Counted across sections 1–7, last on 2026-10-25 (after `log/2026-10-25-gap-fill.md`):

- **Learned:** 68 ✅ · 18 🟡 · 6 ⬜ (92 items) — was 38 · 29 · 15 of 82 earlier the same day
- **Seen on your phone:** 7 ✅ · 3 🟡 · 59 ⬜ — almost only Egg Heist and the dungeon HUD. Every
  menu so far comes from other players' videos.
- **Automated:** only the minimap reading has run on your phone. Five of the traps in section 7
  are handled in the app's code, untested on your phone; two chores are drafted, not runnable yet.

**The single most useful next input** is one screen recording from the player's phone, with *Show
taps and touches* on: log in → main menu → Institute Guide → Mail → Shop → Corner Shop → Exchange →
Mysterious Vendor. That one video would move about fifteen rows from ⬜ to ✅ in the "Your phone"
column, and tune the recording converter (8.3).

— Claude, 2026-10-25
