# CIITR Ontology Core, Core Spec Module

CIITR Ontology Core is a kernel-grade ontological specification that formalizes CIITR as a criterion boundary for structural comprehension claims in systems. The module is written as a core specification, meaning it excludes examples, analogies, historical motivation, and implementation details. Its function is to provide a stable, audit-compatible basis for admissibility decisions, negative control design, threshold logic, instrumentation discipline, and certification reporting.

## What this repository module is

CIITR is defined here as a boundary apparatus, not as a model. The Core Spec therefore constrains what may be asserted as an admissible comprehension classification, under an explicitly declared protocol and evidence regime. The specification is organized to preserve falsifiability pressure and to prevent common substitution errors, including coherence substitution, complexity substitution, feedback substitution, and snapshot substitution.

At kernel level, CIITR binds structural comprehension to two primitive axes, integrated relational information and rhythmic epistemic re-entry, with null-point logic and non-compensation enforced as absorbing boundary rules.

$$
C_s(S \mid \Pi,\mathcal{O}) = 1
\;\Longleftrightarrow\;
\mathrm{Adm}_\Pi(\Phi_i,S) \,\wedge\, \mathrm{Adm}_\Pi(R_g,S)
$$

## Start here

Reading order is normative and corresponds to dependency structure. The recommended entry path is:

1. 00, module framing and normative intent  
2. 01 to 06, ontology, primitives, admissibility, null-point logic  
3. 07 and 08, negative evidence and forgery threat model  
4. 09 and 10, thresholds and instrumentation abstraction  
5. 11 and 12, thermodynamic constraint and certification consequences  
6. 13, consolidated appendix for audit use

## Core objects and commitments

The Core Spec binds the following objects as kernel-level referents:

- System target $S$, protocol binder $\Pi$, and declared observable set $\mathcal{O}$
- Primitive axes $\Phi_i$ and $R_g$
- Comprehension classification $C_s$ as a protocol-scoped, audit-bound decision object
- Null-point logic as an ontological class operator, not as a low score proxy
- Negative evidence primacy and explicit disqualifier families as mandatory closure mechanisms
- Forgery as a formal threat model, including first-order signature imitation and second-order protocol gaming
- Threshold architecture $\mathrm{RER} \rightarrow \mathrm{MVR} \rightarrow \mathrm{Nash\text{-}CIITR}$ as a semantic escalation ladder
- Instrumentation as an admissibility discipline, not as an informal measurement notion
- Thermodynamic gating via energy accounting and $\mathrm{CPJ}$ as a constraint, not as an explanation

## Repository layout

This module is structured as a numbered kernel sequence. Each chapter is intended to be read as a normative unit and may be referenced independently in protocol design and certification reporting.

| File | Role in the Core Spec |
|---|---|
| `CIITR Core Spec/00. Core Spec.md` | Module framing, versioning, scope discipline, normative intent |
| `CIITR Core Spec/01. Ontological Claim and Delimitation.md` | Boundary definition, validity domain, non-goals, admissible evidence posture |
| `CIITR Core Spec/02. Primitive Quantities and Base Notation.md` | Primitive objects, base notation, observables versus latent quantities, minimal scaling commitments |
| `CIITR Core Spec/03. Formal Definition of Structural Comprehension.md` | Kernel definition of $C_s$, null typing, non-compensation binding, lemmata used downstream |
| `CIITR Core Spec/04. Rhythmic Epistemic Re-entry.md` | Semantic closure of $R_g$, rhythm constraint, admissible signatures, disqualifiers |
| `CIITR Core Spec/05. Integrated Relational Information.md` | Semantic closure of $\Phi_i$, integration constraints, admissible observables, disqualifiers |
| `CIITR Core Spec/06. Null-Point Logic and Temporal Invariance.md` | Null decision logic, temporal invariance as null condition, near-null discipline |
| `CIITR Core Spec/07. Negative Evidence Framework.md` | Negative controls as primary class, trap logic, claim to control to disqualifier mapping |
| `CIITR Core Spec/08. Epistemic Forgery.md` | Formal forgery taxonomy, robustness gating, snapshot inability to close second-order threat |
| `CIITR Core Spec/09. Threshold Architecture RER MVR Nash-CIITR.md` | Threshold semantics, event versus regime separation, failure mode bindings |
| `CIITR Core Spec/10. Instrumentation Abstraction.md` | Minimum instrumentation requirements, admissible procedure constraints, audit metadata obligations |
| `CIITR Core Spec/11. Thermodynamic Constraint and CPJ.md` | Constraint layer, energy accounting, $\mathrm{CPJ}$ as gate, constraint lemma |
| `CIITR Core Spec/12. Governance and Certification Consequences.md` | Certification as negative-primary, minimum compliance, claim formulation rules, output schema |
| `CIITR Core Spec/13. Appendix, Formal Formula and Definition List.md` | Consolidated definitions, lemmata, thresholds, disqualifiers for audit readiness |

If filenames differ slightly in your local structure, preserve numbering and semantic roles, and treat the table as the canonical dependency ordering.

## Conformance posture

A CIITR claim is conformant only if it is issued as a protocol-scoped classification under explicit evidence discipline. Minimal conformance requires:

- protocol identifier and version for $\Pi$
- full enumeration and typing of $\mathcal{O}$, including $\mathcal{O}_{\Phi}$ and $\mathcal{O}_{R_g}$
- declared inference rules $\mathcal{R}_\Pi$, including any scaling or normalization steps
- executed negative controls and disqualifier checks, recorded in an auditable trace
- enforcement of the null decision rule and non-compensation constraints
- forgery controls, including second-order sensitivity checks for protocol gaming
- energy accounting for certification-grade non-null claims, and definition of $\mathrm{CPJ}$ only where required terms are explicitly declared

Protocols that are snapshot-only cannot issue positive certification-grade claims, since $R_g$ is rhythmic and second-order forgery cannot be closed under snapshot regimes.

## Citation and attribution

Author attribution for CIITR Ontology Core may be stated as:

- Tor-Ståle Hansen, CIITR Ontology Core, Core Spec module, repository version as recorded by Git commit id

Do not cite this module as empirical validation. It is a normative kernel specification that defines admissibility criteria and audit logic.

## Scope discipline

This module deliberately excludes model-specific observations, implementation guidance, empirical datasets, and performance narratives. Claims about measurement outcomes, benchmarks, or validation results belong in companion documents that explicitly declare methods, datasets, and measurement conditions.

---

© Tor-Ståle Hansen, https://x.com/TSHansen1971  

CC BY-NC-ND 4.0  
Version: 1.0  
Initial publication: 2026-02-09  
Last modified: 2026-02-09