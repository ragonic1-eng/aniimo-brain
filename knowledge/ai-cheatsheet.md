# The AI cheat sheet

What Egg Heist Map sends to its AI (Qwen 3.8 Flash) with every question, boiled down from the
rest of this folder. Kept in the app at `app/src/main/assets/ai/knowledge.md`; this is a copy so
any assistant can use the same short version. Tested 2026-10-27: with it, the AI found the Mail
envelope without other help and made 8 of 9 sensible moves on the player's recorded screens.
— Claude, 2026-10-27

---

# Aniimo on this phone — what you need to know

Screen positions are x,y from 0 to 1000 (0,0 top-left, 1000,1000 bottom-right), landscape.
They are "about here": always aim at what you actually see.

## Never
Never tap: Buy, Purchase, Top-Up, Recharge, Pack, Monthly Pass, Buy Level, Sell, Sell Item,
Release, Delete, Delete Read, Replenish Primegy, Catch and Claim Rewards, Refresh (once free
refreshes are used), the power/log-out icon, or any button showing a price. If the only way on is
one of these, answer "stop". Pods: throw only yellow (Aniipod), then blue (Aniipod Pro), then
purple (Aniipod Mega). Never Hyper (green), Ultra (red with an X), Track (eye), Tumbler (fluffy
ball) or Sparkling Cube (sparkling white).

## Getting out of things
- Menus and panels: the round back arrow at the top-left (about 80,55), or an X at the top-right.
- The main menu closes with the X at the top of its right-hand rail (about 900,75).
- "Item Obtained" / "Obtained" reward screens and the login calendar ("press anywhere to close"):
  tap anywhere, e.g. the bottom middle (500,900).
- "Rate Me" popup: Maybe Later. Cutscenes: Skip (top-right).
- Toasts "Actions too frequent" or "Insufficient EP": wait, then try again.
- Loading screens (big art, a progress bar or tips): wait.
- Title screen: "Start Adventure" (500,805) under the server name.

## The open world (HUD)
- Round minimap top-left (140,150), north up, a yellow arrow is you.
- Top-right icon row (y about 50), right to left: main menu (a pod in a ring, 918,50, always
  right-most) · Shop (purple bag with an S) · Aniimo (cat face) · Institute Guide (open book) ·
  Elite Training (hexagon) · Events (calendar with a star) · Season (S1).
- Party portraits down the right edge; big action buttons bottom-right (main action about
  820,750; jump 890,800; dodge 810,920; Twine 650,900).
- Health bar and energy pips bottom-middle.
- Moving: the joystick appears where the thumb lands in the lower-left (about 200,720); drag from
  there towards the direction. Up = forward (the way the camera faces), down = back.
- Turning the camera: drag across the right half of the screen (not on a button).
- When close enough to use something, a dark pill with an icon and a word appears at about
  650,450 (Check In, Chest, Park Board, Harvest Bud Tickets, Go to Home, Home Shop, Mine,
  Till Soil). Tapping that pill uses it. The pill appearing means you have arrived.
- Tapping an Aniimo in the world locks the camera onto it: avoid tapping the open world.

## Main menu (tap the right-most top-right icon)
Grid of tiles on the right half: Inventory, Aniimo Management, Map, Aniilog, Log, Friends,
Character, Appearance, Party, Events, Elite Training, Homeland, Institute Guide, Holo-Battle Sim,
Operation: Egg Heist, Shop, Courses, Companion Handbook. A thin rail of round icons on its
far right (x about 900): X at the top, then target, ?, sun/moon, a card icon, gear (Settings),
an envelope with a small cat face (**Mail**, about 900,717), a notice icon, power (never).

## Mail
"Mail n/200" top-left. List of letters. Bottom of the list: Delete read (never) and **Claim All**
(about 360,900; a red badge on it when there is something to claim). After Claim All an
"Obtained" screen: tap anywhere. When everything is claimed the letters show ticks; "No Mail"
when empty. Leave with the back arrow top-left.

## Shop and the Corner Shop
"Shop" top-left. Tabs along the bottom: Recommended, Monthly Pass, Pack, Appearance, Item,
**Corner Shop** (about 745,937), Top-Up. Never Monthly Pass, Pack or Top-Up.
Corner Shop: left column Corner Shop / Exchange. Corner Shop shows four "?" boxes and a purple
**Open All** button (about 794,643) — free, once a day; once opened the items show with prices
(that means it is done: do not buy). Exchange: vendor cards (Outpost Vendor, ChillBeanz, Lumen,
Mysterious Vendor, Super Claw, Coilstrike Club). A vendor page has items with a Daily limit,
a quantity stepper and Buy (spends currency: stop and ask).

## Institute Guide → Daily Activity
"Institute Guide" top-left; round tabs down a blue strip on the left: Daily Activity (top),
Aniimo Challenge, Holo-Battle Sim, Stamp Rush. Daily Activity shows task cards:
- yellow card with a blue **Claim** button and a red "!" = done, tap Claim (about y 705);
- dark **Go** = not done (do not tap unless the goal is to do that task);
- "In Progress" = not done; grey with a tick and "Claimed" = finished.
Claimed cards move to the end of the row. The points bar at the bottom (y about 860) has chests
at 100–500; a chest with a red gift badge is ready: tap it (one tap claims all ready chests),
then tap anywhere to close "Item Obtained". No yellow card and no badge = nothing left to do.

## Events
Calendar-with-a-star icon top-right, or main menu → Events. A list of event banners down the
left; each event its own page. Check-ins: day cards, today's has a **Claim**; "Claim Tomorrow"
and greyed "Claimed" are done. Task lists ("Keep the Spark") have blue Claim buttons for done
tasks and Go for not-done ones.

## Homeland and the RV
Main menu → Homeland: the RV screen, with travel buttons bottom-right: **RV Park** and
**Homeland**. In Homeland a bar along the bottom: Aniimo · Manage · Home · Build · Warehouse.
- Daily Orders: Home → Service Hub → Order Quantity. Deliver (dark = possible, grey = not).
  Free refreshes 5 a day; after that they cost coins (stop).
- Seeds: Home → Service Hub → Home Shop (buying spends coins: stop and ask).
- Food: Aniimo → Food → Add All.
- Aniimo trips: RV Park → walk a few steps to the **Park Board** → its pill → Aniimo on a Trip
  → Confirm, Send Again.
- Bud tickets: walk to the Bud Ticket Jar → "Harvest Bud Tickets" pill.

## Catching
Catch mode: a reticle on the Aniimo with the catch chance, a pod picker along the bottom
(y about 890), throw button about 820,760, a red X to leave (890,590). Pick the pod by the rule
above. After an Alpha: "Catch Countdown" with Catch and Claim Rewards (costs 30 Primegy: stop and
ask) or Quit.

## Daily routine (what "do my dailies" means)
Corner Shop Open All · Institute Guide Daily Activity claims and chests · Mail Claim All ·
Events check-ins · Homeland: orders, food, trips. Dailies reset at 04:00.
