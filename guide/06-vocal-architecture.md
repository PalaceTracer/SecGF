---
chapter_id: "06"
retrieval_tags: [voice, lead, vocal_mode, pitched_verse, syllabic_singing, register, resonance, breathiness, articulation, phrasing, vibrato, doubling, harmony, intelligibility]
use_when: "Read when the finished lyric needs a specified vocal performance, vocal layering, or clearer delivery."
output_influence: style
---

# 06 — Vocal architecture

## The vocal result to specify

Design a vocal *scene*: who carries the words, how the lead shapes a phrase, what other voices add, and where those relationships change. The Style field should contain only the decisive audible choices; the finished words stay in Lyrics. [Suno Custom Mode](https://help.suno.com/en/articles/2415873/) provides a separate lyric input. Every sample Style phrase below is a **design hypothesis**. The songwriter designs from written lyrics and preferences only; it never receives, hears, measures, or evaluates any audio.

A voice descriptor is not an identity claim. “One close low-mid lead with crisp consonants” specifies a proposed register, position, and diction. Biographical identity guesses or a named performer cannot replace range, timbre, diction, and arrangement role. If a user has a written voice preference, extract its intended audible qualities. A named persona or demographic label does not establish vowel shape, consonant attack, register, ornament, or melodic behavior. Describe those properties only when the current brief wants them; do not infer an accent. Similarly, “powerful vocals” is incomplete until it says whether force comes from note length, firm onset, vocal weight, a harmony stack, or a mix position.

This workflow has no recorded-voice input. A reference asking for the user's own recording cannot become a prerequisite, an imitation claim, or a voice-cloning instruction. Work from written vocal attributes. The songwriter never receives, hears, or evaluates any audio; a reference's displayed Style or Lyrics tag is text evidence, not a heard performance.

Technical research distinguishes pitch, vocal-fold behavior, and vocal-tract resonance; register can change harmonic balance while resonances shape timbre and vowel information. Use that distinction for analysis, then write in perceptible musical attributes. See [vocal-tract acoustics](https://pubmed.ncbi.nlm.nih.gov/19649157/) and [register-shift research](https://pmc.ncbi.nlm.nih.gov/articles/PMC4167751/). A prompt must not pretend to direct the unseen physiology of a generated singer.

## Map the vocal scene

| Role | Audible decision | Section question |
| --- | --- | --- |
| Lead | One centered voice, alternating leads, or a collective line. | Who must be understood here? |
| Double | A quieter unison shadow of the lead. | Where should a line gain weight without new words? |
| Harmony | Another pitch under or above the lead. | Which sustained word can carry extra color? |
| Answer | A phrase or wordless sound in a gap. | What can respond without covering the story? |
| Space | Near/dry foreground versus distant/wide support. | Does distance change at the lyric turn? |

Write the full map privately, then compile only the important relation: “Single close lead sings a recurring verse contour; a narrow unison double widens the repeated refrain.” The written map should leave the verse exposed and assign the double an explicit refrain entrance. If the map puts support voices on every line, restrict their location or remove them. “Intimate solo” and “continuous equal-level group” conflict unless the prompt assigns them to different moments.

## Choose vocal mode by section

Before color or diction, decide whether each section is **pitched singing**, rhythmic singing, intentional chant, speech, or wordless vocal texture. **No rap** as genre, subgenre, Style tag, neighboring tag, or vocal direction in this project. Use the current user's request and intentional performance tags in the finished lyric; a tag in a liked reference does not choose the new song's mode. Narrative detail, dense syllables, a close microphone, and clear consonants do not by themselves call for speech. For a song intended to be sung, give the verse an audible melody as well as the refrain: a short recurring contour, a few definite pitch steps, or sung notes that lead to a held word. Place speech, whisper, and shouts only in named sections where the current brief asks for them. A breathy sung tone retains pitch; an actual whisper is a distinct requested mode.

State mode positively in Style when it matters: “The lead sings the verses on a compact recurring three-note motif; the refrain climbs to a longer held note.” “Intimate,” “restrained,” “precise,” and “conversational” describe manner but leave melodic mode ambiguous. In a sung brief, do not let those adjectives be the only verse direction. Keep the verse melody cue when shortening the prompt.

## Restrained and rhythmic singing remain melodic

A syllabic verse gives most syllables one note; its tune can be narrow, quick, and plainly articulated. Rhythmic singing can place short pitched notes against syncopation without turning the line into speech. Establish the recurring pitch movement first, then specify soft dynamics, clipped releases, dryness, or consonant detail. A full accompaniment withdrawal must preserve that melodic behavior if the verse is meant to remain sung.

| Current sung brief | Positive verse behavior | Separate delivery choice |
| --- | --- | --- |
| Quiet narrative | “Verses repeat a low stepwise melody, settling on a held vowel at each complete thought.” | Soft onset and a close dry position. |
| Dense urgent text | “Short pitched verse notes recur in a rising-and-falling cell around the steady beat.” | Crisp consonants, clipped releases, replies after lines. |
| Restrained chamber texture | “An exposed lead sings a compact recurring contour over widely spaced notes.” | Light clear core; breath appears only at releases. |
| Driving band arrangement | “Syncopated verse melody stays in a narrow register; the refrain leaps to longer notes.” | Firm attacks in verses, fuller projection at the return. |
| Broad low pulse | “A low sung motif moves by small steps while stressed vowels cross the bass holds.” | Centered tone with a little timing give. |

These are original design moves, not a required three-note formula. Select the contour, phrase span, or sustained destination that fits the actual text. The user's reported unwanted spoken result followed a prompt that explicitly selected an almost-spoken line. That report supports removing the speech cue; it does not prove that one replacement phrase will always produce singing.

## Force, register and melodic duration are independent

A softer verse can retain a full clear pitched core. A more emotional refrain need not be maximal belting: it may change duration, interval span, onset or phrasing instead. A thin/light tone and an active backing can coexist if the foreground is protected. Treat “brighter,” “stronger,” “higher” and “longer” as separate decisions rather than one default escalation.

| Selected goal | Positive melodic behavior | Independently scoped delivery |
| --- | --- | --- |
| Contained intensity | Sung phrases stay rhythmically precise and keep definite pitch destinations | Moderate projection and firmer consonants, not an automatic belt. |
| Larger refrain | The tune opens one interval or holds its stressed vowel longer | Fuller onset only at the return; the clear core persists. |
| Reserved final peak | An upper sustained note appears at the final actual repeated thought | Earlier passages remain controlled; a brief arrangement breath can expose the entry. |
| Rough expressive edge | The recurring verse contour stays sung | Grain appears at selected attacks or peaks, with clear vowel pitch. |
| Continuous urgent bridge | Melody remains active through the existing turn | Preserve force while changing backing focus instead of automatically becoming quiet. |

These original hypotheses extend the documented distinctions in the anonymous production audit; they are not universal preferences or successful-generation claims. A reported wait before a peak does not establish a full all-sound cut. Describe whether the voice, accompaniment and tails stop when that difference matters.

## Independent support voices need independent jobs

If the current brief asks for several vocal lines, decide which one carries words, which one supplies lower sustained support, and which one floats above or answers afterward. Two voices can be a unison reinforcement, a harmony, an exchange or independent counterlines; count alone does not determine the arrangement. Original proposal: “One clear lead sings the verse; a low held harmony supports the refrain while a quieter upper line answers its released vowels.” Give fuller two- or three-line combinations specific entrances and exits. Do not invent a choir, a duet perspective, demographic identity or an accent from the reference's contributors.

## Local exceptions require a named location

The written references contain speech, group responses, processed voices, and duets. Their variety does not establish a default for this project. When the current brief explicitly requests one of these features, decide its mode, entrance, and exit while preserving the intended mode of other sections.

| Optional feature | Necessary section decision |
| --- | --- |
| Spoken aside or whisper | Which existing intro, bridge, or final line carries it, and where pitched singing resumes? |
| Chant or shout | Is the named response pitched or unpitched, and does it answer after the sung lead? |
| Duet | Which actual sections alternate leads, and which repeated line joins them? |
| Harmony or unison double | Which held refrain words gain support, and which narrative lines remain single? |
| Vocal chop | Does a wordless hook answer a named refrain or transition while the verse lead stays intact? |

Do not add a spoken verse to achieve intimacy, a shout to achieve energy, or a duet to imitate a liked song. Read any reference's Style and Lyrics performance tags as separate evidence. If the current brief requires a special section, state the boundary explicitly; avoid global wording that spreads its treatment across the whole song.

## Range, register, and contour

**Pitch height** is where the notes lie; **tessitura** is the region holding most phrases; **register impression** is perceived weight and manner of phonation. A high note need not sound thin, and a low note need not sound forceful. Do not make “deep” carry pitch, darkness, mood, and identity at once. Choose a relative design: a low-mid sung verse motif, a refrain rising above it, and one long destination note at the end. Relative directions are useful when the actual melody and comfortable range are unknown.

A continuous climb, an audible register break, a narrow sung contour, and a wide leap are different events. Put the change where the lyric needs it. “The verse repeats a low three-note sung motif; the final repeated line rises to a light held upper note” is more specific than “soaring voice.” Technical register terms can help private text analysis; the prompt must state the intended contour and color without claiming a heard result. [Register-shift research](https://pmc.ncbi.nlm.nih.gov/articles/PMC4167751/) shows why pitch and phonatory state should not be collapsed into one adjective.

**Ask:** Which line gets the first high note? Is the rise a one-time turn or the default? Must a name or plot-bearing phrase stay in a clear middle range? If the written design raises every line, preserve contrast by keeping information sections low and reserving the lift for one named return.

## Tone color and phonation

Separate **core tone** (clear, round, thin, ringing, grainy), **air or edge** around it, and **onset** (soft, immediate, or firm). A voice can begin gently and then sustain a clear tone; a quiet line can have a firm consonant; a loud line can have a soft attack. Studies of phonation onset and vocal-fold motion support treating breathy and pressed production as different behaviors, but the Style field should specify the audible effect rather than a physiological maneuver. See [phonation onset](https://pubmed.ncbi.nlm.nih.gov/26690882/) and [vocal-fold kinematics](https://pubmed.ncbi.nlm.nih.gov/42059716/).

Bind a texture to a layer and time. “A clear lead gains faint grain on the final held word” gives an arc. “Dry grain-edged lead in front of smooth, distant vowel harmonies” gives a foreground/background relation. Stacking “breathy, gritty, silky, husky, pristine” does not. Avoid global grain or breath instructions when the goal is a local vocal texture. Bind grain to selected lead peaks and breath to phrase endings or a wordless layer. These are written design hypotheses, not assessments of a recording.

Useful paired cues:

- “Soft onset, clear core” asks for gentleness without continuous whisper.
- “Air on line endings” makes breath a release rather than an obstacle to every consonant.
- “Firm attack on the repeated phrase” localizes decisiveness.
- “Clean verse tone, brief edge at the climax” creates development without constant abrasion.

Do not request apparent strain as a persistent vocal trait when the intended sound is momentary effort. Say where a roughened peak occurs and where the clear tone returns.

## Diction and word priority

Mark words that a first-time listener must catch: a name, number, crucial negation, reversal, location, or title phrase. Give them a foreground lead, short melodic treatment, clear consonant beginnings and releases, and space in the accompaniment. Other repeated words can support longer vowels or later ornament. An anonymous wordless layer can become texture without asking the listener to parse competing text.

Sung-word clarity depends on performer, arrangement, and acoustic environment. A survey found musicians often cite diction and acoustics, but it reports beliefs rather than causal effect sizes. An English-word recognition experiment found a modest decline with multiple simultaneous singers compared with one and particular confusion at some final consonants. See [intelligibility survey](https://pubmed.ncbi.nlm.nih.gov/25249987/) and [multi-voice experiment](https://pubmed.ncbi.nlm.nih.gov/27068550/). The practical inference is to expose a key word on its first statement before surrounding later returns with extra voices.

**Prompt hypothesis:** “A precise single lead sings rapid narrative lines on short recurring notes; sustained vowels and harmonies arrive only on the repeated refrain.” **Written audit:** Specify the verse contour, reserve longer notes for the repeated refrain, and place instrumental replies after complete phrases. Keep important words exposed and allow timing give only where it does not compete with their emphasis.

## Phrasing and rhythmic placement

A sung line has a start, a path, a pause, and an ending. Specify the element that shapes this lyric:

- **Pickup and pocket:** entry before, on, or just after the beat. “Slightly ahead” can create urgency while a steady drum remains the anchor.
- **Line length:** clipped cells for dense information; longer arcs when a thought needs to unfold.
- **Breath gap:** a pause that separates complete thoughts or leaves room for an answer.
- **Stress:** weight on a word through duration, beat placement, pitch, or a brief instrumental clearing.
- **Release:** a dry cut, taper, trailing breath, or held vowel, each with a different effect on the following event.

Small timing and pitch differences can be expressive without destroying the perceived note category; see [perceptual singing research](https://pubmed.ncbi.nlm.nih.gov/8061767/). For sung prompts, prefer a relational sentence: “Short sung verse cells lean slightly forward; the refrain settles into longer centered notes.” The text audit should identify verse phrase gaps and the distinct refrain duration. For dense words, pair clipped releases with centered timing rather than adding contradictory urgency to every dimension. “Loose” alone gives no anchor; name what stays steady.

## Ornament and vibrato

A straight tone holds relatively steady pitch; vibrato varies around a center; a slide approaches or leaves a note; a run gives several pitches to a syllable. Use ornaments to emphasize a chosen word or later repetition, not automatically every line. Perceptual work treats vibrato as pitch modulation around a mean and shows that reactions depend on interacting rate, depth, and pitch; “more vibrato” is not a complete musical direction. See [perceptual singing](https://pubmed.ncbi.nlm.nih.gov/8061767/) and [vibrato experiment](https://pubmed.ncbi.nlm.nih.gov/23177756/).

Let the first statement of a crucial hook stay simple; vary the final return. A late-onset vibrato can preserve a stable entrance to a long note. A run can follow a word after its meaning is established. “Mostly straight, syllabic lead; one brief rise on the last refrain word” localizes the intended ornament. If the written design assigns decoration to every syllable, reserve fewer locations. Identify the exact ending that should bloom rather than asking for general emotion.

## Doubles, harmonies, and responses

A double thickens a melody. A harmony introduces another pitch. An answer takes a gap. A group response can turn a private line into a shared one. A wordless pad supplies harmony without new text. These roles are not interchangeable, and none is mandatory. Give each a *time and location*: “quiet low harmony under held refrain endings” or “short high answers between the lead lines.” Avoid full-text support voices covering crucial first statements. The [multi-voice experiment](https://pubmed.ncbi.nlm.nih.gov/27068550/) supports a design precaution when voices overlap.

A useful arc is one exposed lead at the opening, a restrained double on the first return, then an upper harmony or response on the final return. If the lyric demands isolation, the strongest arc may keep one voice and instead change its distance or phrasing. Avoid broad “huge vocals” language when the intended support is selective; bind each support voice to exact sections. Keep the lead centered when the support widens so its words remain focal.

**Prompt hypothesis:** “One lead until the refrain; quiet unison doubles thicken the repeated words, and a wordless high answer appears only on the final return.” **Written audit:** Name each support entrance and its exit; reserve the answer for a gap and expose the first presentation of important words.

## Vocal intensity as a change, not an adjective

Intensity may grow through a higher destination, firmer onset, longer vowels, shorter gaps, added doubles, or a more forward mix. The waveform need not simply get louder. A quiet close line can feel urgent if its consonants meet a sparse pulse; a long loud line can feel gentle with a soft attack. “The final refrain keeps the melody but adds a narrow upper harmony” or “the last word loses every backing voice” specifies an observable change. Choose the cause that serves the lyric; do not demand maximum level, grit, width, and ornament together.

## Compatibility and prompt budget

| Combination | Necessary relation | Design conflict to avoid |
| --- | --- | --- |
| Near lead + wide backing | Lead stays foreground; support expands behind it. | Competing foreground instructions. |
| Breathy color + dense words | Air is limited to tails; core syllables stay clear. | Continuous breath requested across crucial words. |
| Grain + clear diction | Edge colors held vowels, not every consonant. | Global roughness conflicting with clear syllables. |
| Fast verse + group answer | Response enters after the line. | Response assigned before the lead finishes. |
| Higher final refrain + hook clarity | The first hook is plain; later return grows. | First hook and return assigned unrelated contours. |
| Flexible lead + tight pulse | Rhythm section provides a fixed reference. | Flexible timing requested for every source. |

Draft a full working vocal profile, then rank candidates by meaning, audibility, compatibility, and character cost. For an intended sung song, preserve the pitched verse behavior before optional texture or support. A compact Style field may then need only foreground configuration, one delivery trait, one section change, and one support role. Avoid reciting all technical dimensions. Exact lyrics stay unchanged in Lyrics. Necessary unwanted vocal elements belong separately in [Suno Exclude](https://help.suno.com/en/articles/3161921/) when available; an exclusion cannot replace the positive melody design.

## Written vocal audit

Audit the finished prompt against the lyrics and written brief. Every sung verse needs a definite pitch contour before intimacy, diction, texture, or force. Dense information needs an intended note-duration and accompaniment relationship. Each double, harmony, answer, ornament, or requested special mode needs a named section and a clear return to the main mode. Check that register, projection, and note length are independent decisions, with a meaningful contrast where the lyric warrants one.

Remove incompatible global adjectives and unrequested persona or accent assumptions. Preserve key words and finished lyrics. Keep necessary avoidances in EXCLUDE, and retain positive sung behavior in STYLE OF MUSIC. This is a text-only design audit: no generation comparison, playback, signal measurement, transcription of rendered lyrics, or success rating is required or possible in the songwriter workflow.
