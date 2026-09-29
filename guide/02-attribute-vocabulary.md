---
chapter_id: "02"
retrieval_tags: [attribute-map, audible-definition, compatibility, priority, contradiction, uncertainty]
use_when: "Read before choosing attributes or resolving a brief with conflicting musical wishes."
output_influence: style
---

# 02. Attribute vocabulary, relationships, and decisions

## Role of this chapter

This chapter is the navigation system for a finished song brief. It converts wishes into things a listener could identify in a recording. The lyric text comes from the existing lyric workflow; the task here is to design the sounding performance and arrangement. A word such as *warm*, *driving*, *intimate*, or *large* is useful only after it is translated into a cause: note length, rhythmic placement, source tone, vocal distance, density, or a change between sections. No single mood word describes all those causes.

An **attribute** is a variable with at least two audible values. A **role** states what a sound does in the arrangement. A **relationship** states how two roles interact. A **section instruction** states when an attribute changes. A **test** names what to listen for afterward. This distinction prevents a Style field from becoming an inventory of attractive adjectives.

The core map has nine axes: pulse; percussion and low end; harmonic motion; melody and hook; sound-source roles and timbre; vocal architecture; form and dynamics; recording image; and lyric–music fit. The axes are independent enough to diagnose separately, but the recording is a set of interactions. A bright sustained chord bed and a bright short percussion tick can coexist; “bright” alone cannot tell Grok which one the user means. A forceful pulse can sit under a quiet voice. A positive lyrical reading can be carried by minor-colored or unresolved harmony when the contrast is intentional. Choose causes before mood labels.

The following definitions are **musical design vocabulary**, not claims that Suno will reproduce an instruction exactly. Any example of prompt wording is a **testable prompt hypothesis** until an actual generated take is heard. Interface facts and controlled listening are handled in Chapters 01 and 11.

## How to read an attribute

For any candidate phrase, ask five questions.

1. **Object:** Which part of the record does it modify: drums, bass, chord layer, hook, lead voice, backing voices, or the whole mix?
2. **Dimension:** What can change: timing, attack, duration, pitch, register, spectral balance, space, level, or density?
3. **Reference:** Relative to what: a beat, a lyric stress, another sound, or an earlier section?
4. **Test:** What would be audible if the direction succeeded?
5. **Cost:** Does naming this detail justify its characters in the short Style field?

For example, “lively” has no object and a weak test. “Short bass notes answer the kick between beats” identifies object, timing, relationship, and a test. “Lead voice stays close and dry while the refrain chords spread wide” distinguishes foreground from background. It also resolves an apparent conflict between intimacy and scale.

Do not force a numerical answer when the user has given a perceptual one. “Brisk but spacious” can be rendered as a quick subdivision with sparse heavy accents. “Slow and urgent” can mean long bars with active short notes, an insistent repeating hook, or a rising section density. If an exact tempo, key, note range, or recording parameter is unknown, describe relative behavior rather than inventing a measurement.

## Compact attribute dictionary

The contrasts below are not binary categories for classifying songs. They are handles for asking where a sound belongs and whether it changes.

| Axis | Contrast to choose | What a listener could hear |
| --- | --- | --- |
| Pulse | broad versus busy felt motion | How often attention is pulled forward, including half-time or double-time perception. |
| Accents | stable versus displaced | Whether important strikes land on expected beats or between them. |
| Kick–bass relation | lockstep versus conversation | Whether low notes reinforce the kick or answer it in gaps. |
| Harmony | repeating versus traveling | Whether a small chord set cycles or noticeably moves to new ground. |
| Harmonic rhythm | slow versus rapid change | How often chords change, independent of note activity inside each chord. |
| Hook | stated versus answered | Whether the memorable figure belongs to voice, instrument, or their exchange. |
| Source attack | soft versus sharp | How quickly a note rises after onset. |
| Vocal delivery | conversational versus projected | Degree of intensity and outwardness, independent of register. |
| Vocal layers | solo versus doubled or harmonized | Whether added voices reinforce timbre, create chords, or answer the lead. |
| Space | dry/near versus reverberant/far | Whether direct sound or audible ambience dominates a source. |
| Texture | clean versus audibly saturated | Whether nonlinear edge, noise, or roughness colors a sound. |
| Dynamics | level-stable versus strongly changing | Whether intensity and loudness move within phrases and across sections. |

These terms are often useful in pairs. “Sharp attacks, long tails” is a recognizable configuration: the notes declare their entrances yet overlap. “Low-density verse, dense refrain” identifies a change rather than a constant state. “Centered lead, wide chord bed” allocates space by role. In contrast, a chain such as “massive, huge, epic, wide, full” spends characters on nearly the same impression while leaving its cause unspecified.

## Interactions that create a coherent record

**Pulse × attack density.** Tempo alone does not specify urgency. Broad accents with long rests can feel spacious at a brisk speed; a slower beat with repeated small subdivisions can feel insistent. Name both felt motion and event pattern. Tap the large pulse and listen for activity between taps.

**Kick × bass.** The two can start together or answer each other. A held bass can bridge short kicks; clipped offbeat notes can move between them. “Heavy bass and hard kick” leaves the relation vague. State onset and duration: “short bass notes mirror the opening kick, then move between kicks in the refrain.” Listen for both patterns.

**Harmony × lyric density.** Frequent chord changes, moving inner parts, and long tails occupy attention. Dense text may need a smaller repeated chord set or quieter sustained voicings; sparse text can allow more motion. If words should be submerged, state that deliberately.

**Melody × hook ownership.** An instrumental figure can prepare, answer, or compete with a vocal phrase. Place it in gaps after a fast sung hook; a sustained vocal may leave room for a moving countermelody. State who carries the motif and when the other part yields.

**Voice × arrangement.** A near, breathy lead may need a lean bed; a projected refrain can take wider layers and accents. Backing voices can enlarge a refrain but mask dense words. Specify where they enter and whether they double, harmonize, or answer the lead.

**Section arc × invariants.** Keep a bass pattern, motif, or lead timbre recognizable across contrasting sections. Choose one identity cue to persist and one major dimension to change. A refrain can lift through register, density, rhythm, harmony, or voices without increasing all five.

**Recording space × role.** A close dry lead can stand before a wide reverberant bed. “Dry and reverberant” conflicts only when both modify the same source at the same time. Assign each quality to a source or section.

**Brightness × emotion.** High-frequency energy, upper register, forceful attacks, lyrical hope, and cheerful delivery are different variables. Translate the desired feeling into movement, voice, harmony, and texture; judge the full combination after listening.

## Compatibility map

The table is a reasoning aid, not a ban on unusual combinations. Its third column suggests the minimum wording required when a combination is intentional.

| Requested pair | Typical interaction | How to make it coherent |
| --- | --- | --- |
| Brisk movement + spacious weight | Compatible when subdivision and accents differ | “Quick small-note pulse beneath broad half-time accents.” |
| Repeating small chord set + evolving song | Compatible when other dimensions develop | Name a changing bass role, voicing, hook, or section density. |
| Intimate lead + expansive refrain | Compatible by source and section | Keep lead close; widen chord and backing-vocal layers at the refrain. |
| Raw edge + clear lyric | Compatible by source allocation | Put saturation on instruments; keep the lead's consonants forward. |
| Heavy low end + light rhythmic feel | Compatible if sustain is controlled | Specify low weight with clipped notes or selective kick placement. |
| Dense verse + many melodic hooks | Potential masking | Put the instrumental hook between lines or defer it to a gap. |
| Long reverb + rapid consonants | Potential masking | Keep lead dry or duck ambience while words are dense. |
| Quiet opening + immediate hook | Compatible | State a small, exposed motif early, then expand its arrangement. |
| Fixed pulse + free vocal timing | Compatible | Let the vocal phrase behind or across the beat while the rhythm bed stays stable. |
| Simultaneously sparse and full | Incomplete scope | Assign sparse/full to different sections, registers, or sources. |

Some directions are truly incompatible at one object, time, and dimension: “no percussion” and “continuous snare backbeat” for the same section; “one unaccompanied voice” and “stacked harmony throughout”; “no chord motion” and “new chord every beat.” Do not average them into a vague middle. The user's most explicit instruction wins, or ask one focused question if both are equally central. Many apparent conflicts dissolve when scoped by source or section.
