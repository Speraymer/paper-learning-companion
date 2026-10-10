# Rigor Protocol

Use this protocol for long explanations, generated artifacts, method analysis, evidence review, figures, or reproduction work. It sets decision standards; it does not override the user's current goal.

## Modes

| Mode | Minimum completion | Do not |
| --- | --- | --- |
| Scan | Problem, gap, method, one result, limitation, next section | Present a scan as deep reading |
| Full reading | Map of problem, method, evidence, and conclusion | Conclude before reading methods and experiments |
| Review | Claim–evidence matrix, alternatives, concrete evidence request | Substitute generic criticism for analysis |
| Research transfer | Transferable assumptions, methods, evidence, and non-transfer conditions | Call an idea directly reusable without qualification |

Within either Scan or Full reading, **Deep mode** requires an explicit chain from inputs to representations, operations, outputs, objectives/equations, and evidence. Include assumptions, units or tensor/variable shape where relevant, training or inference stages, ablations, metrics, and failure conditions. Do not substitute a code walkthrough for this chain; inspect code only on user request, for reproduction, or when implementation determines the interpretation of a reported result.

With an abstract, low-resolution image, or incomplete PDF, complete only the supportable portion and state the limitation first.

## Paper-type routing

- **Systems/engineering/robotics:** inputs, sensors/data, state representation, interfaces, optimization/control loop, latency, resources, failure modes.
- **Machine learning:** task, data splits, preprocessing, train/validation/test isolation, baselines, metrics, ablations, leakage, generalization boundary.
- **Theory:** definitions, assumptions, propositions/theorems, proof strategy, conditions, counterexamples; intuition is not proof.
- **Experimental science:** sample, variables, controls, measurement, statistics, repetitions, error, and the evidence chain.
- **Clinical/observational studies:** population, eligibility, exposure/intervention, outcome, confounding, effect size, confidence interval; correlation is not causation.
- **Reviews/meta-analyses:** scope, search and inclusion logic, evidence type, heterogeneity, author position, and field consensus.

Maintain a minimal evidence ledger for each important item: claim, direct evidence, source location, support strength, and what it does not establish. Never estimate exact values from low-resolution curves, treat a proxy as a direct measure, present simulation as experimental validation, equate statistical significance with practical importance, or call missing evidence evidence of absence.

## Methods, artifacts, and learning loop

Explain methods in the paper's order: goal, objects/assumptions, mechanism, connections, inputs/outputs, training/inference, cost, and applicability. Keep only essential equations, explaining variables, units/conditions, objectives, weights, and constraints. For a figure, state its question before panels, axes, units, controls, trends, errors, and sample size; then separate what it supports from what it cannot support. For a local request, inspect the figure or formula, caption, and directly relevant method text first; broaden source inspection only when a required definition, assumption, or evidence link is absent. Do not broaden the user-facing explanation merely because more source context was read.

For generated HTML/PDF, ensure readable layout, source locations, distinction between source/redrawn material, and successful rendering. For editable figures, use editable text, shapes, and connectors and check direction, overlap, alignment, print legibility, and opening. For scientific computing, inspect sources/units, run a minimum verification, and protect source data. End with architecture, principle, and evidence options.

<!-- 中文注释：本协议规定不同阅读模式的最低完成标准。深度模式要求完整追踪输入、表示、操作、输出、目标或公式与证据，并说明假设、变量单位或形状、训练或推理、消融、指标和失效条件；它不默认进入代码导读。局部问题先检查目标、图注和相关方法段，再按缺失定义、假设或证据关系扩大原文阅读；内部阅读范围不自动扩大用户看到的讲解范围。 -->
