---
chapter_id: "00"
retrieval_tags: [index, routing, scope, evidence]
use_when: "Read at the start of every song-style task."
output_influence: routing
---

# Suno sound-attribute guide: retrieval index

**Status:** researched chapter draft. **Purpose:** turn the user's finished lyrics and desired sound into a concise, testable Suno Style of Music entry. The existing lyric generator remains responsible for the words. The guide is organized by audible decisions.

**Workflow boundary:** Grok writes the Style prompt before Suno generation from lyrics and written preferences. It will never receive or hear generated song files. Any listening, result scoring, or revision after generation mentioned in these chapters is a separate task for the user or another actual listener; it is never a required songwriter step.

## LLM reading route

1. Read this index, Chapter 01 for current interface behavior, Chapter 02 for the attribute map, and Chapter 10 for the output contract.
2. Inspect the finished lyrics and the conversation's musical preferences. Use Chapter 02's reusable influence bank alongside the wider guide as an open palette for optimization. Choose, adapt or develop relationships that make this song more specific; another sound or original combination remains available when it fits the brief. Read Chapter 06 for every vocal song to decide vocal mode by section; read Chapter 09 when text density or narrative affects phrasing. Retrieve the other focused chapters for the axes that determine this song. Do not retrieve Chapter 11 for the songwriter's Style task: it belongs to the user's separate listening stage. Do not assume a chapter was read merely because its filename appears here.
3. Keep the user's explicit wishes separate from your own proposal. The songwriter never receives generated song files and cannot report heard results.
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
| 11. Human listening and revision | User's separate evaluation after generation; not a songwriter input | `11-listening-tests.md` |
| 12. Worked cases | Seeing original briefs, selected attributes, and compact Style examples | `12-worked-cases.md` |

## Evidence labels

- **Documented interface fact:** a current first-party Suno page supports the statement. Recheck after a product update.
- **Musical principle:** an account of how audible features relate, with a technical or research source where a nontrivial claim warrants one.
- **Documented production account:** a creator or performer reports a composition, arrangement or delivery decision. This supports the reported choice, not our independent listening, a measured signal property, or the user's reason for liking it. Contributor credits establish participation, not audible role or mix position.
- **Prompt hypothesis:** a proposed wording or interaction in Suno that has not yet been tested by generating and listening.
- **Observed result:** a finding logged by the user or another actual listener after generation. The songwriter cannot produce this evidence and must not claim it.

These labels prevent the guide from confusing an available control with guaranteed obedience. They also keep research support tied to the relevant chapter instead of making a source list into a style recipe.

## Scope and defaults

Use finished lyrics; do not silently rewrite them. Do not use named artists or works as shortcuts in output prompts or examples. There is no fixed base-genre catalog in this guide: Chapter 02 maps audible attributes, while user-supplied genres and songs are references for a particular request. If the user supplies a genre or other reference, extract the requested audible traits and give those traits priority over the label. Do not introduce rap as a genre, subgenre, or vocal direction. Specific beat, vocal, source, and mix characteristics make the direction usable.

Exact tempo and key are optional. Do not invent them to look precise. Positive energy, electronic motion, and economical harmony are recurring user interests, not universal requirements for every song. Let the current lyric and explicit brief decide.

The chapter files are the operative guide. The older `RESEARCH_BLUEPRINT.md` documents the plan that led here; `GROK_RUNBLOCK_DRAFT.md` is a prototype. Keep this index and the short project instruction in sync when the chapter guide changes.
