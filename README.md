# 论文陪读教练 / Paper Learning Companion

面向零基础读者的 Codex 论文阅读 skill。它将论文陪读组织为“先建全局地图、再按卡点深入”的学习过程，并把论文事实、背景知识与教学推断分开。

## 能做什么

- 用中文建立论文的研究问题、方法主线、实验证据和局限；
- 对公式、图表、机制提供由浅入深的局部拆解；
- 根据需要生成概念图、可编辑图设计、学习笔记与动态机制演示；
- 动画优先使用具体玩具场景，不将联合优化误画为物理拉拽；图内只保留标明为示例的少量数值，公式放在配套讲解中。

## 安装

将整个目录复制到 Codex skills 目录：

```powershell
git clone https://github.com/Speraymer/paper-learning-companion "$env:USERPROFILE\.codex\skills\paper-learning-companion"
```

重启或刷新 Codex 后，上传论文并直接说“带我读这篇论文”即可。

## 设计边界

本 skill 不替代论文原文核查：关键结论应回溯到页码、图表、公式或附录。外部检索材料和教学示意会与论文实证结果明确区分。

## License

[MIT](LICENSE)
