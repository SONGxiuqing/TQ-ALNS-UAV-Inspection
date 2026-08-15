# Section 5.4 Value of Heterogeneous UAV Configuration

This folder contains the data supporting **Section 5.4, "Value of heterogeneous UAV configuration,"** and **Table 7, "Comparison of homogeneous and heterogeneous UAV configurations over 10 random medium-scale instances."**

## Files

- `Table7_uav_configuration_raw_10runs.csv`
  - Run-level results for the four UAV-configuration strategies over 10 randomly generated medium-scale instances.
- `Table7_uav_configuration_summary.csv`
  - Full-precision summary statistics derived from the raw results.
- `Table7_uav_configuration_paper_table.csv`
  - Paper-facing table with the column names and numerical precision used in Table 7.

## Compared configurations

1. All-light — Type A only
2. All-medium — Type B only
3. All-heavy — Type C only
4. Heterogeneous — Type A + Type B + Type C

All configurations use the same instance-generation procedure, model constraints, cost parameters, and stopping criteria. The only difference is the set of UAV types allowed during platform configuration and task assignment.
