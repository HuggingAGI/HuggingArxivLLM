# LlamaV-o1: 重新审视LLMs中的逐步视觉推理

发布时间：2025年01月10日

`LLM应用

理由：这篇论文主要讨论了如何通过设计一个专门的视觉推理基准和提出新的评估指标来推进大型语言模型（LLMs）在逐步视觉推理中的应用。论文还介绍了一个多模态视觉推理模型LlamaV-o1，并通过实验展示了其在多步骤推理任务中的优越性能。这些内容都属于LLM在实际应用中的改进和优化，因此应归类为“LLM应用”。` `视觉推理` `人工智能`

> LlamaV-o1: Rethinking Step-by-step Visual Reasoning in LLMs

# 摘要

> # 摘要
推理是解决复杂多步骤问题的核心能力，尤其在需要逐步理解的视觉场景中。现有方法缺乏全面的视觉推理评估框架，且未强调逐步解决问题。为此，我们提出了一个框架，通过三大贡献推进大型语言模型（LMMs）中的逐步视觉推理。首先，我们设计了一个专门评估多步骤推理任务的视觉推理基准，涵盖从复杂视觉感知到科学推理的八类挑战，总计超过4k个推理步骤，全面评估LLMs在多步骤中进行准确且可解释的视觉推理能力。其次，我们提出了一种新颖的指标，在单个步骤粒度上评估视觉推理质量，强调正确性和逻辑一致性，相比传统任务结束准确性指标，提供了更深入的推理性能洞察。第三，我们推出了多模态视觉推理模型LlamaV-o1，采用多步骤课程学习训练，任务逐步组织以促进增量技能获取和问题解决。LlamaV-o1专为多步骤推理设计，通过结构化训练范式逐步学习。实验表明，LlamaV-o1优于现有开源模型，且在闭源专有模型上也表现出色。与Llava-CoT相比，LlamaV-o1在六个基准测试中平均得分为67.3，绝对增益3.8%，推理速度提升5倍。我们的基准、模型和代码均已公开。

> Reasoning is a fundamental capability for solving complex multi-step problems, particularly in visual contexts where sequential step-wise understanding is essential. Existing approaches lack a comprehensive framework for evaluating visual reasoning and do not emphasize step-wise problem-solving. To this end, we propose a comprehensive framework for advancing step-by-step visual reasoning in large language models (LMMs) through three key contributions. First, we introduce a visual reasoning benchmark specifically designed to evaluate multi-step reasoning tasks. The benchmark presents a diverse set of challenges with eight different categories ranging from complex visual perception to scientific reasoning with over 4k reasoning steps in total, enabling robust evaluation of LLMs' abilities to perform accurate and interpretable visual reasoning across multiple steps. Second, we propose a novel metric that assesses visual reasoning quality at the granularity of individual steps, emphasizing both correctness and logical coherence. The proposed metric offers deeper insights into reasoning performance compared to traditional end-task accuracy metrics. Third, we present a new multimodal visual reasoning model, named LlamaV-o1, trained using a multi-step curriculum learning approach, where tasks are progressively organized to facilitate incremental skill acquisition and problem-solving. The proposed LlamaV-o1 is designed for multi-step reasoning and learns step-by-step through a structured training paradigm. Extensive experiments show that our LlamaV-o1 outperforms existing open-source models and performs favorably against close-source proprietary models. Compared to the recent Llava-CoT, our LlamaV-o1 achieves an average score of 67.3 with an absolute gain of 3.8\% across six benchmarks while being 5 times faster during inference scaling. Our benchmark, model, and code are publicly available.

[Arxiv](https://arxiv.org/abs/2501.06186)