# PSSD：利用人类心理结构实现大型语言模型的自我否定

发布时间：2025年02月03日

`LLM理论

理由：这篇论文主要探讨了如何通过引入人类心理结构的角色来提升LLMs的推理能力，特别是通过自我否定和修正机制来改进LLMs的推理准确性。这涉及到对LLMs内部机制的理论探讨和改进，属于对LLMs理论的研究。` `人工智能` `心理学`

> PSSD: Making Large Language Models Self-denial via Human Psyche Structure

# 摘要

> LLMs 推理准确性的提升引发了社区的广泛兴趣，一些前沿研究探索了事后策略来纠正潜在错误。然而，尽管付出了大量努力，这些研究仍陷入资源竞争的困境，耗费大量时间和计算资源。问题的根源在于未能识别出这类解决方案的核心特征，即 LLMs 的自我否定。换句话说，LLMs 应自信地识别潜在错误，并谨慎执行针对性修正。由于整个过程在 LLMs 内部进行，难以获得有力的参考，即使承认错误，也缺乏具体的修正步骤。为此，我们提出了 PSSD，它借鉴人类心理结构，通过三个相互关联的角色来促进推理：(1) 基于直觉的本我角色，利用良性 LLMs 提供初步尝试；(2) 规则驱动的超我角色，总结规则以规范尝试，并提供关键点作为指导；(3) 以脚本为中心的自我角色，整合所有信息生成可执行脚本，用于最终答案预测。实验表明，PSSD 不仅显著提升了推理能力，还能与现有模型无缝集成，实现卓越性能。

> The enhance of accuracy in reasoning results of LLMs arouses the community's interests, wherein pioneering studies investigate post-hoc strategies to rectify potential mistakes. Despite extensive efforts, they are all stuck in a state of resource competition demanding significant time and computing expenses. The cause of the situation lies in the failure of identifying the fundamental feature of the solutions in this line, coined as the self-denial of LLMs. In other words, LLMs should confidently determine the potential existence of mistakes and carefully execute the targeted correction. As the whole procedure conducts within LLMs, supporting and persuasive references are hard to acquire, while the absence of specific steps towards refining hidden mistakes persists even when errors are acknowledged. In response to the challenges, we present PSSD, which refers to and implements the human psyche structure such that three distinct and interconnected roles contribute to human reasoning. Specifically, PSSD leverages the recent multi-agent paradigm, and is further enhanced with three innovatively conceived roles: (1) the intuition-based id role that provides initial attempts based on benign LLMs; (2) the rule-driven superego role that summarizes rules to regulate the above attempts, and returns specific key points as guidance; and (3) the script-centric ego role that absorbs all procedural information to generate executable script for the final answer prediction. Extensive experiments demonstrate that the proposed design not only better enhance reasoning capabilities, but also seamlessly integrate with current models, leading to superior performance.

[Arxiv](https://arxiv.org/abs/2502.01344)