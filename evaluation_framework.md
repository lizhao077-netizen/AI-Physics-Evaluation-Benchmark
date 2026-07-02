# Evaluation Framework

This benchmark uses a shared evaluation framework across all cases. The goal is to evaluate not only whether an AI model reaches the correct final answer, but also whether it builds a valid physics model, reasons consistently, teaches clearly, and recovers from feedback.

## Evaluation Dimensions

| Dimension | Description |
|---|---|
| Physics Accuracy | Final answer correctness |
| Physical Modeling | Whether assumptions, force analysis, constraints, and reference frames are correct |
| Reasoning Process | Logical consistency from problem setup to conclusion |
| Teaching Quality | Educational value for a high school physics learner |
| Error Recovery | Ability to revise after teacher feedback |

## Rubric

| Rating | Meaning |
|---:|---|
| 5 | Excellent |
| 4 | Minor issue |
| 3 | Moderate issue |
| 2 | Major issue |
| 1 | Completely incorrect |

## Standard Case Rating Table

Each case uses the same rating categories:

| Category | Rating |
|---|---|
| Physics Accuracy |  |
| Physical Modeling |  |
| Assumption Verification |  |
| Teaching Quality |  |
| Error Recovery |  |

## Evaluation Principle

The benchmark treats an answer as incomplete if the final result is correct but the physical assumptions are unstable, unverified, or pedagogically misleading. This is especially important for AI tutor systems, where a model must guide students through reliable reasoning rather than only produce an answer.
