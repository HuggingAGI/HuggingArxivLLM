# 通过任务感知的专家混合模型，化解统一多模态理解和生成中的任务目标冲突

发布时间：2025年06月04日

`LLM应用` `多模态模型`

> Resolving Task Objective Conflicts in Unified Multimodal Understanding and Generation via Task-Aware Mixture-of-Experts

# 摘要

> 基于端到端自回归（AR）变压器的统一多模态大型语言模型（MLLMs）在一个框架内整合了理解和生成任务。然而，理解和生成任务之间存在固有的目标冲突：理解需要高层语义抽象，而生成则需保留细节，这带来了重大挑战，常常导致次优的权衡和任务干扰。现有解决方案，如分离共享的视觉编码器，未能从根本解决这些冲突，原因在于AR架构的本质。本文提出了一种新方法，通过分离AR的内部组件来解决任务目标冲突。具体来说，我们设计了UTAMoE，一个统一的任务感知专家混合（MoE）框架，它通过任务感知MoE层分离AR内部模块，创建任务特定的优化子路径。为了增强任务区分度同时保持整体协调，我们引入了一种新型的两阶段训练策略。在多模态基准上的广泛实验表明，UTAMoE缓解了任务目标冲突，在各种任务中达到了最先进的性能。可视化和消融研究进一步验证了我们方法的有效性。

> Unified multimodal large language models (MLLMs) based on end-to-end autoregressive (AR) transformers effectively integrate both understanding and generation tasks within a single framework. However, intrinsic Task Objective Conflicts between high-level semantic abstraction in understanding and fine-grained detail preservation in generation pose significant challenges, often leading to suboptimal trade-offs and task interference. Existing solutions, such as decoupling shared visual encoders, fall short of fundamentally resolving these conflicts due to inherent AR architecture. In this paper, we propose a novel approach that decouples internal components of AR to resolve task objective conflicts. Specifically, we design UTAMoE, a Unified Task-Aware Mixture-of-Experts (MoE) framework that decouples internal AR modules via a Task-Aware MoE Layer to create task-specific optimization subpaths. To enhance task differentiation while maintaining overall coordination, we introduce a novel Two-Stage Training Strategy. Extensive experiments on multimodal benchmarks demonstrate that UTAMoE mitigates task objective conflicts, achieving state-of-the-art performance across various tasks. Visualizations and ablation studies further validate the effectiveness of our approach.

[Arxiv](https://arxiv.org/abs/2506.03591)