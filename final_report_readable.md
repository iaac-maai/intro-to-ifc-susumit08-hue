# Final Compliance Report

Generated: 2026-02-24T19:19:07.400653

## Overall Summary
| Section | Checked | Passed | Failed | Warnings | Overall |
| --- | --- | --- | --- | --- | --- |
| Exercise 1 - Space Compliance | 14 | 2 | 12 | 7 | FAIL |
| Exercise 2 - Window Compliance | 21 | 6 | 15 | 0 | FAIL |
| Bonus - Fire Safety | 14 | 11 | 1 | 2 | FAIL |

## Exercise 1 - Space Compliance
### Passed Spaces
| ID | Name | Type | Area m2 | Height m | Req Area | Req Height | Reason |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 2637 | Bathroom 2 | Bathroom | 5.441 | 2.587 | 4 | 2.3 | Meets all checks |
| 1059 | Bathroom 2 | Bathroom | 5.416 | 2.587 | 4 | 2.3 | Meets all checks |

### Failed Spaces
| ID | Name | Type | Area m2 | Height m | Req Area | Req Height | Failure Reason |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 819 | Hallway | Corridor | 7.8 | - | 1.5 | 2.3 | Height not found in quantity sets or geometry. |
| 1928 | Bathroom 1 | Bathroom | 3.998 | 2.587 | 4 | 2.3 | Area 4.00 m2 < minimum 4.00 m2 |
| 2412 | Hallway | Corridor | 7.8 | - | 1.5 | 2.3 | Height not found in quantity sets or geometry. |
| 1627 | Living Room | Living Room | 30.142 | 2.581 | 16 | 2.6 | Height 2.58 m < minimum 2.60 m |
| 67 | Living Room | Living Room | 30.142 | 2.581 | 16 | 2.6 | Height 2.58 m < minimum 2.60 m |
| 212 | Kitchen | Kitchen | 13.898 | 2.587 | 8 | 2.6 | Height 2.59 m < minimum 2.60 m |
| 1782 | Kitchen | Kitchen | 13.898 | 2.587 | 8 | 2.6 | Height 2.59 m < minimum 2.60 m |
| 355 | Bathroom 1 | Bathroom | 3.998 | 2.587 | 4 | 2.3 | Area 4.00 m2 < minimum 4.00 m2 |
| 2789 | Bedroom 2 | Bedroom | 26.178 | 2.581 | 9 | 2.6 | Height 2.58 m < minimum 2.60 m |
| 1442 | Bedroom 1 | Bedroom | 26.119 | 2.581 | 9 | 2.6 | Height 2.58 m < minimum 2.60 m |
| 3013 | Bedroom 1 | Bedroom | 26.119 | 2.581 | 9 | 2.6 | Height 2.58 m < minimum 2.60 m |
| 1218 | Bedroom 2 | Bedroom | 26.178 | 2.581 | 9 | 2.6 | Height 2.58 m < minimum 2.60 m |

### Warnings
| ID | Name | Warning |
| --- | --- | --- |
| 514 | Foyer | Space type could not be classified from Name/LongName. |
| 2108 | Foyer | Space type could not be classified from Name/LongName. |
| 3197 | Utility | Space type could not be classified from Name/LongName. |
| 3325 | Utility | Space type could not be classified from Name/LongName. |
| 3456 | Stair | Space type could not be classified from Name/LongName. |
| 3586 | Room | Space type could not be classified from Name/LongName. |
| 3707 | Roof | Space type could not be classified from Name/LongName. |

## Exercise 2 - Window Compliance
### Passed Checks
| Check | Scope | Entity ID | Entity | Reason |
| --- | --- | --- | --- | --- |
| window_space_linkage | global | - | - | Created 16 space-window link(s). |
| window_min_dimension | window | 6426 | M_Fixed:4835mm x 2420mm:4835mm x 2420mm:145788 | Window 6426: Width 4.83 m and height 2.42 m meet minimum dimensions. |
| window_min_dimension | window | 6531 | M_Fixed:4835mm x 2420mm:4835mm x 2420mm:146016 | Window 6531: Width 4.83 m and height 2.42 m meet minimum dimensions. |
| window_min_dimension | window | 6921 | M_Fixed:750mm x 2200mm:750mm x 2200mm:146885 | Window 6921: Width 0.75 m and height 2.20 m meet minimum dimensions. |
| window_min_dimension | window | 7025 | M_Fixed:750mm x 2200mm:750mm x 2200mm:147051 | Window 7025: Width 0.75 m and height 2.20 m meet minimum dimensions. |
| window_min_dimension | window | 7190 | M_Fixed:2800mm x 2410mm:2800mm x 2410mm:147686 | Window 7190: Width 2.80 m and height 2.41 m meet minimum dimensions. |
| window_min_dimension | window | 7795 | M_Fixed:2800mm x 2410mm:2800mm x 2410mm:149278 | Window 7795: Width 2.80 m and height 2.41 m meet minimum dimensions. |
| window_min_dimension | window | 21980 | M_Fixed:2800mm x 2410mm:2800mm x 2410mm:180318 | Window 21980: Width 2.80 m and height 2.41 m meet minimum dimensions. |
| window_min_dimension | window | 22188 | M_Fixed:2800mm x 2410mm:2800mm x 2410mm:181096 | Window 22188: Width 2.80 m and height 2.41 m meet minimum dimensions. |
| window_min_dimension | window | 22396 | M_Fixed:750mm x 2200mm:750mm x 2200mm:181930 | Window 22396: Width 0.75 m and height 2.20 m meet minimum dimensions. |
| window_min_dimension | window | 22448 | M_Fixed:750mm x 2200mm:750mm x 2200mm:182101 | Window 22448: Width 0.75 m and height 2.20 m meet minimum dimensions. |
| floor_area_available | space | 514 | Foyer | Foyer (514): Floor area available: 17.94 m2. |
| living_space_direct_natural_light | space | 514 | Foyer | Foyer (514): Not a living area; rule not mandatory for this space type. |
| floor_area_available | space | 819 | Hallway | Hallway (819): Floor area available: 7.80 m2. |
| living_space_direct_natural_light | space | 819 | Hallway | Hallway (819): Not a living area; rule not mandatory for this space type. |
| floor_area_available | space | 1928 | Bathroom 1 | Bathroom 1 (1928): Floor area available: 4.00 m2. |
| living_space_direct_natural_light | space | 1928 | Bathroom 1 | Bathroom 1 (1928): Not a living area; rule not mandatory for this space type. |
| floor_area_available | space | 2108 | Foyer | Foyer (2108): Floor area available: 17.94 m2. |
| living_space_direct_natural_light | space | 2108 | Foyer | Foyer (2108): Not a living area; rule not mandatory for this space type. |
| floor_area_available | space | 2412 | Hallway | Hallway (2412): Floor area available: 7.80 m2. |
| living_space_direct_natural_light | space | 2412 | Hallway | Hallway (2412): Not a living area; rule not mandatory for this space type. |
| floor_area_available | space | 3197 | Utility | Utility (3197): Floor area available: 1.75 m2. |
| living_space_direct_natural_light | space | 3197 | Utility | Utility (3197): Not a living area; rule not mandatory for this space type. |
| floor_area_available | space | 3325 | Utility | Utility (3325): Floor area available: 1.73 m2. |
| living_space_direct_natural_light | space | 3325 | Utility | Utility (3325): Not a living area; rule not mandatory for this space type. |
| floor_area_available | space | 3456 | Stair | Stair (3456): Floor area available: 4.92 m2. |
| living_space_direct_natural_light | space | 3456 | Stair | Stair (3456): Not a living area; rule not mandatory for this space type. |
| floor_area_available | space | 3586 | Room | Room (3586): Floor area available: 4.92 m2. |
| living_space_direct_natural_light | space | 3586 | Room | Room (3586): Not a living area; rule not mandatory for this space type. |
| floor_area_available | space | 3707 | Roof | Roof (3707): Floor area available: 145.72 m2. |
| living_space_direct_natural_light | space | 3707 | Roof | Roof (3707): Not a living area; rule not mandatory for this space type. |
| floor_area_available | space | 1627 | Living Room | Living Room (1627): Floor area available: 30.14 m2. |
| window_to_floor_ratio | space | 1627 | Living Room | Living Room (1627): Ratio 0.443 meets minimum 0.125. |
| minimum_opening_dimension | space | 1627 | Living Room | Living Room (1627): At least one linked window meets minimum dimensions (0.60m x 1.00m). |
| living_space_direct_natural_light | space | 1627 | Living Room | Living Room (1627): Living area has at least one linked window. |
| floor_area_available | space | 67 | Living Room | Living Room (67): Floor area available: 30.14 m2. |
| window_to_floor_ratio | space | 67 | Living Room | Living Room (67): Ratio 0.443 meets minimum 0.125. |
| minimum_opening_dimension | space | 67 | Living Room | Living Room (67): At least one linked window meets minimum dimensions (0.60m x 1.00m). |
| living_space_direct_natural_light | space | 67 | Living Room | Living Room (67): Living area has at least one linked window. |
| floor_area_available | space | 212 | Kitchen | Kitchen (212): Floor area available: 13.90 m2. |
| minimum_opening_dimension | space | 212 | Kitchen | Kitchen (212): At least one linked window meets minimum dimensions (0.60m x 1.00m). |
| living_space_direct_natural_light | space | 212 | Kitchen | Kitchen (212): Not a living area; rule not mandatory for this space type. |
| floor_area_available | space | 1782 | Kitchen | Kitchen (1782): Floor area available: 13.90 m2. |
| minimum_opening_dimension | space | 1782 | Kitchen | Kitchen (1782): At least one linked window meets minimum dimensions (0.60m x 1.00m). |
| living_space_direct_natural_light | space | 1782 | Kitchen | Kitchen (1782): Not a living area; rule not mandatory for this space type. |
| floor_area_available | space | 2637 | Bathroom 2 | Bathroom 2 (2637): Floor area available: 5.44 m2. |
| living_space_direct_natural_light | space | 2637 | Bathroom 2 | Bathroom 2 (2637): Not a living area; rule not mandatory for this space type. |
| floor_area_available | space | 1059 | Bathroom 2 | Bathroom 2 (1059): Floor area available: 5.42 m2. |
| living_space_direct_natural_light | space | 1059 | Bathroom 2 | Bathroom 2 (1059): Not a living area; rule not mandatory for this space type. |
| floor_area_available | space | 355 | Bathroom 1 | Bathroom 1 (355): Floor area available: 4.00 m2. |
| living_space_direct_natural_light | space | 355 | Bathroom 1 | Bathroom 1 (355): Not a living area; rule not mandatory for this space type. |
| floor_area_available | space | 2789 | Bedroom 2 | Bedroom 2 (2789): Floor area available: 26.18 m2. |
| window_to_floor_ratio | space | 2789 | Bedroom 2 | Bedroom 2 (2789): Ratio 0.345 meets minimum 0.125. |
| minimum_opening_dimension | space | 2789 | Bedroom 2 | Bedroom 2 (2789): At least one linked window meets minimum dimensions (0.60m x 1.00m). |
| living_space_direct_natural_light | space | 2789 | Bedroom 2 | Bedroom 2 (2789): Not a living area; rule not mandatory for this space type. |
| floor_area_available | space | 1442 | Bedroom 1 | Bedroom 1 (1442): Floor area available: 26.12 m2. |
| window_to_floor_ratio | space | 1442 | Bedroom 1 | Bedroom 1 (1442): Ratio 0.282 meets minimum 0.125. |
| minimum_opening_dimension | space | 1442 | Bedroom 1 | Bedroom 1 (1442): At least one linked window meets minimum dimensions (0.60m x 1.00m). |
| living_space_direct_natural_light | space | 1442 | Bedroom 1 | Bedroom 1 (1442): Not a living area; rule not mandatory for this space type. |
| floor_area_available | space | 3013 | Bedroom 1 | Bedroom 1 (3013): Floor area available: 26.12 m2. |
| window_to_floor_ratio | space | 3013 | Bedroom 1 | Bedroom 1 (3013): Ratio 0.282 meets minimum 0.125. |
| minimum_opening_dimension | space | 3013 | Bedroom 1 | Bedroom 1 (3013): At least one linked window meets minimum dimensions (0.60m x 1.00m). |
| living_space_direct_natural_light | space | 3013 | Bedroom 1 | Bedroom 1 (3013): Not a living area; rule not mandatory for this space type. |
| floor_area_available | space | 1218 | Bedroom 2 | Bedroom 2 (1218): Floor area available: 26.18 m2. |
| window_to_floor_ratio | space | 1218 | Bedroom 2 | Bedroom 2 (1218): Ratio 0.345 meets minimum 0.125. |
| minimum_opening_dimension | space | 1218 | Bedroom 2 | Bedroom 2 (1218): At least one linked window meets minimum dimensions (0.60m x 1.00m). |
| living_space_direct_natural_light | space | 1218 | Bedroom 2 | Bedroom 2 (1218): Not a living area; rule not mandatory for this space type. |

### Failed Checks
| Check | Scope | Entity ID | Entity | Reason |
| --- | --- | --- | --- | --- |
| window_min_dimension | window | 7407 | M_Fixed:819mm x 759mm:819mm x 759mm:147994 | Window 7407: Width/height (0.82 m, 0.76 m) below minimum (0.60 m, 1.00 m). |
| window_min_dimension | window | 7639 | M_Casement:819mm x 759mm:819mm x 759mm:148607 | Window 7639: Width/height (0.82 m, 0.76 m) below minimum (0.60 m, 1.00 m). |
| window_min_dimension | window | 7743 | M_Fixed:819mm x 759mm:819mm x 759mm:148722 | Window 7743: Width/height (0.82 m, 0.76 m) below minimum (0.60 m, 1.00 m). |
| window_min_dimension | window | 7847 | M_Fixed:819mm x 759mm:819mm x 759mm:149537 | Window 7847: Width/height (0.82 m, 0.76 m) below minimum (0.60 m, 1.00 m). |
| window_min_dimension | window | 7899 | M_Casement:819mm x 759mm:819mm x 759mm:149736 | Window 7899: Width/height (0.82 m, 0.76 m) below minimum (0.60 m, 1.00 m). |
| window_min_dimension | window | 7951 | M_Fixed:819mm x 759mm:819mm x 759mm:149924 | Window 7951: Width/height (0.82 m, 0.76 m) below minimum (0.60 m, 1.00 m). |
| window_min_dimension | window | 22032 | M_Fixed:819mm x 759mm:819mm x 759mm:180663 | Window 22032: Width/height (0.82 m, 0.76 m) below minimum (0.60 m, 1.00 m). |
| window_min_dimension | window | 22084 | M_Fixed:819mm x 759mm:819mm x 759mm:180864 | Window 22084: Width/height (0.82 m, 0.76 m) below minimum (0.60 m, 1.00 m). |
| window_min_dimension | window | 22136 | M_Casement:819mm x 759mm:819mm x 759mm:180994 | Window 22136: Width/height (0.82 m, 0.76 m) below minimum (0.60 m, 1.00 m). |
| window_min_dimension | window | 22240 | M_Fixed:819mm x 759mm:819mm x 759mm:181285 | Window 22240: Width/height (0.82 m, 0.76 m) below minimum (0.60 m, 1.00 m). |
| window_min_dimension | window | 22292 | M_Casement:819mm x 759mm:819mm x 759mm:181548 | Window 22292: Width/height (0.82 m, 0.76 m) below minimum (0.60 m, 1.00 m). |
| window_min_dimension | window | 22344 | M_Fixed:819mm x 759mm:819mm x 759mm:181583 | Window 22344: Width/height (0.82 m, 0.76 m) below minimum (0.60 m, 1.00 m). |
| window_min_dimension | window | 23162 | M_Skylight:1180 x 1170mm:1180 x 1170mm:185337 | Window 23162: Width/height (1.17 m, 0.63 m) below minimum (0.60 m, 1.00 m). |
| window_min_dimension | window | 23251 | M_Skylight:1180 x 1170mm:1180 x 1170mm:185718 | Window 23251: Width/height (1.17 m, 0.63 m) below minimum (0.60 m, 1.00 m). |
| window_to_floor_ratio | space | 514 | Foyer | Foyer (514): Ratio 0.000 is below minimum 0.125. |
| minimum_opening_dimension | space | 514 | Foyer | Foyer (514): No windows linked to this space. |
| window_to_floor_ratio | space | 819 | Hallway | Hallway (819): Ratio 0.000 is below minimum 0.125. |
| minimum_opening_dimension | space | 819 | Hallway | Hallway (819): No windows linked to this space. |
| window_to_floor_ratio | space | 1928 | Bathroom 1 | Bathroom 1 (1928): Ratio 0.000 is below minimum 0.125. |
| minimum_opening_dimension | space | 1928 | Bathroom 1 | Bathroom 1 (1928): No windows linked to this space. |
| window_to_floor_ratio | space | 2108 | Foyer | Foyer (2108): Ratio 0.000 is below minimum 0.125. |
| minimum_opening_dimension | space | 2108 | Foyer | Foyer (2108): No windows linked to this space. |
| window_to_floor_ratio | space | 2412 | Hallway | Hallway (2412): Ratio 0.000 is below minimum 0.125. |
| minimum_opening_dimension | space | 2412 | Hallway | Hallway (2412): No windows linked to this space. |
| window_to_floor_ratio | space | 3197 | Utility | Utility (3197): Ratio 0.000 is below minimum 0.125. |
| minimum_opening_dimension | space | 3197 | Utility | Utility (3197): No windows linked to this space. |
| window_to_floor_ratio | space | 3325 | Utility | Utility (3325): Ratio 0.000 is below minimum 0.125. |
| minimum_opening_dimension | space | 3325 | Utility | Utility (3325): No windows linked to this space. |
| window_to_floor_ratio | space | 3456 | Stair | Stair (3456): Ratio 0.000 is below minimum 0.125. |
| minimum_opening_dimension | space | 3456 | Stair | Stair (3456): No windows linked to this space. |
| window_to_floor_ratio | space | 3586 | Room | Room (3586): Ratio 0.000 is below minimum 0.125. |
| minimum_opening_dimension | space | 3586 | Room | Room (3586): No windows linked to this space. |
| window_to_floor_ratio | space | 3707 | Roof | Roof (3707): Ratio 0.000 is below minimum 0.125. |
| minimum_opening_dimension | space | 3707 | Roof | Roof (3707): No windows linked to this space. |
| window_to_floor_ratio | space | 212 | Kitchen | Kitchen (212): Ratio 0.119 is below minimum 0.125. |
| window_to_floor_ratio | space | 1782 | Kitchen | Kitchen (1782): Ratio 0.119 is below minimum 0.125. |
| window_to_floor_ratio | space | 2637 | Bathroom 2 | Bathroom 2 (2637): Ratio 0.000 is below minimum 0.125. |
| minimum_opening_dimension | space | 2637 | Bathroom 2 | Bathroom 2 (2637): No windows linked to this space. |
| window_to_floor_ratio | space | 1059 | Bathroom 2 | Bathroom 2 (1059): Ratio 0.000 is below minimum 0.125. |
| minimum_opening_dimension | space | 1059 | Bathroom 2 | Bathroom 2 (1059): No windows linked to this space. |
| window_to_floor_ratio | space | 355 | Bathroom 1 | Bathroom 1 (355): Ratio 0.000 is below minimum 0.125. |
| minimum_opening_dimension | space | 355 | Bathroom 1 | Bathroom 1 (355): No windows linked to this space. |

### Passed Spaces
| ID | Space | Windows | Ratio | Compliant | Pass Reasons |
| --- | --- | --- | --- | --- | --- |
| 1627 | Living Room | 2 | 0.443 | PASS | Floor area available: 30.14 m2.; Ratio 0.443 meets minimum 0.125.; At least one linked window meets minimum dimensions (0.60m x 1.00m).; Living area has at least one linked window. |
| 67 | Living Room | 2 | 0.443 | PASS | Floor area available: 30.14 m2.; Ratio 0.443 meets minimum 0.125.; At least one linked window meets minimum dimensions (0.60m x 1.00m).; Living area has at least one linked window. |
| 2789 | Bedroom 2 | 3 | 0.345 | PASS | Floor area available: 26.18 m2.; Ratio 0.345 meets minimum 0.125.; At least one linked window meets minimum dimensions (0.60m x 1.00m).; Not a living area; rule not mandatory for this space type. |
| 1442 | Bedroom 1 | 2 | 0.282 | PASS | Floor area available: 26.12 m2.; Ratio 0.282 meets minimum 0.125.; At least one linked window meets minimum dimensions (0.60m x 1.00m).; Not a living area; rule not mandatory for this space type. |
| 3013 | Bedroom 1 | 2 | 0.282 | PASS | Floor area available: 26.12 m2.; Ratio 0.282 meets minimum 0.125.; At least one linked window meets minimum dimensions (0.60m x 1.00m).; Not a living area; rule not mandatory for this space type. |
| 1218 | Bedroom 2 | 3 | 0.345 | PASS | Floor area available: 26.18 m2.; Ratio 0.345 meets minimum 0.125.; At least one linked window meets minimum dimensions (0.60m x 1.00m).; Not a living area; rule not mandatory for this space type. |

### Failed Spaces
| ID | Space | Windows | Ratio | Compliant | Failure Reasons |
| --- | --- | --- | --- | --- | --- |
| 514 | Foyer | 0 | 0 | FAIL | Ratio 0.000 is below minimum 0.125.; No windows linked to this space. |
| 819 | Hallway | 0 | 0 | FAIL | Ratio 0.000 is below minimum 0.125.; No windows linked to this space. |
| 1928 | Bathroom 1 | 0 | 0 | FAIL | Ratio 0.000 is below minimum 0.125.; No windows linked to this space. |
| 2108 | Foyer | 0 | 0 | FAIL | Ratio 0.000 is below minimum 0.125.; No windows linked to this space. |
| 2412 | Hallway | 0 | 0 | FAIL | Ratio 0.000 is below minimum 0.125.; No windows linked to this space. |
| 3197 | Utility | 0 | 0 | FAIL | Ratio 0.000 is below minimum 0.125.; No windows linked to this space. |
| 3325 | Utility | 0 | 0 | FAIL | Ratio 0.000 is below minimum 0.125.; No windows linked to this space. |
| 3456 | Stair | 0 | 0 | FAIL | Ratio 0.000 is below minimum 0.125.; No windows linked to this space. |
| 3586 | Room | 0 | 0 | FAIL | Ratio 0.000 is below minimum 0.125.; No windows linked to this space. |
| 3707 | Roof | 0 | 0 | FAIL | Ratio 0.000 is below minimum 0.125.; No windows linked to this space. |
| 212 | Kitchen | 1 | 0.119 | FAIL | Ratio 0.119 is below minimum 0.125. |
| 1782 | Kitchen | 1 | 0.119 | FAIL | Ratio 0.119 is below minimum 0.125. |
| 2637 | Bathroom 2 | 0 | 0 | FAIL | Ratio 0.000 is below minimum 0.125.; No windows linked to this space. |
| 1059 | Bathroom 2 | 0 | 0 | FAIL | Ratio 0.000 is below minimum 0.125.; No windows linked to this space. |
| 355 | Bathroom 1 | 0 | 0 | FAIL | Ratio 0.000 is below minimum 0.125.; No windows linked to this space. |

## Bonus - Fire Safety
### Longest Route
| From | To Exit | Path | Distance m |
| --- | --- | --- | --- |
| Bathroom 1 | Foyer | Bathroom 1 -> Foyer | 3.117 |

### Passed Checks
| Check | Scope | Entity ID | Entity | Reason |
| --- | --- | --- | --- | --- |
| exit_identification | global | - | - | Identified 4 exit-connected space(s). |
| graph_connectivity_build | global | - | - | Spatial graph built with 12 edge(s). |
| max_travel_distance | global | - | - | Longest travel distance 3.12 m is within limit 25.00 m. |
| exit_door_presence | global | - | - | Found 4 exit door candidate(s). |
| exit_door_min_width | door | 6652 | M_Single-Flush:1250mm x 2010mm:1250mm x 2010mm:146596 | Width 1.25 m meets minimum 0.80 m. |
| exit_door_min_width | door | 6757 | M_Single-Flush:1250mm x 2010mm:1250mm x 2010mm:146678 | Width 1.25 m meets minimum 0.80 m. |
| exit_door_min_width | door | 21821 | M_Single-Glass 1:0813 x 2420mm:0813 x 2420mm:171853 | Width 0.81 m meets minimum 0.80 m. |
| exit_door_min_width | door | 21929 | M_Single-Glass 1:0813 x 2420mm:0813 x 2420mm:171975 | Width 0.81 m meets minimum 0.80 m. |
| dead_end_corridor_length | corridor | 819 | Hallway | Corridor 'Hallway' (819): Not a dead-end corridor. |
| dead_end_corridor_length | corridor | 2412 | Hallway | Corridor 'Hallway' (2412): Not a dead-end corridor. |
| corridor_presence | global | - | - | Identified 2 corridor space(s). |

### Failed Checks
| Check | Scope | Entity ID | Entity | Reason |
| --- | --- | --- | --- | --- |
| all_spaces_reachable_to_exit | global | - | - | Some spaces are not connected to an exit path. |

### Warnings
| Check | Scope | Entity ID | Entity | Warning |
| --- | --- | --- | --- | --- |
| corridor_min_width | corridor | 819 | Hallway | Corridor 'Hallway' (819): Corridor width missing; width check could not be evaluated. |
| corridor_min_width | corridor | 2412 | Hallway | Corridor 'Hallway' (2412): Corridor width missing; width check could not be evaluated. |
