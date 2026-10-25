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

## Still unknown

- What the two bottom-middle buttons do.
- Whether the camera is turned by dragging the right half of the screen.
- The layout outside the dungeon — town, Homeland, menus — which is where the dailies live.

*Signed:* Claude, 2026-10-25
