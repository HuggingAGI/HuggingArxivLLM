# CoherenDream：借助多模态大语言模型反馈，提升3D生成中的整体文本连贯性

发布时间：2025年04月28日

`LLM应用

理由：这篇论文探讨了如何将多模态大型语言模型（MLLMs）应用于改进文本到3D内容生成的过程，特别是在保持语义一致性和优化生成效果方面。研究提出了一种新的方法，结合MLLMs的反馈来提升生成质量，属于LLM的应用层面创新。` `3D生成` `计算机视觉`

> CoherenDream: Boosting Holistic Text Coherence in 3D Generation via Multimodal Large Language Models Feedback

# 摘要

> 评分蒸馏采样（SDS）在文本到3D内容生成领域取得了显著的成功。然而，基于SDS的方法在保持用户提示的语义保真度方面仍面临挑战，尤其是在涉及多个复杂交互对象的情况下。现有的方法通常通过在3D数据集上对多视图扩散模型进行微调来解决3D一致性问题，但这种策略无意中加剧了文本与3D对齐的退化。这一限制源于SDS在优化过程中固有的视图无关偏差的累积，这使其逐渐偏离理想的文本对齐方向。为了解决这一限制，我们提出了一种新型的SDS目标，名为文本一致性评分蒸馏（TCSD），它整合了来自多模态大型语言模型（MLLMs）的对齐反馈。我们的TCSD利用MLLMs的跨模态理解能力，在优化过程中评估和引导文本与3D对应关系。我们还开发了3DLLaVA-CRITIC——一种专门用于评估3D生成中多视图文本对齐的微调MLLM。此外，我们引入了一种基于语义感知空间配置的LLM布局初始化方法，这大大加快了优化收敛速度。 comprehensive evaluations demonstrate that our framework, CoherenDream, establishes state-of-the-art performance in text-aligned 3D generation across multiple benchmarks, including T$^3$Bench and TIFA subset. Qualitative results showcase the superior performance of CoherenDream in preserving textual consistency and semantic interactions. 作为首个将MLLMs纳入SDS优化的研究，我们还进行了广泛的消融研究，以探索3D生成任务中MLLM的最佳适应性。

> Score Distillation Sampling (SDS) has achieved remarkable success in text-to-3D content generation. However, SDS-based methods struggle to maintain semantic fidelity for user prompts, particularly when involving multiple objects with intricate interactions. While existing approaches often address 3D consistency through multiview diffusion model fine-tuning on 3D datasets, this strategy inadvertently exacerbates text-3D alignment degradation. The limitation stems from SDS's inherent accumulation of view-independent biases during optimization, which progressively diverges from the ideal text alignment direction. To alleviate this limitation, we propose a novel SDS objective, dubbed as Textual Coherent Score Distillation (TCSD), which integrates alignment feedback from multimodal large language models (MLLMs). Our TCSD leverages cross-modal understanding capabilities of MLLMs to assess and guide the text-3D correspondence during the optimization. We further develop 3DLLaVA-CRITIC - a fine-tuned MLLM specialized for evaluating multiview text alignment in 3D generations. Additionally, we introduce an LLM-layout initialization that significantly accelerates optimization convergence through semantic-aware spatial configuration. Comprehensive evaluations demonstrate that our framework, CoherenDream, establishes state-of-the-art performance in text-aligned 3D generation across multiple benchmarks, including T$^3$Bench and TIFA subset. Qualitative results showcase the superior performance of CoherenDream in preserving textual consistency and semantic interactions. As the first study to incorporate MLLMs into SDS optimization, we also conduct extensive ablation studies to explore optimal MLLM adaptations for 3D generation tasks.

[Arxiv](https://arxiv.org/abs/2504.19860)