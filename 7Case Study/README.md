# Chapter 7 Case Validation in a Chemical Industrial Park

This folder contains the numerical and spatial data supporting **Section 7, "Case validation in a chemical industrial park"**, including the manuscript-facing data for **Table 10, Table 11, Table 12, and Figure 8 route reconstruction**.

## Manuscript-consistent case structure

- 20 candidate platform sites are reported in the manuscript.
- Five selected/opened platforms are represented in the supplied coordinate data.
- 95 monitoring points.
- Five hazardous sources.
- Three fixed no-fly zones.
- Maximum opened platforms: 5.
- Planning horizon: 24 h.
- Energy chance-constraint confidence level: beta = 0.95.
- Minimum platform-to-hazardous-source safety distance: 500 m.

## Table 12 assignment

- P01 — Type A — M001-M017 — 17 points.
- P02 — Type B — M018-M039 — 22 points.
- P03 — Type C — M040-M060 — 21 points.
- P04 — Type B — M061-M078 — 18 points.
- P05 — Type C — M079-M095 — 17 points.

## Main files

- `Table10_case_data.csv`
- `Table11_uav_parameter_setting.csv`
- `Table12_integrated_platform_location_route_results.csv`
- `selected_platforms_5.csv`
- `monitoring_points_95.csv`
- `monitoring_point_id_mapping.csv`
- `monitoring_point_assignments.csv`
- `hazard_sources_5.csv`
- `no_fly_zones_3.csv`
- `park_boundary.geojson`
- `route_nodes.csv`
- `route_edges.csv`
- `route_summary.csv`
- `uav_computational_parameters_for_route_audit.csv`
- `validation_report.txt`
- `data_availability_note.txt`

## Important scope note

The available source platform file contains the five selected platform coordinates, not the complete coordinates of all 20 candidate sites. The missing 15 candidate coordinates have not been fabricated. Consequently, this package supports verification of the selected-platform layout and route solution, but a complete 20-to-5 location-selection audit requires the full 20-candidate-site dataset.

The 95 monitoring-point identifiers are normalized to M001-M095 to match Table 12. Original source labels are retained in `monitoring_point_id_mapping.csv`.

Source code is intentionally kept separate from this public-data package.
