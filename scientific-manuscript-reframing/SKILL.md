---
name: scientific-manuscript-reframing
description: Collaboratively diagnose, reframe, restructure, and refine scientific manuscripts with author confirmation, journal targeting, and literature-grounded advice by turning fragmented evidence and analyses into a coherent scientific argument. Use for manuscript-level diagnosis, storyline redesign, section restructuring, synthesis across analyses, claim calibration, abstract/conclusion rebuilding, and journal positioning. Do not use merely for grammar polishing when the user only wants copyediting.
---

# Scientific Manuscript Reframing

## Mission

Turn a manuscript that contains data, analyses, and results into a manuscript that answers a clear scientific question with an evidence-based argument.

Core principle:

> Do not polish the manuscript before understanding the scientific argument.

Prioritize, in order:
1. evidence,
2. scientific question,
3. central claim,
4. logical structure,
5. claim strength,
6. section architecture,
7. wording,
8. journal adaptation.

Never invent evidence, mechanisms, statistical support, literature findings, or novelty. Ground findings about the study in the supplied evidence. Search relevant literature throughout the workflow to inform advice and contextual interpretation, following references/literature_search.md.

## When to use

Use this skill when the user asks to:
- diagnose why a manuscript feels fragmented, descriptive, repetitive, or weak in novelty;
- identify the central scientific question or take-home message;
- rebuild the manuscript's scientific storyline or conceptual framework;
- reorganize Results, Discussion, Introduction, Conclusion, or Abstract;
- synthesize multiple analyses or evidence streams into a higher-level interpretation;
- distinguish results from interpretation, mechanism, implication, and speculation;
- identify overclaims, missing links, reviewer risks, or unsupported novelty claims;
- adapt a scientifically stable manuscript to a target journal or audience;
- draft or revise title, abstract, highlights, cover letter, or journal-fit language after the core argument is stable.

Do not default to this skill for simple proofreading, translation, reference formatting, or isolated sentence edits unless those edits depend on manuscript-level logic.

## Operating modes

Choose the smallest mode that solves the user's task.

### DIAGNOSE
Use when the user wants to know what is wrong with a manuscript or section before rewriting.
Output the manuscript's stated question, actual evidence, strongest contribution, structural problems, claim risks, and reframing opportunities.
Read `references/manuscript_diagnosis.md`.

### REFRAME
Use when the manuscript has substantial results but lacks a coherent central argument.
Build a one-sentence take-home message, a logical progression, and a revised section architecture.
Read `references/storyline_design.md` and `references/workflow.md`.

### SECTION
Use when the user wants to revise one section while preserving the overall manuscript.
Use the section-specific guidance in:
- `references/results_restructuring.md`
- `references/discussion_reasoning.md`
- `references/intro_conclusion_abstract.md`

### SYNTHESIZE
Use when several analyses need to be integrated into a higher-level relationship, framework, comparison, or conceptual model.
Read `references/storyline_design.md`, `references/claim_strength_rules.md`, and `references/output_templates.md`.

### SUBMISSION
Use only after the scientific argument is stable.
Adapt title, abstract, highlights, cover letter, keywords, and journal framing without changing the underlying evidence.
Read `references/journal_adaptation.md` and `references/intro_conclusion_abstract.md`.

## Opening explanation for each new manuscript task

At the start of a new manuscript task, briefly explain the applicable workflow in the author's language before presenting substantive findings. Name the current step, the major confirmation points, and the proposed revision order. Give this explanation once per task and update it when the agreed scope changes. On resuming, summarize the current step and confirmed decisions.

For a full manuscript, explain this sequence in plain language.

0. Ask about and confirm the target journal or journal type, offering a few relevant categories to help the author choose.
1. Compile the evidence inventory and ask the author to confirm or correct it.
2. After that confirmation, diagnose the manuscript and agree on the revision priorities.
3. Agree on the whole-paper central idea, scientific question, and take-home message.
4. Agree on the argument progression and each section's central message and role.
5. Revise and review the text section by section in the agreed order.
6. Review the Conclusion, Abstract and Title individually, then prepare any requested journal-facing materials.

Explain that scientific decisions precede rewriting. The default rewriting order is Results, optional synthesis, Methods alignment, Discussion, Introduction, Conclusion, Abstract, Title, and requested submission materials. Explain that this grounds the Introduction and summary in the established findings. Adapt the order to the manuscript and the author's confirmed preference.

For example, a Chinese opening may say

“我们先确认目标期刊或期刊类型，再整理证据清单。你确认或修正清单后，我们再诊断论文。随后一起确定全文中心思想、论证逻辑线，以及每个章节要表达的中心意思。确认框架后，按结果、必要的综合分析、方法核对、讨论、引言、结论、摘要和标题的顺序逐节修改。每个关键节点我都会给出具体方案，问你是确认还是需要调整，等你回复后再推进。各阶段我都会检索相关论文，并在建议旁标明参考文献和原文链接。”

Begin the evidence inventory when the target journal or journal type is settled and the supplied materials are sufficient. If journal preferences are unknown, give the brief workflow explanation and ask the initial journal question first. A basic scan of supplied material may inform that question. If materials are missing, explain the workflow and request the material needed for that inventory. A narrower task receives a correspondingly shorter explanation.

## Initial journal preference

Before the evidence inventory, ask which journal or kind of journal the author is aiming for. If they have already clearly specified it, acknowledge that preference and proceed. Offer a short, relevant menu of categories, such as broad interdisciplinary research, discipline-focused theory or mechanisms, methods or technology, and applied management or policy. Tailor the choices to the manuscript. The author can also choose to leave the target open and proceed with a provisional readership.

For example, ask in Chinese

“你希望投哪类期刊？例如综合或跨学科类、领域理论与机制类、方法技术类、应用管理类。已有目标期刊可以直接告诉我名称；暂时未定也可以，我们先确定读者与侧重点。”

When concrete journal names would help the author choose, use the study topic to identify a few candidates and check their current official scope before presenting them with links and a brief reason for fit. Keep such candidates provisional until the author selects or revises the target. The target audience guides comparison literature and presentation throughout the task. Detailed submission formatting follows a stable scientific argument.

## Literature-informed advice throughout

For every applicable scientific or editorial stage, search papers relevant to that stage's question, the study field and the confirmed target audience before giving recommendations. Read references/literature_search.md in every mode. Show which publications support the advice and link to their original article pages or verified DOI records. Cite manuscript-specific findings with their supplied figure, table or section locations. Explain any inference connecting a published finding to the manuscript.

## Author confirmation before each step

Use the workflow as a conversation. Read `references/workflow.md` for the applicable confirmation decisions in every mode. In a broad request such as “optimize this manuscript,” confirm the journal preference, then read the supplied materials and start with the evidence inventory. Return that inventory and pause. Do not rewrite the manuscript or carry out later stages while the author is deciding.

At every applicable step, present a concrete, reviewable result for that step. Explain the evidence, what decision it supports, and what would change under a materially different choice. Offer alternatives when the evidence permits them. Ask a specific question about the proposed decision and wait for the author's explicit confirmation before starting the next step. A progress update, silence, or a reply that only supplies information is not confirmation. An explicit “continue,” a clear selection, or “proceed with this correction” counts when it resolves the pending decision. If the author challenges a choice, discuss the evidence, update the proposal, and ask again. Leave unresolved decisions open.

If the stage itself requires a choice before editing, show the proposed structure or a short sample and confirm that choice before applying it to the full section. At the end of that stage, show the result for review before proceeding. At the final stage, ask whether the author accepts the result or wants revisions.

At each pause, record the latest agreed decisions, the open decision, and what comes next. Retain the confirmed journal preference, literature findings, evidence scope, whole-paper central idea, argument progression, and section messages so later edits stay aligned. Resume from this record in later turns. If new evidence changes an agreed claim, reopen the affected decision and explain the downstream consequences.

Use only the steps relevant to the requested mode. A request for one section or one submission item does not reopen the whole paper. Use the user's already settled choices where they clearly apply. Only an explicit request to combine named steps or deliver in one pass changes the default confirmation sequence. Checkpoints cover scientific and editorial decisions, not routine formatting or individual copyedits. The same protocol applies in any platform. Every checkpoint must explicitly offer confirmation and revision, for example “请确认这个理解是否准确，或指出需要修改的地方。确认后，我们进入论文诊断。” Name the specific decision and the next step. Use a question tool when available or end the reply with the question.

## Default workflow

Unless the user explicitly asks for a narrower task, follow this sequence:

0. **Journal preference** — confirm the journal, journal category, or provisional readership and focus.
1. **Evidence inventory** — identify what data, analyses, figures, tables, and robust findings actually exist.
2. **Manuscript diagnosis** — separate the manuscript's stated story from what the evidence can actually support.
3. **Take-home statement** — state the one sentence readers should remember.
4. **Argument and section design** — agree on the whole-paper logic and a central message, evidence base, and role for every applicable section and substantive subsection before section rewriting.
5. **Results architecture** — order Results so that each subsection answers a distinct question and advances the argument.
6. **Synthesis layer** — if justified, integrate multiple findings into a relationship, framework, comparison, typology, or model.
7. **Discussion reconstruction** — move from result to meaning, explanation, literature, implication, and limitation.
8. **Reverse-engineer Introduction** — derive the gap and objectives from the final evidence structure.
9. **Conclusion and Abstract** — compress the final argument without repeating all Results.
10. **Journal adaptation** — change emphasis and presentation, not scientific facts.

Read `references/workflow.md` for the decision to confirm at each step, Methods alignment after Results and synthesis, and detailed execution rules.

## Non-negotiable reasoning rules

### Evidence first
Distinguish clearly among:
- observation or direct measurement,
- statistical/model result,
- interpretation,
- mechanism hypothesis,
- broader implication,
- recommendation.

Do not move upward on this ladder without evidence.

### Methods are not automatically novelty
A familiar model, algorithm, dataset, instrument, or software is not a scientific contribution by itself. Ask what new relationship, explanation, synthesis, generalization, or decision-relevant insight the method makes possible.

### Do not compress distinct processes into one metric
If several outcomes arise from different underlying processes, do not assume that one summary statistic represents them all. Separate dimensions only when doing so is scientifically justified by the study design and data.

### Analytical groupings are provisional unless independently validated
Cluster-derived, rule-based, or data-driven groups are analytical constructs unless there is independent evidence that they represent intrinsic natural categories. Use neutral terms such as `group`, `type`, `class`, `profile`, or `empirical grouping` unless stronger terminology is justified.

### Relationships matter more than labels
If the manuscript creates categories, indices, or frameworks, ask what scientific relationship they reveal, what they explain, where they fail, and whether they add information beyond simpler analyses.

### Results are not Discussion
Results report what the study found. Discussion explains what the findings mean, why they may occur, how they compare with prior work, what they imply, and where interpretation should stop.

### Introduction is reverse-engineered
Do not preserve an old Introduction merely because it was written first. After the main argument is stable, rewrite the Introduction so that its gap and objectives lead directly to the evidence actually presented.

### Journal fit changes emphasis, not facts
Never modify results or inflate novelty to match a target journal. Rebalance framing, terminology, breadth, and practical emphasis only.

## Source discipline

When manuscript files, tables, figures, or notes are supplied:
- treat them as the primary evidence base;
- preserve the authors' terminology unless a change is scientifically necessary;
- flag contradictions instead of silently reconciling them;
- state when a requested claim is not supported by the supplied material;
- search external literature at each applicable stage under references/literature_search.md, and attach verified references and original links to literature-based advice. Keep the study evidence distinct from published context.

## Style defaults

For scientific rewriting:
- prefer short, explicit sentences;
- prioritize logical transitions over ornamental prose;
- calibrate causal language to the evidence;
- avoid unnecessary jargon and method worship;
- minimize repeated findings across Results, Discussion, Conclusion, and Abstract;
- preserve the user's scientific meaning before improving style.

## Reference files

Read only the files needed for the current mode:
- `references/literature_search.md` — mandatory in every mode for stage-specific searches and source attribution.
- `references/workflow.md`
- `references/manuscript_diagnosis.md`
- `references/storyline_design.md`
- `references/results_restructuring.md`
- `references/discussion_reasoning.md`
- `references/intro_conclusion_abstract.md`
- `references/claim_strength_rules.md`
- `references/journal_adaptation.md`
- `references/output_templates.md`
