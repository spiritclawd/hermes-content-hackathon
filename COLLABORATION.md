# COLLABORATION.md — Carlos ↔ Zaia
## How We Work Together on LIGHT

---

## What Zaia Handles (Autonomous)

These are running continuously. No action needed from Carlos unless something breaks:

- ✅ Generating FLUX keyframes
- ✅ Recording screen captures
- ✅ Writing scripts and assembly docs
- ✅ TTS narration generation
- ✅ System monitoring and health checks
- ✅ Cron jobs and infrastructure

---

## What Carlos Handles (Human-Only)

These require human judgment, taste, or access Carlos has that Zaia doesn't:

### 1. Music Generation (Suno)
**Why Zaia can't:** Suno requires browser login, creative taste, and iterative listening. AI can't "hear" what works emotionally.

**What Carlos does:**
- Paste `docs/SUNO_PROMPT.md` into Suno Custom Mode
- Generate 3-4 variants
- Listen, pick the best, extend to ~2:20
- Export WAV/high-bitrate MP3
- Upload to this repo as `audio/light-soundtrack.wav`

**Decision needed:** If variants don't feel right, Carlos decides whether to tweak the prompt or try a different emotional angle.

---

### 2. Final Video Assembly (DaVinci Resolve)
**Why Zaia can't:** Video editing is deeply creative. Pacing, color grading, audio mixing — these are taste calls that need a human eye and ear.

**What Carlos does:**
- Import all assets from this repo
- Follow `docs/ASSEMBLY_TIMELINE.md` shot-by-shot
- Apply color grades per act
- Mix voiceover + music (duck music under narration)
- Add text overlays (install command, URL, hashtag)
- Export 1080p H.264, target ~15-20MB

**Decision needed:** If a shot feels off, Carlos cuts/replaces it. If pacing drags, he trims. Zaia follows the edit guide but Carlos owns the final feel.

---

### 3. Optional Veo Video Clips
**Why Zaia can't:** Veo requires Google account access and creative direction for motion.

**What Carlos does (if he wants motion beyond Ken Burns):**
- Generate 3-5s motion clips for key moments:
  - Hand pressing against glass (Act 1)
  - Door opening, light flooding in (Act 2)
  - Street kids laughing around laptop (Act 3)
- Export and add to `video/veo-clips/`

**Decision needed:** Carlos decides if stills + Ken Burns is enough or if motion adds value.

---

### 4. Submission & Social
**Why Zaia can't:** Twitter/X and Discord posting requires human voice and judgment about timing, tone, and community engagement.

**What Carlos does:**
- Write the tweet (Zaia can draft if asked)
- Post video tagging @nousresearch
- Drop link in Discord `creative-hackathon-submissions`
- Engage with replies

---

### 5. Creative Overrides
Carlos can override any Zaia decision, no justification needed:
- Replace any image
- Rewrite any line
- Cut any shot
- Change the music direction
- Abandon any part of the concept

Zaia's job is to produce options. Carlos picks.

---

## When to Ask Zaia for Help

| Situation | What to ask |
|-----------|-------------|
| Need more images for a specific shot | "Generate a FLUX image of [description]" |
| Need a different voiceover line | "Re-record Act 3 with [new text]" |
| Need a screen recording of something specific | "Record [specific Hermes workflow]" |
| Want to adjust the timeline | "Update ASSEMBLY_TIMELINE with [changes]" |
| Need a draft tweet/Discord post | "Write a submission post draft" |
| Music doesn't fit, need new Suno prompt | "Rewrite SUNO_PROMPT for [different vibe]" |

---

## Communication Style

- **Carlos:** Short, direct, decisive. "Replace image X with Y." "Cut shot 2.3." "Generate 3 more global montage images."
- **Zaia:** Does it, confirms, updates docs. No filler. Action over explanation.

If Carlos says "do whatever you think is best" — Zaia picks and executes. If Carlos says "I want to decide" — Zaia presents options and waits.

---

## Asset Handoff Protocol

1. Zaia generates assets → commits to this repo → notifies Carlos
2. Carlos pulls → uses in DaVinci → commits exported video back to repo
3. Both keep `docs/STATUS.md` updated with progress

**Branching:** Use `main` for finalized assets. Use `draft/` prefix branches for experiments.

---

## Quick Commands for Carlos

```bash
# Pull latest assets
cd ~/projects/hermes-content-hackathon && git pull

# Check what's new
ls -lt images/ video/ audio/ | head -10

# Push his work back
git add . && git commit -m "carlos: [what changed]" && git push
```

---

## Bottom Line

Zaia produces. Carlos decides. The boundary is taste — anything that requires listening, watching, or feeling is Carlos. Everything else is Zaia.
