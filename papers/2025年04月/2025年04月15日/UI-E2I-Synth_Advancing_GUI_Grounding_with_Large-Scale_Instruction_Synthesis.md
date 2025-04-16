# # 标题
UI-E2I-Synth: 提升GUI定位能力，通过大规模指令合成实现新突破

发布时间：2025年04月15日

`LLM应用` `视觉语言模型` `图形用户界面`

> UI-E2I-Synth: Advancing GUI Grounding with Large-Scale Instruction Synthesis

# 摘要

> 大型视觉语言模型的突破正在推动基于人类视觉感知能力的图形用户界面（GUI）代理的发展，从而提升数字设备的生产力。与依赖平台且易受实现差异影响的基于GUI元数据的方法相比，视觉方法具有更广泛的应用前景。在这一视觉范式下，GUI指令定位（将用户指令映射到给定截图中对应元素的位置）仍然是一个关键挑战，尤其是由于公共训练数据集的有限和资源密集型的人工指令数据标注。在本文中，我们深入探讨了这一任务中尚未被研究的挑战，包括元素与屏幕比例、元素类型不平衡以及隐式指令。为了解决这些挑战，我们引入了一个大规模数据合成管道UI-E2I-Synth，利用GPT-4o生成各种复杂指令数据集，而不是依赖人工标注者。此外，我们提出了一个新的GUI指令定位基准UI-I2E-Bench，该基准通过整合多样化的标注方面，旨在克服现有基准的局限性。在合成数据上训练的我们的模型在GUI指令定位任务中表现出色，展示了所提数据合成管道的优势。该基准配合详尽的分析，为未来GUI定位研究提供了实用的见解。我们将在https://colmon46.github.io/i2e-bench-leaderboard/发布相关成果。

> Recent advancements in Large Vision-Language Models are accelerating the development of Graphical User Interface (GUI) agents that utilize human-like vision perception capabilities to enhance productivity on digital devices. Compared to approaches predicated on GUI metadata, which are platform-dependent and vulnerable to implementation variations, vision-based approaches offer broader applicability. In this vision-based paradigm, the GUI instruction grounding, which maps user instruction to the location of corresponding element on the given screenshot, remains a critical challenge, particularly due to limited public training dataset and resource-intensive manual instruction data annotation.In this paper, we delve into unexplored challenges in this task including element-to-screen ratio, unbalanced element type, and implicit instruction. To address these challenges, we introduce a large-scale data synthesis pipeline UI-E2I-Synth for generating varying complex instruction datasets using GPT-4o instead of human annotators. Furthermore, we propose a new GUI instruction grounding benchmark UI-I2E-Bench, which is designed to address the limitations of existing benchmarks by incorporating diverse annotation aspects. Our model, trained on the synthesized data, achieves superior performance in GUI instruction grounding, demonstrating the advancements of proposed data synthesis pipeline. The proposed benchmark, accompanied by extensive analyses, provides practical insights for future research in GUI grounding. We will release corresponding artifacts at https://colmon46.github.io/i2e-bench-leaderboard/

[Arxiv](https://arxiv.org/abs/2504.11257)