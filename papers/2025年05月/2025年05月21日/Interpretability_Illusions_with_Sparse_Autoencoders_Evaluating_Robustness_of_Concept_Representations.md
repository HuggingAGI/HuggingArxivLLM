# 稀疏自编码器下的可解释性错觉：评估概念表示的鲁棒性

发布时间：2025年05月21日

`LLM应用` `可解释性AI` `AI安全`

> Interpretability Illusions with Sparse Autoencoders: Evaluating Robustness of Concept Representations

# 摘要

> 稀疏自编码器（SAEs）广泛应用于解释大型语言模型（LLMs）的内部激活机制，通过将其映射到人类可理解的概念表示。尽管现有对SAEs的评估着重于重建-稀疏性权衡、人类可解释性及特征解耦，却忽视了一个关键要素：概念表示对输入扰动的鲁棒性。我们主张，鲁棒性应被视为概念表示的核心考量，因为它直接关联到概念标签的准确性。为此，我们将鲁棒性量化为输入空间的优化问题，并构建了一个全面的评估框架，涵盖现实场景，其中对抗性扰动被设计用于操控SAE表示。实证研究表明，微小的对抗性输入扰动即可有效操控基于概念的解释，而对基础LLMs的输出影响微乎其微。总体而言，我们的研究结果表明，SAE概念表示较为脆弱，可能不适合应用于模型监控与监督等场景。

> Sparse autoencoders (SAEs) are commonly used to interpret the internal activations of large language models (LLMs) by mapping them to human-interpretable concept representations. While existing evaluations of SAEs focus on metrics such as the reconstruction-sparsity tradeoff, human (auto-)interpretability, and feature disentanglement, they overlook a critical aspect: the robustness of concept representations to input perturbations. We argue that robustness must be a fundamental consideration for concept representations, reflecting the fidelity of concept labeling. To this end, we formulate robustness quantification as input-space optimization problems and develop a comprehensive evaluation framework featuring realistic scenarios in which adversarial perturbations are crafted to manipulate SAE representations. Empirically, we find that tiny adversarial input perturbations can effectively manipulate concept-based interpretations in most scenarios without notably affecting the outputs of the base LLMs themselves. Overall, our results suggest that SAE concept representations are fragile and may be ill-suited for applications in model monitoring and oversight.

[Arxiv](https://arxiv.org/abs/2505.16004)