# CODI：通过自蒸馏将思维链压缩至连续空间

发布时间：2025年02月28日

`LLM理论

摘要讨论了CoT（链式思考）方法在提升大型语言模型推理能力方面的研究，并提出了一个新的框架CODI，该框架通过蒸馏和连续空间推理优化了模型的性能。这属于对LLM内部机制和推理方法的理论研究，因此归类为LLM理论。` `人工智能` `模型优化`

> CODI: Compressing Chain-of-Thought into Continuous Space via Self-Distillation

# 摘要

> CoT 通过在自然语言中实现逐步推理，显著提升了大型语言模型 (LLMs) 的推理能力。然而，语言空间可能并非最优选择来进行推理。尽管隐式 CoT 方法试图在不使用显式 CoT 标记的情况下实现推理，但它们在任务性能上始终落后于显式 CoT 方法。我们提出了 CODI（通过自蒸馏实现的连续链式推理），这是一种全新的框架，将 CoT 蒸馏到一个连续空间中，其中共享模型同时充当教师和学生，共同学习显式和隐式 CoT，同时对生成最终答案的标记进行隐藏激活对齐。CODI 是首个在 GSM8k 任务中达到显式 CoT 性能的隐式 CoT 方法，同时实现了 3.1 倍的压缩率，准确率比之前的最先进方法高出 28.2%。此外，CODI 展现了对更复杂 CoT 数据集的可扩展性、鲁棒性和泛化能力。更重要的是，通过解码其连续思维过程，CODI 保留了可解释性，使其推理过程透明。本研究证实，隐式 CoT 不仅是一种更高效的，而且是比显式 CoT 更强大的替代方案。


> Chain-of-Thought (CoT) enhances Large Language Models (LLMs) by enabling step-by-step reasoning in natural language. However, the language space may be suboptimal for reasoning. While implicit CoT methods attempt to enable reasoning without explicit CoT tokens, they have consistently lagged behind explicit CoT method in task performance. We propose CODI (Continuous Chain-of-Thought via Self-Distillation), a novel framework that distills CoT into a continuous space, where a shared model acts as both teacher and student, jointly learning explicit and implicit CoT while aligning their hidden activation on the token generating the final answer. CODI is the first implicit CoT method to match explicit CoT's performance on GSM8k while achieving 3.1x compression, surpassing the previous state-of-the-art by 28.2% in accuracy. Furthermore, CODI demonstrates scalability, robustness, and generalizability to more complex CoT datasets. Additionally, CODI retains interpretability by decoding its continuous thoughts, making its reasoning process transparent. Our findings establish implicit CoT as not only a more efficient but a powerful alternative to explicit CoT.

[Arxiv](https://arxiv.org/abs/2502.21074)