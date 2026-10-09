# Rigor Protocol

Use this protocol for long explanations, generated artifacts, method analysis, evidence review, figures, or reproduction work. It sets decision standards; it does not override the user's current goal.

## Modes

| Mode | Minimum completion | Do not |
| --- | --- | --- |
| Scan | Problem, gap, method, one result, limitation, next section | Present a scan as deep reading |
| Full reading | Map of problem, method, evidence, and conclusion | Conclude before reading methods and experiments |
| Review | Claim–evidence matrix, alternatives, concrete evidence request | Substitute generic criticism for analysis |
| Research transfer | Transferable assumptions, methods, evidence, and non-transfer conditions | Call an idea directly reusable without qualification |

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

Explain methods in the paper's order: goal, objects/assumptions, mechanism, connections, inputs/outputs, training/inference, cost, and applicability. Keep only essential equations, explaining variables, units/conditions, objectives, weights, and constraints. For a figure, state its question before panels, axes, units, controls, trends, errors, and sample size; then separate what it supports from what it cannot support.

For generated HTML/PDF, ensure readable layout, source locations, distinction between source/redrawn material, and successful rendering. For editable figures, use editable text, shapes, and connectors and check direction, overlap, alignment, print legibility, and opening. For scientific computing, inspect sources/units, run a minimum verification, and protect source data. End with architecture, principle, and evidence options.

<!-- 中文注释：本协议规定不同阅读模式的最低完成标准，并按论文类型选择证据规则。重要内容要维护“主张—直接证据—来源—支持强度—不能推出什么”的账本；方法、公式、图表、实验和生成文件都必须可核查。 -->
