# 时间标记中的玄机：高质量视频推理分割

发布时间：2025年01月14日

`LLM应用

**理由**：该论文提出了一种端到端的视频推理分割方法，利用多模态大型语言模型（MLLMs）来捕捉复杂的时空特征。虽然涉及视频分割，但其核心创新在于利用MLLM的自回归学习能力来增强模型的性能，因此属于LLM应用的范畴。` `视频处理` `计算机视觉`

> The Devil is in Temporal Token: High Quality Video Reasoning Segmentation

# 摘要

> 现有的视频推理分割方法过于依赖单一标记来表示关键帧或视频中的对象，难以捕捉复杂的空间和帧间运动。为此，我们提出了VRS-HQ，一种端到端的视频推理分割方法，通过多模态大型语言模型（MLLMs）将丰富的时空特征注入分层标记。我们的核心创新包括时间动态聚合（TDA）和标记驱动的关键帧选择（TKS）。具体来说，我们设计了帧级<SEG>和时间级<TAK>标记，利用MLLM的自回归学习有效捕捉局部和全局信息。随后，采用基于相似性的加权融合和帧选择策略，并利用SAM2进行关键帧分割和传播。TKS在推理过程中根据SAM2的遮挡分数筛选关键帧，以提高定位精度。VRS-HQ在ReVOS上表现卓越，在三个子集的J&F分数上分别超越VISA 5.9%/12.5%/9.1%，展现了强大的时间推理和分割能力。代码和模型权重将在VRS-HQ发布。

> Existing methods for Video Reasoning Segmentation rely heavily on a single special token to represent the object in the keyframe or the entire video, inadequately capturing spatial complexity and inter-frame motion. To overcome these challenges, we propose VRS-HQ, an end-to-end video reasoning segmentation approach that leverages Multimodal Large Language Models (MLLMs) to inject rich spatiotemporal features into hierarchical tokens.Our key innovations include a Temporal Dynamic Aggregation (TDA) and a Token-driven Keyframe Selection (TKS). Specifically, we design frame-level <SEG> and temporal-level <TAK> tokens that utilize MLLM's autoregressive learning to effectively capture both local and global information. Subsequently, we apply a similarity-based weighted fusion and frame selection strategy, then utilize SAM2 to perform keyframe segmentation and propagation. To enhance keyframe localization accuracy, the TKS filters keyframes based on SAM2's occlusion scores during inference. VRS-HQ achieves state-of-the-art performance on ReVOS, surpassing VISA by 5.9%/12.5%/9.1% in J&F scores across the three subsets. These results highlight the strong temporal reasoning and segmentation capabilities of our method. Code and model weights will be released at VRS-HQ.

[Arxiv](https://arxiv.org/abs/2501.08549)