# Chapter 6 Sensitivity Analysis

This folder contains the numerical data supporting **Section 6, Sensitivity Analysis** of the paper.

The sensitivity analysis uses a one-factor-at-a-time design on the same medium-scale spatial instance with 15 candidate platform sites, 50 monitoring points, three hazardous sources, and three fixed no-fly zones. TQ-ALNS is independently executed 10 times at each parameter level using the same set of search seeds.

## Folder structure

- `Table9_sensitivity_parameter_settings.csv`
  - Parameter levels and benchmark values reported in Table 9.
- `Chapter6_experiment_settings.csv`
  - Exact computational settings used for the sensitivity experiments.
- `Chapter6_figure_summary_all.csv`
  - Combined figure-level summary data for Sections 6.1–6.3.
- `all_runs/Chapter6_sensitivity_raw_runs_all.csv`
  - Complete run-level results across all 12 parameter levels.
- `06_1_energy_confidence_level/`
  - Data supporting **Section 6.1** and **Figure 3**.
- `06_2_inspection_demand_scale/`
  - Data supporting **Section 6.2** and **Figure 4**.
- `06_3_battery_capacity/`
  - Data supporting **Section 6.3** and **Figure 5**.

Each parameter level contains 10 independent TQ-ALNS runs. The summary files report run means, standard deviations, and 95% confidence-interval half-widths for the metrics used in the figures.

Source code is not included in this repository.
