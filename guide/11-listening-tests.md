---
chapter_id: "11"
retrieval_tags: [evaluation, listening, A-B test, revision, adherence, log, stop rule]
use_when: "Use after a Style prompt is drafted or generated audio must be judged and revised."
output_influence: evaluation
---

# 11. Listening tests and revision

## Test a prediction, not a feeling of satisfaction

Before generating, write down the two or three most important things a listener should hear. One prediction might be “the bass answers the kick in the spaces between vocal lines”; another might be “the refrain gains width without pushing the lead backward.” A general judgment such as “sounds good” can be useful as a final preference, but it cannot diagnose what to change. The attribute card becomes a set of falsifiable listening questions.

Keep an **attempt record**: lyric revision, exact Style text and count, Exclude text, model, controls, references, and resulting file links. Suno's [v6 FAQ](https://help.suno.com/en/articles/13924481) says Variety may update style prompts and recommends Variety 0 for wording control. Its [Creative Sliders page](https://help.suno.com/en/articles/6141377) describes Style Influence and Audio Influence. Hold these values fixed when testing wording; otherwise the cause of a change is unclear.

## A compact listening scorecard

Play the entire take once without pausing, then check the decisive moments: first entrance, densest lyric line, first repeated phrase, contrast section, final return, and ending. Mark each requested feature **present**, **partial**, **absent**, or **unclear**; attach a timestamp and one sentence of evidence. “Present” requires an audible event, not mere plausibility. “Partial” can mean the source is there but arrives in the wrong section or masks another role. “Unclear” is appropriate when the file or playback conditions cannot distinguish the feature.

| Axis | Ask what is audible |
| --- | --- |
| Pulse and low end | Is the perceived speed right? Do kick and bass align, alternate, or collide as intended? |
| Harmony and motif | Is repetition useful? Does the motif appear in its planned gaps? Is the refrain a real variation? |
| Voice and lyric | Are stressed words and consonants clear? Does the lead delivery develop across sections? |
| Form | Is there a meaningful before/after contrast, or did every section arrive at full density? |
| Recording image | What is in front, wide, distant, dry, saturated, or transient? Does that hierarchy survive on a small speaker? |

## Compare with controlled changes

Generate a baseline pair under one set of controls. Suno's current [v6 FAQ](https://help.suno.com/en/articles/13924481) describes two songs per generation in its v6 workflow. Treat two outputs as variation, not statistical proof. If both miss a decisive attribute, revise one causal phrase; if only one misses, listen for tradeoffs before rewriting.

Change one meaningful instruction per comparison. Replace “huge production” with “wide sustained chords enter only at the refrain,” then hold everything else. A true single-variable test is hard in a generative system because each output varies, but minimizing changed text still improves diagnosis. If the revision improves the target and damages the vocal, the change was not a free gain; retain both observations. Do not keep generating indefinitely to confirm an unimportant nuance.

## Failure diagnosis and the next smallest action

- **Wrong whole-track identity:** Replace vague mood with source roles and pulse behavior; keep lyrics fixed.
- **Correct sources, wrong interaction:** Specify timing: bass with or between kick hits, motif after rather than under words.
- **Masked words:** Thin sustained layers, shorten tails, or ask for a closer lead with crisp consonants; check lyric density too.
- **Flat refrain:** Choose one audible lift: longer chord notes, wider backing, bass entrance, or late vocal harmony.
- **One weak section:** Suno's [Song Editor](https://help.suno.com/en/articles/6141505) documents region replacement; preserve the good take if possible.
- **Unwanted layer:** Name it in the separate [Exclude control](https://help.suno.com/en/articles/3161921); keep Style affirmative.
- **Ignored instruction:** Check model and Variety, then simplify the prompt to the decisive attribute.

Stop when a take expresses the lyric and the top attributes, or revisions create worse tradeoffs. Preserve the file, exact inputs, and notes. A failed hypothesis records what was asked and heard; it does not prove the model can never produce that result. Label listening findings as local evidence, not universal product behavior.
