# VideoRFT：通过强化微调提升多语言大型模型的视频推理能力

发布时间：2025年05月18日

`LLM应用` `视频推理`

> VideoRFT: Incentivizing Video Reasoning Capability in MLLMs via Reinforced Fine-Tuning

# 摘要

> 强化学习微调（RFT）在提升大型语言模型（LLMs）的推理能力方面表现出巨大潜力，并已成功扩展至多模态大型语言模型（MLLMs）。然而，视频推理这一人类智能的核心领域仍面临重大挑战，主要源于视频数据中的复杂逻辑、时序和因果关系。为解决这一难题，我们提出了VIDEORFT，一种将RFT范式扩展至MLLMs以实现人类水平视频推理能力的新方法。VIDEORFT采用RFT的标准两阶段流程：首先通过思维链（CoT）注释进行有监督微调（SFT），然后通过强化学习（RL）提升模型的泛化能力。在视频领域实现这一目标的关键挑战在于高质量视频CoT数据集的极度匮乏。我们通过构建一个完全自动化的CoT整理管道来应对这一难题。首先，我们设计了一种认知启发的提示策略，以激发推理LLM仅基于视频内容的丰富、结构化和字面表示生成初步的CoTs。随后，这些CoTs通过基于实际视频的视觉-语言模型进行优化，确保视觉一致性并减少视觉幻觉。这一管道生成了两个新数据集——用于SFT的VideoRFT-CoT-102K和用于RL的VideoRFT-RL-310K。为了进一步增强RL阶段的效果，我们引入了一种创新的语义一致性奖励机制，旨在明确促进文本推理与视觉证据的对齐。这种奖励机制鼓励模型生成基于视觉输入的连贯且上下文感知的推理输出。通过大量实验验证，VIDEORFT在六个视频推理基准测试中均达到了当前最先进的性能水平。

> Reinforcement fine-tuning (RFT) has shown great promise in achieving humanlevel reasoning capabilities of Large Language Models (LLMs), and has recently been extended to MLLMs. Nevertheless, reasoning about videos, which is a fundamental aspect of human intelligence, remains a persistent challenge due to the complex logic, temporal and causal structures inherent in video data. To fill this gap, we propose VIDEORFT, a novel approach that extends the RFT paradigm to cultivate human-like video reasoning capabilities in MLLMs. VIDEORFT follows the standard two-stage scheme in RFT: supervised fine-tuning (SFT) with chain-of-thought (CoT) annotations, followed by reinforcement learning (RL) to improve generalization. A central challenge to achieve this in the video domain lies in the scarcity of large-scale, high-quality video CoT datasets. We address this by building a fully automatic CoT curation pipeline. First, we devise a cognitioninspired prompting strategy to elicit a reasoning LLM to generate preliminary CoTs based solely on rich, structured, and literal representations of video content. Subsequently, these CoTs are revised by a visual-language model conditioned on the actual video, ensuring visual consistency and reducing visual hallucinations. This pipeline results in two new datasets - VideoRFT-CoT-102K for SFT and VideoRFT-RL-310K for RL. To further strength the RL phase, we introduce a novel semantic-consistency reward that explicitly promotes the alignment between textual reasoning with visual evidence. This reward encourages the model to produce coherent, context-aware reasoning outputs grounded in visual input. Extensive experiments show that VIDEORFT achieves state-of-the-art performance on six video reasoning benchmarks.

[Arxiv](https://arxiv.org/abs/2505.12434)