---
chapter_id: "01"
retrieval_tags: [intake, Suno Custom, Lyrics, Style, Exclude, sliders, model, evidence]
use_when: "Read before compiling any Style field or choosing how to test it."
output_influence: style
---

# 01. Purpose and current creation interface

## The job that begins after the lyrics

The user's existing lyric generator supplies finished words. This guide designs the *audible recording*: pulse, low-end behavior, harmonic motion, sound-source roles, vocal performance, section arc, and production image. It does not rewrite lyrics to solve an arrangement problem. Dense lines may instead call for leaner accompaniment, clearer phrasing, or a different vocal register.

The deliverable is one self-contained **Style of Music** paragraph. Select what makes this recording different, with no fixed sentence count or concluding category. Keep it within the user's observed 1,000-character target and verify its exact length. That target is a user-reported workflow constraint, not a limit verified in the Suno documentation cited here.

This architecture describes sounds and behaviors. Translate any conversational reference into audible properties, such as “short, hard-edged chord attacks alternating with a sustained upper note.” The cases use no named performer or work as a substitute for those properties.

## What goes in each field

In Suno's [Custom mode instructions](https://help.suno.com/en/articles/2415873), Custom exposes a space for the user's own lyrics. Its [Android Custom mode walkthrough](https://help.suno.com/en/articles/3726721) shows lyrics, Styles, advanced options, and title as separate inputs on that platform. Therefore:

| Destination | Put here | Keep out |
| --- | --- | --- |
| **Lyrics** | Finished words and section labels. | Production prose. |
| **Style of Music** | Desired arrangement, performance, and sound. | Lyrics, title, prohibitions. |
| **Exclude** | Unwanted elements, if any. | The main positive sound design. |
| **Project notes** | Internal attribute rationale, count, settings, and later test results. | Text requiring deletion before pasting Style. |

The [Exclude help page](https://help.suno.com/en/articles/3161921) places unwanted elements under Advanced Options. Use it for a real prohibition, such as “no backing choir” when one exposed lead is essential. Leave it empty otherwise; its effectiveness must be heard, not assumed.

## Intake: decide before drafting

Read the finished lyric for meaning and vocal demands: repeated phrase, crowded syllables, breaths, and emotional turn. Distinguish must-have qualities from optional ideas. If an unknown would not change the design materially, choose a reversible default. Never claim to have heard audio that was not auditioned.

Chapter 02 provides the attribute card. Its headings are diagnostic, not mandatory clauses. Omit immaterial features. Use exact tempo or key only if known or central; invented numbers offer false precision. Resolve apparent conflicts by assigning attributes to sources or sections: a close, dry lead may sit over distant, reverberant chords.

## Documented controls versus prompt hypotheses

As checked on 29 September 2026, [Suno's v6 FAQ](https://help.suno.com/en/articles/13924481) describes v6-mini, v6, and v6-wild; says Variety may rewrite style prompts; recommends Variety 0 for wording control; and says Max Mode costs extra credits. Its [Creative Sliders page](https://help.suno.com/en/articles/6141377) describes Style Influence and Audio Influence for uploads. These are interface facts, not promises of exact sound. Keep the model fixed when testing a prompt revision.

Use four evidence labels in project notes and research chapters:

- **Documented interface fact:** Suno's own help currently describes the control or workflow; include a direct URL and check date.
- **Musical design principle:** a causal reason an arrangement or recording choice may help this lyric, grounded in audible relationships. It guides a brief but does not assert model obedience.
- **Prompt hypothesis:** an untested claim that a phrase will steer Suno in a particular way. State the desired audible observation and verify it in generated audio.
- **Observed result:** a specific generated take was heard under recorded settings; describe what was actually audible.

For example, a close lead above a wide chord bed may improve word intelligibility, but exact panning cannot be promised. Compare the recording to the brief even at Variety 0.

## Response contract and initial test setting

Return four separately labeled parts: **STYLE OF MUSIC** (paste-ready text only), **CHARACTER COUNT** (exact count of the Style text including spaces and punctuation, verified with a counting tool), **EXCLUDE** (short field or “none”), and **SONG TITLE** (a brief track name derived from the lyric and internal attribute rationale). Do not print the rationale or a listening-test field. Never include those labels inside the Style paragraph. Count after every edit, using the exact text to be pasted; do not count Markdown fences or surrounding quotation marks.

For a wording test, hold lyrics, model, controls, and references fixed; use Variety 0 where available and log Style Influence and Audio Influence. Suno's [Song Editor](https://help.suno.com/en/articles/6141505) documents section replacement, lyric edits, extensions, and fades. Repair one weak section locally if the rest of a take works.

Recheck Suno's linked help before a new repository release. Use Chapter 11 for tests and revisions and Chapter 12 for worked cases.
