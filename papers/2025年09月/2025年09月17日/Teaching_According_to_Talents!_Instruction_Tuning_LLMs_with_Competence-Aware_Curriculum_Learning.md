# 因材施教！基于能力感知的课程学习指令微调大型语言模型

发布时间：2025年09月17日

`LLM应用` `基础理论`

> Teaching According to Talents! Instruction Tuning LLMs with Competence-Aware Curriculum Learning

# 摘要

> 高效指令微调的目标是提升在特定指令数据集上训练的大型语言模型（LLMs）的最终性能。课程学习作为经典的数据组织策略，已在指令微调中展现出初步成效。然而，现有课程微调方法存在课程刚性缺陷，因其完全依赖静态的启发式难度指标。这些方法无法适应模型训练过程中能力的动态变化，从而形成固定且可能非最优的学习路径。为解决这一难题，我们提出了名为CAMPUS的能力感知多视角课程指令微调框架。CAMPUS具备多项优势：（1）子课程动态选择；（2）能力感知的课程进度调整；（3）多维度难度调度机制。大量实验结果表明，与其他最先进的高效指令微调基线方法相比，CAMPUS性能更优。

> Efficient instruction tuning aims to enhance the ultimate performance of large language models (LLMs) trained on a given instruction dataset. Curriculum learning as a typical data organization strategy has shown preliminary effectiveness in instruction tuning. However, current curriculum tuning methods suffer from the curriculum rigidity, since they rely solely on static heuristic difficulty metrics. These methods fail to adapt to the evolving capabilities of models during training, resulting in a fixed and potentially sub-optimal learning trajectory. To address the issue, Competence-Aware Multi-Perspective cUrriculum inStruction tuning framework termed CAMPUS is proposed. CAMPUS offers several advantages: (1) Dynamic selection for sub-curriculum. (2) Competency-aware adjustment to the curriculum schedule. (3) Multiple difficulty-based scheduling. Extensive experiments prove the superior performance of CAMPUS, compared to other state-of-the-art baselines for efficient instruction tuning.

[Arxiv](https://arxiv.org/abs/2509.13790)