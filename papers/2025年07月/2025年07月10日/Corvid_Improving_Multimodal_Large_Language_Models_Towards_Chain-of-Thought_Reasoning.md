# Corvid：提升多模态大型语言模型的链式推理能力

发布时间：2025年07月10日

`LLM应用` `多模态`

> Corvid: Improving Multimodal Large Language Models Towards Chain-of-Thought Reasoning

# 摘要

> 多模态大型语言模型（MLLMs）的最新进展在多模态感知与理解领域表现卓越。然而，现有开源MLLMs在复杂推理任务中仍显不足，尤其在需要深度思考的决策与问题解决场景下。本文介绍了一款具备增强链式推理（CoT）能力的MLLM——Corvid。在架构设计上，Corvid采用了混合视觉编码器以实现信息丰富的视觉表征，并配备了一个精心设计的连接器（GateMixer）来促进跨模态对齐。为了进一步提升其推理能力，我们构建了MCoT-Instruct-287K，一个高质量的多模态链式推理指令数据集，该数据集从多种公共推理资源中精炼而来。借助这一数据集，我们采用两阶段链式推理格式的训练方法对Corvid进行优化，逐步提升其逐步推理能力。此外，我们还提出了一种有效的推理时扩展策略，使Corvid能够通过自我验证机制有效缓解过度推理和推理不足的问题。实验结果表明，Corvid在数学推理和科学问题解决方面显著优于现有类o1的MLLMs和参数规模相近的最先进MLLMs。项目页面：https://mm-vl.github.io/corvid。


> Recent advancements in multimodal large language models (MLLMs) have demonstrated exceptional performance in multimodal perception and understanding. However, leading open-source MLLMs exhibit significant limitations in complex and structured reasoning, particularly in tasks requiring deep reasoning for decision-making and problem-solving. In this work, we present Corvid, an MLLM with enhanced chain-of-thought (CoT) reasoning capabilities. Architecturally, Corvid incorporates a hybrid vision encoder for informative visual representation and a meticulously designed connector (GateMixer) to facilitate cross-modal alignment. To enhance Corvid's CoT reasoning capabilities, we introduce MCoT-Instruct-287K, a high-quality multimodal CoT instruction-following dataset, refined and standardized from diverse public reasoning sources. Leveraging this dataset, we fine-tune Corvid with a two-stage CoT-formatted training approach to progressively enhance its step-by-step reasoning abilities. Furthermore, we propose an effective inference-time scaling strategy that enables Corvid to mitigate over-reasoning and under-reasoning through self-verification. Extensive experiments demonstrate that Corvid outperforms existing o1-like MLLMs and state-of-the-art MLLMs with similar parameter scales, with notable strengths in mathematical reasoning and science problem-solving. Project page: https://mm-vl.github.io/corvid.

[Arxiv](https://arxiv.org/abs/2507.07424)