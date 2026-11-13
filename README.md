# scientific-manuscript-reframing
An AI skill for scientific manuscript diagnosis, storyline reframing, and evidence-based revision
Turn existing data, analyses, and findings into a coherent manuscript with a clear scientific question and conclusions that match the evidence.

Core principle: **Understand the scientific argument before polishing the prose.**

## What problems does it solve?

A manuscript can contain substantial data and analysis yet still struggle with:

- Disconnected sections and no clear message for readers to take away.
- Results organized in the order analyses were performed, rather than around the scientific question.
- A Discussion that repeats findings without explaining their meaning, possible mechanisms, or limits.
- Novelty claims centered on using a particular algorithm, model, or dataset rather than making a scientific contribution.
- Misalignment between the Introduction, the analyses actually conducted, and the final conclusions.
- Causal explanations inferred from correlations, or exploratory groupings presented as validated natural categories.
- Uncertainty about how to adapt a manuscript for another journal while preserving the underlying facts.

This skill is designed for researchers who already have study materials and need to improve the manuscript's scientific logic. Its primary purpose is not routine proofreading, translation, or reference formatting.

## Capabilities

| Mode | When to use it | Main outputs |
| --- | --- | --- |
| **DIAGNOSE** | Identify why a manuscript feels fragmented, unclear in its contribution, or weakly argued | An assessment of the scientific question and evidence, structural problems, claim risks, and revision priorities |
| **REFRAME** | Build a central scientific argument across multiple findings | A one-sentence take-home message, logical progression, and revised section architecture |
| **SECTION** | Revise Results, Discussion, Introduction, Conclusion, or Abstract individually | A revised section structure, content decisions, and suggested revisions or rewritten text |
| **SYNTHESIZE** | Integrate multiple analyses into a broader scientific insight | Evidence-supported relationships, comparisons, frameworks, or conceptual models |
| **SUBMISSION** | Adapt presentation once the scientific argument is stable | Title, abstract, highlights, cover letter, and journal-positioning language |

Use each mode independently or combine them as needed. The full workflow is not required for every task.

## Default workflow

The skill follows this sequence, narrowing its scope to fit the request:

1. **Inventory the evidence** — Identify available data, analyses, figures, tables, and robust findings.
2. **Diagnose the manuscript** — Compare the question the manuscript claims to answer with what the evidence supports.
3. **Define the take-home message** — State the one sentence readers should remember.
4. **Design the argument** — Organize the material around scientific logic.
5. **Restructure Results** — Make each subsection answer a distinct question and advance the argument.
6. **Synthesize findings** — Assess whether a broader relationship or framework is justified.
7. **Rebuild the Discussion** — Explain meaning, possible mechanisms, connections to prior work, and limitations.
8. **Align the Introduction** — Derive the research gap and objectives from the evidence actually presented.
9. **Refine the Conclusion and Abstract** — Emphasize the central contribution and reduce repetition.
10. **Adapt for the target journal** — Adjust emphasis and presentation while preserving scientific facts.

## Getting started

### 1. Obtain the complete skill package

Download and extract the skill package, or clone this repository. Preserve the relative paths between `SKILL.md` and `references/`; copying only the main file leaves out supporting guidance.

`README.md` explains the repository to users. `SKILL.md` contains the instructions the AI follows.

### 2. Load it into a tool that supports skills

Installation interfaces and skill directories vary by tool. Follow your tool's instructions:

- **If it supports package imports:** Import the complete folder containing `SKILL.md` and its supporting resources, or an archive format the tool accepts.
- **If it supports a local skills directory:** Place the complete skill folder in the designated directory, then refresh or reload as required.
- **If it supports selecting or naming a skill:** After installation, select `scientific-manuscript-reframing` or explicitly request it in your prompt.

This repository provides skill instructions and reference files for an AI tool to execute. Uploading the files to GitHub does not install the skill in that tool.

If your tool can read files but does not support native skills, you can provide the main file and relevant reference files and ask it to follow their workflow. This is a manual instruction-based approach, not native installation or automatic activation.

### 3. Supply your research materials and define the task

Useful inputs include:

- The current manuscript or the sections you want to revise.
- Key figures, tables, captions, and corresponding findings. Provide text descriptions if the tool cannot interpret images.
- Research objectives, data sources, and a summary of the methods.
- Known limitations, analyses that cannot currently be added, and terminology that must be preserved.
- The target journal or readership, if already identified.

Specify whether you want diagnosis before rewriting, your preferred output language, and whether external literature searches are permitted.

Incomplete materials can still support a focused diagnosis. Missing evidence should be flagged, not replaced with invented findings.

## Example prompts

### 1. Diagnose before rewriting

> Use the DIAGNOSE mode of scientific-manuscript-reframing to assess the attached manuscript. Do not polish the text yet. Identify the scientific question it claims to answer, the conclusions supported by the available evidence, its strongest contribution, and the three most important structural problems. Refer to the relevant sections, figures, or tables.

### 2. Rebuild the central argument

> My manuscript contains several analyses, but it reads like a collection of separate tasks. Use REFRAME mode to propose a one-sentence take-home message based on the existing findings and a revised subsection order for Results and Discussion. Explain how each subsection advances the argument. Do not introduce mechanistic explanations that the data do not support.

### 3. Synthesize water-quality remote sensing findings

> I have underway water-quality observations, UAV multispectral imagery, and satellite matchup results. Use SYNTHESIZE mode to assess whether these findings support the argument that hydrodynamic conditions influence matchup errors across spatial scales. Distinguish direct observations, statistical relationships, and mechanistic hypotheses. Identify the validation still needed. If the evidence is insufficient, propose a more defensible central argument.

### 4. Restructure the Discussion

> Use SECTION mode to restructure the Discussion while preserving the scientific meaning and essential terminology. Distinguish interpretation of findings, possible mechanisms, comparisons with previous studies, practical implications, and limitations. Remove repetition of the Results and flag sentences that overstate causality.

### 5. Calibrate novelty claims

> Assess whether my novelty claims amount only to using a particular model or dataset. Based on the existing findings, identify any new relationships, explanations, or synthesis the study provides. Separate contributions directly supported by the evidence, contributions requiring further validation, and claims that should not currently be made.

### 6. Align submission materials

> The scientific argument is now stable. Use SUBMISSION mode and the attached journal requirements to align the central contribution across the title, abstract, highlights, and cover letter. Do not inflate novelty to fit the journal. Flag any missing information.

## Reference files

| File | Purpose |
| --- | --- |
| `references/workflow.md` | Complete workflow |
| `references/manuscript_diagnosis.md` | Manuscript diagnosis |
| `references/storyline_design.md` | Argument design and synthesis |
| `references/results_restructuring.md` | Results restructuring |
| `references/discussion_reasoning.md` | Discussion reasoning |
| `references/intro_conclusion_abstract.md` | Introduction, Conclusion, and Abstract |
| `references/claim_strength_rules.md` | Claim calibration and evidence boundaries |
| `references/journal_adaptation.md` | Journal adaptation |
| `references/output_templates.md` | Output templates |

## Principles and limitations

- **Evidence first:** Distinguish observations, model results, interpretations, mechanistic hypotheses, broader implications, and recommendations.
- **No fabrication:** Do not invent data, literature findings, statistical support, mechanisms, or novelty.
- **Preserve scientific meaning:** Flag contradictions in the supplied materials rather than silently resolving them.
- **Interpret groupings cautiously:** Groups without independent validation should not be treated as established natural categories.
- **Use external literature when requested:** Supplied materials are the default evidence base. External searches, comparisons, and verification require an explicit request and depend on the host tool's retrieval capabilities.
- **No publication guarantee:** This skill supports scientific reasoning and writing. It does not replace the authors' responsibility to verify data, methods, citations, and final claims, and it does not guarantee journal acceptance.
