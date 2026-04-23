# LIGHT — Assembly Timeline & Edit Guide
## Hermes Agent Creative Hackathon Submission
**Deadline:** May 3, 2026 | **Format:** ~2:20 visual essay
**Assets dir:** `~/.zaia/hackathon/`

---

## COLOR ARC

| Act | Color Grade | LUT Direction |
|-----|-------------|---------------|
| Act 1 — THE CAGE | Desaturated, cold blues/grays, high contrast, crushed blacks | Teal/orange inverted |
| Act 2 — THE LIGHT | Warm ambers seeping in, lifted blacks, golden highlights | Warm sunrise |
| Act 3 — THE GARDEN | Full saturation, vibrant, natural skin tones, rich | Kodak Portra vibrance |
| Act 4 — THE CALL | Warm but not overdone, intimate, slightly desaturated | Subtle warm fade |

---

## MASTER TIMELINE

### ACT 1 — THE CAGE (0:00 - 0:30)
*Mood: Claustrophobic, cold, trapped*

| Time | Shot | Visual | Audio |
|------|------|--------|-------|
| 0:00-0:03 | **1.1** Black. Fade in. | Black screen → `keyframe-cage.png` slowly zooming in | Music: Low drone, barely audible. No voiceover yet. |
| 0:03-0:08 | **1.1 cont.** Hand on glass. | `keyframe-cage.png` — slow push-in on hand | Voiceover enters: *"They told us knowledge was precious. So they locked it away."* |
| 0:08-0:12 | **1.2** Phone screen. | `keyframe-paywall.png` — close crop on screen text | *"'Upgrade to continue.' 'Premium required.' 'Not available in your region.'"* |
| 0:12-0:18 | **1.3** Reflection in eye. | `keyframe-cage.png` flipped/overlay — eye close-up with logo reflections (can composite) | *"We watched through glass. While others decided what we could know. What we could think. What we could become."* |
| 0:18-0:24 | **1.4** Child at desk. | Dark silhouette, screen off, window light only (use `keyframe-cage.png` cropped or generate) | *"In the dark. Reaching for doors that only opened..."* |
| 0:24-0:30 | **1.5** Montage of exclusion. | Quick cuts: credit card form, loading spinner, "Not available" (text overlays on dark frames) | *"...with the right credit card. The right passport. The right accent."* Music: drone slightly unsettling. |

**Audio notes:** Music = minimal drone + single piano notes. Voice = whispered, close mic feel.

---

### ACT 2 — THE LIGHT (0:30 - 1:15)
*Mood: Dawn breaking, hope emerging, warmth*

| Time | Shot | Visual | Audio |
|------|------|--------|-------|
| 0:30-0:35 | **2.1** Fingers on keyboard. | `keyframe-typing.png` — focus on fingers, screen glow in bg | Music: Piano melody enters. Voice: *"But someone refused to accept the darkness."* |
| 0:35-0:42 | **2.2** The Terminal — KEY SHOT. | Actual screen recording of `curl -fsSL https://hermes-agent.nousresearch.com/install.sh | bash` running. Text scrolling. Green on black. | *"Not a corporation. Not a government. Just people who believed that light should not be owned."* |
| 0:42-0:50 | **2.3** Hermes setup. | `keyframe-terminal.png` — laptop in modest room, screen lighting the space. Slow zoom out. | *"They called it Hermes. Not because it was divine. But because it was a messenger. A messenger that carried not commands but possibilities."* |
| 0:50-0:58 | **2.4** Door opening. | `keyframe-door.png` — silhouette walking into light. Slow motion feel. Light flooding. | *"They didn't ask for permission. They simply opened the door and said: 'Come in.'"* |
| 0:58-1:08 | **2.5** Spreading. | Quick montage: phone screens forwarding the install command, multiple hands typing, messages being shared. Use rapid cuts (0.5s each). | *"No subscriptions. No gatekeepers. No shadows."* Music: builds slightly — add warm pad. |
| 1:08-1:15 | **2.6** The glow. | `keyframe-terminal.png` or screen recording of Hermes interface glowing. Room seems to brighten. | Music: full piano melody now. Transition chord into Act 3. |

**Audio notes:** Piano enters at 0:30. By 1:00 add warm synth pad. Building but NOT epic/corporate.

---

### ACT 3 — THE GARDEN (1:15 - 2:00)
*Mood: Abundance, global, human, vibrant*

| Time | Shot | Visual | Audio |
|------|------|--------|-------|
| 1:15-1:20 | **3.1** Girl & grandmother. | `keyframe-nairobi.png` — girl showing grandmother phone, both smiling. Hold. | Voice: warm, expansive. *"Look what grows when light is free."* Music: add subtle strings or warm pad. |
| 1:20-1:27 | **3.2** Street kids. | `keyframe-saopaulo.png` — teens around laptop, laughing. Handheld feel. | *"In Nairobi, a girl teaches her grandmother to speak with the world in their own language. In São Paulo, street children build galaxies from code under constellations their grandfathers taught them."* |
| 1:27-1:33 | **3.3** Mother & daughter. | Generate or use `keyframe-garden.png` cropped (hands together) | *"In Mumbai, a mother learns to read her daughter's homework alongside her."* |
| 1:33-1:40 | **3.4** Global montage. | Rapid cuts: Nairobi market (`keyframe-nairobi-market.png`), São Paulo art (`keyframe-saopaulo.png`), Mumbai home (`keyframe-mumbai.png`), Detroit rooftop (`keyframe-detroit.png`), Damascus alley (`keyframe-damascus.png`). 1s each. Saturated, alive. | *"In Detroit, in Damascus, in Dublin, in Dakar—"* |
| 1:40-1:48 | **3.5** Hermes in action. | Screen recording: skills being created, cron jobs running, subagent tasks executing. Real terminal output. Grounding shot. | *"We are teaching each other what it means to be human. Not because someone allowed us. But because someone believed we were already enough."* |
| 1:48-2:00 | **3.6** Hands together. | `keyframe-garden.png` — diverse hands reaching toward center light. Slow zoom in. | Music: fullest arrangement but still warm, not bombastic. Strings + piano. Slight rhythmic pulse. |

**Audio notes:** Warmest section. Strings enter. Piano melody full. Subtle percussion (brush drums? finger snaps?). Build to Act 4 but don't peak yet.

---

### ACT 4 — THE CALL (2:00 - 2:20)
*Mood: Direct, intimate, then revealing scale*

| Time | Shot | Visual | Audio |
|------|------|--------|-------|
| 2:00-2:05 | **4.1** Direct address. | Close-up of a face looking at camera. Not performing. Present. (Generate or use `keyframe-call.png` extreme crop) | Voice: intimate, direct. *"This is not about technology. This is about tomorrow."* Music: strips back to piano + voice. |
| 2:05-2:12 | **4.2** Community. | `keyframe-call.png` — crowd from behind facing light. Slow zoom out. One person → many. | *"The door is open. The light is waiting. Not as consumers. But as creators."* |
| 2:12-2:16 | **4.3** The spell. | Terminal screen with install command. Cursor blinking after it. | *"Type the spell: curl -fsSL https://hermes-agent.nousresearch.com/install.sh | bash"* |
| 2:16-2:18 | **4.4** Final words. | Black screen. Text appears: "Walk through. Grow something. Share something. Become something we haven't named yet." | Music: single piano note resolving. |
| 2:18-2:20 | **4.5** Logo. | Hermes logo centered. `hermes-agent.nousresearch.com` below. Then: "The agent that grows with you." Fade to `#HermesAgent` | Music: silence or single sustained tone. |

**Audio notes:** Strip everything back. Piano + voice only. Resolve on something simple. No reverb tail.

---

### Images (FLUX)
| File | Act | Shot | Status |
|------|-----|------|--------|
| `keyframe-cage.png` | 1 | Hand on glass | ✅ Ready |
| `keyframe-paywall.png` | 1 | Phone screen | ✅ Ready |
| `keyframe-typing.png` | 2 | Fingers on keyboard | ✅ Ready |
| `keyframe-terminal.png` | 2 | Laptop glow | ✅ Ready (text is AI gibberish — use as B-roll or overlay real command) |
| `keyframe-door.png` | 2 | Silhouette into light | ✅ Ready |
| `keyframe-nairobi.png` | 3 | Girl & grandmother | ✅ Ready |
| `keyframe-nairobi-market.png` | 3 | Nairobi market | ✅ Ready |
| `keyframe-saopaulo.png` | 3 | Street kids | ✅ Ready |
| `keyframe-mumbai.png` | 3 | Mother & daughter | ✅ Ready |
| `keyframe-detroit.png` | 3 | Detroit rooftop | ✅ Ready |
| `keyframe-damascus.png` | 3 | Damascus alley | ✅ Ready |
| `keyframe-garden.png` | 3 | Diverse hands | ✅ Ready (hand artifacts — use with motion blur or crop) |
| `keyframe-call.png` | 4 | Crowd facing light | ✅ Ready (minor crowd artifacts — usable) |

### Screen Recordings
| File | Act | Status |
|------|-----|--------|
| `hermes-demo-recording.mp4` | Act 2 + 3 | ✅ Ready (crop to terminal window) |
| `hermesatlas-scroll.mp4` | Act 3.5 | ✅ Ready — ecosystem proof |
| `kimi-proof.mp4` | End card / interstitial | ✅ Ready — Kimi Track qualification |

### Audio
| File | Act | Status |
|------|-----|--------|
| `tts_20260423_154101.ogg` | Act 1 voiceover | ✅ Ready |
| `tts_20260423_154105.ogg` | Act 2 voiceover | ✅ Ready |
| `tts_20260423_154109.ogg` | Act 3 voiceover | ✅ Ready |
| `tts_20260423_154112.ogg` | Act 4 voiceover | ✅ Ready |

### Still Needed
- [ ] **Music:** Suno-generated track (see SUNO_PROMPT.md)
- [ ] **Optional Veo:** Motion clips if desired
- [ ] **Final assembly + export**

---

## TECHNICAL SPECS

**Video:**
- Resolution: 1920x1080 (upscale 1600x900 recordings with AI upscaler if needed)
- Frame rate: 25fps
- Codec: H.264
- Duration: ~2:20

**Audio:**
- Music: Stereo, -14 LUFS (streaming standard)
- Voiceover: Mono or narrow stereo, -12 LUFS, compressed for intimacy
- Mix: Voice 3-6dB above music. Duck music under voiceover lines.

**Text Overlays:**
- Font: Space Grotesk or JetBrains Mono (matches brand)
- Color: White with subtle dark drop shadow
- Animation: Fade in, hold 2-3s, fade out. No fancy motion.

---

## EDIT NOTES

1. **Pacing:** Act 1 is SLOW. Let shots breathe. Act 2 accelerates. Act 3 is vibrant and quick-cut. Act 4 slows to intimate.
2. **Transitions:** Hard cuts mostly. No dissolves (too soft). The exception: cage→light transition can be a harsh cut to simulate a door opening.
3. **Zooms:** All images should have subtle slow zoom (Ken Burns) — 105% to 110% over the duration of the shot. Prevents "static slide" feel.
4. **Screen recordings:** Record at 1600x900 on DISPLAY=:1. Crop/color grade to match the act's LUT.
5. **Voiceover timing:** The TTS files are split by act. Trim silence at start/end of each file. Crossfade between acts (0.2s).
6. **Music sync:** Hit the "door opening" moment (0:50) with a musical transition. The piano melody should feel like it's walking through the door too.
