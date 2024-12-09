# MageBench：搭建大型多模态模型与代理之间的桥梁

发布时间：2024年12月05日

`Agent` `多模态代理` `视觉推理`

> MageBench: Bridging Large Multimodal Models to Agents

# 摘要

> LMMs 展现出了令人瞩目的视觉理解能力，有望应用于对推理和规划能力要求颇高的代理中。然而，现有的基准测试大多在语言部分评估其推理能力，其中的思维链完全由文本构成。我们考虑这样一种情形：在决策过程中，视觉信号不断更新且必不可少。这种链中视觉推理范式更契合多模态代理的需求，却鲜少得到评估。在本文中，我们推出了 MageBench，这是一个以推理能力为导向的多模态代理基准，虽具有轻量级环境，但带来了重大的推理挑战，且极具实用价值。该基准目前涵盖三种类型的环境：WebUI、Sokoban 和 Football，总计包含 483 种不同场景。它全面检验了代理的知识与工程能力、视觉智能和交互技能。结果显示，仅有少数产品级模型优于随机行为，且它们都远逊于人类水平。更确切地说，我们发现当前的模型严重缺乏依据视觉反馈修改规划的能力，以及视觉想象、交错的图像 - 文本长上下文处理等能力。我们期望我们的工作能从代理的视角为 LMM 提供优化方向。我们在 https://github.com/microsoft/MageBench 发布了代码和数据。

> LMMs have shown impressive visual understanding capabilities, with the potential to be applied in agents, which demand strong reasoning and planning abilities. Nevertheless, existing benchmarks mostly assess their reasoning abilities in language part, where the chain-of-thought is entirely composed of text.We consider the scenario where visual signals are continuously updated and required along the decision making process. Such vision-in-the-chain reasoning paradigm is more aligned with the needs of multimodal agents, while being rarely evaluated. In this paper, we introduce MageBench, a reasoning capability oriented multimodal agent benchmark that, while having light-weight environments, poses significant reasoning challenges and holds substantial practical value. This benchmark currently includes three types of environments: WebUI, Sokoban, and Football, comprising a total of 483 different scenarios. It thoroughly validates the agent's knowledge and engineering capabilities, visual intelligence, and interaction skills. The results show that only a few product-level models are better than random acting, and all of them are far inferior to human-level. More specifically, we found current models severely lack the ability to modify their planning based on visual feedback, as well as visual imagination, interleaved image-text long context handling, and other abilities. We hope that our work will provide optimization directions for LMM from the perspective of being an agent. We release our code and data at https://github.com/microsoft/MageBench.

[Arxiv](https://arxiv.org/abs/2412.04531)