# Section 5.1 Experimental Settings, Benchmark Instances, and Input Parameters

This folder contains the numerical input data supporting **Section 5.1, "Experimental settings, benchmark algorithms, and evaluation metrics,"** and **Table 3, "Parameter settings for instances of different scales."**

## Contents

- `Table3_instance_settings.csv`
  - Manuscript-facing Small-, Medium-, and Large-scale settings.
- `global_parameters.csv`
  - Common confidence level, coverage requirement, cost parameters, safety-distance parameter, and other computational inputs.
- `uav_types.csv`
  - Computational parameters for Type A, Type B, and Type C UAVs.
- `small/`, `medium/`, `large/`
  - Representative benchmark instance input data generated with the Table 3 random seed of 7.
- `data_verification.csv`
  - Automatic check that the exported scale dimensions match Table 3.

Each scale folder contains:

1. `monitoring_points.csv` — coordinates, inspection frequency, and inspection duration.
2. `candidate_platforms.csv` — coordinates, candidate-site validity, and platform fixed cost.
3. `hazard_sources.csv` — hazardous-source coordinates and safety-distance requirement.
4. `no_fly_zones.csv` — ordered vertices of the fixed rectangular no-fly zones.
5. `platform_monitoring_distance_reachability.csv` — precomputed platform-to-monitoring-point distance and accessibility data used by the benchmark generator.
6. `instance_metadata.csv` — scale-specific metadata.

## Table 3 benchmark scales

- **Small-scale:** 3/7 opened/total candidate platforms, 16 monitoring points, 3 hazardous sources, 2 no-fly zones, 3 UAVs, platform-opening constraint 3, random seed 7.
- **Medium-scale:** 4/15 opened/total candidate platforms, 50 monitoring points, 3 hazardous sources, 3 no-fly zones, 4 UAVs, platform-opening constraint 4, random seed 7.
- **Large-scale:** 14/18 opened/total candidate platforms, 300 monitoring points, 20 hazardous sources, 2 no-fly zones, 14 UAVs, platform-opening constraint 14, random seed 7.

Unless otherwise stated in the manuscript, the energy chance-constraint confidence level is beta = 0.95 and the minimum system coverage requirement is rho = 0.900.

## Scope note

The seed-7 instances in this folder are the **representative benchmark instances described in Section 5.1 and Table 3**. They should not be confused with:

- the additional independently generated random instances used in **Section 5.5 / Table 8 robustness analysis**, or
- the fixed medium-scale spatial instance used in **Section 6 sensitivity analysis**.

Those data are provided in their corresponding experiment folders.

Source code is not included in the public repository.
