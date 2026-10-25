# The player's rules

Things the player has decided. A chore that breaks one of these is wrong even if it works.
Every assistant reads this before writing a chore. Told by the player on the date given.

## Pods — which to throw, which never

**Told 2026-10-25:** "Use yellow, then blue, then purple. Avoid the prismatic or rarer ones."

The colours, matched against footage (`log/2026-10-25-gap-fill.md`, catch mode and the Alpha
catch screen):

| Order | Pod | Looks like |
|---|---|---|
| 1st | **Aniipod** | white cube, yellow lights — the free one |
| 2nd | **Aniipod Pro** | white cube, blue lights |
| 3rd | **Aniipod Mega** | white cube, purple lights |
| never | Aniipod Hyper | green lights |
| never | Aniipod Ultra | red cube with an X |
| never | Aniipod Track | light blue, an eye on it |
| never | Tumbler | a white fluffy ball |
| never | **Sparkling Cube** | white, sparkling — the "prismatic" one |

How a chore applies it:

1. Select the yellow pod. If the catch chance on screen is at or above the **threshold**, throw.
2. Otherwise select blue; same test. Otherwise purple; same test.
3. If even purple is below the threshold, **stop and tell the player**. Never move on to a
   rarer pod on its own.
4. The five "never" pods go on the app's refuse-list, with Buy, Sell, Release and Top-Up.

**Threshold: 30 %** — a placeholder chosen by Claude until the player names one. Change it here.

*Where the chance shows:* in catch mode, beside the target with the selected pod's name
("86 %  ×1.5 Aniipod Pro"); on an Alpha's catch screen, next to every pod. Reading the number
needs on-device text reading, which the app does not have yet — see `CHECKLIST.md` 8.x.

— Claude, 2026-10-25, from the player's words

**Seen in the player's own catching (2026-10-25):** yellow 315 → 307, blue 399 → 314, purple
1030 → 945 over one session; green Hyper, Track, red Ultra and Sparkling Cube never used. The rule
matches what they do, with blue and purple doing most of the throwing. The chance shows beside the
target as "57%" with the selected pod's bonus ("×1.5 Aniipod Pro"). *Source:* `log/2026-10-25-player-recordings-2-3.md` — Claude, 2026-10-25

## Spending

Anything that spends credits, Glimmer, Primegy or real money asks the player first
(`confirmFirst`). Told 2026-10-24 and repeated since.

## Never

Release an Aniimo · Sell · Delete mail · Top-Up / Pack / Monthly Pass / Buy Level · log out.
