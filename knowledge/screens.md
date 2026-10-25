# The game's screens

One section per screen. For each: how to tell you are on it, what is on it, and where its
buttons lead. This is what lets an assistant read a frame of video and know where the player is.

Positions are fractions of the screen (x of width, y of height), read by eye — "about here".
Full-screen menus look the same on phone, PC and console; only the HUD differs. Unless marked
*phone*, a screen was read off PC or console footage and still needs seeing on the player's phone.
Evidence for all of this: `log/2026-10-25-environment-videos.md`.

### Out in the world (the HUD) — *phone*

- **You can tell by:** round minimap top-left, health bar bottom-middle, ring of action buttons
  bottom-right.
- **Buttons:** see `knowledge/controls.md` for every one and where it sits.
- **Changes with state:** the top-right icon row grows as features unlock (three icons at level 15,
  seven at level 51). Catching swaps the action ring for a row of pod types along the bottom and a
  red X to back out.

### Main menu — *phone*

- **You can tell by:** a grid of rounded tiles down the right half, the player's name and avatar
  above it, a thin vertical rail of small icons on its right with a close X on top.
- **Reached from:** the HUD, by tapping the right-most top-right icon (a pod in a ring). *Inferred*:
  the close X appears exactly where that icon was.
- **Tiles, top to bottom:** Inventory · Aniimo Management · Map (a small round minimap tile) ·
  Aniilog (shows a level) · Log · Friends · Character (shows player level) · Appearance · Party ·
  Events · Elite Training · Homeland · Institute Guide · (three locked tiles) · Courses ·
  Companion Handbook · Shop · more below, reached by scrolling.
- **Right rail:** close X, then small icons including a gear (**Settings**), an envelope
  (**Mail**) and a power symbol at the bottom (log out — never tap in a chore).
- **Changes with state:** a red badge or a small gift on a tile means something is waiting.

### Events

- **You can tell by:** "Events" top-left, a column of event banners down the left edge, the chosen
  event's art filling the rest.
- **Reached from:** main menu → Events, or the calendar-with-a-star icon top-right on the HUD.
- **On it:** each event has its own page. Check-in pages show numbered day cards in three states —
  greyed with a tick and "Claimed", bright with a **Claim** button, and "Claim Tomorrow" /
  "Pending Check-In". Other pages have **Go** or **Go Now** (jumps you to the place),
  **Track**, or **Rules**. The "Quick Leveling Guide" page is a grid of Go shortcuts (Main Story,
  Elite Training, Daily Activity, Catch new Aniimo, Challenge Alpha, Pathfinder Challenge,
  Collect Amber, Journey Quests, Institute Exclusive). The Mysterious Vendor also has a page here
  with Go Now.
- **Changes with state:** the list changes with every update; never find an event by its position
  in the list — find it by its banner title.

### Institute Guide (Daily Activity, Aniimo Challenge, Stamp Rush)

- **You can tell by:** "Institute Guide" top-left, three round tabs down a blue strip on the left.
- **Reached from:** main menu → Institute Guide, or the card-shaped icon top-right on the HUD.
- **Daily Activity tab:** a row of task cards, each with a count ("0/60"), a title, a points
  value, and one of: *In Progress* (no button), a dark **Go** button, or greyed with a tick and
  *Claimed*. A points bar along the bottom with reward chests at 100–500. "Obtained Today" caps
  shown top-left; time to reset top-right.
- **Aniimo Challenge tab:** rows of Alpha challenges, each with rewards and **Go**, or "Not found".
- **Stamp Rush tab:** wide cards (Holo-Battle Sim, Home Orders, Wild Surge, Defeat Alphas, …)
  each with **Go**; a "Weekly earned x/1000" count top-right.

### Shop

- **You can tell by:** "Shop" top-left, currency totals top-right, a row of tabs along the bottom:
  Monthly Pass · Pack · Appearance · Item · **Corner Shop** · **Top-Up**.
- **Reached from:** main menu → Shop, or the stall-with-a-coin icon top-right on the HUD.
- **Corner Shop tab:** two round tabs on the left — **Corner Shop** (today's four boxes and an
  **Open All** button, "Stock refreshes in …") and **Exchange** (a grid of vendor cards: Outpost
  Vendor, ChillBeanz, Lumen, Mysterious Vendor, Super Claw, Coilstrike Club; each card has a
  location pin or an arrow).
- **A vendor's page** (e.g. Mysterious Vendor): item cards with credit prices on the left; the
  chosen item's details on the right with **Daily limit n/n**, a quantity stepper (min, −, +, max),
  the total, and **Buy**.
- **Never:** Top-Up, Pack and Monthly Pass are real money.

*Source:* `log/2026-10-25-streamer-dailies.md` — Claude, 2026-10-25

**Addition (2026-10-25, Claude) to Institute Guide:** by October it has **four** tabs — Daily
Activity, Aniimo Challenge, **Holo-Battle Sim**, Stamp Rush. And a Daily Activity card has a fourth
state: **yellow, with a blue Claim button and a red "!"** — done, points not yet collected.
Claiming greys the card and moves it to the right-hand end of the row. Chests on the points bar
show a **red gift badge** once reachable; tapping one gives an "Item Obtained" box.
*Source:* `log/2026-10-25-streamer-dailies.md` — Claude, 2026-10-25

**Correction (2026-10-25, Claude):** the **Character** tile opens **Info · Badges · Talents** —
the player's title, level and the "Aniimo Level Cap", the four Paths, and the combat and mobility
skill sets. The Profile screen described above is reached from the name card at the top of the
main menu, not from the Character tile. *Source:* `log/2026-10-25-gap-fill.md` — Claude, 2026-10-25

### Aniimo (also where the party is set)

- **You can tell by:** "Aniimo" top-left, Combat / Explore tabs top-right, a column of four party
  cards on the left, a hexagon grid of Aniimo in the middle, a stats card on the right.
- **Reached from:** main menu → Aniimo Management, or the cat-face icon top-right on the HUD.
- **Buttons:** **Level Up** and **Training** bottom-right; sort and filter, "Storage n (x/24)" and
  **Manage** along the bottom. Tapping an Aniimo opens its page: tabs Skills · Star Up · Held
  Items, with **Ascend** and a material cost on Star Up.
- **Never in a chore:** Manage → **Release** (the "Released Aniimo List" warns that training
  materials are not returned).

### Aniilog (the Aniimo index)

- **You can tell by:** "Aniilog" top-left, a row of tall Aniimo cards, a collection bar along the
  bottom, Family Mode / Form Mode top-right.
- **On it:** each Aniimo's Field Notes, Topics (small research tasks), Skills, Evolve, Forms and
  Habitats (opens the map). **Aniilog Level** per region shows research points and a
  **Submit Report** button that pays out rewards — a menu-only claim.

### Map and teleport

- **You can tell by:** "Map" top-left, the region's name, exploration % and coordinates bottom-left,
  a zoom slider on the left, a world switch (Astra / Idyll) bottom-left.
- **Teleport:** tap a Bloom or another travel point → a side panel on the right with **Teleport**
  at its foot.

### Nurture

- **You can tell by:** "Nurture" top-left, a big round emblem in the middle, region names in two
  columns either side, "This area's Prismatic Energy state" above, "Daily Nurture Chances x/25"
  bottom-left.
- **Reached from:** at a Bloom (teleport there from the map), the Nurture prompt.
- **Buttons:** the **+** under the emblem opens **Nurturing Offering** (pick a shard → Confirm);
  **Nurture** bottom-right costs one Nurture crystal (count top-right).

### Catching (out in the world) — *phone*

- **You can tell by:** a hexagon reticle on the target with a catch chance and its bonuses
  (Aniipod type, Backstab for catching from behind), a pod picker along the bottom with counts,
  throw buttons on the right and a red X to back out.
- **After beating an Alpha:** "Catch Countdown" — rewards preview, every pod type with its chance,
  **Catch and Claim Rewards** (costs 30 Primegy) or **Quit**.

### Hatching — *phone*

Choose an Aniipod to twine with the egg → **Confirm** → an animation with **Skip** top-right → the
result (type, quality, form) → **Claim**.

### Homeland screens

- **Home Overview:** an island map of zones — Production, Mine Exploration, Lakeside Recreation,
  Service Hub, Limited-Time Event, Homebuilding. Each zone opens a side panel; Service Hub's lists
  Order Quantity · Home Shop · Co-op Store (each with an arrow) and **Teleport**.
- **Daily Orders:** client cards side by side. Each shows the item and how many you have, the
  rewards, a refresh icon top-right, and **Deliver** — dark when you can deliver, grey when you
  cannot. Top-right: "Today's free refresh attempts n/5". Bottom: current orders, next refresh.
- **Trip Rewards** (Aniimo on a Trip): rewards per Aniimo, **Confirm** and **Send Again**
  ("On Foot: 6h 0m").
- **Home Shop:** seeds to buy; a grid of produce to sell with **Sell Item**.

### Shops with weekly stock

- **Super Claw** (pods): Discount tags, Sold Out, "Weekly Limit n/20", **Buy**.
- **Season shop:** Weekly and Season tabs on the left, a countdown to the weekly reset.
- **Egg Heist shop:** Equipment · Egg Heist Ticket · Eggs · Other; daily limits; a Loadout button.

### Holo-Battle Sim

Three training orbs — Water, Fire, Grass — each rated in stars; a weekly "Time remaining" and a
season timer; "Training Incentive" bottom-left.

### Replenish Primegy

A popup: spend **Glimmer** to restore 60 Primegy; shows the time to full recovery. Confirm spends.

### Select Server (start-up)

"Select Server" with Aniimo-Europe (marked Recommended), Aniimo-Americas and Aniimo-Apac, then
**Confirm**. The login and announcement screens before it are not yet seen.

### Help, and time of day

The main menu rail's **?** opens **Help**, an in-game encyclopedia (tabs All · System · Training ·
Combat · Explore) — a good place to check a mechanic. The rail's **sun** opens a time-of-day dial.

*Source:* `log/2026-10-25-gap-fill.md` — Claude, 2026-10-25

### Egg Heist: the way home

- **You start** on a beach of the Lost Isles **beside the boat** — the sail icon on the game map.
  Escape Condition (Hard): Submit 1 Egg · team Eggshell Coins 60,000; a 15:00 clock.
- **You walk** to a Lost Sanctum portal ("Enter the Lost Sanctum") and go in by its Main (orange)
  or Side (blue) door.
- **With an egg**, the way out is back through the door you came in by, then to the boat, where
  the prompts are **Safe Evacuation · Deliver Egg · Leave**.
*Source:* `log/2026-10-25-player-recordings-2-3.md` — Claude, 2026-10-25

### Log (the quest menu)

- **You can tell by:** "Log" top-left, three pill tabs top-middle: **Lore · Quests · Journey**.
- **Reached from:** main menu → Log.
- **On it:** quest list on the left grouped by heading (Main Story, Growth Story, Home Quests,
  World Rumor, …); details on the right — Quest Targets, Quest Rewards. Bottom-right buttons:
  **Track** / **Untrack**, and **Go** where the game can take you there. A "Filter Range" dropdown
  bottom-left. Journey also opens a Journey Journal (Writings, Landscapes, Curio).

### Elite Training

- **You can tell by:** warm orange-gold page, "Elite Training" top-left, tabs top-right: Core
  Courses · Path of Twining · Path of Discovery · Path of Victory · Path of Splendor.
- **On it:** a chapter card with "Required quests progress", rows of quests each with **Track** or
  *TRACKING*, a points track along the bottom (milestones to 180).

### Settings — *phone*

- **You can tell by:** "Settings" top-left, "Device Performance" top-right, six tabs down the left:
  **Game · Display · Sound · Language · Account · Storage**.
- **Reached from:** main menu → gear on the right rail.
- **Game tab:** "Support Feature → **Unstuck** [Confirm]" at the very top, then Gameplay switches:
  Auto Lock-On After Attack, Always Follow the Locked-On Target, Auto-Adjust Camera When Not
  Locked On, Auto Approach Target When Using Skills, **Tap Model to Lock On Target**, BINI #9
  Assist Frequency, and more below.
- **Display tab:** Graphics, Render Scale, Anti-Aliasing, Frame Rate Cap (30/45/60), Baked Global
  Illumination, Animation Quality, Shadow Quality; "Restore Defaults" bottom-right. Each setting
  is a dropdown on the right of its row.

### Character → Profile

- **You can tell by:** "Profile" top-left, the player's character standing in the middle on a grey
  backdrop.
- **On it:** name card, Badges, Collection Progress (Aniimo Point, Sparkling Aniimo, Style Points,
  Prismana Aniimo); a column of round tabs on the left (avatar, frame, badges, chat bubble, …),
  each with a **Use** / *In Use* button; **Edit** bottom-right.

### Inventory

- **You can tell by:** a grid of item cards with counts, tabs All · Materials · Available,
  a detail panel on the right, currency totals top-right.
- **Buttons:** **Sell** bottom-middle (never in a chore unless that is the chore), "Sort by" bottom-left,
  item categories as round tabs down the left.

### Mail

- **You can tell by:** "Mail n/200" top-left, a list of envelopes with senders and time left.
- **Reached from:** main menu → envelope on the right rail.
- **Buttons:** **Claim All** bottom-middle of the list, right beside **Delete Read**; inside a
  letter, its reward and a **Delete** button.
- **Changes with state:** letters expire (the time left shows on each).

### Season Achievement

- **You can tell by:** "Season Achievement" with a "Part One" badge top-left, a numbered reward
  track across the top, four big cards below: **Aniimo · Combat · Egg Heist · Homeland**, each
  with a percentage.
- **Reached from:** the S1 badge top-right on the HUD.

### Companion Handbook (the season pass)

- **You can tell by:** dark page, "Companion Handbook" top-left, a level number in a ring, a
  reward track of columns, tabs top-right: Companion Handbook · Monthly Pass.
- **Buttons:** left rail Rewards · Quests · Exchange. **Buy Level** and "Level Up to Collector's
  Edition" are paid — never in a chore.

### Harvest Moon Festival (time-limited)

- **You can tell by:** a popup titled "Harvest Moon Festival" with tabs Season Overview · Harvest
  Dailies · Moondew Crops · Harvest Moon Points · Gathering Preparations · Harvest Gathering.
- Runs 20 Oct 22:00 to **28 Oct 05:00 UTC**. Its own **Harvest Dailies** tab is a second daily
  list while it runs.

— Claude, 2026-10-25

## Template

### <name of the screen>

- **You can tell by:** the one or two things always on this screen and nowhere else.
- **Reached from:** which screen, by tapping what.
- **Buttons:** each one, where it sits (roughly, as a fraction of the screen), and where it goes.
- **Changes with state:** anything that looks different once something is claimed, bought or done.
- *Source:* log entry · *signed:* who, when
