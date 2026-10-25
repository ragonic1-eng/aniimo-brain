# How to record so the helper can learn your character

One recording teaches more than ten videos of other people, because it is *your* phone, *your*
buttons, *your* account. This is the exact procedure. It takes about 20 minutes the first time.

## Once: set the phone up

1. **Turn on "Show taps":** Settings → About phone → Software information → tap **Build number**
   seven times (unlocks Developer options). Then Settings → Developer options → scroll to
   *Input* → turn on **Show taps** (Samsung calls it "Show taps and touches"). A small circle now
   appears wherever a finger is. That circle is what the converter tracks — **without it, a
   recording teaches nothing.**
2. **Screen recorder settings:** swipe down the quick panel → long-press **Screen recorder** →
   Video quality **1080p**, Sound **None** (or Media), Selfie video off. Keep the phone in
   landscape as you play.
3. **Keep the game as it is.** Do not change the controls layout, language or graphics between
   recordings — a chore learned on one layout breaks on another.

## Every recording: how to play while it records

- **One routine per recording.** Stop and start a new one for the next routine.
- **Slow and separate.** Pause 2–3 seconds after every tap, and again after each screen finishes
  loading. The converter splits chores on pauses over 4 seconds, so a long pause means "next
  chore".
- **Taps, not flicks.** Press each button squarely and lift. For a hold, keep the finger still.
- **Walking:** push the joystick in one direction and hold for about two seconds, lift, pause.
  Do forward, back, left, right once each. The ring and dot the game draws is what gets learned.
- **Camera:** drag once on the right half of the screen, slowly, left to right; pause; then up.
- **Let popups come.** If a "Rate Me" or any other popup appears, close it the way you normally
  would and carry on. That teaches the app what to expect.
- **Say nothing, type nothing.** Chat, names and friend lists are personal; keep them off screen
  where you can.

## The five recordings, in order of value

| # | Record this | Teaches |
|---|---|---|
| 1 | **Start-up to menus:** open the game → login → any announcements → main menu → Institute Guide (Daily Activity tab) → back → Mail → back → Shop → Corner Shop → Exchange → Mysterious Vendor → back out to the world | Every daily menu on your phone; calibrates the converter |
| 2 | **Walking and camera:** stand in an open area; four joystick pushes, two camera drags, one dash, one jump | How your phone draws the joystick; the camera; the first walking step |
| 3 | **Home round:** main menu → Homeland → RV Park → walk to the Park Board → trips → Confirm → into the RV → Go to Home → Home → Service Hub → Daily Orders → Home Shop → Aniimo → Food → Add All → walk to the Bud Ticket Jar → Harvest | The whole home routine, and what the interact button looks like on a phone |
| 4 | **One catch:** walk up to any common wild Aniimo, open catch mode, select the yellow pod, throw; if it fails, select blue and throw | Catch mode, the pod picker, where the chance shows |
| 5 | **One Egg Heist run**, start to escape | Links the map helper to the rest |

Each should be under five minutes. Shorter is better than complete.

## Then

1. Put the files in `D:\Claude\EggHeistMap\recordings\` on the PC (or attach them in the chat;
   a five-minute 1080p recording is about 300–500 MB, so the folder is easier).
2. Claude runs `tools/video_to_chores.py` on recording 1 first, with `--calibrate` on one tap you
   point out ("the Mail tap at 0:42"), to tune the touch-dot detector to your phone.
3. Claude writes the chores it finds into the brain and the app, ticks the "Your phone" column in
   `CHECKLIST.md`, and tells you which steps it could not read.
4. You check the chore in the app's Review screen before it ever runs.

## What a recording cannot teach

Why you did something. "I refreshed that order because it paid wood" is not in the pixels — say it
in chat when you send the file, one line per recording, and it goes into the chore as the rule.

— Claude, 2026-10-25
