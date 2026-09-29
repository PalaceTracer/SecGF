---
chapter_id: "05"
retrieval_tags: [instrument_roles, timbre, sound_sources, attack, decay, sustain, release, articulation, filtering, modulation, noise, layering, spectral_balance]
use_when: "Read when selecting a few defining sound sources or turning vague texture words into audible timbre and arrangement instructions."
output_influence: style
---

# 05 — Sound sources and timbre

## Choose roles before names

A Style field cannot carry an inventory of every sound. Decide what each needed source **does**: marks the pulse, carries bass, supports chords, states the hook, answers the lead, makes atmosphere, or punctuates a transition. Assign no more than one main carrier to a role unless the intended effect is a clear layer or exchange. “Plucked upper figure answers the vocal” is often more useful than a list of possible instruments because it specifies register, articulation, and timing. A named instrument can still be useful when its characteristic sound is indispensable, but do not expect the name alone to determine performance.

Separate **source identity** from **timbre** and **part behavior**. A keyboard source may have a rounded, sustained tone or a bright, short one; the same nominal source can occupy foreground or background. A guitar-like source can strum chords, play short single notes, sustain a line, scrape rhythmically, or create noise. The Style prompt should carry the smallest combination that prevents an unwanted substitution: source family, audible tone, role, and timing. A sound that has no clear job in the listener’s mental image probably does not deserve prompt space.

## The four audible parts of a note

**Attack** is the start of a sound: abrupt, soft, picked, struck, breathy, bowed, or swelling. **Decay** is what happens after the initial peak. **Sustain** is the level and tone held while the note continues. **Release** is the tail after the note ends. This envelope distinguishes a clicky pluck from a slowly swelling pad even at the same pitch. The [Live 12 manual](https://www.ableton.com/en/live-manual/12/live-instrument-reference/) defines these stages operationally. A [controlled timbre study](https://pmc.ncbi.nlm.nih.gov/articles/PMC5698532/) manipulated attack and release information during source identification, showing that temporal envelope is one contributor to recognizing a sound; it does not reduce all source identity to the envelope alone.

For Style, describe the listener’s experience instead of numbers: “quick attack and short decay,” “rounded onset with a long, airy tail,” “soft swell that blooms after the lead phrase.” A transient can supply rhythm even when the note is harmonically simple. A sustained sound can provide continuity without frequent attacks. The selected envelope should fit the lyric: short plucks may leave consonants exposed; long tails may support held vowels but blur fast speech if placed in the same range.

**Articulation** concerns how one note connects to the next. Detached notes leave gaps; connected notes form a line. Muted attacks emphasize rhythm over ring. A tremoring or repeated articulation adds activity without changing pitch. Do not infer articulation from source name. “Muted, sharply cut chord strokes” and “slowly connected chord tones” are distinct even if both use the same instrument family.

## Brightness, spectrum, and noise

**Brightness** often refers to stronger upper-frequency content relative to lower content, but it also depends on attack and register. A bright onset with a warm tail differs from a continuously thin tone. **Dark** may mean softened upper partials, a low register, or a recessed mix position; specify which is intended. **Hollow**, **nasal**, **metallic**, **glassy**, **woody**, and **grainy** are useful only when paired with role and envelope. “A short metallic two-note answer” gives more direction than “metallic atmosphere.”

A filter can attenuate parts of a spectrum; a moving filter can make a held sound change color over time. A noise component can add hiss, breath, scrape, or roughness. Modulation can vary pitch, amplitude, or tone periodically or irregularly. The [Live 12 manual](https://www.ableton.com/en/live-manual/12/live-instrument-reference/) describes these mechanisms. In Style, describe the audible motion: “a low sustained tone slowly opens brighter,” “a narrow high note wavers gently,” or “a dry strike carries a brief noise edge.” Avoid device parameters unless a user specifically asks for production settings. Text generation may imitate the result without implementing the mechanism literally.

**Warm**, **thick**, **shimmering**, and **vintage** are underspecified by themselves. Translate them. Warm might mean soft attacks and low-mid weight, or gentle saturation, or muted upper content; choose the intended cause. Thick might mean a doubled line, close chord spacing, heavy bass, or long overlapping releases. Shimmering might mean bright sustained high partials with slow movement. Do not force every sound to share one adjective. Contrast gives hierarchy: a dry attack can sit in front of a long diffuse layer, and a dark bass can support a bright short hook.

## Acoustic, electric, sampled, and synthesized behavior

These source families describe production possibilities, not fixed emotional properties. A physically excited source may show tiny variation from one strike to another; a sample may repeat exactly or be deliberately varied; a synthesized tone can be static or highly modulated. A text prompt should describe what is audible: “slight variation in repeated upper attacks,” “identical crisp low hits,” “sustained tone with slow brightness movement.” It should not use “organic” as a substitute for timing, tone, and dynamics.

## Roles and interaction map

| Role | Candidate audible design | Watch for |
| --- | --- | --- |
| Rhythm bed | Repeated clipped attacks on a stable subdivision | Duplicating hats or competing with consonants |
| Harmonic support | Held, widely spaced tones behind the lead | Tails blurring chord changes or lyrics |
| Hook carrier | Short recognizable figure in one exposed register | Hook repeating so often it loses emphasis |
| Counterline | Sparse notes between vocal lines | Simultaneous activity masking the lead |
| Atmosphere | Low-level evolving noise or sustained color | Texture becoming louder than the song’s core |
| Transition marker | One brief swell, strike, or drop | Constant decoration erasing section boundaries |

## Density, register, and layers

**Layer count** is distinct from perceptual density. Two long overlapping sounds can fill more space than five short punctuations. Density rises with overlapping durations, similar registers, repeated attacks, and reverb tails. To protect a vocal, limit concurrency in its register and phrase spaces rather than simply reducing all volume. A low bass, high accent, and midrange lead can coexist more clearly than three simultaneous midrange melodies. This is a practical arrangement heuristic; verify it on the actual render.

**Register handoff** is a useful alternative to piling up layers. A high figure can disappear when the lead moves high, then return when the voice descends. A low pad can recede when bass becomes active. “The high pluck answers only in vocal gaps” encodes this as an audible arrangement rule. If the prompt budget is tight, one such interaction outranks a long list of source names.

## Original prompt fragments and audible tests

These fragments are proposed instructions to test through listening; they are not official Suno syntax.

| Intent | Candidate Style fragment | Listen for |
| --- | --- | --- |
| Exposed words | “Clipped midrange chord strokes stop between dense lead phrases.” | Chords leave actual gaps and consonants remain clear. |
| Recognizable opening | “A dry, glassy three-note figure appears before the first vocal and answers later lines.” | Same figure returns after its opening statement. |
| Growing refrain | “Verse uses narrow, short plucks; refrain keeps their figure but lets the notes ring wider and longer.” | Identity persists while duration and image expand. |
| Slow motion inside a held sound | “Soft sustained upper tone gradually brightens without adding new notes.” | Tone evolves while pitch stays stable. |
| Contrasting surfaces | “Rough short chord attacks sit beneath a smooth, airy sustained layer.” | Distinct foreground and background textures. |
| Cleaner lyric space | “Bass and dry pulse stay low; high accents occur only after line endings.” | The lead has an uncluttered middle register. |

To test a timbre description, replay the first appearance of the target sound and note its onset, body, tail, register, and role. Ask whether the described feature is audible without reading the prompt. If the take substitutes another source but preserves the needed role and timbre, it may still satisfy the song. If source identity is the point, say so in the next prompt. The response should separate “did not generate the requested instrument” from “did not generate the requested effect.”

## Failure diagnosis and smallest revision

If the result is **muddy**, identify whether overlapping tails, crowded midrange, or excessive low sustain is responsible. Revise the relevant part: “shorter chord decay under the lead” is a clearer next move than “better mix.” If it is **thin**, add body to one core source or let a chord sustain longer before adding several new layers. If the **hook is buried**, move its carrier to a separate register or remove a simultaneous competing line. If the **texture never develops**, change one existing source’s envelope or register at a section boundary. If the **generated source is wrong**, specify an audible source family and its role together. If the **sound is too synthetic or too variable**, name the exact feature—repetition, attack variation, noise, sustain movement—that should change.

