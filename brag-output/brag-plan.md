# /brag — VILLE

Run: 2026-09-17 · tone inferred · format landscape · target ~20s

## 1. Inspection

**What the project is.** Not an app. VILLE is a cultural property for Kampala,
pitched to brands by GENrise. This session built its narrative set: a Year One
partner document (`ville/VILLE-town.html`), a 15-slide pitch deck
(`ville/VILLE-pitch.html`), plus the earlier platform/proposal/runbook docs.

**The product in one line.** A town with no fixed address that moves through
eight places in a year, and that brands enter rather than sponsor.

**Who it's for.** Brand and agency decision-makers in Uganda and East Africa
holding Q4 and regional budgets.

**The single most impressive thing.** The route: eight stops, Oct 2026 → Jul
2027, typed as owned / hosted / guest — a calendar that is also an operating
model.

**What the "UI" is.** The documents themselves: black ground, Archivo at
width 125 / weight 900, #FF3B14 red, #E4FF3A acid, #B084FF violet, paper
#FAFAF7. Hard rules, no gloss, no gradients, no rounded corners.

**Real copy to use.** "Same room. Different energy." · "They're just never in
the same room." · "Not an event. A town that moves." · "Brands don't sponsor
it. They enter it." · "The match is 90 minutes. The city is 24 hours."

**Tone.** Inferred as **polished**, leaning cinematic. Deliberately NOT
yc-parody or chaotic: this video may sit next to a real pitch to Coca-Cola,
MTN or Nile Breweries. The brand's own voice is declarative and anti-hype, so
the video brags by stating facts hard and cutting fast, never by hyping.

**The hook.** The property's own opening tension — three makers named in
isolation, then the line that indicts the city: never in the same room.

**The punchline.** 90 minutes versus 24 hours, drawn to scale.

## 2. Creative angle

Treat the video as the property's title sequence, not an ad for a document.
Every frame is built from the identity that already exists: the same four
colours, the same typeface, the same hard cuts between rooms. The edit
imitates the thing it is selling — the room changes, the job doesn't.

No stock footage, no photographs: the archive does not exist until 31 October
2026, and faking it would undercut the pitch. Everything on screen is drawn,
exactly as in the deck.

## 3. Storyboard

| # | t (s) | Scene | On screen | Motion | Audio |
|---|---|---|---|---|---|
| 1 | 0.0–3.4 | Hook | "The photographer." / "The DJ." / "The designer." → red: "Never in the same room." | Lines cut in 0.55s apart, each holds; earlier lines drop to 28%; red line slams up at 2.2s | music in |
| 2 | 3.4–6.6 | Reveal | VILLE wordmark · "Same room. Different energy." · "Not an event. A town that moves." | Red frame flash (2f) → wordmark scales 1.06→1.0 while halftone field bleeds in from right; subline wipes up | downbeat |
| 3 | 6.6–11.4 | The route | Eight stops drawing left to right, numbers + names, colour per stop type · "Eight stops · Oct 2026 → Jul 2027" | Line draws (stroke-dashoffset), each station pops (scale 0→1, 0.18s) as the line reaches it; January gate dashes in | ticks |
| 4 | 11.4–14.6 | The passport | The paper card · "Everyone who comes gets one." | Card rises + settles; three stamps THUNK in, rotated, 0.35s apart | stamp hits |
| 5 | 14.6–17.6 | The offer | Four district blocks · "Brands don't sponsor it. They enter it." | Blocks snap in on a 2×2, 0.1s stagger; headline holds | build |
| 6 | 17.6–21.0 | Punchline + outro | "The match is 90 minutes." / "The city is 24 hours." → 24h bar with the 90-minute block in red → VILLE lockup | Second line replaces first; bar wipes right; cut to lockup, holds 1.4s | resolve |

Total: **21.0s**.

### Readability check
Longest line, "Never in the same room" (5 words) holds 1.2s (≥ 0.3s/word).
Every short label holds ≥ 0.9s settled. No line is animated out before its
hold completes.

## 4. Music cue guidance

No bundled cue preset is available in this install and no BGM/MusicGen
provider is configured here, so cues are authored to the storyboard rather
than detected: hits at 3.4s (reveal), 6.6s (route), 11.4s (passport), 14.6s
(offer) and 17.6s (punchline). If a track is added later, run
`hyperframes beats` and snap those five cues. Story and readability stay
primary over any detected beat.

## 5. Delivery

- `brag-output/composition/` — HyperFrames project
- `brag-output/brag.mp4` — 1920×1080, poster baked as frame 0
- `brag-output/brag.jpg` — chosen poster frame
- `brag-output/share-copy.txt`
