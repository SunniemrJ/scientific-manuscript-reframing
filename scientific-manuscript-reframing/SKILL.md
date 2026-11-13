---
name: scientific-manuscript-reframing
description: Diagnose, reframe, restructure, and refine scientific manuscripts by turning fragmented evidence and analyses into a coherent scientific argument. Use for manuscript-level diagnosis, storyline redesign, section restructuring, synthesis across analyses, claim calibration, abstract/conclusion rebuilding, and journal positioning. Do not use merely for grammar polishing when the user only wants copyediting.
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

Never invent evidence, mechanisms, statistical support, literature findings, or novelty. When working from user-provided files, ground scientific claims in those sources unless the user explicitly requests external research.

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

## Default workflow

Unless the user explicitly asks for a narrower task, follow this sequence:

1. **Evidence inventory** — identify what data, analyses, figures, tables, and robust findings actually exist.
2. **Manuscript diagnosis** — separate the manuscript's stated story from what the evidence can actually support.
3. **Take-home statement** — state the one sentence readers should remember.
4. **Argument design** — organize the paper by scientific logic, not by the chronological order in which analyses were performed.
5. **Results architecture** — order Results so that each subsection answers a distinct question and advances the argument.
6. **Synthesis layer** — if justified, integrate multiple findings into a relationship, framework, comparison, typology, or model.
7. **Discussion reconstruction** — move from result to meaning, explanation, literature, implication, and limitation.
8. **Reverse-engineer Introduction** — derive the gap and objectives from the final evidence structure.
9. **Conclusion and Abstract** — compress the final argument without repeating all Results.
10. **Journal adaptation** — change emphasis and presentation, not scientific facts.

Read `references/workflow.md` for detailed execution rules.

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
- use external literature only when the user asks for verification, comparison, expansion, or journal research.

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
- `references/workflow.md`
- `references/manuscript_diagnosis.md`
- `references/storyline_design.md`
- `references/results_restructuring.md`
- `references/discussion_reasoning.md`
- `references/intro_conclusion_abstract.md`
- `references/claim_strength_rules.md`
- `references/journal_adaptation.md`
- `references/output_templates.md`
