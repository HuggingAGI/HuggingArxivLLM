# 数学神经外科：仅通过前向传递揭示语言模型的数学推理能力

发布时间：2024年10月22日

`LLM理论

**理由**：这篇论文主要探讨了数学推理在LLM参数中的编码方式，并提出了一种方法（MathNeuro）来隔离和干预这些参数，以提升数学推理能力而不影响其他语言任务。这属于对LLM内部机制和理论的研究，因此分类为LLM理论。` `人工智能`

> Math Neurosurgery: Isolating Language Models' Math Reasoning Abilities Using Only Forward Passes

# 摘要

> 数学推理是LLM研究中的热门领域，因其是人工智能的重要标志。然而，关于数学推理如何在LLM参数中编码，以及它是否可独立于模型的研究较少。若能实现，便可通过针对性干预提升数学性能，而不影响非数学行为，并加深对模型编码数学推理的理解。我们提出了MathNeuro方法，仅通过前向传递即可隔离LLM中的数学特定参数。MathNeuro基于现有工作，利用权重和激活计算参数重要性，并通过移除对一般语言任务重要的参数来隔离数学特定参数。修剪这些参数会消除LLM的数学推理能力，但保留其一般语言能力。将这些参数按小常数缩放，可使预训练或指令调优的LLM在GSM8K上的性能提升4-17%，且不影响非数学行为。MathNeuro数据效率高，仅需单个样本即可有效识别数学特定参数。MathNeuro为未来在数学特定参数上的干预研究提供了潜力。

> Math reasoning is a highly active area of Large Language Model (LLM) research because it is a hallmark of artificial intelligence. However, few works have explored how math reasoning is encoded within LLM parameters and if it is a skill that can be isolated within a model. Doing so could allow targeted intervention to improve math performance without altering non-math behavior and foster understanding of how models encode math reasoning. We introduce Math Neurosurgery (MathNeuro), a method for isolating math-specific parameters in LLMs using only forward passes. MathNeuro builds on existing work by using weights and activations to calculate parameter importance, but isolates math-specific parameters by removing those important for general language tasks. Pruning parameters MathNeuro identifies deletes a LLM's math reasoning ability without destroying its general language ability. Scaling these parameters by a small constant improves a pretrained or instruction-tuned LLM's performance by 4-17% on GSM8K while leaving non-math behavior unaltered. MathNeuro is also data efficient: most of its effectiveness holds when identifying math-specific parameters using a single sample. MathNeuro highlights the potential for future work to intervene on math-specific parameters.

[Arxiv](https://arxiv.org/abs/2410.16930)