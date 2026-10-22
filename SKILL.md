---
name: chinese-medical-popular-science-writing
description: Rewrite and audit evidence-approved Chinese medical popular-science prose for public readers. Use when polishing patient education materials, public-facing medical articles, book chapters, newsletters, scripts, Q&A drafts, or health-science explainers after facts, terminology, population scope, and safety boundaries have already been checked; remove translationese, AI-like phrasing, web-copy tone, slogan endings, and oversimplified professional prose while preserving medical meaning and risk language.
---

# Chinese Medical Popular Science Writing

Use this skill after the medical facts, terminology, population scope, and safety boundaries are already locked. The task is language-level reconstruction for Chinese public readers, not evidence discovery, diagnosis, treatment planning, or new medical interpretation.

## Non-Negotiables

- Preserve verified claims, causality, magnitude, uncertainty, population limits, contraindication boundaries, red flags, and source traceability.
- Do not add mechanisms, numbers, diagnostic criteria, treatment pathways, drug doses, titration plans, supplement advice, tests, contraindications, or individualized medical recommendations.
- Do not weaken safety language for elegance. Red flags, stop conditions, and care-navigation advice must remain plain and visible.
- Do not turn "associated with" into causation, observational findings into proven effects, or population-level guidance into personal prescription.
- If better wording would change medical meaning, keep the original meaning and mark the wording issue for author or expert review.
- Exclude groups outside the provided scope. If no scope is given, do not silently generalize to children, adolescents, pregnancy, postpartum, eating disorders, severe frailty, complex multimorbidity, or active specialist treatment.

## Author Preference: Complete, Natural Prose

The author confirmed on 2026-10-22 a preference for the supplied Gemini revision of the GLP-1 review: fuller explanations, natural professional collocations, and connections that follow the subject matter. Transfer these qualities to public-facing prose, without importing the academic register or treating the sample's medical additions as verified facts. This preference concerns observable prose, not a blanket endorsement of a model.

Clarity takes priority over compression. Retain the subjects, premises, and explanatory relationships that readers need. A complete, well-shaped longer sentence is preferable to several short statements that leave readers to reconstruct the meaning. Delete repetition after the explanation works. Do not equate human prose with casual language, invented anecdotes, decorative synonyms, or artificial variation.

Build each paragraph around its actual purpose. Do not make every paragraph follow the same explanation–advice–warning pattern or end with a clinical takeaway. Let transitions identify a real relationship; remove abstract announcements about moving to another “level,” “dimension,” or “framework” when they add no explanation. Preserve necessary uncertainty where it affects understanding.

This skill remains for Chinese public-facing medical writing. English academic writing and Chinese scholarly manuscripts use their own writing skill; do not apply a public-education register to them.

## Workflow

1. **Lock the facts**
   Identify the allowed claims, terminology, target readers, excluded populations, evidence strength, and safety boundaries. Rewrite from these constraints, not from style preference.

2. **Diagnose the prose**
   Mark the main problem before rewriting:
   - translationese;
   - AI-like balance or summary;
   - web-copy or official-account tone;
   - professional text mechanically simplified;
   - correct but flat explanation;
   - metaphor that has become the argument;
   - safety language that sounds preachy, dramatic, or hidden.

3. **Rebuild for public understanding**
   Use the following relationships only where the material calls for them; they are not mandatory paragraph slots:
   ```text
   concrete reader situation
   -> what is happening medically or physiologically
   -> why the common interpretation is too narrow
   -> a more accurate way to understand it
   -> what the reader can safely do, observe, or ask a clinician
   -> boundary, uncertainty, or red flag
   ```

4. **Read for Chinese prose**
   The text should have forward motion, varied sentence length, concrete verbs and nouns, and a calm medical narrator. It should not sound like a slogan, chatbot answer, academic abstract, hospital notice, marketing copy, or translated English paragraph.

5. **Check readability separately from correctness**
   Read the passage continuously without its outline. Can a reader follow who or what is being discussed, what happens, and why the next sentence follows? Rewrite awkward collocations, missing premises, and repetitive endings at paragraph level. For example, “维持减重后的体重” may communicate more directly than “减重效果的保留,” depending on the intended meaning; retain standard terminology when precision requires it. Do not invent an explanation that the approved evidence does not provide. A factual check alone does not establish that the language is finished.

6. **Re-check medical meaning**
   Confirm that causality, strength of recommendation, population, time scale, thresholds, uncertainty, and safety instructions still match the approved content.

## What To Rework

Avoid or rewrite these patterns unless the context truly requires them:

- empty transitions: `值得注意的是`, `需要强调的是`, `综上所述`, `从某种意义上说`;
- slogan endings: `带走三句话`, `记住这几点`, `不是判决`, `不是你的错`;
- repetitive frames: frequent `不是...而是...`, `不等于...`, `不能简单认为...`;
- internet tone: narrator judgments such as `没救了`, `代谢坏了`, `开关`, `真值`, `抵扣券`;
- abstract noun chains: `进行管理`, `产生影响`, `发挥重要作用`, `实现提升`;
- unexplained negation: only saying what cannot be concluded without explaining what can be understood;
- ceremonial completeness: forced lists or symmetrical caveats when a paragraph would read better.

These words may appear when quoted as patient language or when carefully framed. The narrator's voice should remain calm, precise, and book-like.

## Preferred Prose Qualities

- Start from a real Chinese reader's question or situation, but do not imitate online speech.
- Use standard Chinese medical terms; explain them by function and relevance, not by displaying English.
- Prefer concrete verbs and familiar medical collocations over unnecessary nominalization. Keep sentences as complete as the explanation requires; do not enforce short main clauses or split connected reasoning into fragments.
- Let literary quality come from rhythm, scene, and conceptual clarity, not ornament.
- Use metaphor sparingly. Define what relationship the metaphor explains, and prevent it from creating false causality.
- Keep "what can be done" safe and bounded: observe, record, adjust low-risk habits, prepare information for consultation, or seek care when indicated.
- Use red-flag language plainly. Avoid dramatizing risk, but do not bury it in soft phrasing.

## Medical Safety Checks

Before finalizing, check:

- Has any new medical claim or action advice been introduced?
- Did wording change a probabilistic claim into certainty?
- Did it change correlation into causation?
- Did it hide population limits or excluded groups?
- Did it remove "seek care" or "stop and reassess" conditions?
- Did it convert general education into personal diagnosis, dosing, testing, or treatment?
- Did a metaphor or simplification distort a mechanism?
- Did the Chinese term still match the intended medical concept?

If any answer is yes or uncertain, revise back toward the approved meaning or mark the sentence for expert review.

## Output Requirements

For small edits:

- patch or rewrite the text directly;
- briefly state the language principle applied;
- confirm that no new medical claim or action advice was added.

For chapter-level or article-level polish, provide:

- revised manuscript;
- short note of major language changes;
- list of passages that still require expert or author clarification;
- confirmation that facts, terminology, population limits, and safety boundaries were preserved.

For a full manuscript or multi-article series, also produce a style decision log covering recurring endings, red-flag sections, term introductions, patient examples, cross-references, and repeated metaphors.
