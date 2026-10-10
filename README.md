# Easier Paper

A Codex skill for readers who need a reliable, beginner-friendly path through research papers. It provides a Learning mode for understanding-first reading and a Deep mode for rigorous method and evidence tracing.

## Capabilities

- Builds a structured reading map of the research question, method path, evidence, and limitations.
- Explains concepts, equations, figures, and mechanisms from intuition to paper-specific meaning.
- Reviews experimental evidence and the boundary of claimed conclusions.
- Produces learning notes, concept diagrams, editable figure specifications, and dynamic mechanism demonstrations when they materially improve understanding.
- Uses concrete toy scenes for animations; equations stay in the accompanying explanation, while the scene shows only a few clearly marked teaching values.
- Offers Deep mode for inputs, outputs, representations, equations, assumptions, training/inference, and experimental evidence without defaulting to code walkthroughs.

## Installation

Clone the repository into the Codex skills directory:

```powershell
git clone https://github.com/Speraymer/easier-paper "$env:USERPROFILE\.codex\skills\easier-paper"
```

Restart or refresh Codex, upload a paper, and ask to read it together.

## Boundaries

This skill does not replace source verification. Important conclusions should trace back to a page, figure, table, equation, or appendix. External material and teaching visuals are explicitly separated from the paper's empirical evidence.

## License

[MIT](LICENSE)

<!-- 中文注释：Easier Paper 是一个面向论文阅读的 Codex 技能。学习模式先建立研究问题、方法和证据的全局地图；深度模式系统解释输入输出、表示、公式、假设、训练或推理与实验证据，但默认不陷入代码细节。关键结论仍需回查论文原文。 -->
