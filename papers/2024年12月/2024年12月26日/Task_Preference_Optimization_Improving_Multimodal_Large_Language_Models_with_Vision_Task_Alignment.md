# 任务偏好优化：视觉任务对齐助力多模态大语言模型升级

发布时间：2024年12月26日

`LLM应用

**理由**：这篇论文主要讨论了如何通过任务偏好优化（TPO）来提升多模态大型语言模型（MLLMs）在视觉任务中的表现。虽然涉及了多模态和视觉任务，但其核心是优化和改进现有的大型语言模型在特定应用场景中的性能，因此应归类为LLM应用。` `计算机视觉` `多模态学习`

> Task Preference Optimization: Improving Multimodal Large Language Models with Vision Task Alignment

# 摘要

> 当前的多模态大型语言模型（MLLMs）虽然在多种视觉应用中展现了全面的感知和推理能力，但在细粒度或精确的视觉理解上仍有不足。最近的研究要么开发工具使用，要么将特定视觉任务统一到自回归框架中，但往往以牺牲整体多模态性能为代价。为了解决这一问题并以可扩展的方式提升MLLMs在视觉任务中的表现，我们提出了任务偏好优化（TPO），这是一种利用典型细粒度视觉任务中可微分任务偏好的新方法。TPO通过引入可学习的任务标记，在多个任务特定头和MLLM之间建立连接。借助训练中丰富的视觉标签，TPO显著增强了MLLM的多模态能力和任务特定性能。通过TPO中的多任务协同训练，我们观察到协同效应，将单个任务的性能提升到单任务训练方法无法达到的水平。我们在VideoChat和LLaVA上实现了这一方法，与基线模型相比，多模态性能整体提升了14.6%。此外，MLLM-TPO在各种任务中展现了强大的零样本能力，其表现与最先进的监督模型相当。代码将在https://github.com/OpenGVLab/TPO发布。

> Current multimodal large language models (MLLMs) struggle with fine-grained or precise understanding of visuals though they give comprehensive perception and reasoning in a spectrum of vision applications. Recent studies either develop tool-using or unify specific visual tasks into the autoregressive framework, often at the expense of overall multimodal performance. To address this issue and enhance MLLMs with visual tasks in a scalable fashion, we propose Task Preference Optimization (TPO), a novel method that utilizes differentiable task preferences derived from typical fine-grained visual tasks. TPO introduces learnable task tokens that establish connections between multiple task-specific heads and the MLLM. By leveraging rich visual labels during training, TPO significantly enhances the MLLM's multimodal capabilities and task-specific performance. Through multi-task co-training within TPO, we observe synergistic benefits that elevate individual task performance beyond what is achievable through single-task training methodologies. Our instantiation of this approach with VideoChat and LLaVA demonstrates an overall 14.6% improvement in multimodal performance compared to baseline models. Additionally, MLLM-TPO demonstrates robust zero-shot capabilities across various tasks, performing comparably to state-of-the-art supervised models. The code will be released at https://github.com/OpenGVLab/TPO

[Arxiv](https://arxiv.org/abs/2412.19326)