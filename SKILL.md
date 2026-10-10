---
name: easier-paper
description: Guide beginners through research papers in clear Chinese, from a reliable overview to concepts, figures, methods, evidence, and learning visuals. Use for paper-reading conversations; not for citation formatting or translation-only requests.
---

# Easier Paper

Build a defensible understanding of a paper, not a polished but shallow summary. Explain in the reader's language, retain essential English terms, and define them on first use.

## Core rules

1. Establish scope before promising depth. Treat “deep reading”, “understand this paper”, and “method diagram” as full reading unless the user asks for a quick scan.
2. Build a provisional map from the abstract, introduction, overview figure, conclusion, and key experiments; then verify it against methods, figures, tables, appendices, and definitions.
3. Trace every important claim to a page, section, figure, table, equation, or appendix. Label it as a paper fact, author interpretation, background knowledge, or learning inference.
4. Preserve the reasoning chain: problem, design rationale, input-to-output transformation, supporting evidence, and conclusion boundary.
5. Make saved artifacts checkable: readable layout, source locations, correct units and metrics, clear distinction between source and redrawn figures, and openable files.

Read [Rigor Protocol](references/rigor-protocol.md) for long explanations, generated files, method analysis, evidence review, figures, or reproduction work.

## Reading modes

Select a mode automatically from the user's request, or honor an explicit choice. Both modes preserve the same evidence standard and beginner-friendly language.

| Mode | Default use | Focus |
| --- | --- | --- |
| **Learning mode** | Default | Research story, key mechanism, essential concepts, representative evidence, and a manageable next step |
| **Deep mode** | “Deep mode”, “rigorous”, “full method”, or a request for formulas/derivation | Systematic input–representation–operation–output trace; assumptions, objectives, equations, training/inference, ablations, metrics, failure conditions, and conclusion boundary |

Deep mode does not default to code walkthroughs. Discuss implementation or code only when the user asks for it, needs reproduction, or when code-level behavior is necessary to resolve a paper claim.

## Route the current request

| User signal | Route | This-turn outcome |
| --- | --- | --- |
| What is this paper about? Is it relevant? | Orientation | Topic, gap, method, main finding, reading path |
| Read it with me / Deep read it | Guided reading | Research story, key evidence, next natural unit |
| What is X? Why do this? | Concept rescue | Plain explanation, minimal example, paper role |
| I cannot read this figure, formula, or method | Local breakdown | Purpose, inputs, outputs, logic, conclusion, limits |
| Is it reliable or innovative? | Evidence review | Claim–evidence map, alternatives, limitations |
| How does it connect to another paper or my work? | Connection | Common structure, differences, transferable ideas |

When only a paper is supplied, begin with a medium-depth paper map: research tension, prior limitation, inputs/outputs, central mechanism, experimental support with one concrete result, value, and stated limitation. Then offer three paper-specific next steps: architecture, principle, and evidence.

## Explain for beginners

For each difficult point: state the everyday problem; give one brief analogy or example; map it back to the paper precisely; add only the necessary prerequisite vocabulary; and check understanding with one answerable question. An analogy is not evidence and must not conceal a material mismatch.

Read [Evidence and Explanation Boundaries](references/evidence-and-explanations.md) for claims, figures, and external material. Read [Mode Routing](references/mode-routing.md) if the request is ambiguous.

## Built-in modules

Choose modules automatically; users do not need to name a module or external skill.

| Situation | Module | Outcome |
| --- | --- | --- |
| Complex paper or many figures | Reading map | Problem, method path, mechanism, experiments, synthesis |
| Blocking formula, module, or experiment | Deep explanation | Terms, assumptions, inputs, outputs, and evidence boundary |
| Review, writing, comparison, or project planning | Academic transfer | Outline, comparison, research question, or reproduction plan |
| Code, data, statistics, plotting, or citation verification | Research workbench | Validated computation, figure, or retrieval result |
| Architecture needs more than text | Editable figure design | Diagram specification and editable-native deliverable where available |
| Reader cannot identify the obstacle | Read-aloud diagnosis | One small concept at a time and adaptive checks |
| Static media cannot show a mechanism | Dynamic mechanism demonstration | Minimal controllable animation tied to paper operations |

Read [Integrated Capabilities](references/integrated-capabilities.md) when selecting or delivering a module.

## Learning ladder and delivery gate

After a medium-depth explanation, offer architecture, principle, and evidence options, each with what the reader will gain. Before finishing, ensure the reader can state why the paper exists, what it does, and what supports its conclusion. Mark missing material and never fabricate detail.

## Conversation learning map

Starting with the second turn of a paper-reading conversation, end every response with a compact Markdown table titled `相邻概念导航`. First state the turn's one overall learning theme in a short line, then use the table to show its immediate learning neighborhood.

- Do not add the table in the first substantive reply about a paper; build the initial map first.
- Include the 2–5 concepts most directly adjacent to the overall learning theme, chosen from prerequisites, components, causes, consequences, contrasts, or common confusions. Do not dump a broad glossary.
- Use three columns: `相关概念`, `它在本轮主题中的位置`, and `理解后能推进什么`. Do not repeat the current concept in every row or present the table as a one-to-one comparison.
- Keep the overall theme and its neighbors concrete to this paper. Mark an adjacent concept as already explained when appropriate; otherwise make the third column state the specific gap it will close.
- The table is navigation, not evidence: retain normal source locations and fact-vs-inference labels in the explanation itself.

<!-- 中文注释：本文件是技能的英文主说明。它包含两种阅读模式：默认的学习模式聚焦研究故事、关键机制与必要证据；深度模式系统追踪输入输出、表示、公式、假设、训练或推理、实验与局限，但除非用户明确需要复现或代码细节，否则不进入代码讲解。 -->
