# Claim Strength Rules

## Purpose

Prevent common scientific overclaims when translating evidence into conclusions.

## General evidence-to-claim ladder

Use the weakest claim that fully matches the evidence:

1. **Observed/measured** — directly recorded.
2. **Associated with / differed by** — statistical or model relationship.
3. **Consistent with** — agrees with a proposed mechanism or theory.
4. **Suggests / may reflect** — plausible interpretation.
5. **Contributes to / influences** — requires stronger design or convergent evidence.
6. **Causes / determines** — requires causal identification, intervention, or direct process evidence.

## Common unsafe conversions

| Evidence | Avoid | Safer language |
|---|---|---|
| correlation or regression coefficient | X causes Y | X was associated with Y |
| variable importance in a predictive model | X is the main causal driver | X contributed strongly to model prediction |
| better prediction after adding a variable | the added variable explains the mechanism | the variable improved predictive performance |
| simulation result | this will occur in reality | the simulation projects / suggests this outcome under stated assumptions |
| non-significant difference | the groups are equivalent | no statistically detectable difference was found |
| statistically significant effect | important or practically meaningful effect | statistically detectable effect of stated magnitude |
| subgroup pattern without interaction test | effects differ significantly between subgroups | subgroup estimates appeared different; formal interaction evidence is needed |
| cluster membership | intrinsic natural type | empirical/data-driven grouping |
| model fit | model is true | model fit the observed data under the assessed criteria |
| one dataset or site | universal rule | pattern observed in this dataset/context |
| surrogate endpoint | demonstrated real-world benefit | change in the measured surrogate outcome |

## Mechanism claims

Before using `mechanism`, `drives`, `controls`, or `determines`, ask:
- Was the process directly measured?
- Was an intervention or quasi-experimental design used?
- Were plausible alternatives tested?
- Does temporal ordering support the claim?
- Is the conclusion robust to model specification?

If not, prefer `associated with`, `consistent with`, `may reflect`, or `suggests`.

## Prediction versus explanation

Predictive success does not automatically imply mechanistic understanding.
Distinguish:
- prediction accuracy;
- variable association;
- explanatory adequacy;
- causal mechanism.

## Statistical language

Use `significant` only for a defined statistical test.
Whenever possible, report:
- effect size;
- uncertainty interval;
- direction;
- practical relevance.

Do not treat p > 0.05 as proof of no effect.

## Generalization

Match the claim to the sampling frame and study design.
Qualify when evidence is limited to:
- one population;
- one dataset;
- one instrument;
- one experimental condition;
- one geographic or institutional context;
- one model family.

## Classification language

For data-driven groupings, prefer:
- empirical grouping;
- analytical class;
- provisional type;
- profile.

Use formal biological, clinical, mechanistic, or ontological labels only when independently justified.
