# Rationale-Enhanced Decoding for Multi-modal Chain-of-Thought 翻译为中文是“多模态链式推理的增强推理解码方法”。

发布时间：2025年07月10日

`LLM应用` `计算机视觉`

> Rationale-Enhanced Decoding for Multi-modal Chain-of-Thought

# 摘要

> 大视觉语言模型 (LVLMs) 通过整合预训练的视觉编码器与大型语言模型 (LLMs)，展现出令人瞩目的能力。与单模态 LLMs 类似，链式思考 (CoT) 提示被引入 LVLMs，通过结合视觉和文本输入生成中间理由，从而增强多模态推理。尽管 CoT 被认为能提升 LVLMs 的基础性和准确性，但我们的实验揭示了一个重要挑战：现有 LVLMs 在 CoT 推理过程中常常忽视生成的理由内容。为解决这一问题，我们将多模态 CoT 推理重新定义为一种关注理由条件对数似然的 KL 约束奖励最大化问题。作为最优解，我们提出了一种新型的即插即用推理时解码策略——基于理由增强的解码 (RED)。RED 通过协调视觉和理由信息，将不同的图像条件和理由条件的下一个令牌分布相乘。大量实验表明，RED 在多个基准测试和 LVLMs 中，相较于标准 CoT 和其他解码方法，始终显著提升了推理能力。我们的工作提供了一种实用且有效的方法，以提高 LVLMs 中 CoT 推理的忠实度和准确性，为构建更可靠的基于理由的多模态系统奠定了坚实基础。

> Large vision-language models (LVLMs) have demonstrated remarkable capabilities by integrating pre-trained vision encoders with large language models (LLMs). Similar to single-modal LLMs, chain-of-thought (CoT) prompting has been adapted for LVLMs to enhance multi-modal reasoning by generating intermediate rationales based on visual and textual inputs. While CoT is assumed to improve grounding and accuracy in LVLMs, our experiments reveal a key challenge: existing LVLMs often ignore the contents of generated rationales in CoT reasoning. To address this, we re-formulate multi-modal CoT reasoning as a KL-constrained reward maximization focused on rationale-conditional log-likelihood. As the optimal solution, we propose rationale-enhanced decoding (RED), a novel plug-and-play inference-time decoding strategy. RED harmonizes visual and rationale information by multiplying distinct image-conditional and rationale-conditional next token distributions. Extensive experiments show that RED consistently and significantly improves reasoning over standard CoT and other decoding methods across multiple benchmarks and LVLMs. Our work offers a practical and effective approach to improve both the faithfulness and accuracy of CoT reasoning in LVLMs, paving the way for more reliable rationale-grounded multi-modal systems.

[Arxiv](https://arxiv.org/abs/2507.07685)