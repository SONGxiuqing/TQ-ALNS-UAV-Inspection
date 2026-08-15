# Section 5.5 Robustness Analysis over Random Instances

This folder contains the run-level and summary computational results supporting **Section 5.5, "Robustness analysis over random instances," and Table 8, "Robustness results over 10 randomly generated instances."**

## Experimental design

Ten independently generated random instances are tested for each scale. Both the instance seed and the search seed are varied, so the reported results reflect changes in instance structure and stochastic search behavior.

For each method, the reported statistics include the mean objective value, standard deviation, coefficient of variation (CV), mean runtime, mean coverage rate, mean number of open platforms, and feasibility rate. The deviation from run BKS is calculated relative to the best feasible objective value obtained by the compared methods for the same random instance.

## Folder structure

- `small/`
  - `Table8_small_robustness_raw.csv`
  - `Table8_small_robustness_summary.csv`
- `medium/`
  - `Table8_medium_robustness_raw.csv`
  - `Table8_medium_robustness_summary.csv`
- `large/`
  - `Table8_large_robustness_raw.csv`
  - `Table8_large_robustness_summary.csv`
- `Table8_robustness_summary_all_scales.csv`
  - Combined summary statistics for the three instance scales.
- `Table8_file_manifest.csv`
  - File inventory and data dimensions.

## Scale-specific comparisons

- **Small-scale:** MIP / benchmark and TQ-ALNS.
- **Medium-scale:** Greedy, ALNS-only, ALNS-SA, and TQ-ALNS.
- **Large-scale:** Greedy, ALNS-only, ALNS-SA, and TQ-ALNS.

## Reproducibility note

These files are provided to support independent verification of the numerical results reported in Section 5.5 and Table 8. Source code is not included in this repository. Exact numerical instance inputs are provided separately in the numerical-instances folder of the repository.

## Data-availability statement

The numerical test instances and computational results supporting this study are publicly available in the accompanying repository.
