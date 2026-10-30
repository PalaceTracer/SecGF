# 06 — Vocal architecture

## The vocal result to specify

Design a vocal *scene*: who carries the words, how the lead shapes a phrase, what other voices add, and where those relationships change. The Style field should contain only the decisive audible choices; the finished words stay in Lyrics. [Suno Custom Mode](https://help.suno.com/en/articles/2415873/) provides a separate lyric input. Every sample Style phrase below is a **design hypothesis**. The writer works from finished lyrics and written information only; no audio input or result evaluation is available.

A voice descriptor is not an identity claim. “One close low-mid lead with crisp consonants” describes register, position and articulation. Biographical identity guesses or a named performer cannot replace range, timbre, diction, and arrangement role. If a user has a written voice preference, extract its intended audible qualities. A named persona or demographic label does not establish vowel shape, consonant attack, register, ornament, or melodic behavior. Describe those properties only when the current brief wants them; do not infer an accent. Similarly, “powerful vocals” is incomplete until it says whether force comes from note length, firm onset, vocal weight, a harmony stack, or a mix position.

This workflow has no recorded-voice input. A reference asking for the user's own recording cannot become a prerequisite, an imitation claim, or a voice-cloning instruction. Work from written vocal attributes. The songwriter never receives, hears, or evaluates generated song files; a reference's displayed Style or Lyrics tag is text evidence, not a heard performance.

Technical research distinguishes pitch, vocal-fold behavior, and vocal-tract resonance; register can change harmonic balance while resonances shape timbre and vowel information. Use that distinction for analysis, then write intended audible relationships. See [vocal-tract acoustics](https://pubmed.ncbi.nlm.nih.gov/19649157/) and [register-shift research](https://pmc.ncbi.nlm.nih.gov/articles/PMC4167751/). A prompt must not pretend to direct the unseen physiology of a generated singer.

## Map the vocal scene

| Role | Audible decision | Section question |
| --- | --- | --- |
| Lead | One centered voice, alternating leads, or a collective line. | Who must be understood here? |
| Double | A quieter unison shadow of the lead. | Where should a line gain weight without new words? |
| Harmony | Another pitch under or above the lead. | Is support continuous, phrase-local, structural or absent, and which line owns the tune? |
| Answer | A phrase or wordless sound in a gap. | What can respond without covering the story? |
| Space | Near/dry foreground versus distant/wide support. | Does distance change at the lyric turn? |

When useful, map vocal roles privately: who owns the recurring pitched tune, how any supporting lines relate to it, and whether their role stays stable or changes. Collective, alternating or solo configurations are available; assign support timing only when it matters. “Intimate solo” and “continuous equal-level group” conflict unless the prompt assigns them to different moments.

## Choose vocal mode by section

Before color or diction, decide whether each section is **pitched singing**, rhythmic singing, intentional chant, speech, or wordless vocal texture. Use the current user's request and intentional performance tags in the finished lyric; a tag in a liked reference does not choose the new song's mode. Narrative detail, dense syllables, a close microphone, and clear consonants do not by themselves call for speech. For intended singing, positively specify pitched verse behavior; avoid “spoken-sung,” “conversational” and similar speech cues unless that delivery is explicitly requested or tagged. For a song intended to be sung, give actual verses or verse-equivalent passages an explicit recurring pitched contour; treat any actual refrain separately. The chosen melody may use a long arch, changing intervals or a compact gesture according to this song, without a fixed note count. Place speech, whisper and shouts only in named sections where the current brief or an intentional lyric section tag requests them. A breathy sung tone retains pitch; an actual whisper is a distinct requested mode.

State mode positively with an actual melodic behavior chosen for the verse: direction, interval motion, phrase span or how sung rhythm relates to accompaniment. An abstract claim of a “pitched identity” alone does not describe the intended melody. “Intimate,” “restrained” and “precise” describe manner but leave melodic mode ambiguous. Speech-adjacent wording is reserved for an explicitly requested or tagged speech mode. In a sung brief, do not let those adjectives be the only verse direction. Keep the verse melody cue when shortening the prompt.

## Restrained and rhythmic singing remain melodic

A syllabic verse gives most syllables one note; its tune may use any suitable pitch span, motion and phrase length; syllabic setting does not require narrow range or simple harmony. Rhythmic singing can place short pitched notes against syncopation without turning the line into speech. Establish definite sung melodic identity, then choose projection, texture, articulation and recording position appropriate to the selected direction. A full accompaniment withdrawal must preserve that melodic behavior if the verse is meant to remain sung.

Pitched singing is compatible with broad arches, angular syncopation, long unfolding phrases, rhythmic motif variation and collective melodic writing. A compact tune remains available, but is not a corrective default for speech. Recurrence can be recognizable at phrase or section scale through rhythmic or directional identity while pitches develop; it need not repeat a tiny cell on every line. Identical notes, a fixed note count, tonic resolution or a higher refrain are not requirements.


These are original design moves, not a required three-note formula. Select the contour, phrase span, or sustained destination that fits the actual text. The user's reported unwanted spoken result followed a prompt that explicitly selected an almost-spoken line. That report supports removing the speech cue; it does not prove that one replacement phrase will always produce singing.

## Give a sung verse a musical behavior

Describe the verse as a definite pitched tune with an audible behavior selected for the song: its directional motion, recurring interval gesture, phrase span or rhythmic placement relative to accompaniment. Its phrases may develop or repeat at the intended scale. A source can accompany, double or move independently against that tune; describing an instrument as a pitch guide is not itself a vocal melody.

Clear diction, proximity, restraint and a regular syllable count can coexist with expressive pitched singing. Select register, force, onset, sustain, texture and any supporting voices independently. Reserve speech, whisper, chant and shouts for an explicitly requested or intentionally tagged section. The Style paragraph should describe the intended singing rather than explain why the words are easy to understand.

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

When several vocal lines fit the current brief or an open musical direction, decide which carries existing words, which supports or moves independently, and how attention is shared. Group singing is a possible arrangement choice; an explicitly requested special speech mode remains section-specific. Two voices can be a unison reinforcement, a harmony, an exchange or independent counterlines; count alone does not determine the arrangement. Choose whether lines sound together, exchange existing phrases or remain independent, and specify entrances or continuity only where decisive. Do not infer a choir, duet narrative, demographic identity or accent from reference contributors. A collective pitched configuration can be an original song-specific choice in an open brief, without inventing new words or characters.

## Local exceptions require a named location

Choose pitched harmonies, group configurations, doubles or processed vocal textures when the brief or an open direction makes them useful, preserving the supplied words. Speech, chant, whisper or shouts require explicit intent or intentional section tags. When such a special mode is requested, locate it and preserve the intended mode of the other sections.

| Optional feature | Necessary section decision |
| --- | --- |
| Spoken aside or whisper | Which existing intro, bridge, or final line carries it, and where pitched singing resumes? |
| Chant or shout | Is the named response pitched or unpitched, and does it answer after the sung lead? |
| Duet | Do voices share existing words, alternate existing phrases or sing together, and is the pattern stable or changing? |
| Harmony or unison double | Does coordinated support carry full existing text, selected phrases or local words, and who owns the tune? |
| Vocal chop | Does a wordless hook answer a named refrain or transition while the verse lead stays intact? |

Do not add a spoken verse to achieve intimacy, a shout to achieve energy, or a duet to imitate a liked song. Read any reference's Style and Lyrics performance tags as separate evidence. If the current brief requires a special section, state the boundary explicitly; avoid global wording that spreads its treatment across the whole song.

## Range, register, and contour

**Pitch height** is where the notes lie; **tessitura** is the region holding most phrases; **register impression** is perceived weight and manner of phonation. A high note need not sound thin, and a low note need not sound forceful. Do not make “deep” carry pitch, darkness, mood, and identity at once. Choose the relative vocal span, phrase organization and register for this song. Low or high placement, broad or compact motion, local leaps or sustained arcs are available; no verse-to-higher-refrain sequence is required. Relative directions are useful when the actual melody and comfortable range are unknown.

A continuous climb, an audible register break, a narrow sung contour, and a wide leap are different events. Put the change where the lyric needs it. Specify the selected verse contour, interval movement, phrase span or rhythmic relation rather than leaving its musical behavior abstract. Technical register terms can help private analysis; the paragraph describes the intended contour and color. [Register-shift research](https://pmc.ncbi.nlm.nih.gov/articles/PMC4167751/) shows why pitch and phonatory state should not be collapsed into one adjective.

**Ask:** What recognizable melodic behavior should the verse have, and how does its contour relate to the accompaniment and text? Decide whether any high point, repeated destination, change of register or stable range is actually needed; each is a choice, not a built-in sequence.

## Tone color and phonation

Separate **core tone** (clear, round, thin, ringing, grainy), **air or edge** around it, and **onset** (soft, immediate, or firm). A voice can begin gently and then sustain a clear tone; a quiet line can have a firm consonant; a loud line can have a soft attack. Studies of phonation onset and vocal-fold motion support treating breathy and pressed production as different behaviors, but the Style field should specify the audible effect rather than a physiological maneuver. See [phonation onset](https://pubmed.ncbi.nlm.nih.gov/26690882/) and [vocal-fold kinematics](https://pubmed.ncbi.nlm.nih.gov/42059716/).

Bind a texture to a layer and time. “A clear lead gains faint grain on the final held word” gives an arc. “Dry grain-edged lead in front of smooth, distant vowel harmonies” gives a foreground/background relation. Stacking “breathy, gritty, silky, husky, pristine” does not. Scope grain and breath to the intended source and moment. Their requested role must coexist with word priority. These are written design hypotheses.

Useful paired cues:

- “Soft onset, clear core” asks for gentleness without continuous whisper.
- “Air on line endings” makes breath a release rather than an obstacle to every consonant.
- “Firm attack on the repeated phrase” localizes decisiveness.
- “Clean verse tone, brief edge at the climax” creates development without constant abrasion.

Do not request apparent strain as a persistent vocal trait when the intended sound is momentary effort. Say where a roughened peak occurs and where the clear tone returns.

## Diction and word priority

Mark words that a first-time listener must catch: a name, number, crucial negation, reversal, location, or title phrase. Choose suitable word timing, definite pitch and clear consonant beginnings/releases, with foreground or collective ownership appropriate to this design; short melodic treatment or accompaniment space may help but is not compulsory. Other repeated words can support longer vowels or later ornament. An anonymous wordless layer can become texture without asking the listener to parse competing text.

Sung-word clarity depends on performer, arrangement, and acoustic environment. A survey found musicians often cite diction and acoustics, but it reports beliefs rather than causal effect sizes. An English-word recognition experiment found a modest decline with multiple simultaneous singers compared with one and particular confusion at some final consonants. See [intelligibility survey](https://pubmed.ncbi.nlm.nih.gov/25249987/) and [multi-voice experiment](https://pubmed.ncbi.nlm.nih.gov/27068550/). One possible precaution is an exposed first statement followed by supported returns. Collective text delivery or an ornamented first statement remains available when the chosen word timing and organization justify it; the study does not impose a universal sequence.

## Phrasing and rhythmic placement

A sung phrase has a start, a path and an ending; it can continue across printed lines or pause where the chosen performance needs it. Specify the element that shapes this lyric:

- **Pickup and pocket:** entry before, on, or just after the beat. “Slightly ahead” can create urgency while a steady drum remains the anchor.
- **Line length:** compact cells, unequal phrases or long arcs containing short syllabic notes; choose from stress, available duration and intended melody rather than information density alone.
- **Breath gap:** a pause that separates complete thoughts or leaves room for an answer.
- **Stress:** weight on a word through duration, beat placement, pitch, or a brief instrumental clearing.
- **Release:** a dry cut, taper, trailing breath, or held vowel, each with a different effect on the following event.

Small timing and pitch differences can be expressive without destroying the perceived note category; see [perceptual singing research](https://pubmed.ncbi.nlm.nih.gov/8061767/). For sung prompts, specify how melodic phrasing relates to the chosen pulse and actual sections. The phrasing may stay continuous, develop, or contrast where useful. Check the written relation among available phrase space, duration and timing; an actual refrain may keep or change that relation. “Loose” alone gives no anchor; name what stays steady.

## Ornament and vibrato

A straight tone holds relatively steady pitch; vibrato varies around a center; a slide approaches or leaves a note; a run gives several pitches to a syllable. Use ornaments to emphasize a chosen word or later repetition, not automatically every line. Perceptual work treats vibrato as pitch modulation around a mean and shows that reactions depend on interacting rate, depth, and pitch; “more vibrato” is not a complete musical direction. See [perceptual singing](https://pubmed.ncbi.nlm.nih.gov/8061767/) and [vibrato experiment](https://pubmed.ncbi.nlm.nih.gov/23177756/).

A crucial hook may begin plainly and gain later ornament, or begin ornamented, remain unchanged or transform another way. Choose its treatment from the text and intended performance. A late-onset vibrato can preserve a stable entrance to a long note. A run can follow a word after its meaning is established. “Mostly straight, syllabic lead; one brief rise on the last existing refrain word” is one proposal. Choose ornament locations from this text; neither plainness nor constant decoration is required.

## Doubles, harmonies, and responses

A double reinforces a melody; a harmony adds another pitch; a response can follow or deliberately overlap existing material. These roles are not interchangeable. When selected, describe their text ownership and whether they continue, alternate or enter at a specific point. For crucial first statements, coordinate text onsets, tune ownership, register and balance. Full-text unison or chordal ensemble can carry the first statement; an exposed lead is another choice. The [multi-voice experiment](https://pubmed.ncbi.nlm.nih.gov/27068550/) supports considering word priority when voices overlap, within the study’s limits.

A lead with local support, continuous collective singing and rotating foreground are available organizations. If the written design intends local support, bind it to those sections; continuous ensemble ownership is a different deliberate choice. Choose a centered lead, spread ensemble, alternating foreground or distributed image according to text ownership; no single spatial hierarchy is compulsory.

## Vocal intensity as a change, not an adjective

Intensity may grow through a higher destination, firmer onset, longer vowels, shorter gaps, added doubles, or a more forward mix. The waveform need not simply get louder. A quiet close line can feel urgent if its consonants meet a sparse pulse; a long loud line can feel gentle with a soft attack. “The final refrain keeps the melody but adds a narrow upper harmony” or “the last word loses every backing voice” specifies an observable change. Choose the cause that serves the lyric; do not demand maximum level, grit, width, and ornament together.

## The ensemble may own the melody

Solo lead plus backing is one configuration, not the foundation of every song. Two coequal sung parts, coordinated chordal ensemble, rotating ownership, an inner-line tune or several independent pitched lines can carry the words. “Four parts” describes musical functions, not proof of exactly four singers. An unaccompanied design can assign bass, inner movement, tune and upper harmony to voices without requiring drums, chord pads or new wordless syllables.

An [arranging organization documented by the Barbershop Harmony Society](https://www.barbershop.org/intro-to-barbershop-what-is-barbershop) places the melody in the second-highest part of a four-part unaccompanied texture. That specific documented example shows why “highest voice equals lead” is not universal. A new inner-tune design here is an original implementation, not a claim that every close-harmony ensemble is that tradition.

Decide existing text ownership: coordinated same words, actual phrases distributed between parts, or permitted overlap. A group response does not authorize inventing a response line; imitation does not authorize duplicating words that the supplied lyric has only once. With no permission to repeat text, a second part may sustain an existing assigned vowel, take another existing phrase where structurally available, or the design can omit imitation. Wordless material, character exchanges and special modes require the current brief's permission rather than historical genre convention.

## Recurring pitch without a compulsory rise

A restrained sung verse can have a definite compact contour; a continuously developing sung passage can transform its recurring cell instead of repeating a whole tune. Keep that positive pitch cue during compression. If harmony changes, the phrase can retain stress rhythm, directional shape or a clear destination while adapting pitches to the new support. It need not preserve every absolute pitch.

Register, force, grain, ornament, duration and number of parts are independent. An actual refrain can remain level, narrow, more intricate, quieter, reharmonized or extended in duration. A song without one needs no substitute refrain. An unaccompanied or thinning texture stays pitched; a large ensemble remains sung unless an explicit brief or intentional tag calls for speech, chant, whisper or shout at a named section.

## Compatibility and prompt budget

| Combination | Possible coordinated relation | Potential conflict when unintended |
| --- | --- | --- |
| Near lead + wide backing | Lead stays foreground; support expands behind it. | The lead recedes. |
| Breathy color + dense words | Air is limited to tails; core syllables stay clear. | Names vanish. |
| Grain + clear diction | Edge colors held vowels, not every consonant. | All words distort. |
| Fast verse + group answer | Response follows a line, or overlaps with coordinated text and distinguishable rhythm/register. | Unplanned overlap obscures required words. |
| Refrain variation + recognition | Preserve a recognizable rhythmic or directional identity while changing selected intervals, duration or support, if wanted. | Unexplained replacement of its identity; compulsory growth. |
| Flexible lead + tight pulse | Rhythm section provides a fixed reference. | Whole recording wanders. |

Resolve consequential vocal choices and compare alternatives only where useful, by meaning, intended audibility, compatibility and character cost. For an intended sung song, preserve the pitched verse behavior before optional texture or support. A compact Style field needs the vocal and supporting relationships that matter to this song; a section change or support voice is not a required clause. Avoid reciting all technical dimensions. Exact lyrics stay unchanged in Lyrics. Necessary unwanted vocal elements belong separately in [Suno Exclude](https://help.suno.com/en/articles/3161921/) when available; an exclusion cannot replace the positive melody design.
