---
name: chinese-medical-popular-prose-polish
description: Rewrite and audit evidence-approved Chinese public-facing medical popular-science prose so it reads like a polished book manuscript rather than web copy, AI output, translation, lecture notes, or a simplified professional draft. Use when revising大众成书版 chapters, preparing author release review, harmonizing style across chapters, removing network/公众号口吻, improving科普文学性, or performing whole-book final language unification after factual claims and safety boundaries have already been approved.
---

# Chinese Medical Popular Prose Polish

Use this skill after factual claims, terminology, and safety boundaries are already locked. The task is language-level reconstruction, not evidence discovery and not new medical interpretation.

## Confirmed Prose Preference — 2026-10-22

The author prefers the supplied Gemini revision's fuller explanation, natural medical collocations, and substantive progression. Apply these qualities to the intended audience; do not copy its claims or transfer academic language wholesale into public prose.

- Complete the explanation before shortening it. Retain necessary subjects, premises, comparators, and relationships; delete repetition rather than the reasoning a reader needs.
- Develop a paragraph around its actual question. Use a transition only when the content supports the relationship. Do not make every paragraph end with advice, a summary, or a symmetrical caveat.
- Avoid vague noun chains and awkward compressed labels. Name what happens, to whom, and under which conditions. Keep established medical terms and functional complex sentences.
- Expand only what makes the explanation clearer. Rephrasing the same finding twice is not development; do not invent mechanisms, examples, or causality to make the prose flow.
- Review naturalness separately from factual accuracy. Read continuously in the intended language, repair missing links and repetitive endings, then verify evidence strength and safety limits again. Word lists and sentence-length targets cannot certify prose quality.

## Non-Negotiables

- Preserve approved claims, risk boundaries, population limits, uncertainty, and source traceability.
- Do not add mechanisms, numbers, recommendations, diagnoses, contraindications, tests, drugs, supplements, or treatment pathways.
- Do not weaken red-flag or safety language for elegance.
- If a sentence cannot be improved without changing meaning, keep the meaning and mark the wording issue instead.
- For the weight-management book project, use this skill together with `$weight-management-book-research`; it is a prose gate after大众版重写 and before作者发布前终审.

## Rewrite Workflow

1. **Lock facts first**
   Identify the paragraph's claim IDs, allowed scope, excluded content, and safety boundaries. Write from those constraints, not from stylistic preference.

2. **Diagnose the prose**
   Mark whether the problem is:
   - web-copy tone;
   - AI-like balance or summary;
   - translationese;
   - professional text mechanically simplified;
   - correct but flat explanation;
   - metaphor that has become the argument;
   - safety language that has become preachy or alarming.

3. **Rebuild the paragraph**
   Use the following relationships where the content needs them, without requiring each slot in every paragraph:
   ```text
   concrete phenomenon
   -> what is happening physiologically or behaviorally
   -> why the common interpretation is too narrow
   -> a more accurate way to understand it
   -> boundary or care-navigation point
   ```

4. **Read for book texture**
   The paragraph should have forward motion, varied sentence length, and enough specificity to hold attention. It should not sound like a slogan, social-media explainer, academic abstract, or chatbot answer.

5. **Re-check meaning**
   Confirm that causality, magnitude, population, time scale, and uncertainty still match the approved claims.

## Remove Or Rework These Patterns

Avoid these unless the exact context makes them necessary:

- empty judgments: `这不是事实`, `这个变化并不神秘`, `需要注意的是`, `值得强调的是`;
- slogan endings: `带走三句话`, `记住这几点`, `不是判决`, `不是你的错`;
- internet phrasing: `没救了`, `代谢坏了` as narrator judgment, `抵扣券`, `开关`, `真值` in public prose when too casual;
- repetitive frames: frequent `不是...而是...`, `不等于...`, `不能简单认为...`;
- AI-like balance: every paragraph ending with a symmetrical caveat;
- ceremonial completeness: forced lists when a paragraph would read better;
- unexplained negation: saying only what cannot be concluded without explaining what can be understood.

These words may appear when quoted as reader language or when carefully framed, but the narrator's voice should remain calm, precise, and book-like.

## Preferred Prose Qualities

- Start from a real reader perception, but do not imitate online speech.
- Use concrete Chinese verbs and nouns rather than abstract noun chains.
- Let literary quality come from rhythm, scene, and conceptual clarity, not ornament.
- Use metaphor sparingly; define what relationship it helps explain and avoid letting it create false causality.
- Prefer "更合适的说法是..." only when it genuinely improves precision; do not overuse it as a universal transition.
- Use red-flag language plainly and directly. Avoid dramatizing risk.

## Whole-Book Style Harmonization

When polishing multiple chapters or the final manuscript:

- Preserve each chapter's evidence boundary, but unify narrator voice.
- Keep terminology, red-flag presentation, and cross-chapter references consistent. Let chapter endings reflect each chapter's question rather than a standard closing formula.
- Check repeated metaphors and remove those that make the book feel like a collection of posts.
- Keep high-risk chapters more restrained; allow mechanism chapters a little more explanatory rhythm.
- Record any style decision that should affect future chapters in the project's writing standard or handoff file.

## Output Requirements

For small edits, patch the manuscript directly and briefly state the language principle applied.

For chapter-level polish, provide:

- revised manuscript file;
- short note of major language changes;
- list of any places where prose could not be improved without author or evidence clarification;
- confirmation that no new medical claim or action advice was added.

For whole-book harmonization, produce a style decision log in addition to revised text.
