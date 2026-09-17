# Red Room

Monthly Friday night concept for **Club Guvnor**, built on the 2020 silhouette-challenge
format. Runs the **4th Friday of every month**. First edition: **Fri 25 Sept 2026**.

Everything in this folder is the launch campaign for edition one.

---

## What's here

| File | What it is |
|---|---|
| `concept.html` | The full concept: idea, Silhouette Hour, lighting spec, run of show, bar, calendar, rollout |
| `teaser.html` | Week-one teaser poster, feed and story sizes |
| `reveal.html` | The four DJ reveal posters plus the photo brief |
| `reel-player.html` | The 18s teaser reel with its beat breakdown |
| `captions.md` | Post copy for every week of the rollout |
| `exports/` | Rendered PNGs and the MP4 — the files you actually post |
| `reel/` | HyperFrames source for the reel, so it can be re-rendered or edited |
| `photos/` | **Drop the DJ photos here** — see `photos/README.md` |

Open any `.html` file directly in a browser. No build step, no server.

---

## The line-up

| Slot | Act | Set | Notes |
|---|---|---|---|
| Peak | DJ Alisha | 01:00 – 02:30 | Silhouette Hour lands inside this set |
| Opener | DJ Tea | 22:00 – 23:30 | Happy hour, body shots, UV pockets |
| Build | Missterious2 | 23:30 – 01:00 | **Duo** — riser and frame must hold two |
| Close | DJ Hady | 02:30 – 04:00 | UV segment, then free floor |

All four play every edition. The peak slot rotates monthly so each act headlines
once a quarter: Alisha → Tea → Missterious2 → Hady.

---

## Calendar

| Edition | Date | |
|---|---|---|
| 1 | Fri 25 Sep 2026 | Launch |
| 2 | Fri 23 Oct 2026 | |
| 3 | Fri 27 Nov 2026 | |
| 4 | Fri 25 Dec 2026 | **Christmas Day** — skip, move to the 18th, or make it the special |
| 5 | Fri 22 Jan 2027 | |

---

## Two things that will bite you

**Red light kills UV paint.** Neon tattoos do not glow under a red wash. The red
silhouette look and the neon-tattoo look cannot share a lighting state — they have to
be separated by zone or by time. See the lighting section in `concept.html`.

**Silhouettes need backlight, not red light.** A bright source *behind* the body with
no front fill. On an open floor under a red wash, dancers just look like people
standing in red light. They need risers or lit doorframes.

---

## Re-rendering

The posters are plain HTML at fixed pixel sizes — screenshot the `.stage` element at
2x, or open and export however you like.

The reel is a HyperFrames project:

```bash
cd reel
npm install
npx hyperframes check     # lint, runtime, layout, motion, contrast
npx hyperframes render    # writes renders/*.mp4
```

GSAP and the webfonts are vendored under `reel/assets/` on purpose — the renderer
runs in a sandboxed browser with no CDN access, and vendoring also keeps the render
deterministic.

The reel is **silent by design**. Add the *Put On* → *Streets* transition inside
Instagram so it pulls from their licensed library; a baked-in track risks the post
being muted.

---

## Still open

- **The December call.** Christmas Day, one way or the other — decide before the
  campaign starts, since the reveal posts will already be promising a monthly night.
- **Handles and name spellings** from each act, for tagging and the flyer.
- **Licence check** on body-shot service before anything prints.
- **Lighting test** with the real rig, real dancers, real paint — photographed, because
  the phone camera is what matters.
