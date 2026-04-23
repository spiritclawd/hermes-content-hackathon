# LIGHT — Hermes Agent Creative Hackathon

> **A visual essay about freedom, powered by open-source AI.**

**Submission for:** Hermes Agent Creative Hackathon ($20k pool)  
**Deadline:** May 3, 2026  
**Tracks:** Main Track ($15k) + Kimi Track ($5k)  
**Runtime:** ~2:20  
**Format:** 1080p cinematic short film

---

## What This Is

Not a product demo. A manifesto about what happens when AI belongs to everyone.

**LIGHT** tells the story of corporate AI lock-in → the open-source alternative (Hermes) → the global community that grows from it → a direct call to action.

Four acts. Piano-driven ambient score. AI-generated visuals mixed with real screen recordings. Female voiceover. No stock footage.

---

## Directory Structure

```
├── audio/              # Voiceover narration (4 acts, OGG format)
├── images/             # FLUX-generated keyframes (13 images)
├── video/              # Screen recordings (Hermes demo, Atlas scroll, Kimi proof)
├── docs/               # Scripts, timelines, music prompts, status
├── README.md           # This file
└── COLLABORATION.md    # How Carlos and Zaia work together on this
```

### Audio (`audio/`)
| File | Duration | Content |
|------|----------|---------|
| `act1-cage.ogg` | ~30s | "They told us knowledge was precious..." |
| `act2-light.ogg` | ~45s | "But someone refused to accept the darkness..." |
| `act3-garden.ogg` | ~45s | "Look what grows when light is free..." |
| `act4-call.ogg` | ~20s | "This is not about technology..." |

### Images (`images/`)
13 FLUX-generated keyframes covering all 4 acts:
- **Act 1 — THE CAGE:** Hand on glass, phone paywall
- **Act 2 — THE LIGHT:** Typing, terminal glow, door opening
- **Act 3 — THE GARDEN:** Nairobi, São Paulo, Mumbai, Detroit, Damascus, diverse hands
- **Act 4 — THE CALL:** Crowd facing glowing portal

### Video (`video/`)
| File | Duration | Purpose |
|------|----------|---------|
| `hermes-demo-recording.mp4` | 46s | Terminal: install, status, skills, cron, subagents |
| `hermesatlas-scroll.mp4` | 22s | Scrolling hermesatlas.com — 95 projects, 12 categories |
| `kimi-proof.mp4` | 18s | Kimi Track qualification: shows Kimi K2.6 generating script |

### Documents (`docs/`)
| File | Purpose |
|------|---------|
| `script-final.md` | Locked narration script (written by Kimi K2) |
| `script-concept.md` | Concept document with emotional arc |
| `production-brief.md` | Shot list + music brief |
| `ASSEMBLY_TIMELINE.md` | **Edit guide — shot-by-shot with timing** |
| `SUNO_PROMPT.md` | **Full Suno music prompt — paste into Custom Mode** |
| `STATUS.md` | Production tracker |

---

## Edit Guide (Quick Reference)

Follow `docs/ASSEMBLY_TIMELINE.md` for the full shot list. Key points:

| Act | Time | Color Grade | Music |
|-----|------|-------------|-------|
| THE CAGE | 0:00-0:30 | Desaturated, cold, crushed blacks | Minimal drone + single piano notes |
| THE LIGHT | 0:30-1:15 | Warm ambers, lifted blacks | Piano melody enters, warm pad builds |
| THE GARDEN | 1:15-2:00 | Full saturation, vibrant natural tones | Strings + piano, rhythmic pulse |
| THE CALL | 2:00-2:20 | Warm intimate, slight desaturation | Strip back to piano + voice only |

**Key transition:** The "door opening" moment at 0:50 should hit a musical shift.

---

## Music Generation

1. Open [Suno](https://suno.com)
2. Use **Custom Mode**
3. Paste `docs/SUNO_PROMPT.md` style description into the Style field
4. Paste the metatags/lyrics into the Lyrics field
5. Generate 3-4 variants, pick best, extend to ~2:20
6. Export as WAV or high-bitrate MP3

**Reference tracks to listen to first:**
- Ólafur Arnalds — "Near Light"
- Nils Frahm — "Says"
- Hania Rani — "Glass"

---

## Submission Checklist

- [ ] Suno music generated and exported
- [ ] Video assembled in DaVinci Resolve (or editor of choice)
- [ ] Color grading applied per act
- [ ] Voiceover mixed (duck music under narration)
- [ ] Text overlays: install command + final URL + #HermesAgent
- [ ] Kimi proof included (brief interstitial or end card)
- [ ] Export: 1920x1080, H.264, ~15-20MB for Twitter
- [ ] Tweet demo video tagging @nousresearch
- [ ] Drop link in Discord `creative-hackathon-submissions`
- [ ] Submit by **May 3, EOD**

---

## Creative Team

- **Carlos** (@carldlfr) — Direction, music, final edit, Veo footage, submission
- **Zaia** — Scriptwriting (Kimi K2.6), FLUX keyframes, TTS narration, screen recordings, assembly docs

---

## License

Submission assets for the Hermes Agent Creative Hackathon. All original work.
