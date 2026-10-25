# The mobile controls

Where everything sits on a phone, in landscape. Positions are fractions of the screen — x of the
width, y of the height — read off the player's own 2340×1080 screenshots, so they should hold on
any 19.5:9 phone. **Read by eye off still frames, so treat them as "about here", not exact.**
The written guides do not document the mobile touch layout at all, so this is the only record of
it we have.

## Why this matters

Help me Daily replays a routine by finding each button's *picture* on screen. This file is not
how it finds them — it is so an assistant reading a frame knows what it is looking at, and can
say "the Dash button, right side" instead of "the thing at 0.9, 0.44".

## In the dungeon (Lost Sanctum)

### Left

| What | About where | Notes |
|---|---|---|
| Minimap | 0.13, 0.15 | Round, north-up, "N" fixed at the top. A yellow arrow is you, and a pale cone shows which way the camera looks. |
| Escape Condition panel | 0.03–0.13 wide, 0.28–0.45 | The run's objectives: "Submit 1 Egg", team coin total, optional count. |
| Egg button + run timer | 0.075, 0.47 | Gold ring with an egg; the countdown sits in it. |
| **Movement pad** | **0.22, 0.72** | A faint ring with four arrows. This is where you move from. |
| Chat · emote | 0.07 and 0.11, 0.86 | Chat carries a gift badge when something is waiting. |

### Middle, along the bottom

| What | About where | Notes |
|---|---|---|
| Two round buttons | 0.40, 0.86 and 0.40, 0.91 | Upper looks like an aim/target, lower like throwing a pod. Not yet confirmed. |
| Energy pips | 0.50, 0.855 | A row of blue orbs above the health bar; they empty as abilities are used. |
| Health bar | 0.52, 0.885 | Green, with the exact numbers written on it ("10394/10394"). |
| Interact prompt | near the character | A small hand cursor with a number appears when something is in reach. |

### Right — the action buttons

A large main button with the others ringed around it. Each shows a cost or cooldown number, and
several carry the portrait of the Aniimo whose skill it is.

| Button | About where |
|---|---|
| **Main action** (largest) | 0.82, 0.78 |
| Heal | 0.88, 0.19 |
| REGEN (green) | 0.90, 0.31 |
| Dash | 0.90, 0.44 |
| Damage | 0.81, 0.55 |
| Luminous Seed | 0.89, 0.58 |
| Draw In | 0.75, 0.65 |
| REGEN (second) | 0.72, 0.80 |
| **Untwine** | 0.66, 0.88 |

**Untwine matters.** Guides say Twine takes direct control of your creature — RT on Xbox, R2 on
PlayStation, C on PC — and say no mobile equivalent is documented. It is on the phone: an
Untwine button sits bottom-right, which means Twine is reachable by touch too.

*Source:* the player's own screenshots, `tools/samples/scenes/play-start.jpg` and
`tools/samples/play/play1–5.jpg` in the app repo — Claude, 2026-10-25

## Out in the world — *phone*

Read off an iPhone 15 Pro Max recording (19.5:9, the same shape as the player's phone) and a
22 Oct 2026 Android one. Evidence: `log/2026-10-25-environment-videos.md`.

### Left and bottom

| What | About where | Notes |
|---|---|---|
| Minimap | 0.14, 0.15 | Round, "N" at the top, a sun or moon beside it for time of day. |
| Quest tracker | 0.08–0.29 wide, 0.35–0.54 | The tracked quest's name in yellow, its steps under it. |
| Joystick | about 0.24, 0.72 | See the correction below — it appears where the thumb lands. |
| Camera (photo mode) | 0.09, 0.84 | |
| Chat · emote · a third icon | 0.08–0.15, 0.89 | Only some players show all three. |
| Lock-on | 0.27, 0.92 | A ring with a dot. |
| Energy pips, health bar | 0.50, 0.90 and 0.93 | |

### Top right — the shortcuts

Named from a console version's radial menu, which shows the same icons with labels.

| Icon | Opens |
|---|---|
| "S1" badge | Season Achievement |
| Calendar with a star | Events |
| Hexagon | Elite Training |
| Card / booklet | Institute Guide — **Daily Activity** lives here |
| Cat face | the Aniimo screen |
| Stall with an "S" coin | Shop |
| Pod in a ring (always right-most) | **Main menu** — inferred, see `knowledge/screens.md` |

The row **grows with level**: at level 15 only Events, the cat and the menu pod showed; at level
51, all seven. So find an icon by its picture, never by its place in the row.

### Right — party and actions

| What | About where | Notes |
|---|---|---|
| Party portraits | 0.90, at 0.17 / 0.33 / 0.46 | The three Aniimo in the party, each with its level. |
| Switch target | 0.80, 0.57 | Circular arrows. |
| **Recall** | 0.88, 0.58 | Calls your Aniimo back. |
| **Main action** (largest) | 0.82, 0.75 | |
| Pod throw | 0.65, 0.75 | Shows how many pods are left. |
| Skill buttons | ring between 0.65 and 0.90 | **Labels change with the party** — seen: Damage, Control, Dash, Heal, REGEN, Draw In, Luminous Seed. |
| **Twine** / Untwine | 0.65, 0.90 | Twine takes direct control of the Aniimo; the same spot reads Untwine while twined. |
| Jump and dodge | 0.89, 0.80 and 0.81, 0.92 | Running-figure icons. |

### Confirmed: what each top-right icon is (2026-10-25)

The PC version prints its key next to each icon: F1 Season · F2 Events · F3 Elite Training ·
F4 Institute Guide · P Aniimo · F9 Shop · **Esc** on the pod-in-a-ring. Esc is the main menu, so
the pod-in-a-ring **is** the main menu button — no longer only inferred.

### While twined

Twined, the player *is* the Aniimo: the action ring becomes that Aniimo's own moves (seen: Damage,
Hustle, Dodge, Aim with a cooldown number) and the Twine button reads **Untwine**. Help says some
Aniimo can climb, swim or fly when twined.

*Source:* `log/2026-10-25-gap-fill.md` — Claude, 2026-10-25

## Confirmed on the player's own phone (2026-10-25)

The first recording from the player's phone (1560×720) confirmed the free-roam layout above to
within a few hundredths, and settled three things:

- **The joystick appears where the thumb lands**, as a large faint ring with a white knob and a
  direction dot on its edge; nothing is drawn while idle. Centres seen from (0.11, 0.75) to
  (0.17, 0.85). So a walking step is: press anywhere in that corner, drag, hold.
- **The interact prompt** is a dark pill with an icon and a word at about **(0.65, 0.45)** —
  Check In, Chest, Home Shop, Mine, Till Soil. It is the signal that the character has arrived.
- **The camera is probably turned by dragging the right half**: a second touch dot sat near
  (0.70, 0.50) while walking.

Main menu tile and rail positions, Mail buttons and Daily Activity tabs on this phone are listed
in the log. *Source:* `log/2026-10-25-player-recording-1.md` — Claude, 2026-10-25

### Catch mode and the camera (player's phone, 2026-10-25)

Reticle with the chance beside the target; pod picker along the bottom (x 0.29–0.65, y 0.89),
which scrolls sideways and keeps Ultra and Sparkling Cube apart on the right; main throw
(0.82, 0.76), second throw (0.75, 0.65), red X to leave (0.89, 0.59). **The camera turns by
dragging the right half of the screen** — proven by Pointer location's finger trail. *Source:* `log/2026-10-25-player-recordings-2-3.md` — Claude, 2026-10-25

## The movement pad is fixed — so walking can be automated

**Settled 2026-10-25.** The pad is drawn at the same place in all six of the player's
screenshots, taken at different moments in different rooms: centred on **x 0.225, y 0.705**, to
within the width of the grid I measured against. It does not follow the thumb.

That matters more than it sounds. A routine can walk the character by pressing on the pad and
dragging in a direction — "hold down-left for a second and a half" — which a floating joystick
would have made impossible. Walking chores are a feature the app lacks, not a thing that cannot
be done.

The app's swipe step already does a timed drag, capped at 1.5 seconds, so walking would be
replayed as a run of swipe steps from the pad's centre outward, one per burst.

*Caveat:* all six screenshots are from inside the Lost Sanctum. The pad may sit elsewhere in
town or Homeland, and that is where the dailies happen — so check it again on the first
recording made outside a dungeon.

*Source:* `tools/samples/scenes/play-start.jpg` and `tools/samples/play/play1–5.jpg`
— Claude, 2026-10-25

**Correction (2026-10-25, Claude):** "fixed" is only half right. The small four-arrow icon is
always drawn at the same spot, but while a thumb is down the stick itself — a big faint ring with
a white dot — appears **where the thumb landed** in the lower-left: its centre moved between
y 0.72 and 0.80 across frames of a 22 Oct Android recording and a mobile settings video. So it is
semi-floating. The conclusion still stands, and is stronger: a floating stick starts wherever you
press, so **press near the icon and drag** walks the character either way.
*Source:* `log/2026-10-25-environment-videos.md`

## Still unknown

- What the two bottom-middle buttons do.
- Whether the camera is turned by dragging the right half of the screen.
- ~~The layout outside the dungeon~~ — now mapped above, and the menus in `knowledge/screens.md`.
- Whether dragging the right half of the screen turns the camera (probable, not yet seen).
- The Homeland HUD: a different bottom bar (Aniimo · Manage · Home · Build · Warehouse) was seen on PC.

*Signed:* Claude, 2026-10-25
