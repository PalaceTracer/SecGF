---
chapter_id: "02"
retrieval_tags: [attribute-map, audible-definition, compatibility, priority, contradiction, uncertainty, cut, envelope, hook-handoff, source-role, section-scope, detailed-profile, evidence-status, influence-bank, profile-selection, preference-transfer]
use_when: "Read before choosing attributes, selecting reference-derived influences, or resolving conflicting musical wishes."
output_influence: style
---

# 02. Attribute vocabulary, relationships, and decisions

## Role of this chapter

This chapter is the navigation system for a finished song brief. It converts wishes into things a listener could identify in a recording. The lyric text comes from the existing lyric workflow; the task here is to design the sounding performance and arrangement. A word such as *warm*, *driving*, *intimate*, or *large* is useful only after it is translated into a cause: note length, rhythmic placement, source tone, vocal distance, density, or a change between sections. No single mood word describes all those causes.

An **attribute** is a variable with at least two audible values. A **role** states what a sound does in the arrangement. A **relationship** states how two roles interact. A **section instruction** states when an attribute changes. An **intended observation** names what the user could listen for afterward; it is a private design aid, never an extra songwriter output field or a heard-result claim. This distinction prevents a Style field from becoming an inventory of attractive adjectives.

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

Rank each candidate by its fit to a concrete lyric event, its contribution to the song's identity, and the characters needed to state it clearly. Keep a few relationships that explain the whole arrangement, then assign them to sources and real sections. A base sound can be defined by a stable pulse, harmonic loop, lead melody, and a small support bed; one contrasting source or section can change color without accumulating genre tags. If the guide proposes a new break or instrumental passage, distinguish that proposal from a section already written in the finished lyric. The songwriter designs from text and never accesses generation files.

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

For intended sung songs every selected architecture retains explicit pitched verse behavior. Speech, whisper, chant or shout remains available only within the project's existing section-specific permission rules; rap is excluded. No profile requires a recorded voice, access to generated song files or an audio evaluation by Grok. Return exactly **STYLE OF MUSIC**, **CHARACTER COUNT**, **EXCLUDE**, and **SONG TITLE**; the exact final positive Style paragraph remains within the user's observed 1,000-character target.

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

**Kick × bass.** The two can start together or answer each other. A held bass can bridge short kicks; clipped offbeat notes can move between them. “Heavy bass and hard kick” leaves the relation vague. State onset and duration: “short bass notes mirror the opening kick, then move between kicks in the refrain.” The user can later check both patterns in a generated result.

**Harmony × lyric density.** Frequent chord changes, moving inner parts, and long tails occupy attention. Dense text may need a smaller repeated chord set or quieter sustained voicings; sparse text can allow more motion. If words should be submerged, state that deliberately.

**Melody × hook ownership.** An instrumental figure can prepare, answer, or compete with a vocal phrase. Place it in gaps after a fast sung hook; a sustained vocal may leave room for a moving countermelody. State who carries the motif and when the other part yields.

**Voice × arrangement.** A near, breathy lead may need a lean bed; a projected refrain can take wider layers and accents. Backing voices can enlarge a refrain but mask dense words. Specify where they enter and whether they double, harmonize, or answer the lead.

**Section arc × invariants.** Keep a bass pattern, motif, or lead timbre recognizable across contrasting sections. Choose one identity cue to persist and one major dimension to change. A refrain can lift through register, density, rhythm, harmony, or voices without increasing all five.

**Recording space × role.** A close dry lead can stand before a wide reverberant bed. “Dry and reverberant” conflicts only when both modify the same source at the same time. Assign each quality to a source or section.

**Brightness × emotion.** High-frequency energy, upper register, forceful attacks, lyrical hope, and cheerful delivery are different variables. Translate the desired feeling into movement, voice, harmony, and texture; the user may judge the generated combination later.

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
