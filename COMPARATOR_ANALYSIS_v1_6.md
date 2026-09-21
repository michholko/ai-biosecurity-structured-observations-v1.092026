# Comparator analysis v1.6

## Purpose

This comparator corpus tests whether patterns observed in the current AI-security / AI-bio corpus are distinctive to that research ecosystem or recur in adjacent mature fields. It adds 30 sources across six deliberately different traditions: traditional biosafety/biosecurity, safety engineering and human factors, empirical cybersecurity, bioinformatics/data quality, metascience/benchmark validity, and ordinary successful biology as positive controls.

The comparator set is not a systematic review and its counts are not prevalence estimates. It is a structured hypothesis-development sample intended to identify useful contrasts and candidate variables for the next study design.

## High-level synthesis

### 1. Studying small failures is normal safety science, not a retreat from catastrophic risk

WHO and CDC biosafety guidance explicitly treats incidents and near misses as information that should feed risk reassessment, root-cause analysis, corrective action, training, and program improvement. High-reliability and patient-safety literatures likewise use near misses to learn about system weaknesses before severe harm occurs.

**Implication:** the proposed AI-bio strategy—study observable perturbations, near misses, corrections, and recoveries to understand mechanisms relevant to larger harms—has clear precedent in mature safety practice.

### 2. Mature safety disciplines already use relational/system-level causal models

STAMP/STPA, Reason's systems approach, Safety-II, and high-reliability research treat safety as emerging from interactions among technical components, humans, organizations, constraints, defenses, and feedback. They do not assume that component correctness implies system safety.

**Implication:** relational biosecurity can be framed as extending systems-safety logic into connected AI-enabled biological workflows rather than asserting that relationships matter on intuition alone.

### 3. Empirical cybersecurity provides a strong methodological contrast to benchmark-heavy AI security

WINE, the Verizon DBIR, incident analyses, and human cyber-range datasets emphasize representative field observations, longitudinal telemetry, metadata, incident lifecycles, and reproducible process traces. This differs from inferring security primarily from bounded benchmark tasks.

**Implication:** a WINE-like AI-bio observatory or incident/near-miss infrastructure is methodologically well motivated.

### 4. Bioinformatics already contains empirical relational failure trajectories

Annotation errors can percolate through inference chains; incorrect metadata can propagate through public databases; low levels of contamination can create large downstream variant-calling errors; and missing workflow provenance can prevent reproduction. These are pre-AI examples in which information moves but context or meaning is distorted.

**Implication:** biological data provenance, metadata, and dependency lineage are not peripheral governance topics. They are candidate technical control variables in AI-bio systems.

### 5. The proxy-to-claim problem is a general measurement-science problem

Independent benchmark-validity work identifies construct-validity failures, benchmark-choice sensitivity, Goodhart effects, and limited predictive transfer. The issue is therefore broader than AI safety and should be framed as evaluation science rather than as a critique of one community.

**Implication:** the emerging claim-demonstration-distance measure has a strong external intellectual foundation.

### 6. Positive controls show what successful relational architecture looks like

Automated DBTL systems and integrated genomic surveillance do not succeed merely because feedback exists. They deliberately connect measurement, provenance, interpretation, orchestration, authority, action, and subsequent update.

**Implication:** the Set 3 distinction among feedback availability, interpretability, authority/capacity, update, and propagation should remain central.

## The strongest cross-corpus proposition

The comparator set sharpens the research program from a generic claim that "relationships matter" to a more specific proposition:

> Security and capability claims become less reliable when evidence is generated at one system boundary and interpreted as though it described a larger system whose outcomes depend on relationships that were not measured.

Adjacent fields address this problem through a combination of system-level causal models, near-miss learning, field telemetry, provenance tracking, operational feedback, and explicit control architectures.

## What this suggests for the next phase

1. Build matched chains from **benchmark -> workflow -> physical/deployed outcome** wherever the same underlying capability can be traced.
2. Build a **feedback-to-update** analysis distinguishing sensing, interpretation, authority, response, propagation, and learning.
3. Trace **funder problem frame -> funded construct -> metric -> governance use** without treating funder mission as evidence of bias.
4. Add more positive-control workflows and independently sampled comparator papers before making prevalence claims.
5. Consider a prospective AI-bio observatory schema modeled more on empirical cybersecurity / biosafety incident learning than on a leaderboard.
