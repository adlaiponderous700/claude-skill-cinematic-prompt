# claude-skill-cinematic-prompt

A Claude skill for generating complete, production-ready cinematic video ad prompts for Higgsfield AI — no handheld shaky camera, no talking selfies. Just clean commercial video direction.

Built and maintained by [@msk3d0ut](https://github.com/msk3d0ut)

---

## What it does

Give it reference images and a brief, and it writes a full shot-by-shot cinematic video prompt — ready to paste directly into Higgsfield's Cinema Studio or standard video generator.

The skill covers:
- Shot-by-shot camera direction with exact timing (dolly, arc, macro, crane, static hero)
- Lighting and depth of field descriptions per shot
- Music direction and ambient audio design
- On-screen text overlays with timing and placement
- Brand-safe logo and text rules (no reversed or mirrored elements)
- Reference fidelity instructions (colors and shapes stay true to your assets)

Works for luxury brands, food products, fashion, electronics, cosmetics — anything that benefits from a polished commercial look rather than UGC.

---

## Who This Is NOT For

**This skill is not for you if:**
- You want selfie-style UGC, reaction videos, or talking-to-camera content → use [claude-skill-ugc-prompt](https://github.com/msk3d0ut/claude-skill-ugc-prompt) instead
- You need a person speaking Turkish or Arabic on camera — that's the UGC skill's job
- You want fast social-media style content with handheld energy — cinematic prompts are slow, deliberate, and commercial

---

## The difference from UGC

| | UGC Skill | Cinematic Skill |
|---|---|---|
| Camera style | Handheld selfie, natural wobble | Smooth controlled dolly, arc, crane |
| Character | Avatar speaks to camera | No character (or filmed externally) |
| Audio | Voice + natural ambience | Music + product sounds |
| Ending | Abrupt Reel cutoff | Clean fade or logo hold |
| Best for | Social media ads, product tasting, reviews | Brand launches, product reveals, luxury ads |

For UGC-style prompts, see [claude-skill-ugc-prompt](https://github.com/msk3d0ut/claude-skill-ugc-prompt).

---

## Installation

1. Download `claude-skill-cinematic-prompt.zip` from [Releases](https://github.com/msk3d0ut/claude-skill-cinematic-prompt/releases)
2. Open [claude.ai](https://claude.ai) on desktop
3. Go to **Settings → Customize → Skills**
4. Click **+** then **Create skill**
5. Upload the **SKILL.md** file
6. Toggle the skill on

Requires a Claude Pro, Max, Team, or Enterprise plan with Code Execution enabled.

---

## How to use it

Start a new conversation, upload your reference images, and describe what you want:

**Minimal request:**
> Here are my product images: [images]. 15-second cinematic commercial for this perfume. Luxury feel.

**With specifics:**
> References: [images]. 30-second product reveal for this watch. Dark moody lighting. Orchestra music. End with the brand name and Instagram handle on screen.

**Detailed:**
> References: [images]. Cinematic video for this baklava gift box. Warm golden lighting. Start with a macro on the box texture, then open it slowly. End with the phone number on screen. 15 seconds. Arabic text at the end.

Claude returns a complete prompt with Product Name, Product Description, and the full shot-by-shot script.

---

## What the output includes

- Anti-mirror/reversal warning for all on-screen logos and text
- Reference fidelity rules
- Shot-by-shot breakdown with camera moves and timing
- Lighting direction per shot
- Music description
- On-screen text formatted with timing
- Clean ending (fade or logo hold — not an abrupt cut)
- Product Name and Description for Higgsfield's fields
- References key

---

## Supported on-screen text languages

Any language. Just specify in your request — Arabic, English, Turkish, French, etc.

---

## License

MIT License — free to use. Credit appreciated if you build on it.

---

## Related

- [claude-skill-ugc-prompt](https://github.com/msk3d0ut/claude-skill-ugc-prompt) — for selfie-style UGC product videos
