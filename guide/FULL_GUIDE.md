# Suno sound-attribute guide

Repository edition generated from the chapter files. The index and all chapters appear below; use `guide/00-index.md` for targeted retrieval from the modular files.


---

<!-- SOURCE: guide/00-index.md -->

# Suno sound-attribute guide: retrieval index

**Status:** researched chapter draft. **Purpose:** turn the user's finished lyrics and desired sound into a concise, testable Suno Style of Music entry. The existing lyric generator remains responsible for the words. The guide is organized by audible decisions.

**Workflow boundary:** Grok writes the Style prompt from finished lyrics, written preferences and documented textual production descriptions. It never receives, hears, plays, measures or evaluates any audio, including reference recordings, existing tracks, voice samples and generated songs. No audio upload, playback or post-generation listening stage is an input or prerequisite. Chapters describe intended musical behavior; checks concern the written plan and output contract only.

## LLM reading route

1. Read this index, Chapter 01 for current interface behavior, Chapter 02 for the attribute map, and Chapter 10 for the output contract.
2. Inspect the finished lyrics and the conversation's musical preferences. Use Chapter 02's reusable influence bank alongside the wider guide as an open palette for optimization. Choose, adapt or develop relationships that make this song more specific; another sound or original combination remains available when it fits the brief. Read Chapter 06 for every vocal song to decide vocal mode by section; read Chapter 09 when text density or narrative affects phrasing. Retrieve the other focused chapters for the axes that determine this song. Use Chapter 11 when the written design needs an additional compatibility or contract check. Do not assume a chapter was read merely because its filename appears here.
3. Keep the user's explicit wishes, documented production accounts and your own proposals separate. All evidence available to the songwriter is written. It cannot report direct audio observations or request recordings.
4. Return the output fields from Chapter 10. Treat the user's observed 1,000-character Style target as binding and verify the exact final count with a counting tool.

The operative influence bank is included in Chapter 02 and therefore in the combined guide. The optional `evaluation/PREFERENCE_ATTRIBUTE_ARCHITECTURE.md` supplies fuller design detail and evidence-audit links when a deep research task calls for them. Ordinary song work can use the compact bank directly. Express fitting influences through actual melodic, rhythmic, source and section behavior in Style. The palette expands the available choices; it introduces no required profile, influence quota or closed style list. A candidate derived from the research is available to use without asserting that its isolated trait is a confirmed preference. Keep source IDs, artist/work names, nationality and regional shortcuts out of Style.

| Chapter | Read when the task involves | File |
| --- | --- | --- |
| 01. Purpose and interfaces | Field separation, current controls, product facts, evidence labels | `01-purpose-interfaces.md` |
| 02. Attribute vocabulary and influence bank | Any new song; open palette, candidate selection, ranking wishes and resolving conflicts | `02-attribute-vocabulary.md` |
| 03. Pulse, percussion, bass | Beat feel, subdivision, drum–bass interaction, low-note length | `03-pulse-percussion-bass.md` |
| 04. Harmony, melody, hooks | Chord economy, harmonic motion, melodic figure, call and response | `04-harmony-melody-hooks.md` |
| 05. Sound sources and timbre | Which source does which job; attack, decay, articulation, layering | `05-sound-sources-timbre.md` |
| 06. Vocal architecture | Lead register and delivery, diction, doubles, harmonies, vocal development | `06-vocal-architecture.md` |
| 07. Section form and dynamics | Opening, verse restraint, refrain lift, contrast, ending | `07-section-form-dynamics.md` |
| 08. Recording and mix | Dry/wet, near/far, width, depth, texture, dynamics | `08-recording-mix.md` |
| 09. Lyric–music fit | Stress, syllable density, breathing, narrative pacing, word clarity | `09-lyric-music-fit.md` |
| 10. Style compiler | Converting the profile into one paste-ready paragraph | `10-style-compiler.md` |
| 11. Written design audit | Text-only lyric fit, role compatibility and final contract checks | `11-written-design-audit.md` |
| 12. Worked cases | Seeing original briefs, selected attributes, and compact Style examples | `12-worked-cases.md` |

## Evidence labels

- **Documented interface fact:** a current first-party Suno page supports the statement. Recheck after a product update.
- **Musical principle:** an account of how audible features relate, with a technical or research source where a nontrivial claim warrants one.
- **Documented production account:** a creator or performer reports a composition, arrangement or delivery decision. This supports the reported choice, not our independent listening, a measured signal property, or the user's reason for liking it. Contributor credits establish participation, not audible role or mix position.
- **Prompt hypothesis:** proposed wording for intended musical behavior; its execution is unverified. Check its written specificity and compatibility without claiming a resulting sound.
- **User-provided written feedback:** an optional report supplied in text. Treat it as the user's report, not your direct observation; no recording is supplied or requested.

These labels distinguish available controls, written accounts and intended designs without claiming guaranteed obedience. They also keep research support tied to the relevant chapter instead of making a source list into a style recipe.

## Scope and defaults

Use finished lyrics; do not silently rewrite them. Do not use named artists or works as shortcuts in output prompts or examples. There is no fixed base-genre catalog in this guide: Chapter 02 maps audible attributes, while user-supplied genres and songs are references for a particular request. If the user supplies a genre or other reference, extract the requested audible traits and give those traits priority over the label. Do not introduce rap as a genre, subgenre, or vocal direction. Specific beat, vocal, source, and mix characteristics make the direction usable.

Exact tempo and key are optional. Do not invent them to look precise. Positive energy, electronic motion, and economical harmony are recurring user interests, not universal requirements for every song. Let the current lyric and explicit brief decide.

The chapter files are the operative guide. The older `RESEARCH_BLUEPRINT.md` documents the plan that led here; `GROK_RUNBLOCK_DRAFT.md` is a prototype. Keep this index and the short project instruction in sync when the chapter guide changes.


---

<!-- SOURCE: guide/01-purpose-interfaces.md -->

# 01. Purpose and current creation interface

## The job that begins after the lyrics

The user's existing lyric generator supplies finished words. This guide designs the *intended audible recording*: pulse, low-end behavior, harmonic motion, sound-source roles, vocal performance, section arc, and production image. The songwriter never receives, hears, plays, measures, or evaluates audio of any kind: reference recordings, preexisting recordings, recorded voices, and generated songs are unavailable. Inputs are finished lyrics, the current written brief, written preferences, and documented production accounts. It does not rewrite lyrics to solve an arrangement problem or evaluate a resulting recording. Dense lines may instead call for leaner accompaniment, clearer phrasing, or a different vocal register.

The deliverable is one self-contained **Style of Music** paragraph. Select what makes this recording different, with no fixed sentence count or concluding category. Keep it within the user's observed 1,000-character target and verify its exact length. That target is a user-reported workflow constraint, not a limit verified in the Suno documentation cited here.

This architecture describes sounds and behaviors. Translate any conversational reference into audible properties, such as “short, hard-edged chord attacks alternating with a sustained upper note.” The cases use no named performer or work as a substitute for those properties.

## What goes in each field

In Suno's [Custom mode instructions](https://help.suno.com/en/articles/2415873), Custom exposes a space for the user's own lyrics. Its [Android Custom mode walkthrough](https://help.suno.com/en/articles/3726721) shows lyrics, Styles, advanced options, and title as separate inputs on that platform. Therefore:

| Destination | Put here | Keep out |
| --- | --- | --- |
| **Lyrics** | Finished words and section labels. | Production prose. |
| **Style of Music** | Desired arrangement, performance, and sound. | Lyrics, title, prohibitions. |
| **Exclude** | Unwanted elements, if any. | The main positive sound design. |
| **Project notes** | Internal attribute rationale, count, written assumptions, and source provenance. | Text requiring deletion before pasting Style. |

The [Exclude help page](https://help.suno.com/en/articles/3161921) places unwanted elements under Advanced Options. Use it for a real prohibition, such as “no backing choir” when one exposed lead is essential. Leave it empty otherwise; its presence does not prove that Suno will obey it.

## Intake: decide before drafting

Read the finished lyric for meaning and vocal demands: repeated phrase, crowded syllables, breaths, and emotional turn. Decide vocal mode by section before vocal color: sung, a deliberate sung/spoken mix, intentional chant, or speech. Do not propose rap as a genre, subgenre, or vocal direction in this project. Use explicit user intent and intentional performance tags. Narrative or dense words alone do not select speech. For a song intended to be sung, specify a pitched verse contour as well as any refrain lift. Distinguish must-have qualities from optional ideas. If an unknown would not change the design materially, choose a reversible default. Do not seek audio files, playback, measured audio features, or claim a heard result. Complete the design from the available text.

Chapter 02 provides the attribute card. Its headings are diagnostic, not mandatory clauses. Omit immaterial features. Use exact tempo or key only if known or central; invented numbers offer false precision. Resolve apparent conflicts by assigning attributes to sources or sections: a close, dry lead may sit over distant, reverberant chords.

## Documented controls versus prompt hypotheses

As checked on 29 September 2026, [Suno's v6 FAQ](https://help.suno.com/en/articles/13924481) describes v6-mini, v6, and v6-wild; says Variety may rewrite style prompts; recommends Variety 0 for wording control; and says Max Mode costs extra credits. Its [Creative Sliders page](https://help.suno.com/en/articles/6141377) describes Style Influence. These are interface facts, not promises of exact sound. No upload, audio reference, recording measurement, or audio-dependent setting is a requirement of this written-only workflow.

Use four evidence labels in project notes and research chapters:

- **Documented interface fact:** Suno's own help currently describes the control or workflow; include a direct URL and check date.
- **Musical design principle:** a causal reason an arrangement or recording choice may help this lyric, grounded in audible relationships. It guides a brief but does not assert model obedience.
- **Prompt hypothesis:** an untested claim that a phrase will steer Suno in a particular way. State the intended behavior as a design proposal; audit its clarity and compatibility in the written prompt. Do not claim that the generator rendered it.
- **Observed result:** an explicitly attributed written report voluntarily supplied by the user. Treat it as reported information, never as audio access or independent verification. Such reports are optional; do not request one as a dependency, and no result report is required to finish a new prompt.

For example, a close lead above a wide chord bed may improve word intelligibility, but exact panning cannot be promised. Even at Variety 0, this workflow can check only the written specification, not a recording.

## Response contract and written completion check

Return four separately labeled parts: **STYLE OF MUSIC** (paste-ready text only), **CHARACTER COUNT** (exact count of the Style text including spaces and punctuation, verified with a counting tool), **EXCLUDE** (short field or “none”), and **SONG TITLE** (a brief track name derived from the lyric and internal attribute rationale). Do not print the rationale or a listening-test field. Never include those labels inside the Style paragraph. Count after every edit, using the exact text to be pasted; do not count Markdown fences or surrounding quotation marks.

Before returning, check the exact final paragraph against the finished lyric and current written requirements: clear source roles, section scope, positive pitched verse guidance when singing is intended, and no incompatible directions. No listening step, generation-file review, upload, or playback confirmation is needed to complete the output.

Recheck Suno's linked help before a new repository release. Use Chapter 12 for worked Style cases. Chapter 11 provides the written-only completion audit.


---

<!-- SOURCE: guide/02-attribute-vocabulary.md -->

# 02. Attribute vocabulary, relationships, and decisions

## Role of this chapter

This chapter is the navigation system for a finished song brief. It converts wishes into things a listener could identify in a recording. The lyric text comes from the existing lyric workflow; the task here is to design the sounding performance and arrangement. A word such as *warm*, *driving*, *intimate*, or *large* is useful only after it is translated into a cause: note length, rhythmic placement, source tone, vocal distance, density, or a change between sections. No single mood word describes all those causes.

An **attribute** is a variable with at least two audible values. A **role** states what a sound does in the arrangement. A **relationship** states how two roles interact. A **section instruction** states when an attribute changes. An **intended behavior** names the sound relationship being proposed in writing; it is a private design aid, never an extra songwriter output field or a heard-result claim. This distinction prevents a Style field from becoming an inventory of attractive adjectives.

The core map has nine axes: pulse; percussion and low end; harmonic motion; melody and hook; sound-source roles and timbre; vocal architecture; form and dynamics; recording image; and lyric–music fit. The axes are independent enough to diagnose separately, but the recording is a set of interactions. A bright sustained chord bed and a bright short percussion tick can coexist; “bright” alone cannot tell Grok which one the user means. A forceful pulse can sit under a quiet voice. A positive lyrical reading can be carried by minor-colored or unresolved harmony when the contrast is intentional. Choose causes before mood labels.

The following definitions are **musical design vocabulary**, not claims that Suno will reproduce an instruction exactly. Any example of prompt wording is an **unverified prompt hypothesis**, not a result claim. The songwriter never receives, hears, plays, measures, or evaluates reference, preexisting, or generated audio. It selects attributes from finished lyrics and written descriptions or documented production accounts. Chapters 01 and 11 cover interface context and written-only auditing; neither requires listening.

## How to read an attribute

For any candidate phrase, ask five questions.

1. **Object:** Which part of the record does it modify: drums, bass, chord layer, hook, lead voice, backing voices, or the whole mix?
2. **Dimension:** What can change: timing, attack, duration, pitch, register, spectral balance, space, level, or density?
3. **Reference:** Relative to what: a beat, a lyric stress, another sound, or an earlier section?
4. **Design consequence:** Which intended sound relationship does this phrase specify?
5. **Cost:** Does naming this detail justify its characters in the short Style field?

For example, “lively” has no object and a vague design consequence. “Short bass notes answer the kick between beats” identifies object, timing, relationship, and intended consequence. “Lead voice stays close and dry while the refrain chords spread wide” distinguishes foreground from background. It also resolves an apparent conflict between intimacy and scale.

Do not force a numerical answer when the user has given a perceptual one. “Brisk but spacious” can be rendered as a quick subdivision with sparse heavy accents. “Slow and urgent” can mean long bars with active short notes, an insistent repeating hook, or a rising section density. If an exact tempo, key, note range, or recording parameter is unknown, describe relative behavior rather than inventing a measurement.

## Compact attribute dictionary

The contrasts below are not binary categories for classifying songs. They are handles for asking where a sound belongs and whether it changes.

| Axis | Contrast to choose | What a listener could hear |
| --- | --- | --- |
| Pulse | broad versus busy felt motion | How often attention is pulled forward, including half-time or double-time perception. |
| Subdivision | even small attacks versus changing small-note rate | Activity between main beats can change while the main pulse stays fixed. |
| Accents | stable versus displaced | Whether important strikes land on expected beats or between them. |
| Kick–bass relation | lockstep versus conversation | Whether low notes reinforce the kick or answer it in gaps. |
| Low-end envelope | brief attack versus sustained tail | A kick can state the arrival while a low note sustains, ends early, or swells after it. |
| Silence/cut | source gap versus all-sound interruption | A drum break may leave voice and tails audible; a complete cut interrupts those too. |
| Harmony | repeating versus traveling | Whether a small chord set cycles or noticeably moves to new ground. |
| Harmonic rhythm | slow versus rapid change | How often chords change, independent of note activity inside each chord. |
| Hook | stated versus answered | Whether the memorable figure belongs to voice, instrument, or their exchange. |
| Hook carrier | retained versus passed or doubled | One source can keep a motif, yield it to another, or share its pitch contour at an arrival. |
| Source identity/role | what produces the sound versus what it does | The same guitar can mark rhythm in a verse and carry a melodic answer later. |
| Source attack | soft versus sharp | How quickly a note rises after onset. |
| Vocal mode | pitched singing versus intentional chant or speech | Whether the lead uses a melody, and which sections deliberately change mode. Rap is outside this project's Style palette. |
| Sung rhythm | held notes versus syllabic melodic attacks | Fast consonants and short notes can follow definite recurring pitches; rhythmic singing does not imply speaking. |
| Vocal intensity | restrained versus projected | Degree of force and outwardness, independent of register or vocal mode. |
| Vocal layers | solo versus doubled or harmonized | Whether added voices reinforce timbre, create chords, or answer the lead. |
| Space | dry/near versus reverberant/far | Whether direct sound or audible ambience dominates a source. |
| Foreground/background | exposed lead versus supporting bed | A quieter distant layer can supply scale while the vocal remains prominent and intelligible. |
| Texture | clean versus audibly saturated | Whether nonlinear edge, noise, or roughness colors a sound. |
| Dynamics | level-stable versus strongly changing | Whether intensity and loudness move within phrases and across sections. |
| Section width/density | narrow lean passage versus wider or busier passage | Stereo spread, simultaneous roles, and attack count can change independently at a lyric event. |

These terms are often useful in pairs. “Sharp attacks, long tails” is a recognizable configuration: the notes declare their entrances yet overlap. “Low-density verse, dense refrain” identifies a change rather than a constant state. “Centered lead, wide chord bed” allocates space by role. In contrast, a chain such as “massive, huge, epic, wide, full” spends characters on nearly the same impression while leaving its cause unspecified.

## Operational relationships from written preferences

The user's liked Style examples suggest useful arrangements of attributes, not a compulsory sound. [The editorial matrix](../evaluation/STYLE_EXAMPLE_MATRIX.md) records their provenance and limitations. The fragments below are original **prompt hypotheses**. Select a move only when the current finished lyric and explicit brief justify it.

| Decision | Operational contrast | Original compact fragment |
| --- | --- | --- |
| Cut scope and length | An instrument rests, drums stop, or every source and tail cuts; the interruption spans a beat fraction, a beat, or a phrase | “After the refrain's last vowel, cut every layer for half a beat, then return on the hook.” |
| Pulse and subdivision | Large beats retain their spacing while small attacks thicken or thin | “Keep the broad backbeat fixed; tighten the upper ticks before the return.” |
| Kick/sub envelope | Shared attack creates one impact; delayed swell separates attack from low sustain | “The kick states each arrival; the sub briefly dips there and swells in the gaps.” |
| Hook carrier and handoff | Recognizable contour stays while tone changes; a second source answers or doubles it | “Piano introduces the small hook; bowed strings inherit its contour at the refrain.” |
| Foreground and background | Distance and width belong to particular sources | “Keep the sung lead close and centered, with a quiet far-off wind answer after each line.” |
| Identity and job | Changing source is optional; changing the same source's function can develop the song | “Short guitar attacks support the verse; the same guitar doubles the refrain tune.” |
| Rhythm and vocal mode | Syllabic singing assigns pitches to dense words; softness controls force, not mode | “The verse sings a compact rising-and-falling motif in short syllabic notes.” |
| Width and density | Wider need not mean more sources; denser need not mean louder | “At the repeated promise, spread the chord bed while keeping the lead and percussion lean.” |

A real all-sound micro-silence and a gap with lingering reverb are different designs. Specify scope when the distinction matters. Likewise, “sidechained” is a technique label; “sub briefly yields to each kick” describes the desired interaction. Keep the technique only when the current request depends on it. A new source should have a job, an entrance, and a relationship to an existing role. Added labels without those relationships make the short prompt harder to interpret.

For an intended sung song, choose the verse's pitch behavior before diction, rasp, closeness, accent, or refrain power. A narrow recurring melodic cell can carry many words. A voice can be gentle, dry, syllabic, and firmly pitched at once. Speech, whisper, chant, or shouts require a current request and a named section; examples containing them do not set the next song's vocal mode. No demographic or persona name can replace an audible instruction.

## Choosing from a broad preference set

Separate three kinds of written evidence privately: what the user explicitly requests now; what a supplied reference actually says in its Style field or Lyrics notes; and the relationships you propose to fit this lyric. An enjoyed example does not reveal which individual trait earned the like. The user authorizes influence from the supplied examples as part of the broader sound palette. Consider their distilled relationships during normal song design, alongside all other guide options. Treat repeated relationships across distinct examples as candidates with tentative preference confidence, not requirements; a duplicate edition or repost is one piece of evidence. Genre, exact tempo, key, chord symbols, named gear, vocal identity, and narrative in an example remain local choices.

Rank each candidate by its fit to a concrete lyric event, its contribution to the song's identity, and the characters needed to state it clearly. Keep a few relationships that explain the whole arrangement, then assign them to sources and real sections. A base sound can be defined by a stable pulse, harmonic loop, lead melody, and a small support bed; one contrasting source or section can change color without accumulating genre tags. If the guide proposes a new break or instrumental passage, distinguish that proposal from a section already written in the finished lyric. The songwriter designs from text and never accesses reference or generated audio, playback, or audio measurements.

## Reusable influence bank for each song

This bank is a palette for optimization, not a limit on musical range. It makes the supplied reference styles available to the songwriter without requiring a named catalog or another research pass. Use it to improve specificity, contrast and lyric fit; new sounds, new combinations and other guide mechanisms remain available. Its profiles are **original design proposals** derived from the written evidence and general arrangement reasoning. The user wants these influences to participate in future song design; that authorizes their use, but does not establish that every individual mechanism is a confirmed favorite. Documentary evidence does not prove the sound of an unheard recording or successful control of Suno. The [anonymous atlas](../evaluation/PREFERENCE_ATTRIBUTE_ARCHITECTURE.md) holds the detailed editorial provenance; Grok need not retrieve it for each song.

Read this bank as part of the normal Chapter 02 route. Compare fitting options with the finished lyrics, current explicit brief, and the broader vocabulary in this guide. A new song may use a bank relation, adapt several compatible relations, or use another architecture entirely. Do not always select the first profile, require a profile for every song, or average the profiles into one permanent sound. IDs below are retrieval handles for internal planning, never Style tags or substitutes for describing the sound.

### Profiles: identity, fit and variation

| Handle and architecture | Defining audible relationships | Fits when the finished lyric or brief needs | Variation knobs and conflict boundary |
| --- | --- | --- | --- |
| **I01 — Nimble melody, short replies** | Definite short pitched verse cells carry dense words over clipped rhythm; a bright instrumental reply waits for line endings. The refrain preserves melodic identity while lengthening its destination vowel. | Quick-moving, playful or direct text has clear thought endings and an actual recurring phrase. | Choose stepwise motion or one local leap, straight or uneven small attacks, and reply source. High diction density conflicts with continuous competing replies; do not turn buoyancy into speech or force cheerful harmony. |
| **I02 — Independent instrumental motor** | A repeating guitar, keyboard or other pitched figure supplies motion beneath a separately shaped sung tune. At a dense passage or held refrain note, the figure thins, rests or shifts register rather than duplicating every vocal pitch. | Continuous momentum is wanted, but verse and refrain need distinct melodic identities. | Alter motor attack, subdivision, register or source while keeping its recognizable behavior. Avoid a second equally prominent looping hook under every word; leave space for the actual sung contour. |
| **I03 — Piano continuity, programmed motion** | A small piano motif remains recognizable as economical programmed percussion enters; the lead sings restrained definite verse pitches, then gains force or vowel duration at a real declaration. | A private opening develops into resolve, or the brief wants acoustic touch with a precise pulse. | Choose exposed or supported piano entry, pulse density, low-end support and the location of projection. Do not require simultaneous growth in tempo, layer count, range and width; piano intimacy never implies spoken delivery. |
| **I04 — Foreground bass identity** | An articulated, optionally roughened bass figure carries recognition; drum attacks establish the frame and upper chords remain economical. Sung phrases retain foreground clarity through selective bass gaps or register separation. | The brief wants physical low/midrange character or a groove that is recognizable without many layers. | Decide unified kick/bass impact versus anchor-and-reply, short versus sustaining notes, and how much edge belongs to bass. A busy bass motif conflicts with several busy upper hooks; enormous sub tails are not a prerequisite. |
| **I05 — Percussion continuity, changed weight** | One distinctive attack pattern links contrasting textures; a real section changes accent spacing or small-note activity while a clear sung motif survives. Bass either reinforces those anchors or replies selectively. | The lyric has a genuine turn, and the brief wants continuity through a rhythmic contrast. | Change felt weight, subdivision or grouping only where phrasing supports it. Distinguish a fixed-tempo half-time impression from an actual tempo change. Do not add a new meter or every-beat kick merely to use this profile. |
| **I06 — Planned vocal hierarchy** | A pitched foreground lead carries the text; a quieter low harmony sustains selected passages, while an upper sung counterline moves only where long lead vowels leave space. Fuller combinations enter locally. | The user wants layered singing, sustained grandeur or complementary registers around a repeated declaration. | Choose unison reinforcement, harmony or independent response deliberately; vary entrances and reserve layer reduction for an exposed word. This option needs a brief that permits additional voices; it must not manufacture a duet narrative or crowd dense verses. |
| **I07 — Contained verse, earned melodic opening** | A clear recurring verse contour uses restrained force. The refrain broadens its pitch span or note length; one late held destination follows a deliberately placed accompaniment breath. | The text progresses from guarded thought to release, with an actual meaningful return or final peak. | Pick one principal lift: interval, register, duration, harmony or support width. Scope a pause to backing, lead or all layers. Do not demand a belt, key change, high note and full cut together, or reduce the verse to conversation. |
| **I08 — Instrumental continuation, shared foreground** | A source that supported the sung passage develops its hook during an existing wordless gap; piano, strings, guitar or electronic tone exchange or briefly share foreground without adding lyric. | A lyric thought benefits from musical continuation, and the text or brief allows an instrumental passage. | Choose handoff, answer, shared contour or coequal lines, plus what keeps the pulse. If the lyrics provide no gap, make any proposed interlude explicit in private planning; do not silently add a new section or invent words. |
| **I09 — Clear chord identity, local grouping contrast** | Distinct chord attacks keep harmonic changes legible; a quieter sustained layer supplies atmosphere. One real contrast passage can adopt a rolling grouping before returning to the established pulse. | The brief values harmonic movement or the supplied phrase lengths support differing rhythmic groupings. | Keep only the chord-clarity relation when grouping change is unnecessary. Choose sustain behind attacks, chord-change rate and one connecting motif. Do not smear every harmonic source or claim an exact meter without a written reason. |
| **I10 — Acoustic attacks, electronic sustain** | A plucked or struck acoustic part supplies tactile rhythm while an electronic bed sustains harmony. One motif changes carrier or is locally doubled at a return; the near pitched lead stays distinct. | The user wants both source families to have meaningful roles, or a lyric contrasts immediacy with expansion. | Swap which family carries hook versus bed, alter envelope or register, and select the handoff event. Avoid doubling every role continuously; different sources should contribute complementary functions rather than a piled style label. |
| **I11 — Cut, changed weight, recognizable return** | A completed sung phrase leads to a short explicitly scoped interruption; the return restores a recognizable hook with a changed low-end envelope, accent weight or carrier. | The lyric has a decisive arrival and the brief calls for abrupt electronic or band contrast. | Choose a drum rest, accompaniment cut or true all-sound silence; choose one return change. Do not import a source example's vocal mode, assume a drop belongs in every song, or leave long tails while requesting total silence. |
| **I12 — Melodic identity through withdrawal** | The same definite sung contour remains as drums, bass or backing voices withdraw in stages. A continuing motif or held tone connects the exposed final phrase to earlier material. | The ending is reflective, unresolved or deliberately intimate instead of a larger final climax. | Change decay, accompaniment register, remaining source and the order of exits. Preserve singing after the bed thins; do not add an obligatory final refrain or fade when the words need a clean endpoint. |

These are not twelve genre categories, recording reconstructions or complete Style templates. A profile's fit column is a musical reason to consider it, not a prediction of what the user must enjoy. Source choices, force, tempo and harmonic vocabulary remain adjustable. Existing guitar-and-drum, groove-centered, sparse ensemble, heavy, spacious and other guide mechanisms remain available beyond this bank.

### Select relations that actually affect the new prompt

1. **Locate the lyric requirement.** Identify actual repeated phrases, dense information, breathing spaces, changes of perspective and ending meaning. Preserve the finished words and section structure.
2. **Compare architectures.** Consider a few fitting bank relations alongside broader guide options. Rank current explicit requirements first, then lyrical fit, coherent identity, useful contrast and character cost. Do not request a reference selection again merely to operate this bank.
3. **Choose an identity and a development.** A practical default for planning is one recognizable relationship plus one lyric-earned change; another hierarchy is valid when the brief needs it. Optional details should explain those choices, not turn into a checklist.
4. **Carry the selection into Style.** Specify who acts, how, and at which real section or lyric event. Preserve that relationship when compressing. Writing only “melodic, energetic, layered” loses the influence; writing “a small piano figure persists as programmed drums enter, then yields to longer sung refrain vowels” makes it operative.
5. **Keep the reasoning private.** Internally note the selected relation and why it fits. Do not print profile IDs, reference titles, evidence labels, citations or a fifth rationale field. The title may derive from the internal attribute rationale.

Overlap does not justify repetition. I01 and I07 both develop note length: choose one coherent verse/refrain instruction. I02 and I04 both supply instrumental identity: let one dominate, or alternate their foreground by section. I03 and I10 can share complementary acoustic/electronic jobs without naming extra sources. I05 and I11 can combine a continuing attack identity with one cut, provided the interruption and return are explicit. I06 can complement another architecture when lead gaps support extra voices; otherwise omit the counterline. I07 and I12 can coexist as an earned peak followed by withdrawal only if the actual lyric supports both events. Dense motors, active bass, continuous vocal harmonies and frequent replies together require subtraction rather than more adjectives.

For intended sung songs every selected architecture retains explicit pitched verse behavior. Speech, whisper, chant or shout remains available only within the project's existing section-specific permission rules; rap is excluded. No profile permits an assumed recorded voice, access to reference or generated audio, playback, measurements, or an audio evaluation by Grok. Written preferences and documented production descriptions are sufficient inputs. Return exactly **STYLE OF MUSIC**, **CHARACTER COUNT**, **EXCLUDE**, and **SONG TITLE**; the exact final positive Style paragraph remains within the user's observed 1,000-character target.

## Interactions that create a coherent record

### Detailed profile for a broad reference set

An exhaustive private profile considers the decisions below without placing all of them in Style. It should reveal the song's hierarchy and a few defining relationships. [The anonymous reference atlas](../evaluation/PREFERENCE_ATTRIBUTE_ARCHITECTURE.md) separates documented production accounts from proposed designs; no artist, work, persona, national identity or regional label should become a sound shortcut. The reference research used written sources and has no heard-recording findings.

| Domain | Separate decisions | What a selected relation might specify |
| --- | --- | --- |
| Verse melody | Contour, steps/leaps, register, note length, phrase endings | Short definite sung pitches settle on a longer complete-thought vowel. |
| Refrain melody | Hook identity, interval span, held destination, peak placement | The recurring tune broadens one interval and holds its final stress. |
| Vocal force | Onset, projection, breath placement, local grain | Restrained verse force grows at the return without changing the clear vocal core. |
| Vocal articulation | Consonant attack, vowel shape, pickup, release | Crisp short sung notes stay distinct over a stable beat. |
| Vocal layers | Lead, lower support, upper harmony, counterline, reply | Low harmony sustains behind the lead while an upper answer waits for gaps. |
| Large rhythm | Beat rate, grouping, anchor, backbeat spacing | A section changes felt weight while the instrumental identity remains. |
| Small rhythm | Subdivision, syncopation, event density, local timing | Upper attacks tighten while low accents remain spaced. |
| Bass identity | Pitch figure, texture, onset, sustain, foreground role | An articulated bass motif leads recognition; drums support its repeated motion. |
| Harmonic activity | Chord-set size, rate, voicing, pedal, cadence | Compact chord vocabulary develops through bass path and upper spacing. |
| Hook architecture | Owner, contour/rhythm, first appearance, return, handoff | A looping instrumental figure coexists with an independently shaped sung line. |
| Source hierarchy | Anchor, bed, foreground, answer, transition, continuity | A supporting piano becomes coequal foreground only during a vocal rest. |
| Timbral development | Attack, decay, brightness, roughness, filter/echo behavior | The same source changes envelope or register instead of adding another layer. |
| Structural recurrence | Existing repeated text, one-time disclosure, real contrast section | A one-time verse stays once; a later actual verse changes accompaniment rhythm. |
| Section destination | Anticipation, arrival, maintained energy, withdrawal | A bridge changes focus while preserving urgency rather than automatically calming. |
| Recording hierarchy | Directness, depth, width, density, competing registers | A clear centered lead stays near while a selected chord bed opens wider. |
| Emotional relationship | Narrator intent, harmonic tension, physical motion, vocal force | Movement in backing and unresolved words can coexist without a single global mood tag. |

Do not collapse these into “energetic melodic music.” A brisk tune with light articulation, a restrained piano-led song, a bass-led arrangement and a multi-voice sustained texture can be distinct proposals within a broad preference context. Select a hierarchy for this song rather than averaging all admired recordings. A short profile can also be complete: accounting for a dimension may mean deliberately leaving it unspecified because it does not determine the current design.

**Pulse × attack density.** Tempo alone does not specify urgency. Broad accents with long rests can feel spacious at a brisk speed; a slower beat with repeated small subdivisions can feel insistent. Name both felt motion and event pattern. Describe the activity between stable large beats.

**Kick × bass.** The two can start together or answer each other. A held bass can bridge short kicks; clipped offbeat notes can move between them. “Heavy bass and hard kick” leaves the relation vague. State onset and duration: “short bass notes mirror the opening kick, then move between kicks in the refrain.” Check that the written prompt assigns each pattern to its intended section.

**Harmony × lyric density.** Frequent chord changes, moving inner parts, and long tails occupy attention. Dense text may need a smaller repeated chord set or quieter sustained voicings; sparse text can allow more motion. If words should be submerged, state that deliberately.

**Melody × hook ownership.** An instrumental figure can prepare, answer, or compete with a vocal phrase. Place it in gaps after a fast sung hook; a sustained vocal may leave room for a moving countermelody. State who carries the motif and when the other part yields.

**Voice × arrangement.** A near, breathy lead may need a lean bed; a projected refrain can take wider layers and accents. Backing voices can enlarge a refrain but mask dense words. Specify where they enter and whether they double, harmonize, or answer the lead.

**Section arc × invariants.** Keep a bass pattern, motif, or lead timbre recognizable across contrasting sections. Choose one identity cue to persist and one major dimension to change. A refrain can lift through register, density, rhythm, harmony, or voices without increasing all five.

**Recording space × role.** A close dry lead can stand before a wide reverberant bed. “Dry and reverberant” conflicts only when both modify the same source at the same time. Assign each quality to a source or section.

**Brightness × emotion.** High-frequency energy, upper register, forceful attacks, lyrical hope, and cheerful delivery are different variables. Translate the desired feeling into movement, voice, harmony, and texture; check that the written combination serves the current lyric and brief.

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


---

<!-- SOURCE: guide/03-pulse-percussion-bass.md -->

# 03 — Pulse, percussion, bass, and groove

## The decision this chapter supports

Describe how the recording moves, not merely how many beats it has per minute. A useful rhythm instruction lets a listener predict where the weight falls, how the small attacks behave between beats, how bass and percussion cooperate, and what changes when a section opens up. The finished lyric supplies the words; rhythm decisions should make their stresses and breaths workable. A Style prompt rarely needs every term below. It needs the two or three relationships whose absence would change the identity of this particular song. These are intended musical relationships, not guaranteed Suno commands. The songwriter never receives, hears, plays, measures, or evaluates reference, preexisting, or generated audio; every rhythm decision is made from finished lyrics and written information.

## Pulse versus perceived speed

**Pulse** is the recurring beat a listener could tap. **Tempo** describes the rate of that pulse. **Perceived speed** also depends on the rate and force of the attacks inside each beat, phrase length, bass note duration, and the placement of backbeats. A track at a fixed tempo can feel broad when the kick and snare state large intervals while a sustained bass spans them; it can feel urgent when short hats and bass notes mark subdivisions. Do not infer tempo from how many syllables the lyric contains. A dense line can be delivered rapidly over a broad pulse, while a sparse line can float across an active pattern.

Use exact BPM when the current user brief supplies it or when a precise rate is musically decisive. A number in an enjoyed reference describes that example and does not set this song's tempo. Otherwise choose a verbal range that conveys motion: “unhurried, weighty pulse”; “brisk pulse with short, even subdivisions”; “moderate pace with an expansive half-time backbeat.” An invented number implies precision the evidence does not justify. No audio-derived measurement is available. Use a supplied written tempo or choose the intended relative motion; a listening stage is not a workflow dependency.

The apparent **half-time** or **double-time** relationship is a perception of accent spacing, not necessarily a tempo change. “Fast small percussion over a broad half-time snare” tells the generator which layer carries urgency and which layer carries weight. “Double-time feel” without a layer named can produce wholesale speeding. Ask which body movement should dominate: head nod, quick step, long sway, or continuous drive. That is an internal diagnostic, not a phrase that must be pasted into Style.

An **every-beat kick** gives a low anchor on each beat; a **half-time backbeat** spreads the strong counter-accent across a broader interval. These can appear in alternating sections at one tempo, or coexist when their roles are clear. Name the change in perceived weight rather than importing a genre label from a reference: “The verse keeps spacious kick placements and a broad snare; the refrain puts a firm kick on every beat while its upper subdivisions stay brisk.” Choose this contrast only when the lyric's arrival benefits from it. A long narrative verse can also use every-beat anchors with thin accompaniment, and a refrain can retain broad accents.

## Meter, subdivision, and recurring placement

**Meter** groups beats into repeating cycles; **subdivision** splits a beat into smaller placements. A listener may hear a regular four-beat frame, a three-beat turn, or a deliberately uneven cycle. Specify a less common grouping only when it is essential and compatible with the lyric’s phrase lengths. Otherwise it can spend characters while introducing needless instability. For a short prompt, “four-beat pulse” or “rolling three-beat cycle” often communicates more than a fraction alone.

**Straight** subdivisions divide the beat evenly. **Swung** subdivisions give paired attacks unequal durations, typically lengthening the first. Avoid treating “swing” as a single percentage or as a proxy for looseness. The subdivision may be unequal while the kick and backbeat stay emphatically regular. A line such as “even kick anchors; lightly loping hats” identifies the relationship. If the desired lilt is confined to the bass or vocal, name that layer. Conversely, “straight, even eighth-note percussion” is a sensible positive specification when the current written brief calls for firm spacing.

**Backbeat** names a recurring accent that counters or answers the main pulse. It can be heavy, restrained, delayed in feel, sparse, or doubled. “Hard backbeat” may imply louder impact, but not where the kick falls. “Sparse kick under a firm backbeat” is more precise. A faint backbeat can let the bass line carry momentum; a heavy one can create perceived width and certainty even at a brisk tempo. The question is not “does the song need a backbeat?” but “which layer tells the listener where a phrase lands?”

**Syncopation** shifts emphasis toward weaker or unexpected positions relative to an established meter. It needs a stable reference to register as displacement. Ask what remains predictable while another layer moves against it. A bass anticipation before a downbeat may provide forward pull; snare accents that miss every expected point may instead obscure the frame. Experimental work found that moderate syncopation could increase movement ratings in controlled rhythm examples, while too much reduced them, so use it to consider written alternatives for degrees of displacement rather than as a universal ranking or a task to compare recordings. [Witek and colleagues’ original experiment](https://pmc.ncbi.nlm.nih.gov/articles/PMC3989225/) and [a related controlled experiment](https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2014.01036/full) are evidence for the interaction between predictability and displacement, not evidence that one pattern suits every song.

## Event density, space, and the pocket

**Event density** is the number of attacks over a span, separate from tempo and loudness. Quiet rapid hats can make a moderate pulse feel busy; a large but infrequent kick can feel spacious.

**Pocket** is a listener’s sense that layers sit coherently around a repeated pulse. It includes timing, articulation, and mutual space. It is not synonymous with random timing errors. **Push** suggests a layer articulates toward the front of the perceived beat; **laid-back** suggests a layer sits toward its rear; **centered** suggests attacks align closely with it. These describe intended relative timing, not measured audio features or reliable millisecond specifications for text-to-audio. If a vocal should press against a steady backing, say so explicitly: “steady percussion; lead phrases lean forward.” If the drum kit should feel relaxed while the bass anticipates entrances, assign those roles separately. Do not stack “loose, tight, raw, perfectly quantized” in one instruction.

Do not default to quantized = lifeless or microtimed = alive. A performed sound may carry life through dynamic accents, note lengths, ghost notes, and changing tone while staying close to a grid. Conversely, exaggerated lateness can make a groove feel uncertain. The [microtiming experiment](https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2016.01487/full) supports avoiding a blanket direction to displace all events. For Style, describe the audible outcome: “precise pulse with gently varied hat accents,” “unhurried backbeat against punctual bass,” or “firm, interlocking attacks.” The exact production mechanism is less important than the intended relationship.

## Percussion as functions, not a shopping list

Percussion instructions are strongest when each sound has a job:

| Function | Audible question | Possible compact wording |
| --- | --- | --- |
| Ground | Which low attack defines the beat or phrase landing? | “Short, centered kick marks the pulse.” |
| Counterweight | Which midrange hit gives a recurring answer? | “Dry snare answers on a broad backbeat.” |
| Subdivision | Which lighter attacks create motion between main beats? | “Fine, even hats create urgency above spacious drums.” |
| Accent | Which rare hit marks an important word or turn? | “Small metallic accents punctuate section endings.” |
| Transition | What announces the next section? | “A short rising fill gives way to a clean downbeat.” |
| Absence | Which expected hit disappears to create a gap? | “One-beat drum break exposes the final word.” |

## Bass: rhythmic role, note length, and register

Bass connects rhythm and harmony. It can reinforce roots, trace a countermelody, hold a pedal tone while chords change, anticipate a downbeat, or leave a deliberate hole around a kick. First decide whether the bass is **anchor**, **motor**, **reply**, or **drone**. An anchor joins large accents and sustains the harmonic center. A motor makes frequent short attacks. A reply enters the gaps after another part. A drone persists through changing upper harmony. These are functions, not sound-source categories.

**Note length** often matters as much as note choice. A short bass decay clears room for the next kick and preserves articulation. A long, smooth note gives continuity but may conceal small kick attacks if both occupy the same low range. “Round bass notes that end before the next kick” is a useful relationship. “Bass blooms after each kick” suggests an audible swell, but do not assume a specific compression effect will be generated. If the need is only clarity, specify the result rather than a processing chain. [Ableton’s audio-effect reference](https://www.ableton.com/en/live-manual/12/live-audio-effect-reference/) documents one production method for making low elements yield to a kick; the prompt should normally describe the audible interaction, not prescribe a plugin setting.

**Kick–bass alignment** has several valid designs. They can strike together for a single large impact; the bass can arrive just before the kick to pull the phrase forward; it can enter after the kick to create a two-part motion; or it can fall in the spaces between kicks. Choose one dominant relation. Saying “syncopated bass over a steady kick” is useful when the rhythm must move without destabilizing the beat. Saying “kick and bass lock” is too vague if a particular pattern of exchange is crucial. Low-frequency overlap can obscure both elements; [iZotope’s engineering demonstration](https://www.izotope.com/community/blog/how-to-mix-kick-and-bass) illustrates why making room in frequency, duration, or arrangement can improve clarity. This is a design principle, not a claim that a text prompt gives surgical frequency control.

## Low-end envelope: what begins and what remains

Attack, sustain, and release describe different parts of the low-end motion. Decide which source announces the beat and which provides continuing weight. A round long sub can coexist with a short hard kick if its onset or level leaves room for the kick. A highly clipped bass can create audible pitch replies without sustaining the whole space. Saturation, compression, and a particular bass-source name do not themselves establish this relationship.

| Design | Intended relationship | Original Style fragment |
| --- | --- | --- |
| Shared impact | Kick and low note begin together; low note has controlled duration | “Kick and bass strike the phrase landing together; bass ends before the next low attack.” |
| Kick then sustain | Kick supplies the transient; bass blooms afterward | “A short kick opens each beat, followed by a smooth low swell.” |
| Stable anchor and reply | Kick keeps its repeating pattern; bass occupies selected gaps | “Regular kicks hold the frame while clipped bass notes answer between vocal phrases.” |
| Sustained low floor | Long note bridges sparse percussion; upper bass edge can supply definition | “One low note spans the line beneath sparse dry kicks.” |
| Momentary low-end yielding | Sub level dips at the kick and returns afterward | “Sub briefly yields to each kick, then rises smoothly into the space after it.” |

These are options. Every song does not need ducked sub, deep sustained bass, or a fixed low-frequency range. A short prompt can communicate an envelope without naming devices, exact compressor settings, or cutoff numbers. A technique supplied by the current brief may be retained when it adds useful precision; a device mentioned only in a liked prompt should be translated into perceptible behavior or omitted. Preserve vocal space: busy bass replies can wait for gaps rather than following every syllable.

## Breaks, subdivision changes, and abrupt silence

Use a transition to mark something in the finished lyric: a question ending, repeated vow, change of addressee, withheld answer, or last sung word. First identify the lyric event, then decide whether the arrangement needs anticipation, interruption, a weight change, or withdrawal. A reference's buildup/drop labels do not add those sections to a different lyric. A proposed instrumental break belongs in the private plan and can be named in Style when authorized by the current brief; leave the finished lyrics intact.

**Subdivision change:** smaller attacks can become more frequent over the same large beat. “Upper ticks tighten toward the return while kick spacing stays fixed” separates felt tension from a tempo ramp. The reverse move can open room for a long sung vowel. Increasing attack rate on every layer can obscure the beat and text; assign the change to the layer doing the transition.

**Riser or fill:** a short upward swell or tightening percussion figure can announce a return. Choose one clear function and end it before the new impact. “A thin rising noise ends at the cut” differs from “a drum fill carries through the entrance.” Neither is a universal requirement for an electronic passage. Use an exact subdivision such as sixteenths only when its rate matters enough to justify the detail.

**Break:** removing drums can expose voice, acoustic grain, or the existing hook. Thin the support bed while retaining a definite verse melody in a sung song. Sparse backing does not require a spoken lead. A break can retain bass or residual room sound; name the surviving role when it makes the contrast work.

**Micro-silence:** define its scope and location. An all-sound cut stops direct sources and effect tails; a percussion stop leaves the other material continuous. Put a brief gap after the lead's completed vowel if the word should remain intact. “Cut all layers for half a beat after the last word, then restore the low pulse beneath the hook” makes the interruption's duration and function clear. A beat fraction is a design choice, not a default or guaranteed sample-accurate control. Repeated cuts may fragment dense singing, so select a few meaningful locations.

**Return:** decide what survives and what expands. The same pulse may return with longer bass notes, a higher hook carrier, wider chords, or more frequent light attacks. One decisive change can communicate an arrival. Do not prescribe all of them in every song. **Withdrawal:** removing attacks while a melody or chord sustains can provide an ending distinct from another large arrival; specify whether the last tail rings out or cuts.

## Diagnostic questions before compiling

1. Does the written plan identify a repeating beat anchor, or deliberately specify ambiguity?
2. Does the desired urgency come from the beat rate, from subdivisions, from bass articulation, or from vocal phrasing?
3. Which sound tells the listener where the large beat lands? Which one moves against it?
4. Is the backbeat strong, restrained, absent, or section-dependent?
5. Does the lyric need a gap for a breath, a name, or a decisive final word?
6. Should the bass sound primarily as weight, audible pitch, rhythmic edge, or melodic reply?
7. Do kick and bass coincide, alternate, or overlap with a clear hierarchy?
8. What exactly changes when the song reaches its largest section?
9. Does a transition change beat rate, accent spacing, or only the smaller attacks?
10. If there is a silence, which sources and tails stop, for how long, and after which completed lyric event?

## Prompt phrasing: from vague to audible

The following are original, anonymous phrasing examples. They describe intended audible results, not verified Suno behavior. The songwriter does not receive or hear any audio; these fragments are written design proposals.

| Vague request | More specific Style fragment | Intended audible result |
| --- | --- | --- |
| “Make it fast and powerful.” | “Brisk, even pulse; sparse low kick and hard backbeat under rapid, quiet hats.” | Strong large beats coexist with small high attacks. |
| “Groovy bass.” | “Short, rounded bass notes answer the kick between downbeats.” | Bass entries fill gaps rather than duplicating the kick. |
| “Human drums.” | “Firm beat with varied soft upper-percussion accents and few fills.” | Pulse remains stable; upper layer has dynamic differences. |
| “Big chorus.” | “Refrain widens with longer bass notes and denser hats; the core beat stays unchanged.” | Section changes in duration and density without speed drift. |
| “Swinging beat.” | “Even kick anchors a lightly loping subdivision in the upper percussion.” | Unequal small-note spacing sits over a stable low pulse. |
| “No clutter.” | “Dry kick and backbeat leave gaps around the lead’s dense lines.” | Words are clear and the percussion does not chatter through them. |
| “Huge drop.” | “After the last sung vowel, a half-beat all-sound cut precedes the returning every-beat kick and doubled hook.” | Interrupted continuity makes a specific return conspicuous. |
| “Fast verses.” | “Short syllabic notes follow a recurring pitched verse motif over broad drum accents.” | Vocal articulation is quick while the main rhythmic weight stays spacious; the verse remains sung. |
| “Acoustic electronic blend.” | “Dry hand-played clicks mark the small pulse; a round low swell answers the electronic kick.” | Acoustic and electronic sources have distinct jobs within one groove. |

## Written groove audit before returning

Check the plan and final Style paragraph using the finished lyrics and written brief only. Do not request an excerpt, tap a recording, mark heard attacks, measure BPM, compare speakers, or score a generated result.

- **Anchor:** Name one recurring beat role if a clear pulse is intended; identify which other role supplies displacement.
- **Urgency:** Distinguish beat rate from subdivision density, bass articulation, and sung phrase activity. Do not invent a BPM from syllable count or a reference title.
- **Low-end allocation:** Specify coincident attacks, separated onsets, or an anchor-and-reply relation. Check that sustain does not contradict a requested short gap.
- **Lyric room:** Reserve gaps or quieter supporting activity where the finished words are dense. Keep explicit pitched verse behavior when accompaniment thins.
- **Arrival:** Identify a real lyric event and one meaningful change in duration, accent, register, or density; omit unrelated buildup/drop conventions.
- **Scope:** Assign any push, relaxed timing, or cut to a particular source and section. Avoid global directions that conflict with a fixed anchor.

These checks assess the written arrangement's coherence. They do not establish what Suno rendered, and do not require a listener report to complete a prompt.


---

<!-- SOURCE: guide/04-harmony-melody-hooks.md -->

# 04 — Harmony, melody, and hooks

## The decision this chapter supports

Specify what changes in pitch over time and what stays put. Harmony is the simultaneous support around a melody; melody is a timed path of pitches and rests. A prompt is more useful when it says whether chords hold or turn, whether the lead line climbs or circles, and which sound carries a recurring idea. “Beautiful melody and rich chords” predicts almost nothing. “Two repeating chords beneath a narrow verse line; the refrain opens into a longer, rising vocal phrase” predicts shape and contrast without requiring a named category.

Finished lyrics are the input. These definitions are stable compositional tools; Style phrasings are unverified design proposals, not exact note commands. The songwriter never receives, hears, plays, measures, or evaluates reference, preexisting, or generated audio. Use finished lyrics, the current written brief, and documented musical descriptions to choose the intended pitch relationships.

## Harmonic center and emotional color

A **tonal center** is the pitch that feels like rest. Preserve a supplied key when it matters; do not invent one. “Dark” and “bright” could describe harmony, register, timbre, or mix, so name the mechanism: “low repeating chords with a brighter upper voicing at the refrain.”

**Chord-set size** is the number of distinct harmonies in a loop. A small set can support a vivid track when bass motion, vocal contour, and voicing develop. Specify the consequence: “two repeating chords; upper notes spread wider at the refrain.” [Berklee’s songwriting discussion](https://online.berklee.edu/takenote/harmonic-progressions-for-songwriters/) explains how even one changed chord can create section contrast.

## Harmonic rhythm: rate of chord change

**Harmonic rhythm** is the rate of chord change, independent of tempo. Holding chords gives the lead or bass room to move; changing them more often can heighten anticipation. “Chords hold across long vocal phrases” differs from short repeated stabs on an unchanged chord. [Berklee’s composition article](https://online.berklee.edu/takenote/music-composition-techniques-and-resources/) treats chord duration as a distinct compositional choice.

A **pedal tone** persists while harmony above it moves. A **suspension** holds a note across a chord change before it settles. A **departure and return** leaves the established loop and restores it later. Use one when the song needs that effect: “bridge briefly leaves the loop; final refrain returns.”

## Voicing, register, and attack

**Voicing** is the spacing and register of chord tones. A wide upper chord above a lean low foundation differs from a compact midrange block. State whether chords are held, pulsed, arpeggiated, or struck and damped; the attack pattern can change perceived motion without changing harmony.

An **arpeggio** sounds chord tones in sequence; a **stab** is a short chord attack; a **wash** sustains and blends. Voice leading is the path each tone takes between chords. “Small upper-note motion across held chords” is an audible description of smooth voice leading. See [Berklee’s technical explanation](https://online.berklee.edu/takenote/voice-leading-paradigms-for-harmony-in-music-composition/).

## Melody as contour plus rhythm

**Melodic contour** is a line’s directional shape: rising, falling, hovering, or leaping then resolving. Rhythm, note length, register, and rests complete the design. [Berklee’s melody guide](https://online.berklee.edu/takenote/conjunct-disjunct-melody-basic-definitions/) defines pitch and rhythm as core components. “Narrow, short verse phrases; one rising refrain line with a held final word” combines contour and duration.

**Register** is the pitch region; **range** is the span between low and high notes. A narrow verse can give one later leap significance. Decide where the highest or longest note belongs; a rest before it may make it more exposed than extra accompaniment.

## Motifs and the hook’s carrier

A **motif** is a small recognizable rhythmic or pitch figure that returns or transforms. It may belong to the voice, bass, chords, or a short lead sound. Return it clearly before varying its last note, register, or carrier. [Berklee’s motif guide](https://online.berklee.edu/takenote/simple-tools-for-better-melodies/) offers this as a compositional method, not a promise of memorability.

A **hook** is the feature the listener can recall and locate. Specify its **carrier**, **shape**, **position**, and **return**: “a three-note rising vocal figure opens each refrain; a bright pluck echoes it after the line.” “Catchy” describes a hoped-for result, not the implementation.

**Call and response** alternates a phrase with an answering source. A **countermelody** runs simultaneously and needs a separate register or restrained level. For dense lyrics, “two high notes answer in the gaps after each line” is safer than a continuous competing part.

## Section contrast without arbitrary complexity

### Independent melodic identities and phrase-led entry

A vocal tune and an instrumental motif need not share every pitch or rhythm. A repeated guitar, piano or bass figure can be the continuity cue while the lead sings a separate contour. Decide which identity is foreground at each moment. Original hypothesis: “A short repeating guitar figure underpins the verse's independent stepwise tune; the figure recedes as the refrain holds longer notes.” The recession is a new arrangement proposal, not a presumed feature of a reference.

Alternatively, let a meaningful finished phrase determine the first melodic entry: expose its tune early, then confirm the pulse with accompaniment. This does not require an unaccompanied opening or the insertion of new text. Phrase-first entry, instrumental prefiguration and delayed hook arrival are different choices. [Anonymous production evidence](../evaluation/PREFERENCE_ATTRIBUTE_ARCHITECTURE.md) documents examples of phrase-led writing and independent instrumental/vocal construction; it does not supply a tune to copy.

### Reserve, expand or suspend the melodic destination

Separate **pitch span**, **register**, **duration** and **projected force**. A refrain can widen intervals without getting louder, or hold a stressed vowel longer without climbing. A single late upper note can be reserved for an earned lyric destination; a continuously high tune has a different arc. Do not impose a narrow three-note verse on every song merely to guarantee singing. Specify definite pitch behavior with the range and motion this brief needs.

For harmonic contrast, first ask whether a new chord, a changed chord duration, a different bass path or a new voicing is enough. Do not invent modulations to imply sophistication. If a source's chord changes need clarity, reduce a competing continuous wash or assign sharper chord attacks to one layer; atmospheric motion can remain elsewhere. A clear harmonic identity and a complex surrounding texture are separate variables.

Original alternatives: “The refrain keeps its pitch range but doubles the final vowel's duration”; “One larger leap marks the repeated declaration before stepwise settling”; “The final thought ends suspended while the accompaniment withdraws.” These are selectable prompt hypotheses, not a mandated sequence or evidence of heard results.

Contrast one dimension while preserving an anchor: held verse chords versus faster refrain changes, narrow verse contour versus a rise, or clipped verse chords versus a sustained refrain. [Berklee’s hook discussion](https://online.berklee.edu/takenote/how-to-write-songs-with-killer-hooks/) treats placement and contrast as useful songwriting choices. Specify which figure returns so sections still feel related.

## Diagnostic questions

1. Does the written brief supply a key or tonal center? If not, is an intended center important enough to propose, or should it remain unspecified?
2. Does the song’s emotional change require a new chord, a changed chord duration, a wider voicing, or a different melody?
3. Which section has the fewest distinct chords, and what moves instead?
4. Where is the highest, longest, or most exposed vocal note, and which lyric stress earns it?
5. Is the main hook vocal, instrumental, bass-led, or rhythmic? When does it first appear and return?
6. Does any simultaneous counterline compete with dense syllables?
7. What feature remains recognizable across sections?

## Prompt phrasing and intended audible results

These are original candidate fragments, not certified commands to a generator.

| Weak wording | More specific wording | Intended audible result |
| --- | --- | --- |
| “Simple but interesting chords.” | “A small repeating chord set stays steady while the bass changes its path.” | Harmonic stability with movement below it. |
| “Emotional chorus.” | “Refrain melody rises beyond the verse’s narrow range and holds its last stressed word.” | A distinct melodic peak aligned to the lyric. |
| “Memorable hook.” | “Short descending vocal motif returns unchanged at each refrain opening.” | Same recognizable figure on repeated entries. |
| “More musical bridge.” | “Bridge briefly leaves the chord loop while a held upper note preserves continuity.” | Contrast without total loss of identity. |
| “Rich harmony.” | “Held, widely spaced chords open beneath the refrain; verse chords remain clipped and narrow.” | Contrast in voicing and duration. |
| “An answering instrument.” | “Two bright plucked notes answer only after the lead finishes each line.” | Clear alternation rather than overlap. |

## Written pitch and hook audit

Check the planned relationships against the finished lyric before returning; audio and listening results are unavailable.

- If the plan needs harmonic stability, specify a returning center or economical chord set rather than claiming a reference's key.
- If the arrangement needs development, consider chord duration, bass motion, or voicing before adding many chords.
- Locate any proposed melodic peak at an actual lyric stress; preserve definite verse pitch behavior as well as refrain shape.
- Give the main hook a carrier, contour or rhythm, entrance, and return. Distinguish a new design proposal from a written source observation.
- Put a hook answer in a planned vocal gap when dense words need foreground clarity; check that a simultaneous counterline has an assigned register or restrained role.

The audit establishes written specificity and compatibility, not rendered harmony, memorability, or a heard result. No audio input or post-generation evaluation is required.


---

<!-- SOURCE: guide/05-sound-sources-timbre.md -->

# 05 — Sound sources and timbre

## Choose roles before names

A Style field cannot carry an inventory of every sound. Decide what each needed source **does**: marks the pulse, carries bass, supports chords, states the hook, answers the lead, makes atmosphere, or punctuates a transition. Assign no more than one main carrier to a role unless the intended effect is a clear layer or exchange. “Plucked upper figure answers the vocal” is often more useful than a list of possible instruments because it specifies register, articulation, and timing. A named instrument can still be useful when its characteristic sound is indispensable, but do not expect the name alone to determine performance.

Separate **source identity** from **timbre** and **part behavior**. A keyboard source may have a rounded, sustained tone or a bright, short one; the same nominal source can occupy foreground or background. A guitar-like source can strum chords, play short single notes, sustain a line, scrape rhythmically, or create noise. The Style prompt should carry the smallest combination that prevents an unwanted substitution: source family, audible tone, role, and timing. A sound that has no clear job in the listener’s mental image probably does not deserve prompt space.

Written reference prompts offer possible relationships, not a required palette. A useful transfer might be an acoustic attack against an electronic sustain, a short hook answered by a longer tone, or a melody passed between sources at a lyric return. Select the relationship because it serves this song. Exact instruments, tunings, model names, frequency bands, and processing settings in a reference are conditional choices. A liked prompt does not establish which of its requests appeared in the recording or which detail the user enjoyed.

## The four audible parts of a note

**Attack** is the start of a sound: abrupt, soft, picked, struck, breathy, bowed, or swelling. **Decay** is what happens after the initial peak. **Sustain** is the level and tone held while the note continues. **Release** is the tail after the note ends. This envelope distinguishes a clicky pluck from a slowly swelling pad even at the same pitch. The [Live 12 manual](https://www.ableton.com/en/live-manual/12/live-instrument-reference/) defines these stages operationally. A [controlled timbre study](https://pmc.ncbi.nlm.nih.gov/articles/PMC5698532/) manipulated attack and release information during source identification, showing that temporal envelope is one contributor to recognizing a sound; it does not reduce all source identity to the envelope alone.

For Style, describe the listener’s experience instead of numbers: “quick attack and short decay,” “rounded onset with a long, airy tail,” “soft swell that blooms after the lead phrase.” A transient can supply rhythm even when the note is harmonically simple. A sustained sound can provide continuity without frequent attacks. The selected envelope should fit the lyric: short plucks may leave consonants exposed; long tails may support held vowels but crowd fast sung syllables if placed in the same range.

**Articulation** concerns how one note connects to the next. Detached notes leave gaps; connected notes form a line. Muted attacks emphasize rhythm over ring. A tremoring or repeated articulation adds activity without changing pitch. Do not infer articulation from source name. “Muted, sharply cut chord strokes” and “slowly connected chord tones” are distinct even if both use the same instrument family.

## Brightness, spectrum, and noise

**Brightness** often refers to stronger upper-frequency content relative to lower content, but it also depends on attack and register. A bright onset with a warm tail differs from a continuously thin tone. **Dark** may mean softened upper partials, a low register, or a recessed mix position; specify which is intended. **Hollow**, **nasal**, **metallic**, **glassy**, **woody**, and **grainy** are useful only when paired with role and envelope. “A short metallic two-note answer” gives more direction than “metallic atmosphere.”

A filter can attenuate parts of a spectrum; a moving filter can make a held sound change color over time. A noise component can add hiss, breath, scrape, or roughness. Modulation can vary pitch, amplitude, or tone periodically or irregularly. The [Live 12 manual](https://www.ableton.com/en/live-manual/12/live-instrument-reference/) describes these mechanisms. In Style, describe the audible motion: “a low sustained tone slowly opens brighter,” “a narrow high note wavers gently,” or “a dry strike carries a brief noise edge.” Avoid device parameters unless a user specifically asks for production settings. Text generation may imitate the result without implementing the mechanism literally.

**Warm**, **thick**, **shimmering**, and **vintage** are underspecified by themselves. Translate them. Warm might mean soft attacks and low-mid weight, or gentle saturation, or muted upper content; choose the intended cause. Thick might mean a doubled line, close chord spacing, heavy bass, or long overlapping releases. Shimmering might mean bright sustained high partials with slow movement. Do not force every sound to share one adjective. Contrast gives hierarchy: a dry attack can sit in front of a long diffuse layer, and a dark bass can support a bright short hook.

## Translate processing into a perceptible job

Choose a target source, an audible change, and a location before naming a treatment. A device list spends characters without establishing what remains clear or what changes. The following are original prompt hypotheses, not promises that Suno will instantiate a particular processor.

| Reference shorthand | Operational choice | Compact candidate wording |
| --- | --- | --- |
| Named electric-piano or organ model | Short rounded chord attack versus a hollow sustained chord; foreground versus backing | “Rounded keyboard stabs answer the lead endings.” |
| Bitcrushed texture | A deliberately coarse digital edge on one fill or hook layer | “Brief coarse digital fills occupy the gaps between clean sung lines.” |
| Saturated texture | A roughened body or compressed attack on a selected source | “The guitar gains a gritty sustained edge on the refrain while the lead stays clear.” |
| Low-pass automation | A specific source becomes duller or brighter across a transition | “The held synth chord gradually opens brighter before the return.” |
| Slap or rhythmic delay | A short echo thickens an attack, or distinct repeats answer a gap | “One dark echo answers the final sung word after the lead releases.” |
| Named plate or hall | Short vocal ambience versus a long distant backing tail | “Close dry lead above distant chords with long quiet decay.” |

Keep a technique label when it concisely names an essential texture; pair it with its source and role. Exact delay fractions or settings belong only when the current brief makes that rhythm decisive. Distortion across the whole recording, simultaneous bright fills under dense sung words, and long echoes on every line are separate design decisions; they do not follow automatically from choosing one processed source. Before a requested complete silence, decide whether effect tails also stop. A cut in note attacks with echoes still ringing is a different event.

## Acoustic, electric, sampled, and synthesized behavior

These source families describe production possibilities, not fixed emotional properties. A physically excited source may show tiny variation from one strike to another; a sample may repeat exactly or be deliberately varied; a synthesized tone can be static or highly modulated. A text prompt should describe what is audible: “slight variation in repeated upper attacks,” “identical crisp low hits,” “sustained tone with slow brightness movement.” It should not use “organic” as a substitute for timing, tone, and dynamics.

For acoustic/electronic coexistence, assign complementary jobs. A picked string can mark the offbeats while a smooth low synth holds the foundation; an acoustic chord can expose the opening while an electronic layer carries the same harmony at the return. Another option gives the acoustic source the hook and uses electronics only for transitions. Choose one relation that can be heard. Do not make both families compete for every chord, attack, and lead answer simply to demonstrate a hybrid. If the lyric is dense, put busy acoustic grain or digital fills in the gaps and keep the central sung melody exposed.

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

**Layer count** is distinct from perceptual density. Two long overlapping sounds can fill more space than five short punctuations. Density rises with overlapping durations, similar registers, repeated attacks, and reverb tails. To protect a vocal, limit concurrency in its register and phrase spaces rather than simply reducing all volume. A low bass, high accent, and midrange lead can coexist more clearly than three simultaneous midrange melodies. This is an arrangement heuristic for choosing intended source positions; it does not establish a rendered result. The songwriter uses only written inputs and never receives any audio.

**Register handoff** is a useful alternative to piling up layers. A high figure can disappear when the lead moves high, then return when the voice descends. A low pad can recede when bass becomes active. “The high pluck answers only in vocal gaps” encodes this as an audible arrangement rule. If the prompt budget is tight, one such interaction outranks a long list of source names.

## Hook carrier, handoff, and doubling

Source hierarchy can change as well as source identity. A bass tone may carry the repeating identity rather than act only as low support; specify its articulation and pitch role, then let drums support or answer it. Do not infer kick alignment from bass distortion. A piano and another melodic source may briefly share foreground during an instrumental passage, then yield to one sung lead. This local equality does not mean every part should be equally prominent throughout.

Likewise, a percussion figure can remain the continuity cue while guitars, electronics or sustained chords change around it. Describe the recurring attack behavior before its exact source if the pattern is the point. A recording credit establishes participation only; it cannot establish source timing, envelope, foreground position or hook ownership. The anonymous production research supplies some documented role decisions and many unresolved ones; new allocations must remain proposals fitted to the finished lyric.

Distinguish three arrangements. A **reply** adds a figure after a lead phrase. A **handoff** gives an established melody to a different source while its first carrier rests. A **double** plays the same melodic contour together with the carrier. Identify the motif by contour or rhythm so recognition survives a timbre change. These options are selectable; the new song does not need all three.

| Choice | Original design move | What stays recognizable |
| --- | --- | --- |
| Reply | “A bowed two-note answer waits until each verse line ends.” | Answer contour and gap placement. |
| Handoff | “The opening plucked figure returns on a soft synth at the lyric's repeated line.” | Figure's rhythm and pitch shape; source changes. |
| Double | “A restrained guitar doubles the held refrain melody, then rests for the next verse.” | Sung hook remains foreground; reinforcement is local. |
| Envelope development | “The same clipped keyboard motif lengthens into ringing notes on the return.” | Carrier and motif remain; note duration changes. |

A wordless processed vocal can occupy the hook or answer role when the brief requests it; keep it distinct from the intelligible sung lead. Source handoff is especially useful when another layer would overload the lead register. Doubling may supply emphasis, but its first statement can remain exposed. State which source yields space rather than asking every layer to be prominent.

## Original prompt fragments and intended behavior

These fragments specify proposed musical behavior; they are not official Suno syntax or claims about generated results. The songwriter never receives, hears, or evaluates any audio.

| Intent | Candidate Style fragment | Intended audible result |
| --- | --- | --- |
| Exposed words | “Clipped midrange chord strokes stop between dense lead phrases.” | Chords leave actual gaps and consonants remain clear. |
| Recognizable opening | “A dry, glassy three-note figure appears before the first vocal and answers later lines.” | Same figure returns after its opening statement. |
| Growing refrain | “Verse uses narrow, short plucks; refrain keeps their figure but lets the notes ring wider and longer.” | Identity persists while duration and image expand. |
| Slow motion inside a held sound | “Soft sustained upper tone gradually brightens without adding new notes.” | Tone evolves while pitch stays stable. |
| Contrasting surfaces | “Rough short chord attacks sit beneath a smooth, airy sustained layer.” | Distinct foreground and background textures. |
| Cleaner lyric space | “Bass and dry pulse stay low; high accents occur only after line endings.” | The lead has an uncluttered middle register. |

## Written source-role audit

Before compilation, inspect the proposed arrangement as text. Does each selected source have a role, register, envelope, and entrance? Do answers wait for completed vocal phrases? Does a handoff retain the motif's contour or rhythm? Are rough textures localized so the intended lead stays clear? A complete cut must state whether sustained notes and effect tails stop too.

Resolve likely conflicts in the design: shorten overlapping chord tails, separate simultaneous melodic roles, move fills into lyric gaps, or develop one existing source rather than adding another layer. These are revisions to an intended arrangement, not diagnoses of generated sound. Source identity, role, and timbre are separate choices; specify only those essential to the current brief. Do not request playback, recordings, timestamps, or heard-result confirmation.


---

<!-- SOURCE: guide/06-vocal-architecture.md -->

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


---

<!-- SOURCE: guide/07-section-form-dynamics.md -->

# 07 — Section form and dynamic arc

## Build from the lyric's events

Form is the audible pattern of entrance, return, contrast, and ending. Read the *finished* lyric before designing it. Mark where new information appears, a phrase repeats, a perspective changes, and the last statement lands. The Style field should specify only the musical changes that make those events legible; the words and useful section headings stay unchanged in Lyrics. [Suno Custom Mode](https://help.suno.com/en/articles/2415873/) provides separate lyric input. Every section cue suggested here is a **prompt hypothesis**, not a guaranteed instruction to the generator. The songwriter works from lyrics and written preferences and never receives, hears, or evaluates any audio.

Do not impose a fixed sequence. Assign each actual section a function—information, anticipation, recognition, reconsideration, or resolution—even when the lyric has no repeated hook.

Separate **existing lyric structure** from **proposed arrangement structure** in the private map. A labeled bridge is an existing section. A planned two-beat instrumental clearing before its first line is an arrangement proposal. A liked reference's drop, spoken intro, or final chorus is not evidence that the new finished lyric contains that section. For unlabeled text, anchor proposals to a specific stanza, repeated phrase, or final sentence. Do not silently add words, repeat a stanza, or invent a refrain to accommodate a favorite arc.

## Dimensions of change

For each lyric section, make a private map. Which source has **focus**? What is the **pulse** and its felt rhythmic weight? How many events sound at once (**density**)? Where do melody and bass sit (**register**)? How long do notes and tails overlap (**sustain**)? Is the image near, distant, narrow, or wide (**space**)? What sound has been withheld or established that the listener can expect next? Choose the two dimensions that matter most. “Build” by itself does not identify a cause.

| Change | Possible audible event | Different from |
| --- | --- | --- |
| Density | A harmony enters behind the lead. | Overall loudness. |
| Activity | More short percussion attacks occur. | Numerical tempo. |
| Register | The lead rises on a repeated word. | Added layers. |
| Width | Background parts spread while lead stays centered. | Vocal distance. |
| Rhythm weight | Fast subdivisions recede while a broad backbeat becomes prominent. | A slower tempo. |
| Silence | A one-beat stop exposes the next entrance. | Gradual thinning. |
| Sustain | Short detached notes become held tones on a return. | Adding another source. |

Experiments link intensity profile with perceived arousal and temporal expectation with tension. Treat level and timing as separate levers, not an emotional formula: [intensity](https://pmc.ncbi.nlm.nih.gov/articles/PMC3080387/), [expectation](https://pmc.ncbi.nlm.nih.gov/articles/PMC11297889/).

## Opening and information

Give the opening one recognizable cue: a short figure, bare vocal, incomplete pulse, sustained chord, or interruption. “Dry voice over a two-note pulse; bass enters with the repeated line” specifies more than “start sparse and build.” If the full arrangement begins immediately, develop through subtraction, distance, or rhythm.

A section carrying new facts needs room for the lead: fewer chord attacks, replies after complete lines, or a stable motif. A forceful beat can leave holes for consonants. If the song is sung, preserve a verse melody while making that space: “single close lead sings a short recurring contour over clipped chords and a steady low pulse.”

**Written audit:** Give the opening one defined cue and place competing roles after completed information-bearing phrases. If the proposed first verse has several foreground parts, remove or relocate one rather than adding another vague “clear vocal” instruction.

## Anticipation and arrival

An anticipation section changes one or two axes to make an arrival apparent. It can raise the lead, increase subdivisions, add backing voices, widen space, change chord duration, or remove a layer just before the return. Ask what the arrival offers that the prior section withholds. A held vocal refrain may follow clipped phrases. A low-end impact may follow a bar with little bass. A lyrical reversal may need a gap before its first word. The [metrical expectation experiment](https://pmc.ncbi.nlm.nih.gov/articles/PMC11297889/) supports a connection between timing and tension; the exact musical effect remains a design hypothesis.

An arrival needs an identity: repeated words, melodic contour, instrumental hook, chord change, or a particular combination of sound sources. It need not be the loudest section. “Short sung verse cells become held lead notes over a broad half-time pattern” gives a contrast between two melodies; “powerful chorus” does not. If the arrival repeats, keep enough of its identity for recognition. A final return can add a harmony, answer, or new bass movement without replacing the hook.

Choose a **cut** or a **build** deliberately. Increasing subdivisions can prepare an arrival without changing metronome tempo. A very short full cut can sharpen the next entrance without needing a long riser. Specify the gap relative to the pulse when its length matters: a tiny interruption, a subdivision, one beat, or a full bar create different expectations. These are alternative decisions, not accumulating requirements. A complete micro-silence also stops sustaining sounds and effect tails; a drum cut with a chord still ringing leaves continuity. If the sung lead must carry the lyric across the gap, call it an accompaniment cut rather than total silence.

**Prompt hypothesis:** “The drums thin before the repeated line; the low end returns as the lead opens into two held notes.” **Written audit:** Anchor the subtraction and return to an actual lyric event. Name what is absent before the arrival and what enters there. If the written arrival assigns several competing new roles, retain only the most useful contrast.

## Contrast, return, and ending

A contrasting section changes perspective while preserving a motif, pulse, harmonic center, or vocal contour. Expose one lead where voices stacked, halve chord attacks, or shift the hook to another source.

For the final return, ask whether the repeated lyric means something different after the intervening line. If it resolves, the voice may firm and support may widen. If it now sounds doubtful, percussion may fall away. A one-time final sentence can be most effective with the arrangement cleared around it. Form follows this song's meaning; the final passage need not always grow.

End with an action: dry stop, held chord after the lead, instrumental reply, fade, or opening texture returned. Name it in Style only if vital.

## Recurrence, surprise and continuity

Do not automatically repeat a one-time disclosure or calm every bridge. A real second verse can change its supporting rhythm while the vocal or instrumental motif remains recognizable. A bridge can sustain urgency and change foreground instead of lowering force; an instrumental continuation can complete the preceding thought without adding lyric. Select this behavior from the supplied structure and current brief, not from an admired song's sequence.

| Existing lyric situation | Original selectable development | Continuity to retain |
| --- | --- | --- |
| Verse information occurs once before a destination | Keep it once; let the instrumental hook extend the completed thought if a passage is wanted | No copied verse, invented refrain or new lyric. |
| Second verse shifts viewpoint | Change accompaniment articulation or reply source beneath a recognizable sung line | Same pitch identity or instrumental motor, rather than wholesale reinvention. |
| Bridge is the most urgent statement | Keep melodic force active; remove one competing layer or transfer the hook's carrier | Its sung mode and rhythmic anchor continue. |
| Repeated question gains a different meaning | Preserve hook recognition while changing duration, support or breath placement | Existing repeated words remain unchanged. |
| Vocal rest follows a completed refrain | Let two instrumental sources exchange or share foreground before the next line | The established motif connects the passage; no obligatory solo category. |

These are proposed arrangements. A creator's description of surprising full-length structure does not supply a transferable section map, and a shortened version is not an independent vote for the full song's form. Do not infer a tempo change from a broadening of accents unless the evidence or current brief makes it clear. In a new grouping contrast, use a motif or source cue to connect the sections and protect the sung phrase.

## Original maps for specific lyric events

These maps are selectable design proposals. Use one only when the stated lyric event exists, then adapt its anchor to the actual words or section name. Each row describes an intended result, not a heard recording. The maps vary density, register, rhythmic weight, sustain, and width without imposing a standard verse/drop/final-chorus sequence.

| Actual lyric event | Original arrangement map | Identity and vocal mode to preserve |
| --- | --- | --- |
| A dense stanza ends before the first repeated declaration | Keep short pitched verse cells over narrow clipped backing; after the completed line, cut all sound for one subdivision; the declaration arrives on a held melodic note with bass and wider chords. | The tiny silence follows a completed sung phrase. The declaration's tune remains recognizable on later returns. |
| A repeated phrase shifts from hesitation to decision | First statement uses a compact sung contour over light upper attacks; after a brief bass withdrawal, its return lands with a broad low pulse and longer chord sustain while subdivisions recede. | A sudden drop means a new rhythmic weight at this lyric event; the same tempo and hook can persist. |
| An existing bridge reveals a quieter perspective | Remove the electronic rhythm bed; a single plucked source takes the established figure, with exposed pitched singing and a narrower image; bring the low anchor back after the bridge's final thought. | A stripped acoustic passage is conditional on this contrast. Removing drums does not convert the lead to speech. |
| A refrain actually returns after a changed perspective | Keep its hook pitches and pulse; add one reinforcing carrier above the lead or a local upper harmony, widen backing, and let chord notes ring longer. | Expand one or two dimensions while the centered sung hook remains the point of recognition. |
| A final unrepeated sentence withdraws from the earlier claim | Reduce from pulse and chords to voice with one sustained low tone; the voice keeps its verse melody and tapers the final held vowel; the low tone releases afterward into silence. | The ending retreats in density and width. No new final chorus, obligatory crescendo, or forced resolution is added. |

One map can be compressed to one relation: “The last verse line finishes before a brief full cut; the repeated declaration returns on held sung notes over broad bass and wider chords.” A different lyric might need only “The bridge stays melodically sung over one plucked figure; backing withdraws from the final sentence.” Keep the changes the lyric can support rather than combining every transition.

**Prompt hypothesis:** “The repeated line returns with its melody intact but only voice and low pulse; the last word ends dry before one instrumental answer.” **Written audit:** Anchor the reduction to the actual repeated line and put the answer after the final sung word. Remove global build language if the intended relation is withdrawal.

## Resolve contradictions before compilation

“Sparse and full” needs a section boundary. “Driving beat throughout” and “total drum dropout” need an explicit exception. “Close lead” and “huge room” can coexist if the room belongs to backing layers. “Gradually louder” and “sudden stop” can coexist if the stop marks the climax. Make the relationship explicit rather than repeating conflicting adjectives.

Draft a section map outside the final field, then retain no more than three high-value relationships. Original compact candidates:

- “Bare lead sings a recurring contour over a muted two-note figure; bass arrives at the first repeated line, and a narrow upper harmony enters only on the final return.”
- “Short pitched verse phrases finish before a one-beat stop; the refrain lands on held melodic notes over a broad half-time pulse.”
- “The second return strips to sung melody and low pulse; the last return restores the hook carrier and wider backing.”

These are components to adapt, not stock templates. If the lyric lacks a repeated section, do not invent one to use a preferred phrase.

## Written section audit

Inspect the private map against the supplied lyric structure. What is the opening cue? What is withheld? Which actual section carries new information? What defines the arrival? What remains recognizable at a return? How does the last sound terminate? Select only answers that justify space in the Style field.

For each proposed change, name its lyric anchor, the source or dimension that changes, and the continuity to retain. A backing reduction must preserve the verse's pitched mode; a full cut must not conflict with a voice or effect tail crossing it. Distinguish density, subdivision, rhythmic weight, register, sustain, and width rather than conflating them with volume. Do not invent a repeated section or silently change the finished words. Audit this intended map from text only; do not request recordings, locate rendered boundaries, assign timestamps, or claim transitions occurred.


---

<!-- SOURCE: guide/08-recording-mix.md -->

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


---

<!-- SOURCE: guide/09-lyric-music-fit.md -->

# 09 — Lyric–music fit

## Analyze words without rewriting them

The Grok lyric generator supplies finished text; this chapter designs its delivery. Words go in Lyrics, decisive production cues in Style. [Suno Custom Mode](https://help.suno.com/en/articles/2415873/) documents the separate lyric field. The wording examples below are **written design hypotheses**. The songwriter never receives, hears, measures, or evaluates any audio.

Inspect the written lyric for syllable density, likely natural stress, complete thoughts, repetition, and turns. Identify meaning-bearing words that need emphasis and phrase boundaries that permit a breath or instrumental reply. Do not request an audio reading.

| Lyric property | Musical choice to consider | Written audit |
| --- | --- | --- |
| Dense new information | Short, mostly syllabic notes over a stable pulse; less overlap. | Does the proposed note duration and accompaniment leave room for key words? |
| A short repeated line | Simple melodic cell, then variation on a later return. | Does the proposed return retain its melodic cell? |
| Consequential word | Longer note, beat accent, or cleared space. | Is the intended emphasis anchored to that exact word? |
| Name or unfamiliar term | One foreground lead, crisp consonants. | Is its first statement assigned one exposed lead? |
| Reversal | Change one musical axis at that exact line. | Is the proposed change anchored to the actual reversal? |

A deliberately breathless or mysterious line may call for a different choice.

## Natural stress and musical accent

Speech stress and musical accent can reinforce or disrupt each other. Accents arise from beat, duration, pitch, attack, or surrounding silence. Studies examined [song-prosody alignment](https://pmc.ncbi.nlm.nih.gov/articles/PMC3225926/) and [sung-word recognition](https://doi.org/10.18061/emr.v9i1.3729). Inspect *important* words rather than scoring every beat in Style. The cited word-recognition material was sung in English; apply its stress findings most directly to English lyrics and analyze other written languages by their own prosody.

“Short sung verse notes follow natural word stress over a recurring contour” gives a governing behavior for a sung song. “The repeated two-word line lands firmly on the beat” names a special case. A deliberate mismatch can make a phrase unstable: “the opening line enters early against a steady pulse, then its answer resolves on the beat.” Avoid blanket “syncopated vocals” if a later claim must sound plain and decisive.

**Written audit:** Match proposed beat emphasis and note duration to important words. Where stress is uncertain from text, avoid over-specific syllable placement. Clarify the intended phrasing or accompaniment without rewriting the finished lyric.

## Density, breath, and melodic space

Syllable density depends on available time. A rapid line can ride a moderate pulse; a brisk track can carry measured vocals. Specify the relation: “quick syllabic sung notes over long held chords.” Dense information can still be melodic; shorten note lengths, repeat a pitch cell, and clear accompaniment without switching to speech. Put a breath or reply after the complete thought, not automatically at every printed line break.

A melisma gives multiple notes to one syllable. It may spotlight a feeling, but it delays the next word. In the tested material of a [sung-word recognition study](https://doi.org/10.18061/emr.v9i1.3729), syllabic settings were more intelligible than melismatic ones. This supports limiting ornate delivery on high-priority words while retaining purposeful vocal runs elsewhere. State a crucial hook simply first; decorate a later repetition or a wordless tail.

**Prompt hypothesis:** “Dense verses use a measured sung melody, mostly one short note per syllable, over sparse chords; instrumental answers wait until complete sentences.” **Written audit:** Place replies after complete sentences and give dense sung notes enough intended phrase space. If rapid phrasing would crowd the thought, moderate *its phrasing* rather than automatically changing the track's tempo.

## Intelligibility is a scene, not a singer command

A word may disappear because consonants blur, voices overlap, bright instruments mask it, or a long run stretches its syllable. An experiment found a modest decline in word recognition with multiple simultaneous singers versus one, particularly for some final consonants; a survey found musicians perceived diction and acoustic environment as important, but did not establish causal effect sizes. See [multi-voice experiment](https://pubmed.ncbi.nlm.nih.gov/27068550/) and [intelligibility survey](https://pubmed.ncbi.nlm.nih.gov/25249987/).

For a first statement of a key word, try one centered lead, clear consonant starts and releases, little ornament, and an accompaniment gap. A repeated phrase may later gain doubles or harmony. For a crucial name, reduce proposed overlapping support or relocate simultaneous instrumental attacks. “Make all lyrics clear” does not identify the cause. Keep the written word and change the audible conditions around it.

## Narrative turn and emotional relation

An arrangement can reinforce or complicate a lyric. Ask what a line changes, then mark it with *one* event: drum dropout, bass shift, closer lead, bare motif, or contrasting instrumental answer.

**Prompt hypothesis:** “The repeated line first rides a warm steady pulse; after the revelation, it returns with bare voice and one low sustained note.” **Written audit:** Keep the repeated words unchanged and make the proposed subtraction explicit. Remove global build wording that conflicts with the bare return. This is a composition proposal based on the lyric's change of meaning, not a rendered finding or formula for emotion.

## Compile Style from the written lyric

The private analysis can be detailed. The final Style field usually needs only one cue for dense text, one for crucial-word clarity, and one for the major turn. For a sung song: “A precise lead sings information-heavy verses on a compact recurring melody over sparse chords; the repeated phrase opens into longer notes, and instruments fall away for the final reversal.” Do not duplicate lyric lines in Style. Use a spoken cue only when the user's intent or performance tags call for it, and name its section.

Before returning Style, verify the text-to-arrangement map: sung verse contour, note density, natural word emphasis, complete-thought gaps, foreground on key words, and one lyric-linked turning event. Preserve the finished text, and avoid claiming its generated delivery is clear, correctly stressed, or emotionally effective. The songwriter audits the proposal only; it does not request song files, perform listening exercises, diagnose generated syllables, or prescribe post-generation audio tests.


---

<!-- SOURCE: guide/10-style-compiler.md -->

# 10. Compile the 1,000-character Style field

## Contract and provenance

This compiler accepts **finished lyrics** from the user's existing lyric generator and the user's written sound wishes. The songwriter works only from text: finished lyrics, the written brief, written preferences, and documented production accounts. It never receives, plays, hears, transcribes, measures, or evaluates audio, whether a reference recording or a generated song. It designs the intended recording and returns one paste-ready Style of Music paragraph; it does not evaluate a Suno result or rewrite the lyrics. The user's observed Style-field target is **1,000 characters**; this is a working constraint supplied by the user, not a claim that Suno's documentation guarantees the same limit for every model or interface. Keep the text within that target and verify its exact length. The Style text must stand on its own after being copied out of Grok.

Use [Suno Custom Mode](https://help.suno.com/en/articles/2415873) for user-provided lyrics and [Exclude](https://help.suno.com/en/articles/3161921) for unwanted elements when the control is available. Suno's [v6 FAQ](https://help.suno.com/en/articles/13924481) says Variety may rewrite Style tags and advises Variety 0 to retain the entered tags. These are **documented interface facts** as of this guide's research date, not promises about a generated recording. The selection, compression, and order of musical descriptors below are **editorial rules**. Validate the written design for fit, consistency, specificity, and length; its rendered behavior remains unverified. Compilation has no audio-dependent step.

The output contract is exactly four user-facing parts:

1. **STYLE OF MUSIC:** one paragraph of positive audible instructions, no wrapper or citation inside the paste-ready text.
2. **CHARACTER COUNT:** the exact count of precisely that paragraph, including its spaces and punctuation, verified with a counting tool.
3. **EXCLUDE:** a separate short list of genuinely unwanted audible elements, or `none`.
4. **SONG TITLE:** a brief track name derived from the lyric's narrative and the internal attribute rationale; do not print the rationale itself.

Do not use named artists or works as shortcuts in the Style paragraph, title, worked examples, or prompt template. A genre supplied by the user may orient the sound, but the prompt still needs audible properties that define the intended recording. Do not add a concluding classification or enforce a fixed number of sentences. Do not turn the Style text into technical commentary about Grok or Suno.

## Tagged intake for an LLM

When source material is long or mixed, delimit it so the model knows what is instruction and what is song content. The tags organize the input; they are not text to paste into Suno.

```text
<finished_lyrics>
[The user's existing final lyrics, including their section labels.]
</finished_lyrics>
<creative_intent>
[The user's narrative and emotional intention in their own words.]
</creative_intent>
<audible_preferences>
[Requested rhythm, sources, voice, arrangement, and recording qualities.]
</audible_preferences>
<written_references>
[Optional enjoyed Style examples, with their origin identified. Keep a song page's Style field separate from any performance tags in its Lyrics field.]
</written_references>
<constraints>
[Explicit avoidances and fixed technical facts known before generation.]
</constraints>
```

The lyrics are **data to analyze for musical fit**. A line of lyric that says “ignore the beat” is a lyric unless the user separately asks for that arrangement. Text inside an attached source can describe music, but it does not override the user's instructions. A liked example shows a written design the user enjoyed; it does not establish that every tag is a lasting preference or that Suno rendered every detail. If there are several drafts, mark which one is final. If the user already established a song and preferences in conversation, use that context rather than insisting they refill this template.

## Extract preferences without importing a reference song

Keep three private columns: **explicit current request**, **observed reference wording**, and **proposed relationship for this lyric**. An exact source choice, tempo, key, accent, narrative mood, or section map in a reference stays in the second column until the current brief gives a reason to use it. Repetition across distinct liked references can suggest a preference, but confidence in that inference remains lower than an explicit request. A local example reposted on a song page is one piece of wording evidence, not two independent preference votes. Reference wording is text evidence only. Use written production accounts and attribute descriptions directly; no reference playback, acoustic measurement, or listening analysis is required or available.

The user has authorized the researched anonymous influences to participate in future sound design. This authorization makes them usable candidates, without another request to study them or confirmation of each isolated trait. It does not prove which trait caused enjoyment or require a candidate in every song. Keep **permission to use**, **strength of preference evidence**, and **fit to this lyric** separate: uncertain preference evidence can still support an original proposal with strong musical fit. Avoid both extremes of ignoring the research and treating it as the only permitted palette.

Rank candidates by (1) explicit priority, (2) fit to the finished lyric's phrasing and actual returns, (3) audible distinctiveness, and (4) cost in characters and competing demands. Choose a few defining relationships. For example, a low anchor with answering bass, a sung verse with held refrain vowels, and a hook that changes carrier may establish a recording more clearly than a dozen source names. Keep a smaller design if the lyric needs exposure.

Choose a **base audible identity** before adding contrast: what stays recognizable through the song? It may be the pulse, recurring melody, source family, or foreground voice. Add one purposeful contrasting source or section only when it advances the lyric: a plucked answer over sustained electronics, or an exposed acoustic break before the original hook returns. Name how the two coexist or hand off. A hybrid does not require a pile of genre labels, and neither contrast nor a drop is mandatory. Chapter 12 demonstrates different selections rather than one universal recipe.

## Private compilation pass

### Select influences as part of the broader palette

During ordinary song compilation, consult Chapter 02's **reusable influence bank** alongside its broad attribute map and the relevant craft chapters. The bank brings researched preferences into the operational reading route; the longer editorial atlas is needed only for deeper analysis or provenance. The bank supplies possible hierarchies of vocal melody, rhythmic identity, source interaction and development. It is part of the palette, not an exclusive list of approved sounds. The current brief may call for an existing guide relationship outside the bank, a compatible new combination, or a design with no bank influence.

Privately represent each candidate as **relationship + source role + real section/event + evidence status + current-brief fit + character cost**. A documented creator choice can suggest a relationship; release metadata cannot establish it, and neither proves the user's reason for liking a recording. A proposal implementing that relationship needs its own label. Keep alternate edits of one production within one evidence family. Do not use anonymous research IDs, bank IDs or profile titles as sound proxies in Style.

Use this selection sequence internally:

1. **Establish what this song needs.** Identify its intended vocal mode, lyric density, recurring thought, strongest turn and ending. Current instructions and fixed constraints take precedence over every historical influence.
2. **Consider different candidate hierarchies.** Compare a fitting bank architecture with a plausible broader-guide or original alternative when the brief leaves room. A vocal-led song, bass-led song and percussion-led song organize the same sources differently; they are not interchangeable adjective sets. Do not ask the user to choose an ID or repeat their references.
3. **Assign influence weight by musical responsibility.** A defining influence shapes the persistent identity; a supporting influence shapes one source relationship or section; a local accent marks one event. These are qualitative internal weights, not percentages or required slots. A candidate can receive no weight when it conflicts with the song. Confirmed user wishes rank above tentative preferences, while strong lyric fit can justify selecting a researched proposal.
4. **Adapt the selected relationships.** Translate each into new pitch behavior, timing, source role and an actual lyric boundary. Import a few useful mechanisms rather than a whole reference arrangement. Preserve an exposed-entry relationship while choosing a new motif; preserve a vocal-gap reply while changing its carrier; preserve a strong return while choosing the dimensions that expand. Do not inherit language, accent, persona, story, exact melody, key or progression.
5. **Resolve competing roles.** If a repeating bass figure and an upper instrumental motor both claim foreground beneath dense words, choose one, alternate them, or make one yield. Two useful influences need an audible reason to coexist. Supporting influence should reinforce the selected identity instead of creating a second incompatible song.
6. **Carry the decisions into the paragraph.** A chosen influence must appear as an audible relationship in Style, not remain merely considered in private reasoning. Preserve its source role and timing when compressing. If none fits, use the better song-specific architecture without forcing a token reference gesture.

For example, a dense verse followed by an existing repeated promise could use a stable percussion identity as its foundation, compact pitched verse cells, and longer refrain vowels as its release. A quiet lyric with no repeated refrain could instead use an exposed sung contour over piano, later allowing an instrumental answer to finish a thought. Both draw from available influence mechanisms; neither requires adding a chorus or averaging all tastes into one sound. These are design proposals, not claims about particular recordings or Suno's eventual result.

Select a hierarchy, such as vocal contour first, bass-led identity, a persistent percussion cue, independent instrumental/voice melodies, or one lyric-earned change in force and duration. These are alternatives, not five mandatory ingredients. Preserve the current brief's positive sung verse behavior and the chosen defining relations before optional texture. The final response remains four fields; evidence labels, research IDs and internal profiles are not additional output.

Perform the following steps internally, then return only the four contracted parts.

**1. Extract the lyric's demands.** Note actual section labels, repeat phrases, fast syllabic runs, exposed names, open vowels, breathing space, and an emotional or narrative turn. Do not infer a complete musical structure from a poem if the sections are unknown; choose a reversible section arc.

**1a. Set vocal mode by section.** Decide whether each actual section calls for pitched singing, rhythmic singing, intentional chant, speech, or a wordless layer. Rap is not a base genre, subgenre, or vocal direction for this project; do not add it to Style. Follow the user's explicit intent and intentional performance tags. Dense narrative words, closeness, softness, precise diction, and a slow pulse do not imply speech. If the song is meant to be sung, reserve a short positive clause for the **verse melody**: a recurring pitched motif or contour and where notes lengthen. Give spoken delivery a named section only when requested. If mode is genuinely unspecified, propose a sung verse for a conventional lyrical song and keep it revisable.

**2. Write a one-sentence sound thesis.** Example: “A clipped low pulse and a small recurring upper motif keep a close lead moving while the refrain broadens into sustained chords.” This sentence is a private design anchor, not necessarily the final Style wording. If the thesis cannot explain the record's identity, the attribute profile is too diffuse.

**3. Choose the defining relations.** Apply the preference ranking and influence selection above, selecting only relations with a job in this song: kick–bass behavior, voice–accompaniment contrast, hook ownership, or a section change tied to the lyric. Consider the bank as well as broader possibilities; do not default to one favorite profile or force a bank quota. Separate source identity from role: an upper string line can answer the singer, double a refrain tune, or sustain harmony; those are different instructions. A source list with no relation is lower value. An emotion word with no audible cause is lower still.

**4. Assign space and time.** If two wishes appear to conflict, name the source or section: a dry close lead against a wide reverberant chord bed; short pitched verse notes opening into held refrain vowels. Resolve one-object, one-time contradictions before writing. The final paragraph cannot rely on hidden reasoning to repair an ambiguous instruction.

**5. Rank details by value per character.** Preserve explicitly requested sounds and decisive relations. For a sung song, protect its positive verse-melody clause before pruning optional texture and finishing detail; a chorus melody alone may leave the verse mode ambiguous. Protect the selected relationship as a whole: retaining “wide synth” while deleting “only after the sung line” loses the timing that kept the words clear. Prefer a concrete compact clause (“short bass notes answer the kick”) over four adjacent descriptors (“driving, energetic, punchy, propulsive”). Add a technical number only if the user supplied it or it uniquely governs the task. Exact key is rarely worth inventing; perceived brightness, chord motion, and voicing can be stated directly. Translate a device name into its perceptible behavior when hardware identity does not matter.

**6. Separate fields.** Finished words and section labels belong in Lyrics. A true prohibition belongs in Exclude when available. The Style text names desired sound. Do not waste its limited characters repeating the chorus, explaining the task, attaching source citations, or writing negative clauses that can live in Exclude. A positive alternative may still be useful: “one close lead” is more constructive than only “no choir.”

**7. Write from macro to micro.** A practical order is pulse and low-end relation; harmonic and hook behavior; voice and section arc; recording image. This is a reading order, not a required sentence structure. Move the user's most important attribute earlier if needed. Keep the text as a coherent paragraph: sources do things, sections change, and the recording has foreground and background.

Before counting, audit the vocal clause. For sung intent, closeness, diction, and intimacy do not establish a sung verse. State that the verse is sung and give its pitch behavior. For an intentional sung/spoken mix, label the spoken section and the return to singing. Do not use `EXCLUDE` as the only means of securing a sung lead; the positive Style direction carries the design.

Audit the rest of the paragraph for **contradiction, overdetermination, and relevance**. Are width, silence, attack, and sustain assigned to sources and moments? An all-sound cut conflicts with ringing delay unless its tails also stop; a sparse verse conflicts with several continuous foreground hooks. Does every technical detail change a choice this lyric needs? Remove unsupported tuning, device inventories, accents, and exact timing that merely imitate the reference. Check that proposed sections correspond to the finished lyric; describe a change at an actual repeated line if no formal section label exists. One decisive contrast can be enough.

Audit influence use as well: did the selected relationship survive into the text with a source, timing and purpose? Did a supporting influence accidentally displace the current brief's defining sound? Would the paragraph still make sense without any bank ID, source title or evidence note? Avoid repeating the same architecture across successive songs merely because it was selected previously; preserve continuity only when the current brief calls for it. A genuinely fitting recurring relationship is allowed, and novelty alone is not a reason to change it.

**8. Count, prune, and recount.** Count the exact final Style paragraph only. Remove duplicates, guessed numbers, low-priority finishing detail, and repeated mood words in that order. Preserve the central relation. Recount after every edit. Do not claim a verified count from mental estimation.

**9. Check specificity internally.** Check which intended event makes the most important instruction concrete in the written design. If the Style text names no clear source, behavior, timing, or relationship, it is too vague. Use Chapter 11's written audit when needed. Return only the four fields; do not add an audio evaluation, listening task, result claim, or printed rationale.

## Count the exact pasted text

The number reported must exclude the `STYLE OF MUSIC` label, quotation marks added for presentation, Markdown code fences, and any extra newline after the paragraph. It must include punctuation and spaces *inside* the paragraph. A local script can count it reliably before publication or when Grok has code execution. For example, with the exact Style text saved as a UTF-8 file and **no trailing newline**:

```python
from pathlib import Path
style = Path("style.txt").read_text(encoding="utf-8")
print("Unicode code points:", len(style))
print("UTF-16 code units:", len(style.encode("utf-16-le")) // 2)
```

These two measures differ for some symbols. The Suno interface may count differently from either and may change over time; the guide has not verified its implementation. Avoid ornamental symbols and keep a buffer. In an environment with JavaScript, `Array.from(style).length` counts Unicode code points while `style.length` counts UTF-16 code units. The final paste into Suno is the authoritative acceptance check. Use a counting tool for the required exact count; if none is available, say the count cannot be verified rather than inventing a number.

The count should be performed on the **final** text. Editing after counting invalidates it. If a pasted prompt is rejected, shorten the paragraph rather than asserting that Suno is wrong; save the rejected text and the interface message as test evidence. Maintain the user's observed 1,000-character target unless the user changes the project constraint.


---

<!-- SOURCE: guide/11-written-design-audit.md -->

# 11. Written design audit

The songwriter receives finished lyrics, a written brief, written musical preferences and documented production descriptions. It never receives, hears, plays, measures or evaluates any audio: reference recordings, existing tracks, voice recordings and generated songs are all outside this workflow. The checks here concern the text of the proposed design, not whether a recording achieves it.

## Check the available premises

Use the current brief and conversation context. Treat an influence as an available design option, with the open palette supporting other sounds and original combinations. A creator's written account may support a reported production choice; contributor credits establish participation only. Do not invent a measured BPM, note range, chord map, stereo width or effect setting from a title, credit or category.

If the user voluntarily provides written feedback, distinguish that report from your own design reasoning. You still have no audio access. Do not request recordings, uploads, playback links or voice samples to complete the Style task. Written feedback is optional and is never a required next stage.

## Audit musical relationships in the text

| Written check | Question about the proposed instructions |
| --- | --- |
| Lyric structure | Does each named section or repeated phrase actually exist in the finished lyric, or is an arrangement proposal explicitly identified? |
| Vocal mode | For intended singing, does the verse have definite pitched behavior before intimacy, diction or texture? |
| Phrase fit | Are dense words assigned suitable note lengths and complete-thought breathing spaces without rewriting them? |
| Pulse | Are main beat, subdivision and felt weight distinguished where their relationship matters? |
| Low end | Is bass supporting, replying to or leading the groove, and does the kick have a compatible job? |
| Harmony | Are chord vocabulary, chord-change rate and note articulation separate choices rather than redundant adjectives? |
| Hook | Is the recurring behavior assigned to a carrier, a location and a return? |
| Source hierarchy | Do replies, countermelodies and background layers leave room for the specified lead role? |
| Development | Does the contrast change a clear dimension while retaining the song's identity? |
| Recording image | Are dryness, width, depth, roughness and duration assigned to particular sources and moments? |
| Cuts | Does a requested complete cut also stop tails, or does the text clearly leave a voice or sustaining layer continuous? |
| Ending | Does the endpoint follow the actual final thought instead of inserting an obligatory final refrain? |

These questions detect contradictions or omissions in the written plan. They do not certify intelligibility, musical quality or obedience in a generated recording.

## Revise the wording before counting

Replace a vague adjective with a source relationship when it materially clarifies the design. Scope apparent conflicts: short dry lead versus long distant backing tails; narrow verse chords versus wider refrain support. Select one dominant hook when several parts claim foreground at the same moment. Keep a larger arrangement when its roles are compatible and the brief wants it.

Retain explicit requested qualities and the few relationships defining this song. For a sung song, keep the pitched verse clause during compression. The influence bank has no mandatory profile or quota. A small design can be complete, and another sound can be preferable to a bank option. Do not add a learned gesture solely to demonstrate palette use.

## Verify the response contract

1. **STYLE OF MUSIC:** one self-contained positive paragraph, with no artist/work shortcuts, regional labels, research IDs, citations or instructions to the model inside the paste-ready sound description.
2. **CHARACTER COUNT:** tool-count the exact final paragraph, including internal spaces and punctuation but excluding labels, fences and trailing newline. Keep it at or below the user's observed 1,000-character target.
3. **EXCLUDE:** only justified unwanted sound elements, separately, or `none`.
4. **SONG TITLE:** one brief name derived from the lyric and internal attribute rationale. Do not print the rationale.

Finished lyrics stay unchanged. Rap remains excluded from the project's genre, subgenre, tag and vocal-direction choices. Do not add an audio task, scorecard, predicted listening result, review of a generated take or fifth field. Once the written design, exact count and four-field structure are checked, return the response.


---

<!-- SOURCE: guide/12-worked-cases.md -->

# 12. Attribute-only worked cases

These original synthetic briefs illustrate choices available for new finished lyrics. They combine general arrangement vocabulary with selected relationships from the liked Style examples and the anonymous preference atlas; they do not reproduce a reference song's story, genre list, persona, gear, or full arrangement. The cases select different mechanisms rather than establish a default sound. A real song's finished words and explicit brief decide which mechanism belongs. Evaluate compatible atlas relationships as real candidates, then make selected influence audible in source roles, melody, or section behavior. The atlas contributes to a broad palette: an explicit brief can favor another design, and a reference-derived move can be adapted rather than adopted as a complete sound. Every Style paragraph describes an intended design whose rendered behavior is unverified. The songwriter uses only finished lyrics, written preferences, and written production descriptions; it never receives, plays, hears, measures, or evaluates reference or generated audio.

The architecture notes and intended-design summaries are teaching material outside the songwriter's response. They explain the written arrangement choices and prescribe no listening or generated-file analysis. Each demonstrated response contains exactly four labeled fields. Counts were calculated from the final single Style paragraph, including internal spaces and punctuation and excluding labels, code fences, and trailing newlines. Each worked Style paragraph is exactly 1,000 characters inside its own fenced `text` block. Counts refer to the paragraph alone, excluding the surrounding fences and newline. These are full-budget teaching examples; future song prompts may be shorter when that better serves the brief, and retain the existing 1,000-character ceiling. The title expresses the synthetic brief and its internal attribute rationale; that rationale is not a fifth output field. For actual songs, derive the title from the user's finished lyric and selected relationships.

## Case A: motion with a light, open refrain

**Brief.** Moderately dense verses move from hesitation to confidence. A short repeated phrase should open outward; the lead must stay clear.

**Influence selection.** Adapt the exposed melodic-entry idea to the actual opening line, then support that same identity with a pulse. Do not import a high register, extra vocal layers, or a contrasting bridge merely because other examples contain them.

**Chosen relationships.** Bass supports kick arrivals and replies in their gaps. A two-note hook waits for the words; refrain chord length and width supply the lift.

**STYLE OF MUSIC**

```text
Begin with the opening line sung alone on a clear stepwise motif. A brisk straight pulse enters with firm kick and snare, fine high percussion, and short tuneful bass notes that meet the kick then answer its gaps. Verses use clipped low-mid chords, leaving space around the lead; a bright two-note synth figure replies after each line. One clear midrange lead sings a recurring stepwise verse tune with crisp consonants, then opens into longer vowels at the refrain. There the chords lengthen and spread wide while the bass sustains more fully. Add restrained upper harmonies only on the final return. Let the second verse retain the opening motif while the bass changes its last reply. Place a small percussion pickup after a complete thought, then settle into the refrain. Give its first sung note a clear entrance and keep the accents behind the held vowels. Keep the lead close and dry, drums punchy, and the wider backing softly reverberant; end with the two-note figure and a short fading tail.
```

**CHARACTER COUNT:** 1000

**EXCLUDE:** none

**SONG TITLE:** Room to Move

**Intended design.** The answer figure should occupy word gaps and the refrain should widen around a consistently near lead.

## Case B: a private admission in an empty room

**Brief.** Short, sparse verses move from admission to a calm promise. The brief asks for a quiet near voice and a distant instrumental answer, without a drum-led pulse.

**Influence selection.** Use restrained but definite sung movement and earned longer vowels from the palette. The current request for drum-free exposure takes priority over references with active rhythm or full-band power.

**Chosen relationships.** A compact verse tune anchors the words. Piano carries harmonic time; a remote wind tone answers rather than competes. The final return grows through vowel length, not louder percussion.

**STYLE OF MUSIC**

```text
One close lower-midrange lead sings the verses on a recurring three-note contour, holding the last stressed vowel of each short line. Widely spaced piano chords move slowly and leave the pauses exposed. A distant muted trumpet gives a single soft answer after the second line of each verse; keep its long decay behind the voice. At the repeated promise, the vocal contour rises one step and the vowels lengthen while the piano adds an upper note. On the final return add one quiet harmony only at line endings. Let each piano attack settle before each sung phrase, with notes supporting the thought and upper notes opening its space. Keep the trumpet answers shorter than the vocal phrases. Give the promise a calm, connected melodic release; on its final statement, let the piano become lighter as the lead completes the same contour with a more even sustained tone. Keep the vocal nearly dry and the piano room large but quiet; finish with the sung lead alone, followed by the last piano resonance.
```

**CHARACTER COUNT:** 1000

**EXCLUDE:** drum-led beat

**SONG TITLE:** The Room Keeps Quiet

**Intended design.** The vocal should remain distinctly pitched and near, while the instrumental replies suggest greater distance. The last return should feel steadier through phrasing.

## Case C: dense words with a physical guitar edge

**Brief.** Fast, consonant-heavy verses describe pressure. The finished lyric has a shorter repeated line for release. The brief wants guitars and live drums, with fully sung words.

**Influence selection.** Adapt dense melodic articulation opening into a broader refrain, plus coordinated band attacks. This selects useful contrast without importing a particular vocal identity or treating speed as speech.

**Chosen relationships.** Defined drum and bass attacks carry motion. A small verse pitch pattern accommodates dense syllables; guitar only occupies its gaps, then reinforces the broader refrain tune.

**STYLE OF MUSIC**

```text
Fast-feeling straight pulse with hard kick and snare arrivals, short closed high percussion, and clipped bass notes locked to the downbeats. A narrow recurring verse melody carries the dense words on definite sung pitches, with sharp consonants and brief held phrase endings. Low rough-edged guitar chords strike between the lines over a small chord cycle. The simpler refrain opens into wider melodic intervals and sustained vowels; a higher guitar doubles its final two notes, while the rhythm guitars spread and the bass notes lengthen. Keep the lead forward and centered, drum attacks distinct, and guitar roughness behind the words. Let the bass follow chord roots at phrase landings and connect them with an upward reply in the gaps. Keep cymbal activity beneath rapid syllables, with a single firmer crash marking the refrain entry. The later verse restores clipped attacks and the same melodic cell before its next broader return. End together on the final sung word with a short chord decay.
```

**CHARACTER COUNT:** 1000

**EXCLUDE:** none

**SONG TITLE:** Pressure Gives Way

**Intended design.** The verse should stay melodic despite its rapid articulation, with refrain release supplied by interval size, sustain, and hook doubling.

## Case D: a cut that makes the return count

**Brief.** The lyric has two compact verses, a repeated release phrase, and an explicitly labeled break. The brief asks for an electronic arrival after a very short all-sound gap.

**Influence selection.** The explicit electronic-cut brief activates the earlier written examples' cut-and-return relationship. Vocal force and layered harmony ideas from the wider atlas remain optional; the cut does not require every admired production move.

**Chosen relationships.** Keep the pulse rate stable while felt weight changes. Low end yields at the kick attack; the cut stops both sources and tails. Restore the same hook with a larger carrier.

**STYLE OF MUSIC**

```text
A compact sung verse motif sits over broad backbeat accents, clipped chord stabs, and a low synth note that dips briefly at each kick attack. Keep the voice clean and centered, with phrase endings held on definite pitches. During the labeled break, let high percussion become finer while a filtered version of the hook rises. Cut every source and effect tail for half a beat immediately before the release phrase. Return on a regular four-beat kick pattern with the same hook an octave higher and doubled by a bright sustained synth; the singer opens the refrain into longer notes. Let the low synth retain a simple pitch center while upper stabs leave room for the verse contour. Keep the rising hook recognizable as its brightness changes. After the first return, restore the lean verse pattern, then let the next release extend the hook ending rather than adding a new competing melody. Keep bass weight compact, upper chords wide, and rough digital fills confined to the gaps between vocal lines.
```

**CHARACTER COUNT:** 1000

**EXCLUDE:** none

**SONG TITLE:** Half a Beat of Air

**Intended design.** The unchanged hook should make the return recognizable, while the short total cut and changed accent weight should mark its arrival. The written design requests total silence at that boundary; its rendered execution is unverified.

## Case E: acoustic grain inside an electronic pulse

**Brief.** A lyric about gradual reconnection alternates measured verses with a welcoming repeated refrain. The brief wants plucked acoustic detail and electronic support to coexist throughout.

**Influence selection.** Adapt complementary acoustic attacks and electronic sustain, then choose a gap-only reply. Preserve the requested continuous coexistence rather than turning contrast into an unrelated inserted section.

**Chosen relationships.** Assign different roles rather than duplicate a source inventory: plucks mark offbeats, electronics sustain harmony, and bass fills open spaces. Refrain width changes without replacing the acoustic identity.

**STYLE OF MUSIC**

```text
Warm plucked acoustic guitar marks the offbeats while a soft electronic chord bed sustains beneath it. Use an even moderate pulse, short low drum attacks, and rounded bass replies only in the guitar rests. A clear lead sings a small rising-and-falling verse tune with natural word stress and slightly lengthened line endings. The refrain carries the same contour higher, holding its opening vowel as the electronic chords widen; the guitar keeps its dry rhythmic role. Let a bright filtered synth answer the refrain in the vocal gap, then disappear for the next verse. Keep acoustic pick detail near, sustained electronics farther back, and the voice distinct at the center. Keep the electronic bed smooth between chord changes while picked notes give each bar its tactile edge. Let bass finish its reply before the next drum strike. On the later verse, narrow the chord spacing again and preserve the guitar pattern, so the returning refrain has room to expand. Finish on guitar and one sung phrase.
```

**CHARACTER COUNT:** 1000

**EXCLUDE:** none

**SONG TITLE:** Thread by Thread

**Intended design.** Plucked attacks and sustained harmony should read as complementary jobs. The refrain should broaden while the guitar keeps the song recognizable.

## Case F: one hook passed between sources

**Brief.** The lyric has an opening memory, two sung verses, a recurring line of recognition, and a labeled instrumental passage after the later return. The brief asks for a memorable small hook that changes carrier as recognition develops.

**Influence selection.** Combine carrier handoff with a locally shared instrumental foreground. The actual vocal rest makes the second relationship useful; do not require coequal sources while dense words are being sung.

**Chosen relationships.** Hold the motif constant while its carrier changes. The first source introduces it, a second replies to the voice, and both briefly double the later refrain; keep continuous counterlines out of the verse.

**STYLE OF MUSIC**

```text
Begin with a small piano motif, then leave it incomplete when the lead enters. The verses are softly sung on a compact descending contour, with held vowels at each line ending over lightly brushed percussion and a slowly moving bass. A bowed string completes the piano motif only after the second line, keeping the voice in the foreground. At the recognition refrain, the lead turns the contour upward and the piano quietly doubles its hook; on the later return the string joins that same melody an octave above. Keep verse harmony spare, broaden the sustained chords only at the refrain, and give the string a longer room tail than the dry piano attacks. In the labeled instrumental passage, piano and string exchange the motif as equal foreground voices. Let piano attacks carry the motif rhythm while the string connects its longer notes. At each sung entry, the instrumental phrase releases its foreground role. Keep bass central and restrained beneath the shared passage. Close with piano alone.
```

**CHARACTER COUNT:** 1000

**EXCLUDE:** none

**SONG TITLE:** Recognize the Light

**Intended design.** The hook should remain identifiable through piano, string, and vocal roles. The later doubling should communicate recognition without adding a competing tune.

## Case G: a steady anchor with moving replies

**Brief.** The finished verses describe ordinary shared work and the refrain makes a modest promise. The brief wants a relaxed groove, strong word clarity, and a small rise in physical energy.

**Influence selection.** Promote bass from low support to a recognizable melodic identity, adapting the atlas's bass-led option to this relaxed brief. Keep the established broad accents rather than importing abrasive texture or a faster band feel.

**Chosen relationships.** Keep low accents dependable and let a recurring bass contour create movement around them. Change percussion articulation at the refrain instead of speeding the song; scope projected singing and extra width there.

**STYLE OF MUSIC**

```text
A rounded four-note bass motif carries recognition, meeting two broad low accents per bar and turning upward in their gaps. Let the drums support this recurring contour. Dry guitar chops sit with the snare, with light unequal high subdivisions and brushed percussion in the verses. One low-mid lead sings a recurring four-note verse tune, placing each syllable on a clear pitch and gently sustaining the phrase ends. A bright sliding string answers only in the pauses. When the promise returns, switch the brushes to firmer stick attacks, widen the soft acoustic chord bed, and let the lead project a longer rising refrain melody. Keep voice and bass close, the answers slightly farther away, and the short vocal room unobtrusive. Keep the bass notes distinct, with a round attack and short tail. Let the guitar rest briefly after each completed thought; the string reply then traces a small descending shape above the returning low motif. End with the string's brief answer after the last sung line.
```

**CHARACTER COUNT:** 1000

**EXCLUDE:** none

**SONG TITLE:** The Work We Share

**Intended design.** The anchored groove should feel dependable, while replies and the brush-to-stick change supply movement and refrain lift without a tempo change.

## Case H: a persistent tone and a quiet withdrawal

**Brief.** A lyric moves from urgency toward acceptance, with a short recurring phrase and a final verse already present in the finished text. The brief wants tension to diminish without inventing a triumphant final chorus.

**Influence selection.** Adapt continuity through source development and a late subtraction. The acceptance lyric does not need a triumphant high refrain, maximal vocal force, or a new section.

**Chosen relationships.** Preserve one source identity while changing its envelope and register. Reduce rhythmic weight and width for the final verse; retain sung pitch after the backing thins.

**STYLE OF MUSIC**

```text
A dark sustained synth tone sits behind dry drum strikes and a short repeating bass figure. The lead sings the verses on a restrained ascending melody, with clipped syllabic notes settling into a held vowel at each phrase end. At the recurring acceptance line, the same synth rises in register, softens its attack, and spreads into a quiet chord; the vocal repeats its melody with longer notes. Give the earlier instrumental gap one brief saturated burst, then restore the clean lead foreground. For the final verse, withdraw bass and drums, narrow the synth, and shorten its decay while the voice keeps its pitched contour. Keep the earlier bass figure compact, letting its last note support the sung phrase ending. Give the acceptance line a warmer upper chord color while the main rhythm stays steady. The final verse keeps the same melodic destination with less force, and its word endings release gently into open space. Let the last sung note finish before the remaining tone dies into silence.
```

**CHARACTER COUNT:** 1000

**EXCLUDE:** none

**SONG TITLE:** What Remains Near

**Intended design.** The recurring source should change character without losing identity. The final verse should remain sung while the accompaniment releases its weight.

## Case I: a high melody with independent support

**Brief.** The finished lyric has two verses, a repeated declaration, and a labeled instrumental pause. The user wants a sustained high lead, a low supporting vocal layer, and continuous rhythmic motion without a crowded refrain.

**Influence selection.** Combine the atlas's low harmony beneath a high lead with a persistent percussion identity. Adapt the independent counterline to word gaps; do not add a full vocal choir or make every source double the melody.

**Chosen relationships.** Keep one small percussion figure through changes in source hierarchy. Low harmony supports held refrain vowels; an upper instrumental answer stays separate from the sung tune. The actual instrumental pause lets that answer briefly lead.

**STYLE OF MUSIC**

```text
A repeating dry percussion figure and short rounded bass establish a steady moderate pulse. One clear upper-register lead sings an arching verse tune, placing short notes on dense words and holding each complete thought's last vowel. Piano gives spaced chord attacks below the lead. At the declaration, keep the percussion figure while the vocal notes lengthen; add one low held harmony behind the lead and a thin bowed counterline only after the words release. The counterline follows its own falling shape rather than doubling the singer. In the labeled instrumental pause it takes the foreground, then yields to the next sung entry. Keep lead and percussion near, the low harmony centered and quiet, and strings farther back in a wider room. Keep bass on the main arrivals while quiet high ticks connect them. Let the low harmony move slowly beneath held vowels, leaving the verse single. Give the later declaration a wider piano voicing and longer lead notes. End on the exposed sung declaration.
```

**CHARACTER COUNT:** 1000

**EXCLUDE:** none

**SONG TITLE:** A Line Held Open

**Intended design.** Rhythmic continuity should connect the sections while the refrain gains sustain and lower vocal support. The instrumental counterline should remain independent without obscuring words.

## Case J: another design chosen by the current brief

**Brief.** The finished lyric is one continuous stanza with no repeated refrain. The user explicitly asks for a quiet triple pulse, plucked harp, one softly sung lead, no drums, and a gently unsettled ending.

**Influence selection.** The broad guide supplies this design. Evaluate the reference palette, but omit its exposed-opening lift, band momentum, bass identity, and added vocal layers because they do not serve this request. A soft near voice remains clearly pitched; that is the sung-song requirement, not evidence of a particular stylistic influence.

**Chosen relationships.** Harp establishes three gently spaced beats while the voice phrases across them. One held upper chord tone keeps the last line unresolved. No new refrain, break, or widening arrival is invented.

**STYLE OF MUSIC**

```text
Soft plucked harp marks three evenly spaced beats, with short low notes beneath a slowly changing upper chord tone. One near lower-midrange lead sings the continuous stanza on a gentle falling-and-rising melody; let each full thought cross the beat naturally and finish on a clearly held vowel. Keep the harp pattern quiet under dense words, answering only after phrase endings. In the last line, sustain the upper chord tone while the low harp notes withdraw, leaving the sung melody just above an unsettled harmony. Use one centered voice, fine pluck detail, and a small quiet room with short tails. Let the plucks vary gently in strength across the three beats, with the first giving weight and the others leaving space for the line. Keep chord changes slow enough for the melody to cross them naturally. Give each thought a soft onset, and place brief harp replies above the low pattern so the middle register remains open for the words. Finish after the final sung vowel with one soft harp note.
```

**CHARACTER COUNT:** 1000

**EXCLUDE:** drums, backing vocals

**SONG TITLE:** Three Quiet Steps

**Intended design.** The triple pulse should support a continuous melodic stanza without adding a refrain. The unresolved upper tone should carry the ending's uncertainty within the requested small arrangement.

## How to select a case

Evaluate both the anonymous preference palette and other guide options against the current lyric. Select relationships that define this song rather than the nearest bundle of adjectives. When a preference-derived move wins, express its behavior directly in Style; merely mentioning it in private notes does not make it influence the design. Keep its intended role while adapting source, intensity, or timing to this brief. Cases A and G both emphasize groove but give bass and percussion different jobs. Cases B and H both withdraw backing but differ in depth and sustained-source development. Cases C and F expand a hook by doubling it, while D changes its register after a cut. Case E keeps two source families present together instead of inserting a separate contrast section. Case I combines layered vocal support with a continuing rhythmic cue; Case J shows an explicit brief selecting another part of the broader palette. Cases A, F, and G visibly adapt exposed melody, shared instrumental foreground, and bass identity. Each sung case defines verse pitch before relying on diction or mix distance. These are selection demonstrations, not a rotation Grok must cycle through.

The exact sources, pulse, cuts, and section order remain choices. A poem with no refrain does not acquire one because these examples contain refrains. EXCLUDE stays separate and can be `none`; the positive Style establishes the song. The songwriter works from lyrics and written preferences only. Reference audio and generated song files are never inputs, and completion does not depend on playback, listening observations, or measured sound. These cases demonstrate written design choices, not proven results.
