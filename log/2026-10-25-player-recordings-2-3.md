# The player's recordings 2 and 3 — catching, and the start of an Egg Heist run

**Watched by:** Claude, 2026-10-25. Both 1560×720, variable frame rate, recorded with
**Pointer location** on — a bar of exact coordinates along the top and crosshair lines through
each finger. That makes every touch unambiguous; the faint "Show taps" disc of recording 1 is no
longer needed.

## Recording 2 — 19 min 28 s, open world (`Screen_Recording_20261025_213626_Aniimo.mp4`)

Catching in Rosetower Woods and Breezy Plains (1:00–13:45), Nurture (14:00), the Outpost, then
hatching at the Hatchinator (16:51–18:48) while queued for Egg Heist ("Stop Matching"), Aniilog
topics (19:00), walking in Astra. **No Egg Heist run** — the match had not started when it ended.

**Catch mode on this phone** (9:18, 8:39):

| What | About where | Notes |
|---|---|---|
| Target reticle | on the creature | hexagon; beside it **"57%"** and the pod's bonus, "×1.5 Aniipod Pro" |
| Pod picker | bottom, x 0.29–0.65, y 0.89 | scrolls sideways; the selected pod has a grey ring; Ultra and Sparkling Cube sit apart, right of a gap |
| Throw (main) | 0.82, 0.76 | large |
| Throw (second) | 0.75, 0.65 | smaller, same icon |
| Leave catch mode | red X 0.89, 0.59 | |
| Nearby list | left, 0.10–0.20, 0.60–0.75 | the creatures in reach, name and level |
| Pickups | left, 0.10, 0.60–0.73 | "Aniipod Pro ×1" as pods are picked back up |

**What the player actually throws** (pod counts across the session): yellow Aniipod 315 → 307,
blue Pro 399 → 314, purple Mega 1030 → 945; green Hyper (251), Track (43), red Ultra (6) and
Sparkling Cube (1) never moved. Blue was selected even with yellow available. So the stated rule
— yellow, blue, purple, nothing rarer — matches what they do, with blue and purple doing most of
the work.

**Camera confirmed:** while walking, Pointer location drew a second finger's trail on the right
half of the screen — the camera is turned by dragging there.

## Recording 3 — 2 min 47 s, Egg Heist start (`Screen_Recording_20261025_214040_Aniimo.mp4`)

| When | What |
|---|---|
| 0:21–0:57 | Egg Heist lobby (Hard), party, Gear Repair confirm (costs Eggshell Coins), backpack |
| 1:00 | Loading: "Search the ruins of the Lost Isles for the entrance to a Lost Sanctum… then escape with them by boat." |
| 1:09–1:27 | **Spawn on a beach beside the boat** (the sail icon on the game map at 1:18). Escape Condition: Submit 1 Egg · Team Eggshell Coins earned 0/60000; 15:00 clock |
| 1:33–1:48 | Walk to a Sanctum portal: "Enter the Lost Sanctum" pill (first try: "Not enough stamina") |
| 1:48 | "Your team has discovered the Sanctum. Open the map to view Sanctum entrance locations." |
| 1:57–2:06 | Egg Heist Map: compass (Hard) → two matches, **Layout 42** (3 rooms away) vs 49 → picked 42 — **the arrow was switched off** |
| 2:12 | tapped the egg nest → "First time checking this nest… Egg found / Empty" |
| 2:15–2:36 | walking the first corridors (13:59 → 13:44 left) |
| 2:42 | Settings → turned on "Show where I am, and an arrow to the next nest" |
| 2:45 | **The app's own main screen came up with Android's "Share your screen?" dialog — and the phone's screen recorder stopped.** End of recording. |

## What this showed about the app

1. **The arrow was off at the start of the run.** The cause: when the phone's screen recorder
   starts, it takes the screen from the app, and the app answered by switching the arrow off for
   good. **Fixed in v0.16.0:** it now pauses, the egg ring shows "!", and one tap starts it again.
2. **Turning the arrow on mid-run pulled the player out of the game** into the app's main screen.
   **Fixed in v0.16.0:** the permission dialog opens in its own task, over the game.
3. **After "Egg found" the app pointed at the next nest**, never home. **Added in v0.16.0:** it
   points back to the door you came in by, then says "out to the boat".
4. **Screen recording and the arrow cannot run at the same time** on this phone: Android gives the
   screen to one capturer. Recordings of a run will never show the arrow working.

— Claude, 2026-10-25
