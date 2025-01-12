# 多模态大语言模型（MLLMs）能否进行多模态推理？EMMA：一个增强的多模态推理基准

发布时间：2025年01月09日

`LLM应用

理由：这篇论文主要讨论的是多模态大型语言模型（MLLMs）在结合文本和图像进行推理方面的能力，并提出了一个新的基准测试EMMA来评估这些模型的综合推理能力。虽然涉及到了多模态推理和模型架构的改进，但核心内容仍然是关于如何应用和改进现有的LLM技术来解决实际问题，因此应归类为“LLM应用”。` `人工智能`

> Can MLLMs Reason in Multimodality? EMMA: An Enhanced MultiModal ReAsoning Benchmark

# 摘要

> # 摘要
有机地结合文本和图像进行推理是人类智能的核心，然而多模态大型语言模型（MLLMs）在这方面的能力仍待深入挖掘。现有基准测试多偏重文本推理或依赖浅层视觉线索，难以全面评估综合的视觉与文本推理能力。为此，我们推出了EMMA（增强型多模态推理）基准，专注于数学、物理、化学和编程领域的多模态推理。EMMA任务要求跨模态的高级推理，无法通过单一模态独立完成，为MLLMs的推理能力提供了更全面的测试。我们对顶尖MLLMs在EMMA上的评估显示，即便采用思维链提示和测试时计算扩展等先进技术，模型在处理复杂多模态和多步骤推理任务时仍存在显著不足。这些发现凸显了改进多模态架构和训练范式的紧迫性，以缩小人类与模型在多模态推理上的差距。

> The ability to organically reason over and with both text and images is a pillar of human intelligence, yet the ability of Multimodal Large Language Models (MLLMs) to perform such multimodal reasoning remains under-explored. Existing benchmarks often emphasize text-dominant reasoning or rely on shallow visual cues, failing to adequately assess integrated visual and textual reasoning. We introduce EMMA (Enhanced MultiModal reAsoning), a benchmark targeting organic multimodal reasoning across mathematics, physics, chemistry, and coding. EMMA tasks demand advanced cross-modal reasoning that cannot be addressed by reasoning independently in each modality, offering an enhanced test suite for MLLMs' reasoning capabilities. Our evaluation of state-of-the-art MLLMs on EMMA reveals significant limitations in handling complex multimodal and multi-step reasoning tasks, even with advanced techniques like Chain-of-Thought prompting and test-time compute scaling underperforming. These findings underscore the need for improved multimodal architectures and training paradigms to close the gap between human and model reasoning in multimodality.

[Arxiv](https://arxiv.org/abs/2501.05444)