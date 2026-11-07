---
name: chinese-medical-popular-prose-polish
description: Rewrite and audit evidence-approved Chinese public-facing medical popular-science prose so it reads like a polished book manuscript rather than web copy, AI output, translation, lecture notes, or a simplified professional draft. Use when revising大众成书版 chapters, preparing author release review, harmonizing style across chapters, removing network/公众号口吻, improving科普文学性, or performing whole-book final language unification after factual claims and safety boundaries have already been approved.
---

# Chinese Medical Popular Prose Polish

Use this skill after factual claims, terminology, and safety boundaries are already locked. The task is language-level reconstruction, not evidence discovery and not new medical interpretation.

## 已确认的科普评论写法 — 2026-11-07

适用于有研究支撑的社会观察型科普长文；不把这种评论语气强加给诊疗说明、知情同意或医学指南。用户认可的是明确判断、持续推进的论证和可感知的生活图景，不是夸张的神经科学术语。

- 动笔前用一句话确定全文要回答的问题和证据允许的核心判断。让各节沿着同一问题推进，避免机械拼接“背景—研究—限定—建议”。
- 从具体体验进入，逐层解释行为如何发生、为什么值得担忧、现实代价在哪里、个人和平台能改变什么。这个顺序可调整，不是每篇必须填满的模板。
- 科学严谨是判断强度与证据强度相称，不是取消判断。区分实证结果、机制解释、趋势推断和价值判断；研究不能证明永久损伤，不妨碍讨论已经可见的时间挤占和生活代价。
- 把必要限定紧贴对应结论，同一证据边界说明清楚一次即可。不要每推进一段就用“尚不能证明”“仍需研究”“并非保证有效”撤回论点；不可为行文流畅省去会改变读者理解的风险、人群或因果边界。
- 研究服务于论证：交代对读者有意义的研究对象、设计和发现，然后接回正在讨论的问题。不要让正文成为研究摘要的串联。
- 用读书、等待、练习技能、完成研究等具体经验解释注意力和延迟回报。允许有解释力的比喻、简洁的判断句和有节制的加粗；力量来自推理和经验，不来自术语或恐惧。
- 不把“多巴胺黑洞”“前额叶休眠失能”“脑功能被永久损伤”当作未经证实的机制；不把短剧直接等同老虎机，不把影像活动差异写成长期损伤，不把相关性写成因果。
- 结尾回到全文矛盾，允许一个由论证自然得出的简洁收束，不强制附加免责、就医建议或整齐的三点总结。具体行动与文章定位相称。
- 完稿分别做两次检查：先检查每节是否推进核心问题、有没有重复自我限定；再检查数字、来源、因果、人群和医学边界。文风认可不等于事实已核验，示范稿中的新闻、法规和研究细节仍须独立核对。

示例立论（只说明写法，不作为其他文章的固定内容）：内容生产成本下降与连续推荐结合，使娱乐更容易持续；有限的时间和注意力因而更容易被挤占。依次解释观看动力、持续投入的机会、消费风险和停止观看的条件，而非借“脑损伤”增强冲击力。

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
