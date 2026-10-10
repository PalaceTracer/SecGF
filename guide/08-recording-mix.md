---
chapter_id: "08"
retrieval_tags: [recording image, mix, depth, width, reverb, clarity, density, saturation, dynamics, transients, low end]
use_when: "Use when the desired recording should feel close, spacious, forceful, delicate, raw, polished, or clearly layered."
output_influence: style
---

# 08. Recording and mix image

## Specify the intended recording image

The songwriter uses written lyrics, preferences, and reference descriptions only; it never receives, hears, measures, or evaluates any audio. The Style paragraph can request a recording image, but it is not a mixer project. A number for compressor ratio, reverberation time, or equalizer cutoff would imply a directness of control that a text generation workflow has not established. Describe the *audible result* and the relationship between sound sources. “Close, dry lead; wide chord reflections behind it; short, punchy drums and warm sustained bass” gives the model a scene with hierarchy. “Professional, clean, huge, warm, polished, raw, vintage, pristine” gives incompatible or redundant impressions with no clear roles.

An audio engineer can build these effects using level, equalization, panning, dynamic control, reverberation, delays, saturation, source selection, and performance. The [Ableton Live audio-effect reference](https://www.ableton.com/en/manual/live-audio-effect-reference/) documents how filters affect frequency content, reverberation parameters affect reflections and tails, compression responds to level, and its Utility effect changes stereo width or sums to mono. Those mechanics support the vocabulary below. They do not establish that a particular Suno prompt will map to a particular internal signal path.

## Foreground, depth, and air

**Foreground** means the listener's attention lands on a source. It is influenced by relative level, transient definition, intelligibility, spectral space, and dryness. The loudest element is not always the clearest: a lead can feel close at moderate level if consonants stay legible and a busy chord bed avoids its active range. In Style language, name the source and its relation: “one close lead above restrained low-register chords.” The written design should protect the lead's phrase space, especially when the full arrangement is proposed to enter.

**Depth** is not a single wet/dry switch. Direct sound, early reflections, delayed repeats, and a diffuse tail can imply different spaces. Ableton's reference explains early reflections as the first room echoes and pre-delay as the interval before reflections; decay describes how long the tail falls away. For this guide, these are explanatory mechanisms. A Style prompt should usually specify perception: “small, short room around the drums” or “long diffuse reflections behind the upper notes.” Avoid giving the entire mix the same long tail when intelligibility and attack are the song's main needs. If the vocal is meant to feel remote, say whether it remains intelligible: “distant lead with clear consonants” is a deliberate intended balance that needs source hierarchy.

**Air** can mean spectral openness, sparse arrangement, low noise, or a spacious tail. It is ambiguous until paired with a cause. “Airy” might produce hiss, wide pads, or a breathy vocal, any of which may be wrong. Choose “space between short chord stabs,” “soft upper harmonics around the lead,” or “a long, quiet tail after the final phrase.” Conversely, “intimate” might mean dry proximity, low arrangement density, quiet vocal delivery, or small-room reflections. Identify the intended cue.

## Width, center, and translation

Stereo width is the perceived left-to-right spread. A single central lead, central kick, and focused bass can anchor an otherwise wide frame. Wider chord layers, answering motifs, and reflections can create contrast around that anchor. “Wide” should identify *which* layer expands, and ideally when: “narrow verse chords open into wide sustained refrain harmonies.” Applying width to every element throughout may reduce contrast, and the result may change on a small speaker or in mono. Ableton documents both stereo-width adjustment and mono summing in its Utility effect, including why low-frequency mono compatibility may matter for playback. That is a production principle for expressing intended width; it does not establish any technique in a generated file.

## Frequency balance and separation

“Bright” and “dark” are not complete mix briefs. Brightness could come from crisp percussion, sharp consonants, upper-note motifs, or a broad treble lift; the emotional effect of each differs. “Warm” could mean strong low mids, rounded attacks, restrained upper harmonics, gentle saturation, or sustained lower-register tones. State which source supplies it. In the Ableton reference, low-pass and high-pass filters respectively attenuate content above or below a cutoff. That documents one engineering route to timbral difference, not a reason to put filter settings in the Style field.

Arrange spectral roles before asking for more equalization. A sustained bass note occupies low space longer than a short bass pluck. A dense chord bed may obscure the vocal even when each layer sounds good in isolation. A high, thin answer figure can coexist with the lead if it appears between phrases. Useful Style language captures the relationship: “rounded bass sustains beneath short kick strikes; chord attacks leave the lead's midrange exposed.” This is a proposed separation of roles, not a claim about generated audio.

Low-end descriptions should distinguish **weight** from **note definition**. A long sub tone can provide physical weight but may obscure bass pitch on small speakers; a shorter bass note with audible harmonics can make the line easier to follow. “Heavy bass” says little about the rhythmic role. “Short, tuneful bass notes lock to the kick on downbeats, then answer the gaps” states both weight and motion. If bass and kick strike together, one can provide a sharp start and the other a sustaining body. If they alternate, the groove can feel active without extra percussion. These are arrangement relations that affect the recording image.

## Density is a time pattern

Layer count alone does not determine perceived density. Consider how long sounds should persist and how their attacks should overlap. Four short elements that take turns may feel clear; two sustained sources in the same register may feel opaque. Ask whether a layer should be present continuously, only on selected beats, between vocal lines, at transitions, or solely at the refrain. “Lean verses” has more meaning when followed by what remains: “voice, bass, and a clipped two-note chord pulse in verses; wider sustained chords enter at the refrain.”

## Saturation, distortion, and surface texture

Saturation can add harmonics, thickness, and edge; obvious distortion can change the apparent source identity and reduce note clarity. The Ableton effect reference documents increasing drive as increasing distortion or saturation in several devices. A text prompt should identify where roughness belongs: “slight grain on the lead at peaks,” “mild harmonic edge on the bass,” or “fuzzy chord layer behind a clean vocal.” Asking for the entire mix to be both pristine and heavily distorted makes its hierarchy unclear. A clean foreground with textured backing can be coherent; a raw performance in a carefully separated mix can also be coherent if the axes are named separately.

## Dynamics without a hardware fantasy

Dynamic range is the contrast between quieter and louder moments, at the scale of an attack, phrase, section, or whole song. Compression can reduce peaks and alter apparent loudness; attack and release determine how it reacts over time. Ableton's compressor documentation explains these controls and the way fast settings can change transient character. For a Style prompt, translate the desired experience: “firm attacks with breathing room between hits,” “restrained verse, broad refrain without flattening the lead,” or “tight, even percussion under a more variable vocal.”

## Compile a coherent image

Select one dominant production image and up to two purposeful contrasts. A useful sequence for drafting is **foreground → supporting depth → rhythmic texture → sectional change**. The order need not appear literally in the final Style field, but it prevents a collection of unrelated adjectives.

Before compiling, ask: Which source is in front? Which layer supplies width or distance? Which attacks need to stay distinct? What sonic change marks the refrain? Which crucial lyric line is most at risk of masking? Answer with source and section names. “Close lead” is incomplete if every competing layer is also pushed forward.

| Weak request | Compact design candidate |
| --- | --- |
| “Huge and clear” | “Close lead over wide sustained refrain chords; short drum tails leave words exposed.” |
| “Warm but punchy” | “Rounded bass body beneath distinct kick attacks; bright short accents stay behind the lead.” |
| “Spacious verse” | “Sparse chord attacks with a short quiet room around the lead and audible gaps after lines.” |

## Written recording-image audit

Check the proposed image against the intended source roles and lyric demands. Which layer owns the foreground? Which backing layer carries width or distance? Are kick attack and bass sustain distinct in the description? Do long tails overlap dense words? Does the actual refrain have a stated spatial contrast? Does roughness belong to a selected source rather than contradicting a clean lead?

If the written design crowds the lead, thin a simultaneous role, shorten its intended tail, or move it into phrase gaps. Bind width to a source and section instead of using a global adjective. Preserve a coherent core image with only the contrasts that serve this song. These are design edits made before generation; do not request matched-level playback, mono checks, timestamps, measurements, rendered-result ratings, or audio files.
