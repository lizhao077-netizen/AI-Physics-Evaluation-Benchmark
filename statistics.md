# Statistics

## Current Dataset

| Metric | Value |
|---|---:|
| Total Cases | 5 |
| Models Evaluated | ChatGPT |
| Total AI Responses | 18 |
| Major Error Categories | 5 |

## Error Categories

| Error Type | Cases |
|---|---:|
| Physical Modeling | 3 |
| Force Analysis | 1 |
| Geometry Interpretation | 1 |
| Conditional Reasoning | 1 |
| Constraint Modeling | 1 |

## Case Coverage

| Case | Topic | Correction Rounds | Primary Failure |
|---|---|---:|---|
| Case 001 | Electromagnetism | 5 | Physical Modeling |
| Case 002 | Mechanics | 1 | Physical Modeling |
| Case 003 | Electromagnetism | 1 | Geometry Interpretation |
| Case 004 | Electromagnetism | 1 | Conditional Reasoning |
| Case 005 | Mechanics | 5 | Constraint Modeling |

## Overall Findings

The most common issue is not simple calculation failure. The model often knows relevant formulas but applies them before verifying the physical model.

Across the current dataset, common weaknesses include incomplete force analysis, unverified assumptions, incorrect interpretation of constraints, and failure to distinguish possible outcomes from necessary outcomes.

The model usually improves after teacher feedback, which suggests strong error recovery. However, it often depends on external correction rather than proactively checking the consistency of its own assumptions.
