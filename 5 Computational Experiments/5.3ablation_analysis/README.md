# Section 5.3 Ablation Analysis of Tailored Repair Mechanisms

This folder contains the data supporting **Section 5.3, "Ablation analysis of tailored repair mechanisms,"** and **Table 6, "Ablation results of tailored repair mechanisms over 10 random medium-scale instances."**

## Files

- `Table6_ablation_raw_10runs.csv`
  - Run-level results for five TQ-ALNS variants over 10 randomly generated medium-scale instances.
- `Table6_ablation_summary.csv`
  - Full-precision summary statistics derived from the raw results.
- `Table6_ablation_paper_table.csv`
  - Paper-facing table with the column names and numerical precision used in Table 6.

## Compared variants

1. Full TQ-ALNS
2. w/o NFZ repair
3. w/o Energy repair
4. w/o Compatibility repair
5. w/o All specific repairs

All variants use the same instance-generation procedure, model constraints, cost parameters, stopping criteria, and search framework. The ablation changes only the specified tailored repair mechanism(s).
